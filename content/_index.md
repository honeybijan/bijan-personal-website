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
            I am a computer scientist and mathematician interested in the synthesis and transportation of knowledge from and between multiple settings. I study topics related to causality, distribution shift, decision fusion, and mixture models. I am working to apply these ideas to pressing computational challenges in the biological and health sciences.
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