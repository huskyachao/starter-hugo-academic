---
title: "(MobiCom'22) mmEve: Eavesdropping on Smartphone's Earpiece via COTS mmWave Device"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chao Wang
  - Feng Lin
  - Tiantian Liu
  - Kaidi Zheng
  - Zhibo Wang
  - Zhengxiong Li
  - Ming-Chun Huang
  - Wenyao Xu
  - Kui Ren

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2022-10-14T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-14T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 28th Annual International Conference on Mobile Computing And Networking*
publication_short: ""

abstract: Earpiece mode of smartphones is often used for confidential communication. In this paper, we proposed a remote(>2m) and motion-resilient attack on smartphone earpiece. We developed an end-to-end eavesdropping system mmEve based on a commercial mmWave sensor to recover speech emitted from smartphone earpiece. The rationale of the attack is based on our observation that, soundwaves emitted from the smartphone's earpiece have a strong correlation with reflected mmWaves from the smartphone's rear. However, we find the recovered speech suffers from the sensor's self-noise and smartphone user's motion which limit attack distance to less than 2m, causing limited threats in real world. We modeled the motion interference under mmWave sensing and proposed a motion-resilient solution by optimizing the fitting function on I/Q plane. To achieve a practical attack with reasonable attack distance, we developed a GAN-based denoising scheme to eliminate the noise pattern of the sensor, which boosted the attack range to 6--8m. We evaluated mmEve with extensive experiments and find 23 different models of smartphones manufactured by Samsung, Huawei, etc. can be compromised by the proposed attack.

# Summary. An optional shortened abstract.
summary: In this paper, we proposed a remote(>2m) and motion-resilient attack on smartphone earpiece. We developed the mmEve system based on COTS mmWave sensors to recover speech emitted from smartphone earpiece.

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
url_slides: 'https://huskyachao.github.io/slides/mmEve-presentation.pdf'
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtu.be/_FUz6TE_5yM'
url_video: 'https://youtu.be/OLUg1OVgqqk'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  placement: 1 # change the display size of the image (value: 1/2/3)
  caption: "Image credit: Chao Wang" #[**Chao Wang**](https://unsplash.com/photos/pLCdAaMFLTE)
  focal_point: 'Center' # chnange the center of the resized image
  preview_only: false
  alt_text: ''

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
