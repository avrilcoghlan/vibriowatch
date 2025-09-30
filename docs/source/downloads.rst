Downloading and sharing Vibriowatch data 
========================================

This section will cover:

* `Downloading data for a set of isolates`_.
* `Downloading data for a collection`_.
* `Sharing data with collaborators`_.
* `Plotting the tree and data for a Vibriowatch collection in Microreact`_.
* `Bulk downloads of all Vibriowatch data`_.

Downloading data for a set of isolates
--------------------------------------

You can download data for a set of isolates by first creating a list of the isolates you are interested in.

For example, this links to a `list of all publicly available isolates in Vibriowatch`_.
If you click on the list you will see a list like this (showing the top of the list):

.. _list of all publicly available isolates in Vibriowatch: https://pathogen.watch/genomes/all?access=public&genusId=662

.. image:: Picture141.png
  :width: 800

If you are interested in downloading the data for the top 5 isolates, you can click the boxes
beside their names:

.. image:: Picture142.png
  :width: 800

Then if you click on the purple button saying "5 Selected Genomes" at the top right of the webpage, you can click on
"Download data", and this will allow you to download data for those 5 genomes, such as:

* fasta files of the genomes
* metadata for the genomes (e.g. place and date of collection)
* AMR predictions - this says whether each isolate is predicted to be resistant (or not) to a set of antimicrobials
* AMR genes/mutations - this says whether each isolate has any of a set of known *V. cholerae* AMR genes and mutations
* Inctyper - this says whether each isolate is predicted to have plasmids
* MLST 
* stats - genome assembly statistics (e.g. N50)
* lineage - this is based on PopPUNK
* virulence predictions from the Vista tool - this says whether each isolate has any of a set of known *V. cholerae* virulence genes
* etc.

Downloading data for a collection
---------------------------------

You can also download data for a "collection" from Vibriowatch.

For example, this links to the `collection for the isolates sequenced by Chun et al 2009`_. 

.. _collection for the isolates sequenced by Chun et al 2009: https://pathogen.watch/collection/2c43jl3z2xs8-vibriowatch-collection-chun-et-al-2009

At the top right of the webpage for a collection, you will see a small "Downloads" button:

.. image:: Picture143.png
  :width: 50

If you click on this "Downloads" button, you will have the be able to choose to download data for the collection, such as:

* virulence predictions from the Vista tool - this says whether each isolate has any of a set of known *V. cholerae* virulence genes
* metadata for the genomes (e.g. place and date of collection)
* typing for the genomes, e.g. MLST and PopPUNK for identifying lineages, and IncTyper (for plasmid predictions)
* stats - genome assembly statistics (e.g. N50)
* AMR predictions - this says whether each isolate is predicted to be resistant (or not) to a set of antimicrobials
* AMR genes/mutations - this says whether each isolate has any of a set of known *V. cholerae* AMR genes and mutations
* a phylogenetic tree, e.g. in Newick (.nwk) format

Sharing data with collaborators
-------------------------------

You can share a Vibriowatch collection with your collaborators by clicking on the "Information" icon at the top right
of the webpage when you are viewing your collection:

.. image:: Picture149.png
  :width: 50

