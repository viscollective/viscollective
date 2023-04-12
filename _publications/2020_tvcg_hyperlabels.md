---
layout: publication
# Quotes make the : possible, otherwise you can type this without quotes
title: "HyperLabels: Browsing of Dense and Hierarchical Molecular 3D Models"
# Keys must be unique to each paper, see section below for more details
key: 2020_tvcg_hyperlabels
# Select one of the options below
type: paper 
# use this if this paper was previously a preprint and you need to preserve the old URL
# redirect_from: /publications/2017_preprint_lineage
# Uncomment the line below for publications which should only appear on a personal webpage
# personal: y

# Papers are ordered by year. However, in years with many papers, we want some ordering at a lower level. You can do 
# that by specifying an order for the papers of that year. For example, 2019-11 will put papers with values lower than 
# 2019-11 below that paper. Notice that sorting is lexicographic.  
order: 2020-02

# Auto-generates titles and alt-descriptors
shortname: Hyperlabels
# Add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/publications/
image: 2020_tvcg_hyperlabels.png
# Add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/publications/
image_large: 2020_tvcg_hyperlabels_teaser.png

# Authors in the "database" can be used with just their person "key"
authors:
- David Kouřil 
- Tobias Isenberg 
- Barbora Kozlikova
- meyer
- Eduard Gröller
- Ivan Viola
# A link to an internal blog post (use only the relative URL)
blog-post: 

# Include a shortened name for the journal or conference/proceedings
journal-short: TVCG
year: 2020

# Create BibTeX info, using one of the entry choices
# Articles have a "journal", and inproceedings have a "booktitle"
# Preprints are articles with the location of preprint mentioned in "journal"
# You can remove fields you don't need, or else leave them blank
# Try to include a DOI, or use the publisher URL below
# Specify new BibTeX fields by adding a new key and value inside "bib:"
bibentry: inproceedings
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics
  booktitle: 
  editor: 
  publisher: IEEE
  address: 
  doi: 10.1109/TVCG.2020.2975583
  url: 
  volume:
  number: 
  pages: 
  month:
  pmcid:

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award: 

# Provide a link to the publisher's webpage if no DOI is available
publisherURL: 

# Link to an official preprint server
preprint_server: 

# Links to a project hosted on VDL, or else externally on your own site
project: 


# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.
videos:  
 - name: "HyperLabels VIS talk"
   youtube-id: Tu2SSJjQI3c
   file:
 
# Provide a preprint and supplement pdf
pdf: 2020_tvcg_hyperlabels.pdf
supplement: 

# Extra supplements, such as talk slides, data sets, etc.
supplements:

# Supplemental, cc-by images. Make caption brief (at most 60 chars).
images:


# Link to the repository where the code is hosted
code: 

abstract: "<p>
We present a method for the browsing of hierarchical 3D models in which we combine the typical navigation of hierarchical structures in a 2D environment---using clicks on nodes, links, or icons---with a 3D spatial data visualization. Our approach is motivated by large molecular models, for which the traditional single-scale navigational metaphors are not suitable. Multi-scale phenomena, e. g., in astronomy or geography, are complex to navigate due to their large data spaces and multi-level organization. Models from structural biology are in addition also densely crowded in space and scale. Cutaways are needed to show individual model subparts. The camera has to support exploration on the level of a whole virus, as well as on the level of a small molecule. We address these challenges by employing HyperLabels: active labels that---in addition to their annotational role---also support user interaction. Clicks on HyperLabels select the next structure to be explored. Then, we adjust the visualization to showcase the inner composition of the selected subpart and enable further exploration. Finally, we use a breadcrumbs panel for orientation and as a mechanism to traverse upwards in the model hierarchy. We demonstrate our concept of hierarchical 3D model browsing using two exemplary models from meso-scale biology.
</p>"

---
