---
layout: default
title: Home
---
<!-- Add fonts for icones -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1.9.4/css/academicons.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/simple-icons-font@v9/font/simple-icons.min.css">

<!-- ICONS --> 
<div id="social-icons" class="social-icons">

  <!-- Scholar (FA has no Google Scholar icon; using graduation cap) -->
  <a href="https://scholar.google.com/citations?user=LKYHvDMAAAAJ&hl=en" target="_blank" rel="noopener" aria-label="Google Scholar">
    <i class="fa-solid fa-graduation-cap"></i>
  </a>
  
  <!-- LinkedIn -->
  <a href="https://www.linkedin.com/in/said-aj-hassan" target="_blank" rel="noopener" aria-label="LinkedIn">
    <i class="fa-brands fa-linkedin"></i>
  </a>

  <!-- Bluesky -->
  <a href="https://bsky.app/profile/saidhassan.bsky.social" target="_blank" rel="noopener" aria-label="Bluesky">
    <i class="fa-brands fa-bluesky"></i>
  </a>

  <!-- Email -->
  <a href="mailto:said.aj.hassan@gmail.com" aria-label="Email">
    <i class="fa-solid fa-envelope"></i>
  </a>

  <!-- CV (text link) -->
  <a href="/assets/cv/Hassan_CV_web.pdf" target="_blank" rel="noopener" aria-label="CV" class="cv-link">CV</a>
</div>


<!-- Script to move icons under your profile photo -->
<script>
  (function () {
    function placeIcons() {
      var header = document.querySelector('header');
      var img = header ? header.querySelector('img') : null;
      var icons = document.getElementById('social-icons');
      if (!header || !icons) return;
      if (img && img.parentNode) {
        img.insertAdjacentElement('afterend', icons);
      } else {
        var desc = header.querySelector('p');
        (desc || header).insertAdjacentElement('beforeend', icons);
      }
      icons.style.display = 'block';
    }
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', placeIcons);
    } else {
      placeIcons();
    }
  })();
</script>

<!-- The script below makes it possible to click on abstracts for papers -->

<script>
  function toggleAbs(id, link){
    const box = document.getElementById(id);
    const show = (box.style.display === 'none' || box.style.display === '');
    box.style.display = show ? 'block' : 'none';
    link.textContent = show ? '[Close]' : '[Abstract]';
  }
</script>

## About me