If you then choose "Shared: available to anyone with the link, no sign-in required" in the menu that appears,
you will be able to give the link for your collection (the address at the top of the webpage, something like:
https://pathogen.watch/collection/a1xycm9s9pvm-h22-and-close-relatives-1326-genomes) to your collaborators, and then they will be able
to view the collection too. 

Plotting the tree and data for a Vibriowatch collection in Microreact
---------------------------------------------------------------------

`Microreact`_ is a very nice tool that allows easy and pretty plotting of phylogenetic tree data, as well as metadata and other computed data (e.g. AMR and virulence predictions) beside the tree.

.. _Microreact: https://microreact.org/

It's possible to download all the metadata and computed data from a Vibriowatch collection and upload it into Microreact to re-plot it there.
This is particularly useful if you want to plot multiple types of data/metadata beside a phylogenetic tree (e.g. country, date of collection, presence/absence of virulence genes, etc.).

For example, this links to the `collection for the isolates sequenced by Chun et al 2009`_. 

.. _collection for the isolates sequenced by Chun et al 2009: https://pathogen.watch/collection/2c43jl3z2xs8-vibriowatch-collection-chun-et-al-2009

At the top right of the webpage for a collection, you will see a small "Downloads" button:

.. image:: Picture143.png
  :width: 50

If you click on this "Downloads" button, you will have the be able to choose to download data for the collection, 
and you can choose to download the tree as a .nwk format file, the metadata table, and the virulence gene predictions.
This should give you three files that you have downloaded, called something like:

* pathogenwatch-vibcl-2c43jl3z2xs8-vibriowatch-collection-chun-et-al-2009-collection-tree.nwk
* pathogenwatch-vibcl-2c43jl3z2xs8-vibriowatch-collection-chun-et-al-2009-metadata.csv
* pathogenwatch-vibcl-2c43jl3z2xs8-vibriowatch-collection-chun-et-al-2009-vista.csv

Then you can go to the `Microreact`_ website to upload the data.

.. _Microreact: https://microreact.org/

On the Microreact website, click on "UPLOAD" at the top right of the website. 
Then you will see a circle saying "Drop files here". Select the three files above (..collection-tree.nwk, ..metadata.csv, ..vista.csv)
on your computer (press down "Shift" on your keyboard to select three files at once), and drag and drop them into the "Drop files here" circle on the website.
You should see a box pop up like this:

.. image:: Picture144.png
  :width: 350

Press "Continue". Then a box will pop up asking you to select the "Main data file" from a menu. Select the "..metadata.csv" file.
Then it will ask you to select the ID column, and you can select "NAME" as the ID column. Press "Continue".
Then it will ask you to select the ID columns for the other files, and again select "NAME" as the ID columns for all the files. Press "Continue" again.

Then it should open the data in Microreact. You should see a panel with a map on the top left, with your tree on the top right, and with the metadata below them.

.. image:: Picture145.png
  :width: 900

You can colour the isolates in the tree and dots in the map by different values in the metadata table. If you scroll along the metadata
table to the right (drag the slider below the metadata table), you will find the column with the country of isolation of the isolates, which has
the heading "ISOLATION". Click on the "ISOLATION" heading in the metadata table. You should now see that the isolates in the tree and dots
on the map are coloured according to country where the isolates were collected:

.. image:: Picture146.png
  :width: 900

If you want to plot additional variables beside the tree, you can click on the "Controls" button at the top right of the tree panel:

.. image:: Picture147.png
  :width: 50

If you click on "Metadata blocks" in the menu that appears, you can click on "Serotype phenotype" and "Serogroup phenotype" and "ctxA" and "ctxB", to plot the serotype (e.g. Inaba/Ogawa) and
serogroup (e.g. O1/O139/O37/etc.) phenotypes and presence/absence of *ctxA* and *ctxB* genes beside the tree, and then press "X" at the top of the menu to close the menu. You can also
click "Legend" at the top right of the tree panel to see a legend. You should now see the serogroup and serotype and *ctx* gene presence/absence beside the tree:

.. image:: Picture148.png
  :width: 800

Bulk downloads of all Vibriowatch data
--------------------------------------

You can download all the data for *V. cholerae* from Pathogenwatch using the following links:

* https://pathogenwatch-public.ams3.cdn.digitaloceanspaces.com/Vibrio cholerae__amrsearch-snps-genes.csv.gz : AMR mutations and genes
* https://pathogenwatch-public.ams3.cdn.digitaloceanspaces.com/Vibrio cholerae__amrsearch.csv.gz : antimicrobial resistance predictions
* https://pathogenwatch-public.ams3.cdn.digitaloceanspaces.com/Vibrio cholerae__cgmlst.csv.gz : closest relatives (from core genome MLST)
* https://pathogenwatch-public.ams3.cdn.digitaloceanspaces.com/Vibrio cholerae__core.csv.gz : presence/absence of *V. cholerae* core genes
* https://pathogenwatch-public.ams3.cdn.digitaloceanspaces.com/Vibrio cholerae__fastas.zip : fastas files for all genomes (a very large file!)
* https://pathogenwatch-public.ams3.cdn.digitaloceanspaces.com/Vibrio cholerae__inctyper.csv.gz : plasmid prediction using IncTyper
* https://pathogenwatch-public.ams3.cdn.digitaloceanspaces.com/Vibrio cholerae__metadata.csv.gz : metadata for all genomes
* https://pathogenwatch-public.ams3.cdn.digitaloceanspaces.com/Vibrio cholerae__metrics.csv.gz : assembly statistics 
* https://pathogenwatch-public.ams3.cdn.digitaloceanspaces.com/Vibrio cholerae__mlst.csv.gz : MLST analyses
* https://pathogenwatch-public.ams3.cdn.digitaloceanspaces.com/Vibrio cholerae__poppunk2.csv.gz : PopPUNK lineage assignments
* https://pathogenwatch-public.ams3.cdn.digitaloceanspaces.com/Vibrio cholerae__vista.csv.gz : virulence gene predictions (using the Vista tool)

CholeraBook
-----------

If you would like to learn more about cholera genomics, you may also be interested in our `Online Cholera Genomics Course (CholeraBook)`_.

.. _Online Cholera Genomics Course (CholeraBook): https://cholerabook.readthedocs.io/

Contact
-------

I will be grateful if you will send me (Avril Coghlan) corrections or suggestions for improvements to my email address alc@sanger.ac.uk
