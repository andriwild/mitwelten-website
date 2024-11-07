---
title: ecosystem
linkTitle: ECOSYSTEM STUDIES 
menu: {intervention: {weight: 10}}
---

{{< blocks/cover title="Citizen Science based Ecosystem Studies" image_anchor="top" height="full" color="gray" >}}
{{< blocks/link-down color="secondary" >}}
{{< /blocks/cover >}}



<!-- New Section -->

{{% blocks/section color="primary" %}}
<div class="mx-auto" style="width: 90%">


One research approach in the _Mitwelten project_ was based on natural **science principles**. By monitoring the ecosystems of the three field studies, we wanted to gain insight into the quality of biodiversity in the (peri-)urban habitats. Since it is not possible to measure and map the full richness of nature, we decided to analyze the presence of indicator species or families: five types of morphospecies of pollinating insects and the bird species. 

To complete the picture, human presence was also examined, as humans have a significant influence on (peri-)urban sites and to treat them as equal actors of the _Mitwelt_. By using the same systems in standardized circumstances in different habitats, we were able to make statements about the locations and compare them. The experiments for the investigations were carried out by the interdisciplinary team and the sensor systems were developed to best answer ecological questions and minimize management efforts.


{{< figure src="/mitwelten-website/images/logo/mitwelten_logo.png" width="100%" >}}

{{% /blocks/section %}}




<!-- New Section -->

{{% blocks/section color="secondary" %}}
<div class="mx-auto" style="width: 90%">
  <h1 class="text-center">BIRD DIVERSITY</h1>

---

<p class="text-center">
How can bird species in different habitat types be identified and compared using audio logger recordings and open source ML models?
<p>
<br>
<div class="row align-items-start">
    <div class="col-md-6">
        <figure>
            <img src="/mitwelten-website/images/interventions/ecosystem/BirdDiversity.png" width="100%" alt="Bird identification based on extensive sound recordings and ML evaluation. 2021-2023">
	        <figcaption><p style="font-size:11px; text-align:right;">Bird identification based on extensive sound recordings and ML evaluation. 2021-2023.</p></figcaption>
        </figure>
    </div>
    <div class="col-md-6">
    <h3>Introduction</h3>
    <p>To learn more about the local bird life, we analyzed the three Field Study Sites. We first defined locations with different habitat types, recorded the singing activities with audio loggers (AudioMoth, https://www.openacousticdevices.info), and analyzed the bird species using a data pipeline based on the machine learning (ML) model BirdNET. 
    </p>
    </div>
</div>
<br>
<br>

<h3>Data Collection and Methods</h3>

The species identifications showed errors that had to be corrected: exclusions based on time and location (migratory season, time of day, habitat type), verification of improbable species with reports from the birding community, and sound recording verification by citizen scientists (prevalidation) and experts using the open-source software Label Studio. We categorized the sounds that led to wrong bird identifications in the peri-urban environment – but also enriched it as a cacophony of sounds – into five types: human voices or artifacts (anthropophony), weather sounds (geophony), other animal classes (e.g. water frog) and bird species (biophony), (Krause 2015). 

<br>
<h3>Objectives and Findings</h3>

The goal was to develop an ML pipeline for the analysis of the collected big data, to identify the bird species and to compare the quality of the different peri-urban habitats. In addition, we were interested in characterizing the different soundscapes and to explore the possibilities of applying ML to improve the public’s everyday sound experience.

For further information please read the open access publication ‘Bird Diversity in Peri-urban Areas of the City of Basel’. (Coming soon!)

{{% /blocks/section %}}




<!-- New Section -->

{{% blocks/section color="teal" %}}
<div class="mx-auto" style="width: 90%">
  <h1 class="text-center">POLLINATOR DIVERSITY</h1>

---

<p class="text-center">
How can pollinating insects be determined by ML analysis of photos taken at regular intervals?
<p>
<br>
<div class="row align-items-start">
    <div class="col-md-6 align-items-end">
    <h3 class="text-end">Introduction</h3>
    <p class="text-end">
To learn more about the local insect communities, we analyzed the Field Study Sites and defined locations in different habitat types. In accordance with entomological standards, we used cameras mounted above potted flowers to take photos of flower-visiting insects at regular intervals.
    </p>
    </div>
    <div class="col-md-6">
        <figure>
            <img src="/mitwelten-website/images/interventions/ecosystem/PollinatorDiversity.jpg" width="100%" alt="Determining pollinating insects using ML analysis of large photo datasets. 2021-2023.">
	        <figcaption><p style="font-size:11px; text-align:right;">Determining pollinating insects using ML analysis of large photo datasets. 2021-2023.</p></figcaption>
        </figure>
    </div>
</div>
<br>
<br>

<h3>Data Collection and Methods</h3>

We distinguished between five different morphospecies: honey bee, wild bee, bumblebee, hoverfly, and fly. A YOLOv5-based machine learning (ML) model was used to first identify the blossoms in the photos and subsequently the insects on the blossoms. 


<br>
<h3>Objectives and Findings</h3>

The main goal was to develop and examine our phytometer approach and to compare the ecological qualities of the places and habitat types within the field studies. We also gained insights into the assembly and maintenance of biological monitoring infrastructures and data validation processes involving citizen scientists.

For further information please read the open access publication ‘Bird Diversity in Peri-urban Areas of the City of Basel’. (Coming soon!)

{{% /blocks/section %}}





<!-- New Section -->

{{% blocks/section color="yellow" %}}
<div class="mx-auto" style="width: 90%">
  <h1 class="text-center">HUMAN PRESENCE</h1>

---

<p class="text-center">
How can human presence be identified in local recreation areas and nature reserves?
</p>
<br>
<div class="row align-items-start">
    <div class="col-md-6">
        <figure>
            <img src="/mitwelten-website/images/interventions/ecosystem/HumanPresence.jpg" width="100%" alt="Human presence identification in recreational areas and nature reserves. 2021-2023.">
	    <figcaption><p style="font-size:11px; text-align:right;">Human presence identification in recreational areas and nature reserves. 2021-2023.</p></figcaption>
        </figure>
    </div>
    <div class="col-md-6 align-items-end">
    <h3>Introduction</h3>
    <p>
In addition to biological monitoring through sampling of birds and insects, we also recorded the presence of humans, since they should be treated as equal habitat actants. 
    </p>
    </div>
</div>
<br>
<br>

<h3>Data Collection and Methods</h3>

The main objective was to determine the number of anonymized individuals at specific locations at different times in order to study their possible influence on the ecosystems. Together with the nature conservation commission (Heide Kommission) and the park rangers, we designed a network of PAX counters that was assembled and maintained by interdisciplinary teams. 
<br>

<h3>Objectives and Findings</h3>

The aim was to find out which places were most frequented, how many people were near vulnerable conservation areas, if the new bathing area reduced visitor pressure on an unofficial bathing area in the nature reserve, and if visitor management measures were effective.

For further information please read the open access publication ‘Bird Diversity in Peri-urban Areas of the City of Basel’. (Coming soon!)

{{% /blocks/section %}}
