---
title: "(UbiComp'22) Wavesdropper: Through-wall Word Detection of Human Speech via Commercial mmWave Devices"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chao Wang
  - Feng Lin
  - Zhongjie Ba
  - Fan Zhang
  - Wenyao Xu
  - Kui Ren

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2022-07-07T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-07-07T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies/UbiComp 2022*
publication_short: ""

abstract: Most existing eavesdropping attacks leverage propagating sound waves for speech retrieval. However, soundproof materials are widely deployed in speech-sensitive scenes (e.g., a meeting room). In this paper, we reveal that human speech protected by an isolated room can be compromised by portable and commercial off-the-shelf mmWave devices. To achieve this goal, we develop Wavesdropper, a word detection system that utilizes a mmWave probe to sense the targeted speaker's throat vibration and recover speech contents in the obstructed condition. We proposed a CEEMD-based method to suppress dynamic clutters (e.g., human movements) in the room and a wavelet-based processing method to extract the delicate vocal vibration information from the hybrid signals. To recover speech contents from mmWave signals related to the vocal vibration, we designed a neural network to infer the speech contents. Moreover, we explored word detection on a conversation with multiple (two) probes and reveal that the adversary can detect words on multiple people simultaneously with only one mmWave device. We performed extensive experiments to evaluate the system performance with over 60,000 pronunciations. The experimental results indicate that Wavesdropper can achieve 91.3% accuracy for 57-word recognition on 23 volunteers.

# Summary. An optional shortened abstract.
summary: Chao Wang, Feng Lin, Zhongjie Ba, Fan Zhang, Wenyao Xu, and Kui Ren.
# In this paper, we reveal that human speech protected by an isolated room can be compromised by portable and commercial mmWave devices. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- icon_pack: fab
  icon: youtube
  name: Presentation
  url: https://youtu.be/P-PaBAo0Dds

url_pdf: ''
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
url_slides: 'https://huskyachao.github.io/slides/Wavesdropper-presentation.pdf'
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtu.be/P-PaBAo0Dds'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
