---
title: "Accessible maths e-resources"
author: 'Emma Cliffe, Skills Centre: MASH, University of Bath'
date: 'TALMO, June 2020'
site: bookdown::bookdown_site
lang: en
documentclass: article
classoption: a4paper
fontsize: 10pt
geometry: margin=2.5cm
output:
  clavertondown::word_clav:
    toc: true
    number_sections: true
    keep_md: true
  clavertondown::gitbook_clav:
    split_by: section
    config:
      download: [["Notes.pdf","Standard print PDF"], ["NotesClear.pdf","Clear print PDF"], ["NotesLarge.pdf","Large print PDF"], ["Notes.docx","Accessible Word document"], ["Notes.epub","Accessible EPub book" ]]
      sharing: no
  clavertondown::pdf_clav:
    latex_engine: pdflatex
    dev: pdf
    keep_tex: true
    fig_caption: false
    toc: true
  clavertondown::html_clav:
    toc: true
  clavertondown::epub_clav:
    toc: true
---

\newpage
\pagenumbering{arabic}

# Where do you start? {-}

* Why is it important?
* What do you need to do?
* How do you get started?

# Why is it important?

* New law
* Processing of concepts - copy across
* All students may need to work with text in new ways in the new world e.g. Using their ebook reader to get away from their laptop

# What do you need to do?

* Modes of presentation
* Structure

# How do you get started?

## Authoring in Word

Copy basic idea in and then link to the Word stuff you already have

* Workshop
* Entering equations

## What about LaTeX?

### Hobson's choice

* MathAltNotes and why you should avoid it
* Other ways 

### Markdown/RMarkdown/Bookdown

\BeginKnitrBlock{theorem}<div class="bookdown-theorem" id="thm:thm1"><strong>(\#thm:thm1) </strong>A labeled theorem here.</div>\EndKnitrBlock{theorem}

\BeginKnitrBlock{proposition}<div class="bookdown-proposition" id="prp:prop1"><strong>(\#prp:prop1) </strong>A labeled theorem here.</div>\EndKnitrBlock{proposition}

\BeginKnitrBlock{lemma}<div class="bookdown-lemma" id="lem:lem1"><strong>(\#lem:lem1) </strong>A labeled theorem here.</div>\EndKnitrBlock{lemma}

\BeginKnitrBlock{theorem}<div class="bookdown-theorem" id="thm:thm2"><strong>(\#thm:thm2) </strong>A labeled theorem here.</div>\EndKnitrBlock{theorem}

\BeginKnitrBlock{corollary}<div class="bookdown-corollary" id="cor:cor1"><strong>(\#cor:cor1) </strong>A labeled theorem here.</div>\EndKnitrBlock{corollary}

### Work in progress: Claverton Down

\BeginKnitrBlock{Thought}<div class="newtheorem"><span class="Thought" id="Thought:tho1"><strong> Thought (\#Thought:tho1) </strong></span>A labeled theorem here.</div>\EndKnitrBlock{Thought}

\BeginKnitrBlock{Nugget}<div class="newtheorem"><span class="Nugget" id="Nugget:nug1"><strong> Nugget (\#Nugget:nug1) </strong></span>A labeled theorem here.</div>\EndKnitrBlock{Nugget}

This is a test. Now go to \@ref(prp:prop1).

## Accessible diagrams

Copy from the email and include a Desmos sine wave in case we have time

# Further information

* sigma
* stemenable

# Thanks & questions

* Where you can download this
* How you can contact me

<!--chapter:end:index.Rmd-->

