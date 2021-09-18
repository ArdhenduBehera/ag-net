## Asish Bera, Zachary Wharton, Yonghuai Liu, Nik Bessis and Ardhendu Behera
**Department of Computer Science, Edge Hill University, United Kingdom**

### Abstract
Deep Convolutional Neural Networks (CNNs) for recognizing images with distinctive classes have shown great success, but their performance in discriminating fine-grained changes is not at the same level. We address this by proposing an end-to-end CNN model, which learns meaningful features linking fine-grained changes using our novel attention mechanism. It captures the spatial structures in images by identifying semantic regions (SRs) and their spatial distributions, and is proved to be the key to modeling subtle changes in images. We automatically identify these SRs by grouping the detected keypoints in a given image. The “usefulness” of these SRs for image recognition is measured using our innovative attentional mechanism focusing on parts of the image that are most relevant to a given task. This framework applies to traditional and fine-grained image recognition tasks and does not require manually annotated regions (e.g. bounding-box of body parts, objects, etc.) for learning and prediction. Moreover, the proposed keypoints-driven attention mechanism can be easily integrated into the existing CNN models. The framework is evaluated on six diverse benchmark datasets. The model outperforms the state-of-the-art approaches by a considerable margin using Distracted Driver V1 (Acc: 3.39%), Distracted Driver V2 (Acc: 6.58%), Stanford-40 Actions (mAP: 2.15%), People Playing Musical Instruments (mAP: 16.05%), Food-101 (Acc: 6.30%) and Caltech-256 (Acc: 2.59%) datasets.

### Context-aware Attentional Pooling (CAP)
Our CAP is designed to encode spatial arrangements and visual appearance of the parts effectively. The module takes input as a convolutional feature from a base CNN and then _learns to emphasize_ the latent representation of multiple integral regions (varying coarseness) to describe hierarchies within objects and parts. Each region has an anchor in the feature map, and thus many regions have the same anchor due to the integral characteristics. These integral regions are then fed into a recurrent network (e.g. LSTM) to capture their spatial arrangements, and is inspired by the visual recognition literature, which suggests that humans do not focus their attention on an entire scene at once. Instead, they focus sequentially by attending different parts to extract relevant information. A vital characteristic of our CAP is that it generates a new feature map by focusing on a given region conditioned on all other regions and itself.

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ArdhenduBehera/ag-net/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
