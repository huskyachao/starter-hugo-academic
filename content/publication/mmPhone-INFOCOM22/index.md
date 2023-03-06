---
title: "(INFOCOM'22) mmPhone: Acoustic Eavesdropping on Loudspeakers via mmwave-characterized Piezoelectric Effect"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chao Wang
  - Feng Lin
  - Tiantian Liu
  - Ziwei Liu
  - Yijie Shen
  - Zhongjie Ba
  - Li Lu
  - Wenyao Xu
  - Kui Ren

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2022-05-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Conference on Computer Communications 2022*
publication_short: ""

abstract: More and more people turn to online voice communication with loudspeaker-equipped devices due to its convenience. To prevent speech leakage, soundproof rooms are often adopted. This paper presents mmPhone, a novel acoustic eavesdropping system that recovers loudspeaker speech protected by soundproof environments. The key idea is that properties of piezoelectric films in mmWave band can change with sound pressure due to the piezoelectric effect. If the property changes are acquired by an adversary (i.e., characterizing the piezoelectric effect with mmWaves), speech leakage can happen. More importantly, the piezoelectric film can work without a power supply. Base on this, we proposed a methodology using mmWaves to sense the film and decoding the speech from mmWaves, which turns the film into a passive "microphone". To recover intelligible speech, we further develop an enhancement scheme based on a denoising neural network, multi-channel augmentation, and speech synthesis, to compensate for the propagation and penetration loss of mmWaves. We perform extensive experiments to evaluate mmPhone and conduct digit recognition with over 93% accuracy. The results indicate mmPhone can recover high-quality and intelligible speech from a distance over 5m and is resilient to incident angles of sound waves (within 55 degrees) and different types of loudspeakers.

# Summary. An optional shortened abstract.
summary: This paper presents mmPhone, a novel sound recovery system that can recover high-quality speech protected by soundproof environments via mmWave sensing. 

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
url_slides: 'https://huskyachao.github.io/slides/mmPhone-presentation.pdf'
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_video: 'https://youtu.be/AIh0l00qxP4'

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
