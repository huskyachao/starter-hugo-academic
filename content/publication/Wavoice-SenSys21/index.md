---
title: 'Wavoice: A noise-resistant multi-modal speech recognition system fusing mmwave and audio signals'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tiantian Liu
  - Ming Gao
  - Feng Lin
  - Chao Wang
  - Zhongjie Ba
  - Jinsong Han
  - Wenyao Xu
  - Kui Ren

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2021-11-15T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 19th ACM Conference on Embedded Networked Sensor Systems*
publication_short: In **ACM SenSys'21**

abstract: With the advance in automatic speech recognition, voice user interface has gained popularity recently. Since the COVID-19 pandemic, VUI is increasingly preferred in online communication due to its non-contact. Additionally, various ambient noise impedes the public applications of voice user interfaces due to the requirement of audio-only speech recognition methods for a high signal-to-noise ratio. In this paper, we present Wavoice, the first noise-resistant multi-modal speech recognition system that fuses two distinct voice sensing modalities, i.e., millimeter-wave (mmWave) signals and audio signals from a microphone, together. One key contribution is that we model the inherent correlation between mmWave and audio signals. Based on it, Wavoice facilitates the real-time noise-resistant voice activity detection and user targeting from multiple speakers. Furthermore, we elaborate on two novel modules into the neural attention mechanism for multi-modal signals fusion, and result in accurate speech recognition. Extensive experiments verify Wavoice's effectiveness under various conditions with the character recognition error rate below 1% in a range of 7 meters. Wavoice outperforms existing audio-only speech recognition methods with lower character error rate and word error rate. The evaluation in complex scenes validates the robustness of Wavoice.

# Summary. An optional shortened abstract.
summary: In this paper, we present Wavoice, the first noise-resistant multi-modal speech recognition system that fuses two distinct voice sensing modalities, i.e., millimeter-wave (mmWave) signals and audio signals from a microphone, together.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: 'https://huskyachao.github.io/slides/mmEve-presentation.pdf'
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtu.be/_FUz6TE_5yM'

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
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
