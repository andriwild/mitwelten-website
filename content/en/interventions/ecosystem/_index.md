---
title: ecosystem
linkTitle: ECOSYSTEM STUDIES 
menu: {intervention: {weight: 10}}
---

{{< blocks/cover title="Ecosystem Studies" image_anchor="top" height="full" color="gray" >}}
{{< blocks/link-down color="secondary" >}}
{{< /blocks/cover >}}

<!-- New Section -->

{{% blocks/section color="primary" %}}
<div class="mx-auto" style="width: 90%">


One research approach in the Mitwelten project was based on natural science principles. By monitoring the ecosystems of the three field studies, we wanted to gain insight into the quality of biodiversity in the (peri-)urban habitats. Since it is not possible to measure and map the full richness of nature, we decided to analyze the presence of indicator species or families: five types of morphospecies of pollinating insects and the bird species. To complete the picture, human presence was also examined, as humans have a significant influence on (peri-)urban sites and to treat them as equal actors of the Mitwelt. By using the same systems in standardized circumstances in different habitats, we were able to make statements about the locations and compare them. The experiments for the investigations were designed in the interdisciplinary team and the sensor systems were developed to best answer ecological questions and minimize management efforts.


{{< figure src="/images/logo/mitwelten_logo.png" width="100%" >}}
{{% /blocks/section %}}



<!-- New Section -->

{{% blocks/section color="secondary" %}}
<div class="mx-auto" style="width: 90%">
  <h1 class="text-center">BIRD DIVERSITY</h1>

---

To learn more about the local bird life, we analyzed the three Field Study Sites. We first defined locations with different habitat types, recorded the singing activity with audio loggers (AudioMoth, https://www.openacousticdevices.info), and analyzed the bird species using a data pipeline based on the machine learning (ML) model BirdNET. The species identifications showed errors that had to be corrected: exclusions based on time and location (migratory season, time of day, habitat type), verification of improbable species with reports from the birding community, and sound recording verification by citizen scientists (prevalidation) and experts using the open-source software Label Studio. We categorized the sounds that led to wrong bird identifications in the peri-urban environment into five types: human voices or artifacts (anthropophony), weather sounds (geophony), other animal classes (e.g. water frog) or bird species (biophony), (Krause 2015). 
The main objectives were to develop an ML pipeline for the collected big data, to study the bird diversity and to compare the quality of the different peri-urban habitats. In addition, we were interested in characterizing the different soundscapes along a typical citizen walk in the park and to explore the possibilities of applying ML to improve the citizen's everyday sound experience.

For further information please read the open access publication ‘Bird Diversity in Peri-urban Areas of the City of Basel’. (Coming soon!)


</div>
{{% /blocks/section %}}




<!-- New Section -->

{{% blocks/section color="yellow" %}}

<div class="mx-auto" style="width: 90%">
  <h1 class="text-center">POLLINATOR DIVERSITY</h1>

----

To learn more about the local insect communities, we analyzed the Field Study Sites and defined locations in different habitat types. In accordance with entomological standards, we decided to work with cameras fixed above potted flowers to record insects that landed on the flower heads to identify five different morphospecies: honey bee, wild bee, bumblebee, hoverfly, and fly. Using a two-stage evaluation pipeline for systematic machine learning (ML) image processing, the blossoms of the potted species were first assigned and framed as an area in the image using YOLOv5 models for object recognition. Flower visitors were then searched for in these image sections, identified and finally assigned to one of the five morphospecies. The main goals were to examine our phytometer approach and to compare the ecological qualities of the places and habitat types within the field studies. We also gained insights into designing outdoor biological monitoring infrastructures by means in collaboration with citizen scientists.

For further information please read the open access publication ‘Bird Diversity in Peri-urban Areas of the City of Basel’. (Coming soon!)

</div>

{{% /blocks/section %}}



<!-- New Section -->

{{% blocks/section color="info" %}}

<div class="mx-auto" style="width: 90%">
  <h1 class="text-center">HUMAN PRESENCE</h1>

----

In addition to biological monitoring through sampling of birds and insects, we also recorded the presence of humans, since they should be treated in the same way. The main objective was to determine the number of anonymized individuals at specific locations at different times in order to study their possible influence on the ecosystem. Together with the nature conservation commission (Heide Kommission) and the park rangers, we designed a network of PAX counters that was created, maintained and repeatedly adapted to the seasonal needs of the rangers. The aim was to find out which places were most frequented, how many people were near vulnerable conservation sites, if the new bathing area reduced visitor pressure on a unofficial bathing area in the nature reserve, and if visitor management measures were effective.

For further information please read the open access publication ‘Bird Diversity in Peri-urban Areas of the City of Basel’. (Coming soon!)

</div>

{{% /blocks/section %}}
