---
title: Collection History
layout: about
permalink: /history.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://cdil.lib.uidaho.edu/images/palouse_sm.jpg" %}

## Collection History

This collection has a history. I am practicing how to use **Markdown**. _This text is in Italics._ This is a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/).

#### Here is a list of items:

* This is the first list item.
* The second list item.
* The third.

#### And a numbered list of items:

1. The first item.
 With a line underneath it.
2. And the second item.
 With a line underneath it.

## Featured Includes

### Audio

#### Audio clip from collection (auto-caption)

{% include feature/audio.html objectid="psychiana004" width="50" %}

#### External audio clip (w/caption)

{% include feature/audio.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/good_news_04.mp3" width="50" caption="Radio program episode outlines the purpose of the 'Good News' radio program, to broadcast positive and peaceful things rather than negative." %}

### Images

#### Image from the collection (auto-captions)

{% include feature/image.html objectid="psychiana027" width="75" %}

#### Two images from the collection (w/captions)

{% include feature/image.html objectid="psychiana005;psychiana066" width="75" caption="I Talked With God Advertisement;William Walter DeBolt at his Desk" %}

#### Multiple images from the collection (auto-captions)

{% include feature/image.html objectid="psychiana018;psychiana019;psychiana020" %}

#### External image (no caption)

{% include feature/image.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_f7_miscellanious_negatives_010.jpg" width="75" caption=" " alt="Copies of the June 1948 edition of the The Way: A Quarterly Publication of the Psychiana Religion" %}

#### External image (w/caption and a link)

{% include feature/image.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_psychiana_photographs_001.jpg" width="75" caption="Photograph of Corner Drug Store in Moscow, ID" link="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_psychiana_photographs_001.jpg" %}

### Documents

#### PDF from collection (auto-caption)

{% include feature/pdf.html objectid="psychiana006" width="50" %}

#### PDF from collection (w/caption)

{% include feature/pdf.html objectid="psychiana009" width="50" caption="A flyer featuring an illustration of a lighthouse on the coast representing the light of God within the viewer." %}

#### External PDF (w/caption)

{% include feature/pdf.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b7_f13_028.pdf" width="50" caption="A flyer to all Americans advertizing Frank B. Robinson's newest book." %}

### Videos

#### Video from collection (auto-caption)

{% include feature/video.html objectid="psychiana001" width="75" %}

#### External Vimeo video (w/caption)

{% include feature/video.html objectid="https://vimeo.com/329958483" width="50" caption="Psychiana Inc. - The World’s Largest Mail-Order Religion" %}

#### External YouTube video (w/caption)

{% include feature/video.html objectid="https://www.youtube.com/watch?v=bPmae07GKv0" width="50" caption="Psychiana - Frank B. Robinson Original Recordings - Radio Show Broadcast - 1935" %}

### Bootstrap Features

#### Button

{% include feature/button.html text="CollectionBuilder Website" link="https://collectionbuilder.github.io/" color="success" %}

#### Alert

{% include feature/alert.html text="This is an **_alert_** feature" color="warning" align="center" %}

#### Modal

{% include feature/modal.html button="This is a modal feature to click on" title="when clicked:" text="Here is more information provided after you click on the modal feature." color="primary" %}

#### Card

{% include feature/card.html header="Card Example" text="The card features an image from the collection as a caption" objectid="psychiana018" width="50" centered=true %}
