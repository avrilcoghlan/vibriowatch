*Vibrio cholerae* genomic data
==============================

In this section, we will describe:

* `The Vibrio cholerae reference genome`_.
* `What genomic data is available for Vibrio cholerae`_.
* `Pathogenwatch and Vibriowatch`_.
* `How many V. cholerae genomes are in Vibriowatch`_.
* `Where in the world were the isolates in Vibriowatch collected`_.
* `How to search for an isolate in Vibriowatch and see its report page`_.
* `How to make a collection of isolates in Vibriowatch`_.
* `Exploring the timeline for a collection of isolates`_.
* `Exploring the tree for a collection of isolates`_.
* `Displaying metadata on the tree for a collection of isolates`_.
* `Finding your list of collections in Vibriowatch`_.

The Vibrio cholerae reference genome
------------------------------------

The *Vibrio cholerae* genome was first sequenced by `Heidelberg et al 2000`_. They sequenced strain N16961, which belongs to the current pandemic lineage (7PET lineage). They found that the genome is four Megabase and consists of two circular chromosomes, a larger chromosome of about three Megabase and a smaller chromosome of about 1.1 Megabase. Together, these two chromosomes have about 4000 genes, and their GC content of the chromosomes is about 47%. 

.. _Heidelberg et al 2000: https://pubmed.ncbi.nlm.nih.gov/10952301/

.. image:: Picture17.png
  :width: 300

It's worth bearing in mind that N16961 is the reference strain, but there may be a wide variety of genomic variation in the *V. cholerae population* worldwide. Some interesting examples have already been reported. `Johnson et al 2015`_ reported a *V. cholerae* isolate that has the two chromosomes fused into one big chromosome. `Okada et al 2015`_ reported an isolate with a third replicon of nearly one Megabase so that its genome size was five Megabase. As we sequence more and more genomes of *V. cholorae* isolates, we are likely to see more and more genomic variation.

.. _Johnson et al 2015: https://pubmed.ncbi.nlm.nih.gov/25977434/

.. _Okada et al 2015: https://pubmed.ncbi.nlm.nih.gov/26079534/

What genomic data is available for Vibrio cholerae
--------------------------------------------------

Since the year 2000, genome sequencing technologies have greatly improved, and this has meant that many different *V. cholerae* isolates have had their genomes sequenced. An example of this with a key paper by `Chun et al 2009`_, who sequenced the genomes of 23 diverse *V. cholerae* isolates that had been collected over nearly 100 years. These isolates included both clinical and environmental isolates from many different countries. 

.. _Chun et al 2009: https://pubmed.ncbi.nlm.nih.gov/19720995/

Since then, many more *V. cholerae* genomes have been sequenced. This plot shows with the number of isolates sequenced in 22 key papers ranging from the year 2000 at the top to 2022 at the bottom:

.. image:: Picture19.png
  :width: 300

Together these 22 key papers have published 3254 *V. cholerae* genomes, of which 84% belonged to the current pandemic lineage (7PET lineage). All of these genome data has been useful to clinicians and epidemiologists to try and understand the spread of *V. cholerae* around the world and also to scientists and epidemiologists interested in *V. cholerae* genome evolution, for example, the spread of antibiotic resistance genes, and the presence or absence of virulence genes. 

Of course, these 22 key papers do not include all papers that have published *V. cholerae* genomes. In fact, if you look at the `NCBI database`_ or `ENA database`_, you will be able to find about 5700 *V. cholerae* genome assemblies. These will include some genomes that were published in papers that I have not listed here, but also some genomes that have not yet been published. Furthermore, if you look in the ENA database, you will see about 14,500  *V. cholerae* sequence runs, which are unassembled reads for *V. cholerae* isolates. This reflects the fact that many researchers in the past have not assembled reads into assemblies but simply aligned the reads to the reference genome. 

Clearly, there is a huge amount of genomic data available for *V. cholerae*. Our goal in the VibrioWatch project is to make all this data available and useful for clinicians, epidemiologists and researchers studying *V. cholerae*.

.. _NCBI database: https://www.ncbi.nlm.nih.gov/data-hub/genome/?taxon=666

.. _ENA database: https://www.ebi.ac.uk/ena/browser/advanced-search

Pathogenwatch and Vibriowatch
-----------------------------