I am a Postdoctoral Prize Research Fellow at [Nuffield College, University of Oxford](https://www.nuffield.ox.ac.uk), where I completed my PhD in 2024. My dissertation was recently awarded the [Best PhD Thesis Prize in Sociology](https://ecsrnet.eu/ecsr-prize-for-best-phd-thesis/) by the European Consortium for Sociological Research (ECSR).  

I study social stratification with a focus on education. My current research examines the potential and limitations of school interventions in reducing inequalities in educational outcomes by socioeconomic and ethnic background. Methodologically, I specialize in causal inference and often employ quasi-experimental designs to answer questions related to school choice, teacher effectiveness, and racial/ethnic discrimination.  

## Publications

<ul class="pubs">

  <li>
    <a href="https://academic.oup.com/esr/article/39/3/352/6843667">
      Do Refugee Children Impair the Academic Performance of Native Children in the School?
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

  <li>
    <a href="https://link.springer.com/article/10.1007/s40865-022-00211-0">
      The Importance of Living Arrangements for Criminal Persistence and Desistance: A Novel Test of Exposure to Convicted Family Members
    </a>
    <span class="meta">
      (with David Kirk, Lars H. Andersen)  
      <em>Journal of Developmental and Life-Course Criminology</em>  
      <a href="#" class="abslink" onclick="toggleAbs('abs-living', this); return false;">[Abstract]</a>
    </span>
    <div id="abs-living" class="abstract-box">
      Leveraging the richness of population register data in Denmark, this study provides an in-depth examination of the residential situations of the formerly incarcerated over the first 3 years after prison. These data allow us to examine precisely who former prisoners reside with after release, and whether the characteristics of housemates, such as prior conviction status, and relationship type, such as familial ties, are associated with criminal reconviction. While Denmark has one of the lowest incarceration rates in the world, like many other Western countries, it is challenged by high recidivism rates among the formerly incarcerated. Using data on the population of all individuals released from prison between 1991 and 2014 and estimation via Cox proportional hazards models, we find that formerly incarcerated individuals who move into a residence with other individuals with criminal records have significantly greater hazards of reconviction, even after controlling for an extensive set of observed confounders. Residing with family members, particularly spouses, significantly reduces the likelihood of recidivism, but only if the family members do not have a recent criminal conviction. Results underscore the importance of housing arrangements and family ties during the post-release period.
    </div>
  </li>

</ul>

## Working Papers
<ul class="pubs">

  <li>
    A Muslim School Advantage? Evidence from a Natural Experiment
  
    <span class="meta">
      (Sole-authored)  
      <em>Review and Resubmit, American Journal of Sociology</em>  
      <a href="#" class="abslink" onclick="toggleAbs('abs-muslim', this); return false;">[Abstract]</a>
    </span>
    <div id="abs-muslim" class="abstract-box">
      Do ethnic enclaves improve or impede ethnic minorities' social outcomes? In this study, I examine the impact of Muslim schools in Denmark on ethnic minority children's academic performance, as a case study of this broader question. Using a natural experiment design that induced a sudden and unanticipated student flight from Muslim to public schools, I document large positive Muslim school effects in reading and mathematics. Through several robustness checks, I show that disruption effects do not explain these results. Finally, I empirically test two theoretical mechanisms underlying the observed effects: ethnic homogeneity and teacher biases. While I do not find evidence of teacher biases in my analyses, I find that ethnic homogeneity is a key driver of the observed positive effects, lending support to oppositional culture explanations. From a policy perspective, these results highlight that targeted assimilation policies that seek to further the social integration of ethnic minorities may potentially have unintended consequences and come with costs to other outcomes that policymakers care about-in this context, academic performance. 
    </div>
  </li>

  <li>
    Teacher Sorting and Inequalities in Student Achievement
      

    <span class="meta">
      (Sole-authored)  
      <em>TEST</em>  
      <a href="#" class="abslink" onclick="toggleAbs('abs-teacher', this); return false;">[Abstract]</a>
    </span>
    <div id="abs-teacher" class="abstract-box">
      Teachers play a formative role in shaping children’s school experiences and ultimately, their educational outcomes. In this study, I use full population Danish administrative data to explore the consequences of unequal access to
qualified teachers in three steps. First, I document strong patterns of teacher-student sorting in Denmark, one of the world’s most equal societies and generous welfare states. In short, teachers from higher socioeconomic backgrounds and with higher prior academic achievements tend to select into schools serving high-achieving children from privileged backgrounds. Second, I investigate the effect of teacher qualifications on students’ test score performance. To facilitate causal estimates, I exploit plausibly exogenous shocks to teacher changes induced by parental leave spells, which, I show, are unrelated to an extensive set of observed classroom characteristics, including student well-being and measures of classroom climate. Finally, I explore differentials in the impact of teacher qualifications by students’ socioeconomic background. I find no consistent evidence of differential teacher effects, implying that teacher-induced learning inequalities are mainly driven by teachers' sorting behavior. This finding highlights that policies designed to equalize access to quality teachers can be effective in reducing learning disparities.
    </div>
  </li>

  <li>
    Schools and Learning Inequalities: A Theoretical Model of Quantitative and Qualitative School Effects
      

    <span class="meta">
      (with Richard Breen)  
      <em>TEST</em>  
      <a href="#" class="abslink" onclick="toggleAbs('abs-school', this); return false;">[Abstract]</a>
    </span>
    <div id="abs-school" class="abstract-box">
Do schools reduce or amplify learning gaps by socioeconomic background? In this paper, we contribute to this longstanding sociological debate in three ways. First, we develop a formal model that clarifies relevant theoretical estimands and counterfactuals. Second, our theoretical model synthesizes previously contradictory findings in the literature on schools and inequality by distinguishing between quantitative and qualitative school effects. Third, we empirically test a central hypothesis from our model: that the positive returns to improvements in school quality are concentrated among children from lower socioeconomic backgrounds. To test this hypothesis, we use administrative register data from Denmark and a natural experiment design that relies on variation in school quality induced by unanticipated changes in school district boundaries over time. We show that children redistricted to higher-quality schools substantially improve their test score performance in reading, and, crucially, these effects are strongest among children from lower socioeconomic backgrounds. These findings suggest that equalizing school quality can be an effective means of reducing learning inequalities.
    </div>
  </li>

</ul>
