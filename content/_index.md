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
            I am a computer scientist and mathematician interested in the task of combining data and knowledge from multiple places, topics, and modalities. I study causality, distribution shift, decision fusion, and mixture models. I am working to apply these ideas to new computational challenges in the biological and health sciences. Before starting at the Broad, I was an NSF Graduate Research Fellow and Amazon AI4Science Fellow at Caltech, where I completed a PhD in Computing and Mathematical Sciences under the supervision of Shuki Bruck and Leonard Schulman. I will be starting as an Assistant Professor at Dartmouth's Thayer School of Engineering in January 2025 and am actively recruiting postdocs and Ph.D. students.
          </p>
          <p style="text-align: justify;"> 
            I am also an internationally competitive distance runner and enjoy applying my research to sports analytics. I am the developer of <a href="https://www.lacctic.com/">LACCTiC</a>, which is used by coaches and athletes across the NCAA to compare performances over varying conditions and terrain.
          </p>
          <div style="text-align: center;">
            {{< button relref="/research" >}}Research{{< /button >}}
            {{< button relref="/side" >}}Side Projects{{< /button >}}
            {{< button relref="/education_experience" >}}Education/Work{{< /button >}}
            {{< button relref="/running" >}}Running{{< /button >}}
          </div>
          <div style="text-align: center;">
            {{< figure src="ResearchGraphic2.png" id="ResearchGraphic2" >}}
          </div>
        </dif>
---