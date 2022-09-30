---
title       : "Gene trees and molecular dating"
subtitle    : "BSX-3139 Molecular Ecology and Evolution"
author      : Dr Axel Barlow
job         : "email: a.barlow.@bangor.ac.uk"
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : zenburn      # {zenburn, tomorrow, solarized-dark, ...}
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {selfcontained, standalone, draft}
knit        : slidify::knit2slides
logo        : LA_Full_colour_reversed.svg
biglogo     : A1_FullColour.svg
assets      : {assets: ../../assets}
license     : by-nc-sa
github:
  user: drabarlow
  repo: BSX-3139_gene_trees_mol_dating
  branch: "gh-pages"
---



<!-- adding bold and italic options -->
<style>
em {
  font-style: italic
}
strong {
  font-weight: bold;
}
</style>

## Gene trees and molecular dating

- What are gene trees?
- What can they be used for?
- What shapes the gene tree?
- Calibrating trees

---

## Gene tree

- Evolutionary history of a genetic locus, represented as a tree
- (not always an actual gene)
- Can be used to infer species or population histories*
- Any recombining genome has multiple loci, each with its own gene tree
- Easy to calculate using genetic data (often sequences)

---

## Gene tree terminology

<img src="./assets/img/term.png" alt="plot of chunk unnamed-chunk-1" width="90%" style="display: block; margin: auto;" />

--- .segue .dark 

## What can we use gene trees for?

---

## Gene trees in Molecular Ecology

<img src="./assets/img/trees_use.svg" alt="plot of chunk unnamed-chunk-2" width="80%" style="display: block; margin: auto;" />

---

## Grass snakes

<img src="./assets/img/helvetica.JPG" alt="plot of chunk unnamed-chunk-3" width="70%" style="display: block; margin: auto;" />

---

## Grass snakes

<embed src="./assets/img/2013-Mitochondrial_phylogeography_contact_zones_and_taxonomy_of_grass_snakes_(Natrix_natrix_N._megalocephala).pdf" title="plot of chunk unnamed-chunk-4" width="100%" height="500" type="application/pdf" />

---

## Glacial refugia

<img src="./assets/img/LGM_Europe_Map_v1.png" alt="plot of chunk unnamed-chunk-5" width="100%" style="display: block; margin: auto;" />

--- .segue .dark 

## What shapes the gene tree?

---

## Allele evolution

<img src="./assets/img/evol_tre.svg" alt="plot of chunk unnamed-chunk-6" width="100%" style="display: block; margin: auto;" />

---

## An example

<img src="./assets/img/div1.svg" alt="plot of chunk unnamed-chunk-7" width="100%" style="display: block; margin: auto;" />

---

## An example

<img src="./assets/img/div2.svg" alt="plot of chunk unnamed-chunk-8" width="100%" style="display: block; margin: auto;" />

---

## An example

<img src="./assets/img/div3.svg" alt="plot of chunk unnamed-chunk-9" width="100%" style="display: block; margin: auto;" />

---

## An example

<img src="./assets/img/div4.svg" alt="plot of chunk unnamed-chunk-10" width="100%" style="display: block; margin: auto;" />

---

## An example

<img src="./assets/img/div5.svg" alt="plot of chunk unnamed-chunk-11" width="100%" style="display: block; margin: auto;" />

---

## An example

<img src="./assets/img/div6.svg" alt="plot of chunk unnamed-chunk-12" width="100%" style="display: block; margin: auto;" />

---

## Observations

- Drift sorts the lineages into clades
- This takes time, we can't detect the divergence immediately
- We go through stages of complete/incomplete monophyly
- Mutation builds upon the clades, monophyly is retained [unless there is gene flow]
- In this example, the phylogeny does not represent the sequence of population splits
- The phylogenetic divergence times are older than the population splits
- Each locus goes through its own history of lineage sorting
- The unpredictability is reduced with smaller population sizes and older splits [more drift]
- These processes are the same for species-level phylogenies

--- &twocol

## Evidence from whole genome analysis

*** =left

<img src="./assets/img/cave_mono.svg" alt="plot of chunk unnamed-chunk-13" width="100%" style="display: block; margin: auto;" />

*Barlow et al. 2018. Nat. Ecol. Evol*


*** =right

- Brown bear, polar bear, extinct cave bears
- Aligned nuclear genomes, divided into 25 kb blocks
- Only 50 % of blocks show the correct species relationships
- Rest are a mix of all possible topologies

--- .segue .dark 

## Calibrating trees

--- &vcenter

## Branch length are typically scaled to genetic distance

<img src="./assets/img/brown_undated.svg" alt="plot of chunk unnamed-chunk-14" width="100%" style="display: block; margin: auto auto auto 0;" />

--- &vcenter

## Imagine if they could be scaled to time

<img src="./assets/img/brown_dated.svg" alt="plot of chunk unnamed-chunk-15" width="100%" style="display: block; margin: auto auto auto 0;" />

--- .class bg:white

## Molecular clock hypothesis

- Substitutions seem to occur at an approximately constant rate
- This means genetic distance is proportional to time
- Sometimes the relationship breaks down (divergent lineages, saturation, selection)
- At the population level it generally works well

<img src="assets/fig/unnamed-chunk-16-1.png" alt="plot of chunk unnamed-chunk-16" width="60%" style="display: block; margin: auto;" />

--- .class #id

## Methods of calibrating the tree

- If we assume a molecular clock, we can use external sources of information to calibrate the tree
- **Genetic distance per unit time**

### There are 3 (interdependent) parameters of interest:

- `tip ages`
- `node ages`
- `substitution rate`

--- &twocol

## Sabretooth cat genera

- When did they diverge from living cats?
- How diverged are they from one another?

*** =left

### *Smilodon*

<img src="./assets/img/smilodon_skull.jpg" alt="plot of chunk unnamed-chunk-17" width="100%" style="display: block; margin: auto;" />

*** =right

### *Homotherium*

<img src="./assets/img/Homotherium_serum.jpg" alt="plot of chunk unnamed-chunk-18" width="100%" style="display: block; margin: auto;" />

*Sergiodlarosa, CC BY-SA 3.0*

---

## Molecular dating of sabretooth cats

<img src="./assets/img/sabre_tree.svg" alt="plot of chunk unnamed-chunk-19" width="85%" style="display: block; margin: auto;" />


--- &thankyou

## Next time:

**Ancient DNA 1**



