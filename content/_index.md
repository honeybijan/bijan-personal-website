---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: |2-
        <dif style = "margin: 10px;">
          <p style="text-align: justify;"> 
            I study issues that arise when synthesizing information from multiple datasets, modalities, and batches into machine learning and AI models. Topics include causality, distribution shift, decision fusion, and mixture models. I am working to apply these ideas to new computational challenges in defense and biology. I am recruiting postdocs and Ph.D. students.
          </p>
          <p style="text-align: justify;"> 
            I am also an internationally competitive distance runner and enjoy applying my research to sports analytics. I am the developer of <a href="https://www.lacctic.com/">LACCTiC</a>, which is used by coaches and athletes across the NCAA to compare performances over varying conditions and terrain.
          </p>
          <div style="text-align: center;">
            {{< button relref="/research" >}}Research{{< /button >}}
            {{< button relref="/side" >}}Side Projects{{< /button >}}
            {{< button relref="/education_experience" >}}Experience{{< /button >}}
            {{< button relref="/running" >}}Running{{< /button >}}
          </div>
          <div style="text-align: center;">
            {{< figure src="ResearchGraphic2.png" id="ResearchGraphic2" >}}
          </div>
        </dif>
---