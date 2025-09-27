---
layout: default
title: Home
---

<!-- The script below makes it possible to click on abstracts for papers -->

<script>
  function toggleAbs(id, link){
    const box = document.getElementById(id);
    const show = (box.style.display === 'none' || box.style.display === '');
    box.style.display = show ? 'block' : 'none';
    link.textContent = show ? '[Close]' : '[Abstract]';
  }
</script>

I am a Postdoctoral Research Fellow at [Nuffield College, University of Oxford](https://www.nuffield.ox.ac.uk), where I completed my PhD in 2024. My dissertation was recently awarded the [Best PhD Thesis Prize in Sociology](https://ecsrnet.eu/ecsr-prize-for-best-phd-thesis/) by the European Consortium for Sociological Research (ECSR).  

I study social stratification with a focus on education. My current research examines the potential and limitations of school interventions in reducing inequalities in educational outcomes by socioeconomic and ethnic background. Methodologically, I specialize in causal inference and often employ quasi-experimental designs to answer questions related to school choice, teacher effectiveness, and racial/ethnic discrimination.  

## Publications

<!-- REFUGEE PAPER -->
<ul class="pubs">

  <li>
    <a href="https://academic.oup.com/esr/article/39/3/352/6843667?login=false">
      Do Refugee Children Impair the Academic Performance of Native Children in the School? Informative Null Results from Danish Register Data
    </a>
    <span class="meta">
      (with Camilla Hvidtfeldt, Lars Højsgaard Andersen, Rebecca Overgaard Udsen)  
      <em>European Sociological Review</em>  
      <a href="#" class="abslink" onclick="toggleAbs('abs-refugee', this); return false;">[Abstract]</a>
    </span>
    <div id="abs-refugee" class="abstract-box">
      Discussions concerning the social impact of accepting refugee immigrants arise each time large numbers of refugees apply for protection in rich countries. However, little evidence exists on how the integration of refugees into core welfare institutions affects native citizens who depend on and interact with these institutions. In this paper, we focus on whether receiving refugees in a school cohort affects the academic performance of natives, using administrative data from Denmark, which contain test scores on all children in public schools. We exploit variation in the timing of refugees’ entrance to schools to facilitate causal estimates. Our findings show that refugees tend to cluster in schools that had poorer performance even prior to the refugees’ arrival. When we take this selection pattern into account, the effect of receiving refugees on the academic performance trajectory of natives is both statistically insignificant and substantially unimportant.
    </div>
  </li>

<!-- JDLC PAPER -->
</ul>

<li>
  <a href="#">
    The Importance of Living Arrangements for Criminal Persistence and Desistance: A Novel Test of Exposure to Convicted Family Members
  </a>
  <span class="meta">
    (with David Kirk, Lars H. Andersen)  
    <a href="#" class="abslink" onclick="toggleAbs('abs-living', this); return false;">[Abstract]</a>
  </span>
  <div id="abs-living" class="abstract-box">
    Leveraging the richness of population register data in Denmark, this study provides an in-depth examination of the residential situations of the formerly incarcerated over the first 3 years after prison. These data allow us to examine precisely who former prisoners reside with after release, and whether the characteristics of housemates, such as prior conviction status, and relationship type, such as familial ties, are associated with criminal reconviction. While Denmark has one of the lowest incarceration rates in the world, like many other Western countries, it is challenged by high recidivism rates among the formerly incarcerated. Using data on the population of all individuals released from prison between 1991 and 2014 and estimation via Cox proportional hazards models, we find that formerly incarcerated individuals who move into a residence with other individuals with criminal records have significantly greater hazards of reconviction, even after controlling for an extensive set of observed confounders. Residing with family members, particularly spouses, significantly reduces the likelihood of recidivism, but only if the family members do not have a recent criminal conviction. Results underscore the importance of housing arrangements and family ties during the post-release period.
  </div>
</li>
