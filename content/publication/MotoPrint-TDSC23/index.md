---
title: "(TDSC'23) MotoPrint: Reconfigurable Vibration Motor Fingerprint via Homologous Signals Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yijie Shen
  - Feng Lin
  - Chao Wang
  - Tiantian Liu
  - Zhongjie Ba
  - Li Lu
  - Wenyao Xu
  - Kui Ren

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-03-05T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-03-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Dependable and Secure Computing*
publication_short: In **TDSC'2023**

abstract: Device fingerprints can satisfy the high-security requirement of modern mobile applications (e.g., mobile payments) by guaranteeing the operation is performed on a trusted device. However,existing works on device fingerprints are weak to leakage, which leads to an irreversible failure of the device fingerprint authentication system after suffering from fingerprint theft attacks.The vulnerability drives us to propose a reconfigurable device fingerprint, i.e., MotoPrint, that can recover the system after suffering from such attacks. MotoPrint stems from the motor vibration that can represent in both signals of the accelerometer and the gyroscope (i.e., they are homologous motion signals). Therefore, we designed a two-path feature extracting network and a sensor-independent training strategy to eliminate sensor noise that can decline authentication performance. In addition, MotoPrint has a complete reconfiguration mechanism to cope with fingerprint leakage, which brings the damaged authentication system back to health. The evaluation of 80 stand-alone vibration motors and 20 in-built ones shows that MotoPrint can achieve high authentication accuracy of 98.5%. Meanwhile, we also demonstrate the reconfigured MotoPrint, which can also effectively indicate the device’s uniqueness with over 98% accuracy, is independent of MotoPrints under other stimulating codes.


# Summary. An optional shortened abstract.
summary: In this paper, we propose a kind of reconfigurable device fingerprint based on motor vibration patterns, that is resistent to fingerprint cloning attacks.

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
