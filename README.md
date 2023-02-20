## Dual adversarial models with cross-coordination consistency constraint for domain adaption in brain tumor segmentation

### Paper

![](https://gitee.com/walynlee/upload-image/raw/master/image-20230211205933970.png)

### Abstract

The brain tumor segmentation task with different domains remains a major challenge because various tumors and cancers of different grades and severities may belong to different distributions, limiting the ability of a single segmentation model to label tumors of varying severities and growth. Semi-supervised models are strong unsupervised domain adaptation learners. However, one of the main drawbacks of using a mean teacher is that given a large number of iterations, the teacher model weights converge to that of the student model, and any biased and unstable predictions are carried over to the student. In this paper, we propose a novel unsupervised domain adaptation (DA) framework for the brain tumor segmentation task which uses dual students and adversarial training to effectively tackle domain shift with MR images. Herein, the adversarial strategy and consistency constraint for each student can align the feature representation on source and target domains. Furthermore, we introduced the cross-coordination constraint for target domain data to constrain the models to produce a more confident prediction. We validated our framework on the cross-subtype and cross-modality tasks in brain tumor segmentation and achieved better performance than traditional unsupervised domain adaptation and semi-supervised framework.

### Demo

![image-20230211215308987](https://gitee.com/walynlee/upload-image/raw/master/image-20230211215308987.png)

![image-20230211215322018](https://gitee.com/walynlee/upload-image/raw/master/image-20230211215322018.png)

Full paper preview at Google link: https://drive.google.com/file/d/1QLBoiYwBsS7VA9LEWR554w8jKDP85vY4/view?usp=sharing
