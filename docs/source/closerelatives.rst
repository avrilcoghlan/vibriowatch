Finding closely related isolates
================================

In this section, we will describe how you can:

* `Use cgMLST to find close relatives of your isolate`_.
* `Build a phylogenetic tree of their isolate and its closest relatives`_.

Use cgMLST to find close relatives of your isolate
--------------------------------------------------

Since the MLST scheme of `Octavia et al 2013`_ was based on just seven genes, more recently `Liang et al 2020`_ have created a 'core genome MLST' (cgMLST) scheme for *V. cholorae*. This is based on 2443 core genes, that is genes that are present in almost all *V. cholorae* isolates sequenced by 2020. In VibrioWatch, we use this core genome MLST scheme to place isolates into clusters of closely related isolates. 

.. _Octavia et al 2013: https://pubmed.ncbi.nlm.nih.gov/23776471/

.. _Liang et al 2020: https://pubmed.ncbi.nlm.nih.gov/32540931/

For example, isolate HCUF_O1 is an isolate collected in Haiti in 2010, sequenced by `Hasan et al 2012`_. 

.. _Hasan et al 2012: https://pubmed.ncbi.nlm.nih.gov/22711841/

You can search for isolate HCUF_01 in Vibriowatch by clicking on the three small horizontal bars at the top left of the Pathogenwatch website:

.. image:: Picture9.png
  :width: 150
  
This will bring up a menu:

.. image:: Picture10.png
  :width: 150
  
If you click on 'All Genomes' in the menu, you will then see a list of all the genomes in Pathogenwatch. 
A search bar will now appear at the top left: 

.. image:: Picture22.png
  :width: 150
  
If you type 'HCUF' in the search bar, it will find isolate HCUF_01, and you can click on the isolate's name to go to its report page. The top of its report page shows that HCUF_01 has Sequence Type 69 (ST69) in the Octavia scheme, so likely belongs to the current pandemic lineage (7PET lineage):

.. image:: Picture26.png
  :width: 650
  
If you scroll down the report page for HCUF_01, you will come to the 'core genome clustering' (cgMLST) section:

.. image:: Picture27.png
  :width: 650
  
This shows that HCUF_01 belongs to a cgMLST cluster of 1049 isolates, when a threshold of 10 base differences (10 SNPs) is used to define clusters (ie. when any two isolates that differ by 10 or fewer SNPs in the 2443 core genes are put into the same cgMLST cluster). 

Build a phylogenetic tree of their isolate and its closest relatives
--------------------------------------------------------------------

Bla bla

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

