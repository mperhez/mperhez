---
title: Agent-based Network Intent Control - Demo

# event: Wowchemy Conference
# event_url: https://example.org

# location: Wowchemy HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: Short video for intent network control using agents.
abstract: "This video presents the PoC demo of an agent-based control solution for a software-defined network integrated with ONOS SDN Controller & with anomaly detection based on online quantile estimation. A simple network is emulated using Mininet with 5 hosts, 3 switches and 8 links with different properties. In ONOS, there is a number of point-to-point intents configured for the paths between all the hosts. Switches are involved in more than one intent in order to ensure communication between the hosts. In the Multi Agent System (MAS) there are two types of agents: Digital Asset Agents (DAAs) & Service Manager Agent (SMA). DAAs are mapped one-to-one with Switches. Every DAA monitors a Switch and collects throughput measurements per intent. The SMA aggregates measurements reported by DAAs and checks for anomalies in the profile using the quantile estimation algorithm. When the SMA observes an anomalous behaviour in the aggregated profile of one of the switches it triggers the re-routing of the intent via ONOS. Likewise it notifies the Engineering Team group via Slack."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
# date: "2030-06-01T13:00:00Z"
# date_end: "2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
# - example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
{{< youtube COhcIgRFn3Y >}}
