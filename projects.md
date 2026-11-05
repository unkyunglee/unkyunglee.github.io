---
layout: page
title: Projects
full-width: true
---
<style>
  div[role="main"] {
    width: 100%;
    max-width: 1150px;
    margin-left: auto;
    margin-right: auto;
    padding-left: 24px;
    padding-right: 24px;
    box-sizing: border-box;
  }
</style>

## My Career Path
During my PhD at the University of North Carolina at Charlotte, I developed a strong foundation in statistical theory and probability, with a focus on survival analysis. In particular, I worked on semiparametric regression models for cumulative incidence functions under two-phase sampling designs, where important biomarker information is available for only a subset of study participants due to a two-phase sample/Case-cohort design. In biomedical research, measuring biomarkers can be expensive or time-consuming. Researchers therefore often measure them in a selected subset of participants using a two-phase sampling design. Accounting for this selection is essential when estimating associations between biomarkers and disease outcomes. To address to this issue and and provide valid estimation and statistical inference with incomplete biomarker data, we developed an inverse probability weighted estimation approach. This methods were applied to the RV144 HIV vaccine trial to investigate associations between immune-response biomarkers and the risk of infection with different genetic types of HIV. This research was published in [*Computational Statistics & Data Analysis* (2018)](https://pmc.ncbi.nlm.nih.gov/articles/PMC5993453/). This work was extended by developing a doubly robust augmented inverse probability weighted estimation approach that improves the efficiency and robustness of statistical inference by incorporating additional information from observed covariates [*Canadian Journal of Statistics* (2023)](https://pmc.ncbi.nlm.nih.gov/articles/PMC10022693/).

[View presentation slides (PDF)]({{ '/resources/PhDwork_IPW_CIF.pdf' | relative_url }})

After my PhD, I joined Texas A&M University as a postdoctoral research associate in an NIH T32 program. My postdoctoral training helped me grow into an independent researcher. I learned valuable research skill sets including identifying meaningful research questions, developing R packages, and communicating the value of my methods through presentations. Equally important, I learned to step outside my comfort zone, embrace new challenges, and collaborate with researchers across disciplines. One major project involved modeling longitudinal biomarkers to estimate disease onset in Huntington’s disease [*Biostatistics* (2021)](https://pmc.ncbi.nlm.nih.gov/articles/PMC8596391/). We developed a non-parametric approach to identify changes
in the progression of motor symptoms while accounting for measurement error. Applied to the PREDICT-HD study, our method identified potential onset earlier than clinician-based assessments,
suggesting its promise as a complementary, data-driven measure.I also collaborated with an animal science laboratory, where I helped analyze repeated-measures amino acid data from small samples using mixed-effects models. That experience gave me a lot of practical exposure to working with scientists and translating statistical methods into approaches they could actually use.

I then moved to FDA CBER as an ORISE Research Fellow, where my work shifted more directly toward clinical trial methodology. I developed a foundation in clinical trial design, conduct,
and statistical analysis through studying Steven Piantadosi’s *Clinical Trials: A Methodologic Perspective* (https://onlinelibrary.wiley.com/doi/book/10.1002/0471740136). In collaboration with Dr. Zhenzhen Xu, I devoted my time to develop a design and analysis procedure for immuno-oncology trials, which involves non-proportional hazards and We implemented the methods in an R package called PRIME+. Rather than estimating only an average treatment effect across all patients, PRIME+ estimates treatment effects for different groups of responders. We also developed statistical testing procedures and sample size calculation methods to improve the design and analysis of clinical trials. Through simulation studies, we demonstrated that accounting for differences in patients' treatment responses can improve statistical power and potentially reduce the number of patients required to achieve the same statistical power, particularly when treatment responses vary substantially across patient subgroups and their characteristics are accurately specified. The manuscript is currently under review by Dr.Xu. 

After that, I wanted to broaden my experience from developing statistical methods to understanding how clinical studies are evaluated in real regulatory settings, so I moved to FDA CDRH as a Mathematical Statistician. There, I reviewed clinical studies for therapeutic and diagnostic medical devices, including study designs, analysis plans, and statistical issues in regulatory submissions. I also worked closely with internal review teams and sponsors.

Overall, my career has progressed from statistical methodology development, to biomedical research, to clinical trial methodology, and then to regulatory evaluation. Now I’m interested in bringing all of those experiences together in pharmaceutical clinical development.







     
