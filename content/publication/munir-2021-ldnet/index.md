---
title: "LDNet: end-to-end lane marking detection approach using a dynamic vision sensor"
date: 2021-01-01
publishDate: 2022-09-26T08:45:08.120563Z
authors: ["admin", "Shoaib Azam", "Moongu Jeon", "Byung-Geun Lee", "Witold Pedrycz"]
publication_types: ["2"]
abstract: ""
featured: false
publication: "*IEEE Transactions on Intelligent Transportation Systems*"
tags: []
abstract: Modern vehicles are equipped with various driver-assistance systems, including automatic lane keeping, which prevents unintended lane departures. Traditional lane detection methods incorporate handcrafted or deep learning-based features followed by postprocessing techniques for lane extraction using frame-based RGB cameras. The utilization of frame-based RGB cameras for lane detection tasks is prone to illumination variations, sun glare, and motion blur, which limits the performance of lane detection methods. Incorporating an event camera for lane detection tasks in the perception stack of autonomous driving is one of the most promising solutions for mitigating challenges encountered by frame-based RGB cameras. The main contribution of this work is the design of the lane marking detection model, which employs the dynamic vision sensor. This paper explores the novel application of lane marking detection using an event camera by designing a convolutional encoder followed by the attention-guided decoder. The spatial resolution of the encoded features is retained by a dense atrous spatial pyramid pooling (ASPP) block. The additive attention mechanism in the decoder improves performance for high dimensional input encoded features that promote lane localization and relieve postprocessing computation. The efficacy of the proposed work is evaluated using the DVS dataset for lane extraction (DET). The experimental results show a significant improvement of 5.54% and 5.03% in F1 scores in multiclass and binary-class lane marking detection tasks. Additionally, the intersection over union ( IoU ) scores of the proposed method surpass those of the best-performing state-of-the-art method by 6.50% and 9.37% in multiclass and binary-class tasks, respectively.

# Summary. An optional shortened abstract.
summary: This paper explores the novel application of lane marking detection using an event camera by designing a convolutional encoder followed by the attention-guided decoder. The spatial resolution of the encoded features is retained by a dense atrous spatial pyramid pooling (ASPP) block. The additive attention mechanism in the decoder improves performance for high dimensional input encoded features that promote lane localization and relieve postprocessing computation.
# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9518365'
url_code: 'https://github.com/munirfarzeen/LDNet.git'
url_dataset: ''
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

---

