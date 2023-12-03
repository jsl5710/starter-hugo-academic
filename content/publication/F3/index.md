---
title: 'Detecting False Claims in Low-Resource Regions: A Case Study of Caribbean Islands'

# Authors
# If you created a profile for a user (e.g., the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jason Lucas
  - Adaku Uchendu
  - Michiharu Yamashita
  - Jooyoung Lee
  - Shaurya Rohatgi
  - Dongwon Lee

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-010-01T00:00:00Z'
doi: 10.18653/v1/2022.constraint-1.11

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Empirical Methods in Natural Language Processing* 2023 Singapore, Southeast Asia.
publication_short: In *EMNLP.ACL* 

abstract: Recent ubiquity and disruptive impacts of large language models (LLMs) have raised concerns about their potential to be misused (i.e., generating large-scale harmful and misleading content). To combat this emerging risk of LLMs, we propose a novel “Fighting Fire with Fire” (F3) strategy that harnesses modern LLMs’ generative and emergent reasoning capabilities to counter human-written and LLM-generated disinformation. First, we leverage GPT-3.5-turbo to synthesize authentic and deceptive LLM-generated content through paraphrase-based and perturbation-based prefix style prompts, respectively. Second, we apply zero-shot in-context semantic reasoning techniques with cloze-style prompts to discern genuine from deceptive posts & news articles. In our extensive experiments, we observe GPT-3.5-turbo’s zero-shot superiority for both in-distribution and out-of distribution datasets, where GPT3.5-turbo consistently achieved accuracy at 68-72%, unlike the decline observed in previous customized and fine-tuned disinformation detectors. Our codebase and dataset are available at https://github.com/mickeymst/F3.

# Summary. An optional shortened abstract.
summary: This paper demonstrates the dual capacity of LLMs for misuse and defense against disinformation without requiring additional training. It is the first study to (1) generate both real and fake disinformation, (2) discover and remove reverse hallucination disinformation error, and (3) detect disinformation using LLMs' emergent abilities, such as in-context learning and semantic reasoning. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://pike.psu.edu/publications/emnlp23-f3.pdf
url_code: https://github.com/mickeymst/F3
url_dataset: https://github.com/mickeymst/F3
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
