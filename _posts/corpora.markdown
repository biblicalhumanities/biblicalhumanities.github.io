My first set of queries will be based on the [lowfat](https://github.com/biblicalhumanities/greek-new-testament/tree/master/syntax-trees) treebanks. 


### Getting the Lowfat Treebanks

The first step is to get a copy of the treebanks.  You can do this in the following ways:

1. Download the [zip file](https://github.com/biblicalhumanities/greek-new-testament/archive/master.zip) and unzip it, or
2. Use a git client: 
`$ git clone https://github.com/biblicalhumanities/greek-new-testament/`

Either way, you now have a directory called `greek-new-testament`, which contains four different versions of the Greek New Testament:

    ./greek-new-testament/syntax-trees/nestle1904-lowfat/xml/gnt.xml
    ./greek-new-testament/syntax-trees/nestle1904/xml/gnt.xml
    ./greek-new-testament/syntax-trees/sblgnt/xml/gnt.xml
    ./greek-new-testament/syntax-trees/sblgnt-lowfat/xml/gnt.xml

The first two are analyses of the [Nestle 1904 Greek New Testament](https://sites.google.com/site/nestle1904/), the last two are analyses of the [SBLGNT](http://sblgnt.com/). The lowfat versions are designed to be easier to query, so we will use those in this tutorial.  For this tutorial, it does not matter whether you use `nestle1904-lowfat/gnt.xml` or `sblgnt-lowfat/gnt.xml`.

### XML Structure of the Lowfat Treebanks

These files contain the analysis for each chapter in a separate file. The file named `gnt.xml` includes each of the other files:

{% highlight xml %}
    <gnt xmlns:xi="http://www.w3.org/2001/XInclude">
        <xi:include href="01-matthew.xml"/>
        <xi:include href="02-mark.xml"/>
        <xi:include href="03-luke.xml"/>
        <xi:include href="04-john.xml"/>
        <xi:include href="05-acts.xml"/>
        <xi:include href="06-romans.xml"/>
        <xi:include href="07-1corinthians.xml"/>
        <xi:include href="08-2corinthians.xml"/>
        <xi:include href="09-galatians.xml"/>
        <xi:include href="10-ephesians.xml"/>
        <xi:include href="11-philippians.xml"/>
        <xi:include href="12-colossians.xml"/>
        <xi:include href="13-1thessalonians.xml"/>
        <xi:include href="14-2thessalonians.xml"/>
        <xi:include href="15-1timothy.xml"/>
        <xi:include href="16-2timothy.xml"/>
        <xi:include href="17-titus.xml"/>
        <xi:include href="18-philemon.xml"/>
        <xi:include href="19-hebrews.xml"/>
        <xi:include href="20-james.xml"/>
        <xi:include href="21-1peter.xml"/>
        <xi:include href="22-2peter.xml"/>
        <xi:include href="23-1john.xml"/>
        <xi:include href="24-2john.xml"/>
        <xi:include href="25-3john.xml"/>
        <xi:include href="26-jude.xml"/>
        <xi:include href="27-revelation.xml"/>
    </gnt>
{% endhighlight %}

Each book consists of a sequence of sentences, which have *word groups* (represented by `wg` elements) and *words* (represented by `w` elements).  For instance, here is the representation of the first sentence in Luke 24:19, "καὶ εἶπεν αὐτοῖς· Ποῖα;"

{% highlight xml lineno %}    
    <sentence>
      <cite>Luk24:19:1-24:19:4</cite>
      <wg nodeId="420240190010040" class="cl" role="s">
        <w morphId="42024019001" class="conj" lemma="καί">καὶ</w>
        <wg nodeId="420240190020030" class="cl">
          <wg nodeId="420240190020020" class="cl" head="true">
            <w morphId="42024019002" 
               class="verb" 
               role="v" 
               head="true" 
               lemma="λέγω"
               person="third"
               number="singular"
               tense="aorist"
               voice="active"
               mood="indicative">εἶπεν</w>
            <w morphId="42024019003" 
               class="pron" 
               role="io" 
               lemma="αὐτός" 
               case="dative"
               gender="masculine"
               number="plural">αὐτοῖς</w>
          </wg>
          <w morphId="42024019004" 
             class="pron" 
             lemma="ποῖος" 
             case="accusative"
             gender="neuter"
             number="plural">Ποῖα;</w>
        </wg>
      </wg>
    </sentence>
{% endhighlight %}

### Getting an XQuery Processor


### First Queries

