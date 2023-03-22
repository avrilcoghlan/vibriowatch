Predicting virulence genes
==========================

This section will cover:

* `Short guide for those in a hurry: does my isolate express cholera toxin`_.
* `Predict virulence genes in your isolate`_.

Short guide for those in a hurry: does my isolate express cholera toxin
-----------------------------------------------------------------------

Cholera toxin (CT) is a toxin usually produced by *Vibrio cholerae* of the current pandemic lineage (7PET lineage),
and is a protein that causes profuse, watery diarrhoea.

Cholera toxin is encoded by the `ctxA`_ and `ctxB`_ genes.

A quick way to find out whether your isolate likely expresses cholera toxin is to look at the predicted virulence genes for your isolate in Vibriowatch.

Once you have sequencing reads or a genome assembly for your isolate to Vibriowatch (see `Is my isolate Vibrio cholerae? <https://vibriowatch.readthedocs.io/en/latest/assemblies.html#short-guide-for-those-in-a-hurry-is-my-isolate-vibrio-cholerae>`_), Vibriowatch will display a piechart showing the species of your isolates are, e.g.:

.. image:: Picture7.png
  :width: 650

To view the report pages for your isolates, which will tell you their predicted virulence genes, you need
to click on the 'View genomes' link in the middle of the piechart.
  
This will bring up a list of your isolates in Vibriowatch, looking something like this:

.. image:: Picture8.png
  :width: 650
  
To go to the report page for a particular isolate, click on the link on the left in the 'Name' column, e.g. '1_S1_L001'.

If you scroll down the 'report page' for your isolate, you will find a section with the heading 'Virulence Genes'. 

For example, here is 'Virulence Genes' part of 
the report page for an isolate HCUF-01:

.. image:: Picture89.png
  :width: 650

The tick next to 'ctxA' shows that the cholera toxin gene `ctxA`_ is present. 
Because this isolate probably has `ctxA`_, it probably produces cholera toxin, so will give rise to severe cholera.

.. _ctxA: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07330

(Note: there is currently a problem predicting gene *ctxB* in Vibriowatch, which we are currently working on fixing.)

If you found this useful, you may want to read through the rest of the tutorial to find out more details.

Predicting additional virulence genes in your isolate
-----------------------------------------------------

It is well described that certain 'virulence genes' can make *Vibrio cholerae* more virulent, causing more severe disease. The most important virulence genes for *V. cholerae* are the `ctxA`_ and `ctxB`_ genes, which encode the cholera toxin and also the `tcpA`_ gene which encodes the toxin coregulated pilus, which is important for colonisation of the host. The `ctxA`_ and `ctxB`_ genes are almost always found in isolates belonging to the current pandemic lineage (7PET lineage), but are occasionally found in isolates of other lineages too. 

As well as `ctxA`_, `ctxB`_, and `tcpA`_, *V. cholerae* isolates can also have some 
other virulence genes of lesser importance, such as additonal toxin genes `zot`_, `ace`_, `hlyA`_, `makA`_ and `rtxA`_. 

.. _ctxA: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07330

.. _ctxB: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07325

.. _tcpA: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS04280

.. _zot: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07335

.. _ace: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07340

.. _hlyA: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS14860

.. _makA: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS18340

.. _rtxA: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07295

Vibriowatch uses a tool called ‘VISTA’, based on BLAST, to identify virulence genes in *V. cholerae* genomes.
Let's look again at the section of the report page on 'Virulence Genes' for isolate HCUF-01: 

.. image:: Picture89.png
  :width: 650
  
The ticks show that the intestinal colonisation gene  `ompU`_, regulatory gene,
`rpoS`_, and toxin genes `ctxA`_, `hlyA`_, `toxR`_, `ace`_, `makA`_, and `zot`_ genes are present. There is a '~' symbol for the `ctxB`_ gene, indicating that there was a partial match to it. This could either mean that the `ctxB`_ gene is truncated in this isolate, or that there are one or more SNPs in `ctxB`_ in this isolate. 

.. _ompU: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS03340

.. _rpoS: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS02845

.. _ctxA: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07330

.. _hlyA: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS14860

.. _toxR: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS05040

.. _ace: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07340

.. _makA: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS18340

.. _zot: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07335

.. _ctxB: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07325

It seems that this isolate has `ctxA`_ and likely has `ctxB`_, and that there is one or more SNP in its `ctxB`_ gene, since `ctxB`_ is known to have several circulating SNPs in the *V. cholerae* species (see `Lee et al 2021`_). Because this isolate probably has both `ctxA`_ and `ctxB`_, it probably produces cholera toxin, so will give rise to severe cholera.

.. _ctxB: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07325

.. _ctxA: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07330

.. _Lee et al 2021: https://pubmed.ncbi.nlm.nih.gov/34566903/

Below the Virulence gene list, there are also some virulence gene clusters listed, such as the TCP cluster, where the TCP cluster includes genes *tcpABCDEFHIJNQRST*, the Lux operon includes genes *luxOPQSU*, the RTX operon includes *rtxABCD*, and the MSHA pilus includes *mshABCDEFGHIJKMN*. 
The TCP cluster contains the important virulence gene `tcpA`_ and is part of the 'Vibrio Pathogenicity Island-1' (VPI-1), a genomic island often found in isolates of *V. cholerae* that belong to the current pandemic lineage (7PET lineage).

.. _tcpA: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS04280

In the example above, the isolate has a partial hit to `rtxA`_ in the RTX operon, which as for `ctxB`_ gene (see above), may either mean that the `rtxA`_ gene is truncated in this isolate, or that there are one or more SNPs in the `rtxA`_ gene in this isolate.

.. _rtxA: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07295

.. _ctxB: https://biocyc.org/gene?orgid=GCF_900205735&id=FY484_RS07325

Contact
-------

I will be grateful if you will send me (Avril Coghlan) corrections or suggestions for improvements to my email address alc@sanger.ac.uk

