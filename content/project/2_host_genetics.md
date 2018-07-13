+++
title = "Host genetics + microbiome"
date = 2018-07-02T17:17:33+02:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = ""

# Optional image to display on homepage.
image_preview = "microbiome_genetics_fig.png"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

Much of my work has been focused on elucidating the role of host genetics in determining gut microbiome composition.  

[Click here to see the full list of publications related to this work.](#pubs)
  
Scroll down or click the following links to read about host genetics in the Hutterites, TwinsUK, and more:

<img style="margin: 10px; float: left" src="/img/hutterites.png" width="120">  [Microbiome GWAS in the Hutterites](#hutterites)  
photo: [Kelly Hofer](http://www.hutterites.org/galleries/work-and-agriculture/)

<br clear="all">

<img style="margin: 10px; float: left" src="/img/cellHM_fig.png" width="120">  [Host genetics + microbiota interactions in the TwinsUK](#twinsUK)

<br clear="all">

<img style="margin: 10px; float: left" src="/img/toothBeTold_fig.png" width="120">  [Reviews and commentaries](#andMore)

<br clear="all">


<a name = "hutterites"></a>

<br>
<br>
## <span class="align_left"><i class="fa fa-angle-double-left fa-1x"></i><b>Microbiome GWAS in the Hutterites</b><i class="fa fa-angle-double-right fa-1x"></i></span>

<img style="margin: 10px; float: left" src="/img/PVE.png" width="300" height="400">

While many environmental factors are known to contribute to gut microbiome composition, the extent to which host genetic variation plays a role is unclear. 
Using the same population as the [seasonal study](/project/2_host_diet_environment/) (the Hutterites), where inter-individual variation in diet is limited, I examined the role of sex and age as well as host genetics in determining the relative abundances of the most common bacteria in the gut. 
To do so, I implemented [methods](http://www.xzlab.org/software.html) that specifically account for the relatedness across individuals and examined genetic variation genome-wide. 
While this is an important first step at examining host genetics, I really can't state enough the limitations of the sample size in this study and the number of tests performed. 
That being said, I do find bacteria that show evidence of heritability in my samples and have genome-wide (but not study-wide) significant associations with SNPs in the genome.
<br clear="all">  
To read more, check out:

- [**Genome-wide association studies of the human gut microbiota.**](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0140301) <u>Davenport ER</u>, Cusanovich DA, Michelini K, Barreiro LB, Ober C, and Gilad Y.  PLoS One. 2015;10(11):e0140301  
<i class="fa fa-angle-double-right fa-1x"></i>_This article was highlighted as an Editor's pick for both the PLoS Microbiology and PLoS Experimental Biology special collections:  
<http://collections.plos.org/microbiology-picks> &  
<http://collections.plos.org/experimental-biology>_

Also check out our GWAS of the nasal microbiome in the Hutterites, led by Dr. Catherine Igartua:

- [**Host genetic variation in the mucosal immunity pathways influences the upper airway microbiome**](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-016-0227-5) Igartua C, <u>Davenport ER</u>, Gilad Y, Nicolae DL, Pinto J\\*, and Ober C\\*. Microbiome. 2017;5(16)


&nbsp;


<a name = "twinsUK"></a>

<br>
<br>
## <span class="align_left"><i class="fa fa-angle-double-left fa-1x"></i><b>Host genetics + microbiota interactions in the TwinsUK</b><i class="fa fa-angle-double-right fa-1x"></i></span>

### GWAS of gut microbiota in TwinsUK

<img style="margin: 10px; float: left" src="/img/cellHM_figure4.jpg" width="300" height="400">

As a postdoc, I've continued examining the role of host genetics using the [TwinsUK cohort](http://www.twinsuk.ac.uk/). 
This large, well-characterized cohort gives us much more power to detect associations between variation in the human genome and abundance of bacteria in the gut. We now have replication across multiple studies that show lactase persistence alleles are associated with lower levels of _Bifidobacteria_ in the gut. 
The study was led by Julia Goodrich, while I contributed several analyses to study, including the replication of the _LCT-Bifidobacterium_ association in the Hutterites, PrediXcan analyses, and microbiomeGWAS analyses. 
<br clear="all">  
To read more, check out:

- [**Genetic determinants of the gut microbiome in UK twins**](http://www.sciencedirect.com/science/article/pii/S1931312816301536) Goodrich JK, <u>Davenport ER</u>, Beaumont M, Jackson MA, Knight R, Ober C, Spector TD, Bell JT, Clark AG, and Ley RE. Cell Host & Microbe. 2016;19(5), 731-743 


### Complex genotype associations with gut microbiota in TwinsUK

<img style="margin: 10px; float: left" src="/img/ABO.png" width="300" height="600">

In addition to genome-wide studies in the TwinsUK, I also examined two loci in depth that were previously implicated as playing roles in determining gut microbiome composition.
Cell surface antigens potentially act as either energy sources or tethers for bacteria to adhere to the gut. 
Therefore, host variation controlling antigen structure or expression could be factors influencing gut microbiome composition.
One such antigen is encoded by the ABO locus - known commonly as your blood type.
This antigen not only exists on the surface of red blood cells, but also along mucosal surfaces in individuals with an intact _FUT2_ gene (secreting individuals). 
ABO antigen and secretor status are risk factors for a number of diseases, including some that also show association with gut microbiome composition.
With that in mind, I set out to identify links between the host genome (in _ABO_ and _FUT2_), the composition of the gut microbiome, and disease state. 
However, that plan was cut short as ABO and secretor status were NOT associated with overall microbiome composition, diversity, or the abundances of individual bacteria in the gut, despite the barrage of different tests thrown at the data. 
These [lack of significant] results highlight the importance of performing replication studies using large, well-powered cohorts.
<br clear="all">  
To read more, check out:

- [**ABO antigen and secretor statuses are not associated with gut microbiota composition in 1,500 twins**](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-016-3290-1). <u>Davenport ER</u>, Goodrich JK, Bell JT, Spector TD, Ley RE, and Clark AG. BMC Genomics. 2016;17:941 
 
 
<a name = "andMore"></a>

<br>
<br>

## <span class="align_left"><i class="fa fa-angle-double-left fa-1x"></i><b>Reviews and commentaries</b><i class="fa fa-angle-double-right fa-1x"></i></span>

In addition to examining host genome-microbiome interactions in the two study populations highlighted above, check out some reviews and commentaries I've written on the subject:

<img style="margin: 10px; float: left" src="/img/gut_microbes_rev.png" width="160"> [**Elucidating the role of the host genome in shaping microbiome composition.**](http://www.tandfonline.com/doi/full/10.1080/19490976.2016.1155022)  
<u>Davenport ER</u>.  Gut Microbes. 2016;7(2), 178-184
<br clear="all">

<img style="margin: 10px; float: left" src="/img/science_rev_fig.png" width="160"> [**Cross-species comparisons of host genetic associations with the microbiome**](http://science.sciencemag.org/content/352/6285/532)  
Goodrich JK\*, <u>Davenport ER</u>\*, Waters JL\*, Clark AG, and Ley RE. Science. 2016;352(6285), 532-535

<br clear="all">

<img style="margin: 10px; float: left" src="/img/ann_rev_gen_fig.png" width="160"> [**The relationship between the human genome and microbiome comes into view**](https://www.annualreviews.org/doi/abs/10.1146/annurev-genet-110711-155532)  
Goodrich JK, <u>Davenport ER</u>, Clark AG, and Ley RE. Annual Reviews of Genetics. 2017;51, 413-433
<br clear="all">

<img style="margin: 10px; float: left" src="/img/toothBeTold_fig.png" width="160">  [**Tooth be told, genetics influences oral microbiome**](https://www.sciencedirect.com/science/article/pii/S1931312817303517) <u>Davenport ER</u>. Cell Host & Microbe. 2017;22(3), 269-278

<br clear="all">
<a name = "pubs"></a>

<br>
<br>
