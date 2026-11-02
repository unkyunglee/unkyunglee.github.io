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

## Featured Projects

### Projects in FDA: Improving a Clinical Trial Design for Cancer Immunotherapy

[View presentation slides (PDF)]({{ '/resources/UnkyungLee_JobTalk_FDACDRH_40mins_Final.pdf' | relative_url }})

Cancer immunotherapy has transformed cancer treatment, but not all patients respond to these therapies in the same way. Some patients experience substantial benefits, others respond moderately, and some may not benefit at all. These differences can produce complex survival patterns, making it difficult for conventional statistical methods to accurately evaluate treatment effectiveness.

In collaboration with Dr. Zhenzhen Xu, I developed PRIME+, a statistical approach designed to account for heterogeneous treatment responses in immuno-oncology clinical trials. Rather than estimating only an average treatment effect across all patients, PRIME+ estimates treatment effects for different groups of responders. We also developed statistical testing procedures and sample size calculation methods to improve the design and analysis of clinical trials. Through simulation studies, we demonstrated that accounting for differences in patients' treatment responses can improve statistical power and potentially reduce the number of patients required to achieve the same statistical power, particularly when treatment responses vary substantially across patient subgroups and their characteristics are accurately specified.

Our goal is to develop more efficient clinical trial designs and provide researchers with a better understanding of how different groups of patients benefit from cancer immunotherapy.

**Manuscript in preparation:** Lee, U. and Xu, Z. *Design for Immuno-Oncology Clinical Trials with a Heterogeneous Patient Population.* (Currently under coauthor review)

### PhD projects: Competing Risks Data Analysis with Missing Biomarkers under Two-Phase Sampling

[View presentation slides (PDF)]({{ '/resources/PhDwork_IPW_CIF.pdf' | relative_url }})

During my PhD, I developed statistical methods for the analysis of semiparametric cumulative incidence model with competing risks data when important biomarker information is available for only a subset of study participants due to a two-phase sampling/Case-Cohort Design.

In biomedical research, measuring biomarkers can be expensive or time-consuming. Researchers therefore often measure them in a selected subset of participants using a two-phase sampling design. Accounting for this selection is essential when estimating associations between biomarkers and disease outcomes.

To address this issue, we developed inverse probability weighted estimation procedures for incomplete covariate data under generalized case-cohort/phase-two sampling designs. This method accounted for missingness by the designs and provided valid estimation and statistical inference with incomplete biomarker data. We also established the asymptotic properties of the proposed estimators and evaluated their finite-sample performance through simulation studies.

This methods were applied to the RV144 HIV vaccine trial to investigate associations between immune-response biomarkers and the risk of infection with different genetic types of HIV. This research was published in [*Computational Statistics & Data Analysis* (2018)](https://pmc.ncbi.nlm.nih.gov/articles/PMC5993453/).

In subsequent collaborative research, we extended this work by developing a doubly robust augmented inverse probability weighted estimation approach 
that improves the efficiency and robustness of statistical inference by incorporating additional information from observed covariates. This work was published in the [*Canadian Journal of Statistics* (2023)](https://pmc.ncbi.nlm.nih.gov/articles/PMC10022693/).


     
