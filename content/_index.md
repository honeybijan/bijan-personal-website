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
            I am a Ph.D candidate at Caltech working with Shuki Bruck and Leonard Schulman. My interests include mixture models, high-level data fusion, and stability to distribution shift - usually through the lense of causality. I'm especially interested in techniques for illuminating hidden causal structures.
          </p>
          <div style="text-align: center;">
            {{< button relref="/research" >}}Research{{< /button >}}
            {{< button relref="/side" >}}Side Projects{{< /button >}}
            {{< button relref="/education_experience" >}}Education/Work{{< /button >}}
            {{< button relref="/running" >}}Running{{< /button >}}
          </div>
        </dif>
---