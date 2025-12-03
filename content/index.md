---
title: "Shared Control/Autonomy: A Historical Perspective, Current Trends, and the Role of Generative AI"
description: "A concise landing page for the SC/SA survey."
authors:
  - name: "Michael Hagenow"
    affiliation: "University of Wisconsin - Madison"
  - name: "Mario Selvaggio"
    affiliation: "University of Naples Federico II"
  - name: "Xuehui Yu"
    affiliation: "National University of Singapore"
  - name: "Yanwei Wang"
    affiliation: "Generalist AI"
  - name: "Yiannis Demiris"
    affiliation: "Imperial College London"
  - name: "Andreea Bobu"
    affiliation: "Massachusetts Institute of Technology"
  - name: "Yilun Du"
    affiliation: "Harvard University"
  - name: "Harold Soh"
    affiliation: "National University of Singapore"
  - name: "Dylan Losey"
    affiliation: "Virginia Tech"
  - name: "Julie Shah"
    affiliation: "Massachusetts Institute of Technology"
buttons:
  # - text: "Preprint (arXiv)"
  #   url: "https://arxiv.org/abs/2501.01234"
  - text: "PDF"
    url: "/shared_control_autonomy_survey/survey_preprint.pdf"
  - text: "Interactive Table (coming soon)"
    url: "#interactive-table"   # or wherever your table anchor is
---

{{< survey-hero >}}
{{< survey-buttons >}}

<img src="scsa_survey_teaser_website.png"
     alt="Teaser image"
     style="width: 100%; height: auto; display:block; margin: 0 auto;" />

## Overview

In shared control and shared autonomy systems, humans collaborate with robot agents to achieve common goals. Research in this area dates back over 40 years, with numerous applications, such as in manufacturing, robot surgery, and assistive technologies. Shared control approaches have even seen some commercialization efforts in areas like semi-autonomous driving and automotive assembly. Recently, shared control and shared autonomy approaches have gained significant traction, with hundreds of new methods published in scientific papers each year. In this paper, we examine recent approaches and trends in these methods, investigating several crucial aspects that are underexplored in previous surveys. First, we provide descriptive statistics and trends related to human input methods, technical approaches, and applications. Second, we examine the growing role of generative artificial intelligence approaches in shared control and autonomy. Based on these insights, we offer updated recommendations for future approaches.




## Interactive Table
Coming soon!
{{< csv-table src="survey_table.csv" search=true sort=true >}}

## Citation

<div class="bibtex-box">
<pre>
@article{hagenow2025shared,
  title   = {Shared Control/Autonomy: A Historical Perspective, Current Trends, and the Role of Generative AI},
  author  = {Hagenow, Michael and Selvaggio, Mario and Yu, Xuehui and Wang, Yanwei and Demiris, Yiannis and
             Bobu, Andreea and Du, Yilun and Soh, Harold and Losey, Dylan and Shah, Julie},
  year    = {2025},
  note    = {Preprint, available at: https://wisc-rt2.github.io/shared_control_autonomy_survey/survey_preprint.pdf}
}
</pre>
</div>

<style>
.bibtex-box {
  border-left: 4px solid #2b6cb0;
  padding: 0.75rem 1rem;
  background: #f6f9ff;
  border-radius: 4px;
  overflow-x: auto;   /* enables horizontal scroll if needed, but rarely used now */
  margin: 1rem 0;
}

.bibtex-box pre {
  margin: 0;
  font-size: 0.65rem;
  font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace;
}
</style>