Next we'll tell you about Pathogenwatch, and its *V. cholerae* component, which we call **VibrioWatch**. `Pathogenwatch`_ is a website that can be used as a global platform for genomic surveillance of pathogens of humans. It has been developed by the Centre for Genomic Pathogen Surveillance, a collaboration between the University of Oxford and the Wellcome Sanger Institute. So far, Pathogenwatch includes almost 250,000 genomes for bacterial pathogens of humans that cause worldwide problems. This is a phylogenetic tree (tree adapted from `Avican et al 2021`_) of some major bacterial pathogens of humans, showing the number of genomes (as of January 2023) that are in Pathogenwatch so far for those species:

.. image:: Picture20.png
  :width: 500

.. _Pathogenwatch: https://pathogen.watch/

.. _Avican et al 2021: https://pubmed.ncbi.nlm.nih.gov/34078900/

You can see that there are several species (e.g. *Steptococcus pneumoniae*) that include a large fraction of the genomes added so far. This reflects the fact that the research communities studying those species have found Pathogenwatch to be an extremely useful website for disseminating and analysing genome data for their species. 

How many V. cholerae genomes are in Vibriowatch
-----------------------------------------------

We are convinced that Pathogenwatch is a useful website for *V. cholerae*, and so we have started uploading *V. cholerae* genomes to Pathogenwatch. So far, we have put about 4700 *V. cholerae* genomes into Pathogenwatch (as of February 2023), that is, its *V. cholerae* component Vibriowatch. 
But as we mentioned above, there are many 1000s of genomes already available, and our goal is to upload as many more as possible in the near future. 

As well as the genome sequences for the approximately 4700 genomes, we have also uploaded metadata for those genomes that we have manually curated
from the papers that published the genomes. This metadata includes strain name(s); assembly accession in databases (e.g. NCBI or ENA databases); PubMed id. of the paper; and phenotypic data for biotype, serogroup, serotype, and antimicrobial resistance. 

You can see a list of the *V. cholerae* genomes uploaded into Pathogenwatch by visiting the `Pathogenwatch`_ website. 

.. _Pathogenwatch: https://pathogen.watch/

Note that you can also find the full list of genomes in your private Vibriowatch account by clicking on the three small horizontal bars at the top left of the Pathogenwatch website:

.. image:: Picture9.png
  :width: 150
  
This will bring up a menu:

.. image:: Picture21.png
  :width: 150
  
If you click on 'Public Genomes' in this menu, it will give you the list of all the genomes in Pathogenwatch. 

To just select *V. cholerae* genomes, click on 'Genus' in the menu that now appears:

.. image:: Picture22.png
  :width: 150
  
Then select 'Vibrio', to select just genomes from *V. cholerae*. You will now see a list of the approximately 4700 *V. cholerae* genomes (just showing the top of the list here):

.. image:: Picture23.png
  :width: 850

Where in the world were the isolates in Vibriowatch collected
-------------------------------------------------------------

Once you have got the list of the approximately 4700 *V. cholerae* isolates in Vibriowatch (see above), 
if you now click on 'Map' (instead of 'List') at the top of the page, it will show a map of where these approximately 4700 isolates were collected:

.. image:: Picture24.png
  :width: 850

For example, you can see 207 were collected from Mexico, 198 from Haiti, and 262 from China, and so on. 

The approximately 4700 isolates were collected between 1916 and 2020. 
As we put more and more genomes into Pathogenwatch for *V. cholerae*, the map will be updated, and we hope to cover a larger time span. 

In the next sections, we will explain some analyses that can be carried out on the VibrioWatch website, both of the approximately 4700 genomes already uploaded, but also of genomes that you upload yourself into your private space in the VibrioWatch website.

How to search for an isolate in Vibriowatch and see its report page
-------------------------------------------------------------------

You can search for an isolate in Vibriowatch by searching by its isolate/strain name(s).
For example, isolate HCUF_O1 is an isolate collected in Haiti in 2010, sequenced by `Hasan et al 2012`_. 

.. _Hasan et al 2012: https://pubmed.ncbi.nlm.nih.gov/22711841/

You can search for isolate HCUF_01 in Vibriowatch by clicking on the three small horizontal bars at the top left of the Pathogenwatch website:

.. image:: Picture9.png
  :width: 150
  
This will bring up a menu:

.. image:: Picture10.png
  :width: 150
  
If you click on 'All Genomes' in the menu, you will then see a list of all the genomes in Pathogenwatch. 

To just select *V. cholerae* genomes, click on 'Genus' in the menu that now appears:

