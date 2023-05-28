---
description: '13'
---

# 4.3 Trophic Niche Analysis

## Trophic position

* 1 base - <img src="../.gitbook/assets/Screen Shot 2023-05-12 at 11.34.08 AM.png" alt="" data-size="line">
* Assumptions:&#x20;
  * Consumers acquire N from one source&#x20;
  * δ15Nbase captures full variation in δ15N
  * Consumer is at steady state with the diet&#x20;
  * lambda is valid for the δ15Nbase&#x20;
  * ∆15N is valid for the system&#x20;
* Mass balance mixing models:&#x20;
  * need δ values for consumer,  all diet sources, and the trophic fractionation ∆ between diet & consumer&#x20;
* Trophic discrimination factors (TDF)&#x20;
  * source mixing polygon has to overlap all the consumer values, otherwise you've missed a source.&#x20;
  * for every additional source, you need an additional isotope&#x20;
* Bayseian mixing models & R packages&#x20;
* Best practices for building a mixing model

<figure><img src="../.gitbook/assets/Screen Shot 2023-05-12 at 10.30.56 AM.png" alt=""><figcaption></figcaption></figure>

## References

#### <mark style="color:purple;">Conti-jerpe 2020</mark>

C and N ratios calculated in 7 different species of coral for both host and symbiont. The authors found that the host was usually depleted in C and enriched in N, following our expectations for trophic fractionation. They additionally made some unsubstantiated claims about the relationship between heterotrophy:photosynthesis and morpholgoy and bleaching tolerance. Good example of SIBER analysis comparing the overlap of ellipses.&#x20;

<figure><img src="../.gitbook/assets/Screen Shot 2023-05-26 at 12.51.30 PM.png" alt="" width="375"><figcaption></figcaption></figure>

#### <mark style="color:purple;">Muscatine 1989</mark>

The first study to ever do SIA on separate host and sym. They found that both host and sym decrease δ13C with depth, and that the difference between them (∆C) increased with depth as well. This supports more recent evidence of isotope fractionation in corals. This is a good study to get some basic values if needed. &#x20;

#### <mark style="color:purple;">Muscatine 1994</mark>

This was a partner study to Muscatine 1989, (which addressed C) looking at trends in δ15N over depth. They did not find changes in δ15N across depth gradients, but did find the expected results that symbionts had lower δ15N values than the host because of trophic fractionation (although they did not understand WHY at all). Good study to get N values if needed. &#x20;

#### <mark style="color:purple;">Maier 2010</mark>

The authors conducted δ13C and δ15N SIA on 3 species along a depth gradient. They found that δ15N and δ13C decreased along a depth gradient, but that ∆C host-sym did not change along the depth gradient. The authors present ideas about DIN limitation in corals, and also propose that δ15N and δ13C values may be representative of potential life strategy where energy is either invested in tissue growth and maintenacne or in fast skeletal growth at the expense of some tissue.&#x20;

#### <mark style="color:purple;">Swart 2005a</mark>

The authors monitored SIA N and C values in host, symbiont, and skeleton over a two year period. (δ15N host +6.6 ‰, sym +4.7 ‰ / δ13C host -13.3 ‰, sym -12.2 ‰, skeleton \~+1.4 ‰). They did not find differences in sites, and only found seasonal variation in C. They also evaluated the effects of sewage and proximity to people on the isotopes and did not find any patterns.

#### <mark style="color:purple;">Alamaru 2009</mark>

Authors investigated SIA C and N in two morphologically different species of coral (one branching w/ small polyps, other massive w/ large polyps) and were the first to quantify the SIA of lipids for both fractions. They found δ13C decreases for sym and host and in both lipids by 7-8 ‰ across the light gradient, espeically when compared to photosynthesis. δ15N did not change much across the depth gradient. Generally, lipids were δ13C depleted by  -3.5 ‰ compared to their host. Morphological differences that led to feeding strategy differences were associated with isotope enrichment. C:N decreases with depth, possibly reflecting a reduction in the lipid storage at depth.&#x20;

#### <mark style="color:purple;">Post 2002</mark>

This paper presents the best methods for assessing trophic level and determining baseline/end member isotope values. They give equations and assumptions for different TP models. Their work is based on snails and mussels in lakes.&#x20;

#### <mark style="color:purple;">Einbinder 2009</mark>

The authors investigated depth related changes in δ13C and morphology. They found that the highly branching species S. pistilatta shifted from a hemispherical shaped colony to a more platelike colony shape with depth, and smaller colonies in deep environments. The δ13C of the host coral tissue changed from a value of –15‰ in shallow water to –23‰ at the deep reef. The ∆C host-sym change from 0-30m but then remained constant from 30-60m.&#x20;

#### <mark style="color:purple;">Price 2021</mark>

The authors conducted four analyses of bulk SIA in seven species of coral to try to quantify the heterotrophy - symbiosis relationship. δ13C and δ15N host-symbiont revealed strong patterns but also exhibited an inverse relationship, where heterotrophy was associated with more negative δ13C values and more positive δ15N values. A SIBER analysis tested overlap of ellipses which did not always follow the expected pattern of host enrichment in both C and N. Bayesian mixing model analysis unraveled the relative contribution of zoop, POM, and DIM (dissolved inorganic matter) which aligned with the first two analyses. Interestingly the SIBER and Bayesian analyses didn't agree. This study emphasized that the use of isotopes may not always reflect hetero- vs autotrophy, but also proportion of resources shared between sym and host, as well as differential allocation of resources.&#x20;

#### <mark style="color:purple;">Sturaro 2021</mark>

Authors analyzed SIA for 6 species of coral under depth, season, and site differences. They found that site and depth had impacts on trophic niche plasticity. Corals fom more variable environments had larger niches for both host and symbiont than from more stable environments. Deeper corals had niches that indicated a higher degree of heterotrophy than shallow corals. No differences found in diet by season. One aposymbiotic coral exhibited a niche that did not overlap with the symbiotic coral, and it had significantly lower δ13C and higher δ15N values than its symbiotic counterparts.&#x20;

#### <mark style="color:purple;">Tremblay 2015</mark>

#### <mark style="color:purple;">Skinner 2022</mark>

#### <mark style="color:purple;">Swart 2005b</mark>

#### <mark style="color:purple;">Radice 2019</mark>

#### <mark style="color:purple;">Lesser 2010</mark>

#### <mark style="color:purple;">Chikaraishi 2009</mark>
