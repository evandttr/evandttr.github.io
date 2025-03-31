---
layout: page
title: "Handwritten Text Recognition" 
---

At Penn Libraries, I worked with developers and librarians to design a project that harnessed open-source AI-powered text recognition technologies to create transcriptions of over a thousand manuscripts from the university's digitized special collections. The project was focused on a collection of medical dissertations from the beginning of the 19th century and used the Python-based tool Kraken to train models based on collections of transcribed dissertations. The results of the project are summarized in a [blog post](https://uniqueatpenn.wordpress.com/2024/08/28/a-thousand-scripts-one-model-transcribing-19th-century-penn-medical-dissertations-using-handwritten-text-recognition/) featured on the Unique at Penn a blog of the University of Pennsylvania Libraries.

![378seg](https://github.com/user-attachments/assets/3e025b4f-fed3-4a68-9554-917a30ed8b15)
A segmented image from one the medical dissertations included in the project [An Inaugural Dissertation on Dysentery](https://openn.library.upenn.edu/Data/0002/html/378_748_pom_10_9.html) (378.748 POM 10.9)  

![378tran](https://github.com/user-attachments/assets/d2ba7474-bbc9-4037-b0a0-1b1455f88d96)
A corrected transcription from An Inaugural Dissertation on Dysentery (378.748 POM 10.9). The excerpted text reads: “being repeated as often as the state of the system should demand it; but during some seasons when the system appears disposed to fall into a typhus condition, caution in the use of bloodletting becomes necessary; but generally in our climate […]”

<div style="text-align: center;">
  <hr style="width: 50%; margin: 2em auto;" />
</div>

As a graduate fellow at Princeton's [Center for the Digital Humanities](https://cdh.princeton.edu/), I designed and implemented a project to make a 16th-century manuscript held in Princeton's Special Collections more accessible to researchers using AI-powered [Handwriting Text Recognition](https://en.wikipedia.org/wiki/Handwriting_recognition). This technology represents a powerful means of promoting access to cultural heritage, providing ways to extract text from cultural heritage materials and make otherwise static images of manuscripts searchable. And what's more, the surprisingly intuitive tools on the market today are a great way to introduce students to manuscript studies and paleography. 

The manuscript I worked to transcribe (cataloged as [Notes de lecture, ca. 1578-1612.](https://catalog.princeton.edu/catalog/9960613933506421)) is a [commonplace book](https://en.wikipedia.org/wiki/Commonplace_book), or a compilation of reading notes, quotations, and observations collected from other books by an anonymous author. I used the platform [Transkribus](https://readcoop.eu/transkribus/) to develop and train a handwriting recognition model and to enrich and insert tags into an excerpted transcription of the manuscript. The excerpted PDF below depicts one simple output realized using this method: a searchable, highlightable scan of the manuscript from which single lines can be copied, and raw text can be easily extracted. The tags and encoding are visible as colored underlining marking abbreviations, comments, errors, and unclear text - all tagged words are catageorized in the last pages. 

<iframe src="https://drive.google.com/file/d/1SQkvbfOu2ys4i31y9GBykTMWZb1DXyiJ/preview" width="640" height="480" allow="autoplay"></iframe>