.. image:: Picture22.png
  :width: 150
  
Then select 'Vibrio', to select just genomes from *V. cholerae*. You will now see a list of the approximately 4700 *V. cholerae* genomes (just showing the top of the list here):

.. image:: Picture23.png
  :width: 850
  
A search bar will now appear at the top left: 

.. image:: Picture22.png
  :width: 150
  
If you type 'HCUF' in the search bar, it will find isolate HCUF_01:

.. image:: Picture28.png
  :width: 850
  
Note that sometimes if there is a hyphen or dash in the name of an isolate, you might not find the isolate if is stored in a slightly different format in Vibriowatch. For example, HCUF_01 is stored as 'HCUF01' in Vibriowatch, so you won't find it if you search for 'HCUF_01' or 'HCUF-01', but you can find it if you search for part of the name, e.g. 'HCUF'. 
  
You can click on the isolate's name (link 'HCUF01') to go to its 'report page'. 
The report page shows the curated metadata for the isolate, as well as bioinformatics analyses of the isolate.
This shows the top of the report page for HCUF-01:

.. image:: Picture26.png
  :width: 650

How to make a collection of isolates in Vibriowatch
---------------------------------------------------

A nice feature of Pathogenwatch/Vibriowatch is that it is possible to make a 'collection' of isolates, and Vibriowatch will
build a tree for the isolates in the collection, and let you display their metadata, as well as results of some bioinformatics analyses, on the tree.

As mentioned above, a key early paper on *V. cholerae* genomics was by `Chun et al 2009`_, who sequenced the genomes of 23 diverse *V. cholerae* isolates. 

.. _Chun et al 2009: https://pubmed.ncbi.nlm.nih.gov/19720995/

The 23 isolates sequenced by `Chun et al 2009`_ were: MO10, B33, MJ-1236, CIRS-101, N16961, RC9, NCTC_8457, MAK757, BX330286, 2740-80, O395, V52, 12129(1), MZO-3, AM-19226, TMA21, 623-39, MZO-2, 1587, V51, RC385, VL426, and TM11079-80. 

.. _Chun et al 2009: https://pubmed.ncbi.nlm.nih.gov/19720995/

To make a collection in Vibriowatch for these isolates, we can search for the isolates one-by-one (in the same way that we searched for HCUF-01 above). To include the isolate in the collection, when we find the isolate, we tick the box on the left of the isolate's name: 

.. image:: Picture29.png
  :width: 850
  
When you have searched for and ticked the boxes for all 23 of the genomes sequenced by `Chun et al 2009`_, you will see a purple button the top right saying '23 Selected Genomes':
  
.. image:: Picture30.png
  :width: 150
  
If you click on this purple button you will see another purple button saying 'Sign in to create collection':
  
.. image:: Picture31.png
  :width: 250
  
You will need to now sign into the Pathogenwatch/Vibriowatch website.
To make a collection on the Pathogenwatch/Vibriowatch website, it's necessary
to make an account first, for example, using your email address as your login. 

Once you have logged in, if you now click on the purple button saying '23 Selected Genomes', you will see a purple button 'Create collection'. You will need to fill in a title and brief description of the collection, and a PubMed id. if you like:

.. image:: Picture32.png
  :width: 350
  
The collection will only be visible in your private Vibriowatch account, so only you will be able to view it.
Now click on the 'Create now' purple button to create the collection.

Vibriowatch will now build a tree for the collection, which may take a little while if your collection has hundreds of isolates, but will
be very fast for the 23 isolates of `Chun et al 2009`_.

.. _Chun et al 2009: https://pubmed.ncbi.nlm.nih.gov/19720995/

You will now see a map showing where the isolates in the collection were collected (at the top), and a timeline of when they were collected (at the bottom):

.. image:: Picture33.png
  :width: 850
  
Exploring the timeline for a collection of isolates
---------------------------------------------------

By default, the timeline for a collection of isolates shows the day of collection. To see instead the year of collection, click on this small 'Settings' symbol at the top right of the timeline panel: 

.. image:: Picture34.png
  :width: 50
  
You will see a menus appear with settings for the timeline:

.. image:: Picture35.png
  :width: 350
  
To change from day of collection to year of collection, click on 'Day' in the settings menu, and choose 'Year'. You will now see the timeline in terms of year of collection of the isolates. You can see that the isolates were collected between 1930 and 2004.

