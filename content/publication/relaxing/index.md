---
title: "Relaxing Platform Dependencies in Agent-based Control Systems"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Marco Perez Hernandez
- Duncan McFarlane
- Ajith Parlikad
- Manuel Herrera
- Amit Jain

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-01-01T00:00:00Z"
doi: "https://doi.org/10.1109/ACCESS.2021.3059273"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Access*
# publication_short: In *ICW*

abstract: Agent-based systems have been widely used to develop industrial control systems when they are required to address issues such as flexibility, scalability and portability. The most common approach to develop such control systems is with agents embedded in a platform that provides software libraries and runtime services that ease the development process. These platforms also bring challenges to the agent-based control system engineering. For example, they might introduce default design features, such as a global directory of agents. Furthermore, agents are generally locked in a platform and depend on the platform's available support for deployment across computing infrastructures. This article addresses these challenges through an approach for building agent-based control systems, that relaxes the dependencies in multiagent system (MAS) platforms, through the use of container-based virtualisation. The proposed approach is elaborated via a reference architecture that enables the implementation of agents as self-contained applications that can be deployed, on-demand, in independent environments but still are able to communicate and coordinate with other agents of the control system. We built a prototype using this approach and evaluated it in the context of a case study for the supervisory control of digital network infrastructures. This case study enabled us to demonstrate feasibility of the approach and to show the flexibility, of the resulting control system, to adopt several topologies as well as to operate at different scales, over emulated networks. We also concluded that designing agents as individual deployment units is also cost-effective especially in control scenarios with low number of stable agents.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Agent-based control, multiagent systems, micro services, container-based virtualisation industrial control, system containers.]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9354153'
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**mperhez**](/content/publication/relaxing/featured.png)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
