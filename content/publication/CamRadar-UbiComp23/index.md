---
title: "(UbiComp'23) CamRadar: Hidden Camera Detection Leveraging Amplitude-modulated Sensor Images Embedded in Electromagnetic Emanations"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ziwei Liu
  - Feng Lin
  - Chao Wang
  - Yijie Shen
  - Zhongjie Ba
  - Li Lu
  - Wenyao Xu
  - Kui Ren

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-01-11T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-11T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies/UbiComp 2023*
publication_short: In **UbiComp'23**

abstract: Hidden cameras in sensitive locations have become an increasing threat to personal privacy all over the world. Because the camera is small and camouflaged, it is difficult to detect the presence of the camera with naked eyes. Existing works on this subject have either only covered using wireless transmission to detect cameras, or using other methods which are cumbersome in practical use. In this paper, we introduce a new direction that leverages the unintentional electromagnetic (EM) emanations of the camera to detect it. We first find that the digital output of the camera's image sensor will be amplitude-modulated to the EM emanations of the camera's clock. Thus, changes in the scope of the camera will directly cause changes in the camera's EM emanations, which constitutes a unique characteristic for a hidden camera. Based on this, we propose a novel camera detection system named CamRadar, which can filter out potential camera EM emanations from numerous EM signals quickly and achieve accurate hidden camera detection. Benefitting from the camera's EM emanations, CamRadar will not be limited by the camera transmission types or the detection angle. Our extensive real-world experiments using CamRadar and 19 hidden cameras show that CamRadar achieves a fast detection (in 16.75s) with a detection rate of 93.23% as well as a low false positive rate of 3.95%.

# Summary. An optional shortened abstract.
summary: In this paper, we introduce a new hidden-camera-detection method that leverages the unintentional electromagnetic (EM) emanations of hidden cameras.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
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
