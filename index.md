# Research

[ **[Research](/index.md)** ][ [Curriculum Vitae](/cv.md) ][ [Github](https://github.com/molikd) ][ [Contact](/contact.md) ]

---

I'm interested in the factors that affect microbial communities’ diversity overtime. Which and how much of deterministic factors, like the environment that the microbes are occupying, and then more stochastic things, like selection and genetic drift affect the communities. I utilize Computational Genomics, and Computational Ecology to look at the dynamics of this relationship. This central Computational Eco-Evo theme of  lends itself to other questions: What new computational tools need to exist in order to gain a deeper understanding of this dynamic? When exposed to an increasing deterministic factor, like salt concentration, how will microbial communities respond? How do microbial communities recover after stress?

In order to answer these questions, I both write new software, generally in the vain of big data, as well as use experimental systems, specifically the tool-set that metabarcoding and whole genome sequencing can provide. This means that I implement new data-basing and alignment strategies in order to solve the questions that I am interested in.


![Env heatmap](assets/heatmap-1.png)<br>
`environmental variables influencing sample to sample simularity`

I also research computational methods in general ecological data: specifically within Metabarcoding, which is the idea of using a single gene region to parse out which species are in a sample; Working out how to associate community structure with the environment; and looking at rare and pathogenic species in large amounts of data


K-mer comparison methods that estimate distances between gnomic data can be used to generate environmental sample to sample distances in both metagenomic and metabarcoding applications. A pair-wise matrix of distances can be clustered via hierarchical methods. This De novo clustering of k-mer derived distances may describe the community structure of such samples, and may correlate with the environment. Such is the case with data correlated with soil measurements in the Atacama desert or data of shipping ports with sampling location from around the world. Some of the algorithms that can be leveraged to do this, like those using sketching (as is the case with Mash), suffix trees, or de Bruijn graphs show increased speed over original methods. Such methods can also be used to determine the presence or absence of a targeted species, as is shown with the search for the yeast C. Neoformans in 12634 18S metagenomic datasets. Available methods in k-mer analysis can be used in metagenomic and metabarcoding studies for the determination of significant subsets and for the presence absence of particular species.


![All pairwise](assets/dendogram-1.png)<br>
`12634 18S metagenomic datasets compared to eachother, colored by type of source, ie:soil vs. aquatic`

<meta name="keywords" content="David Molik, Molik, Metagenetic, Metabarcoding"/>
<meta name="description" content="David Molik's research interests: Expploring Metagenetic and Metabarcoding analysis"/>
<meta name="subject" content="david.molik.co : A Personal Webpage">
<style>body {background-color: #cee4ae; color: #4d4d4d;}
img { border-width: 1px; border-color: #A9A9A9;}
a:link { color: 	#264073; }
a:visited { color: #264073; }
a:hover { color: #264073; }
a:active { color: #003399; }
hr {	background: #595959; }
blockquote { border-left: 1px solid #595959; }
code { color: #4d4d4d; }
p { color: #4d4d4d; } 
</style>