If you hover your mouse over the box representing a particular isolate, you will see the year of collection of that isolate pop up over the box representing the isolate:

.. image:: Picture36.png
  :width: 850
  
Exploring the tree for a collection of isolates
-----------------------------------------------

As mentioned above, Vibriowatch builds a tree for each collection of isolates. This tree is built using the neighbour-joining
algorithm, a relatively fast and reliable method for building phylogenetic trees. You should see a big purple button 'View tree' in the middle of the map of isolates for your collection. If you click on the purple button, you will see the tree of your isolates on the left panel, the map of your isolates on the right panel, and the timeline for your isolates below that:

.. image:: Picture37.png
  :width: 850
  
By default, the isolate names are not shown on the tree. To show the isolate names on the tree, click on the small 'Settings' symbol at the top right of the tree panel:

.. image:: Picture34.png
  :width: 50
  
You will see some menus appear with settings for the tree:

.. image:: Picture38.png
  :width: 550

To show the isolate names on the tree, click on the 'Nodes and labels' menu that appeared, and slide the 'Show leaf labels' slider to the right. You should now see the isolate names appear on the tree. To see the whole of your tree, you may have to zoom out by rolling the rollerball on your mouse away from you:

.. image:: Picture39.png
  :width: 650

Displaying metadata on the tree for a collection of isolates
------------------------------------------------------------

Instead of showing the isolate name beside the leaves (tips) of the tree, you can instead show some of the curated metadata that was uploaded to Vibriowatch with the genome sequences.

To do this, click on the button saying 'Timeline' below the tree, and instead select 'Metadata' from the menu that appears:

.. image:: Picture40.png
  :width: 100

Now instead of the map, below the tree you will see a panel with curated metadata:

.. image:: Picture41.png
  :width: 850

You can click on a column that you want to display beside the tree instead of the isolate names, e.g. 'serogroup_phenotype' to show the experimentally determined serogroups:

.. image:: Picture42.png
  :width: 850

You will now see the serogroups displayed beside the leaves of the tree in the tree panel:

.. image:: Picture43.png
  :width: 450

We can see that the isolates collected by `Chun et al 2009`_ had a variety of serogroups, including O1, O139, O37, O39, etc.
Some of the isolates were just assigned serogroup 'non O1', so it was only determined that they were not O1, but their exact serogroup was not determined. Isolates belonging to the current pandemic lineage (7PET lineage) have been found to be serogroup O1, or sometimes O139. 

.. _Chun et al 2009: https://pubmed.ncbi.nlm.nih.gov/19720995/

Finding your list of collections in Vibriowatch
-----------------------------------------------

If you want to find a collection that you previously made in Vibriowatch, you can see a list of all your collections
by clicking on the three horizontal bars at the top left of the Vibriowatch website:

.. image:: Picture9.png
  :width: 150
  
This will bring up a menu:

.. image:: Picture44.png
  :width: 150
  
If you click on 'My collections' in this menu, it will bring up a list of all your collections. If you move your mouse over a particular
collection, it will bring up buttons showing a bin (which if you click on it, will delete the collection), a button saying 'list genomes' to 
see a list of genomes in the collection, and a button saying 'view collection' to see the tree and map for that collection:

.. image:: Picture45.png
  :width: 850


Acknowledgements
----------------

I would like here to acknowledge the great help and work of my colleagues at the Wellcome Sanger Institute, especially Dr Matthew Dorman, Dr Florent Lassalle, Dr Sina Beier, Dr Alyce Taylor-Brown, Dr Adrian Cazares, Sam Dougan, and Prof. Nicholas Thomson, and all of the Thomson group.

Thank you also to our fantastic collaborators Dr Corin Yeats and Prof. David Aanensen who have developed Pathogenwatch at the Centre for Genomic Pathogen Surveillance, and have extensively adapted it for Vibriowatch.

Thank you to Dr Josefina Campos (INEI-ANLIS Malbran, Argentina),
Dr Neelam Taneja and Nisha Singh (PGIMER Chandigarh, India), 
and Dr Yann Boucher (National University of Singapore),
who have advised us on Vibriowatch.

Lastly, but very importantly, we would
like to say thank you to our funders who have funded our work. These are the Bill and Melinda Gates Foundation, and also the University of Oxford, Wellcome Trust, and Wellcome Sanger Institute. 

Contact
-------

I will be grateful if you will send me (Avril Coghlan) corrections or suggestions for improvements to my email address alc@sanger.ac.uk


