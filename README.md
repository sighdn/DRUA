# Disentangling Representation and Cross-Domain Adaptation for Unsupervised Change Detection in Multimodal Remote Sensing Images
## Abstract
Change detection in multimodal remote sensing images presents significant challenges, particularly for abrupt damage assessment. Multimodal images (e.g., SAR vs. optical) have different physical characteristics, making it difficult to detect land cover changes through direct comparison. Existing approaches typically rely on supervised learning (requiring costly labeled data), one-to-one modality mappings (which struggle with complex real-world modality variations), or structure similarities of modality-specific features (limiting generalizability).In this paper, we propose a novel unsupervised Disentangled Representation with Unpaired cross-domain Adaptation (DRUA) framework to address these issues.DRUA disentangles raw images into style representations (modality-specific attributes)  and content (land cover features).It uses style filters to enable flexible many-to-one/one-to-many mappings, capturing modality-specific knowledge without paired data.
By aligning content domains via maximal projection optimization of the raw image, DRUA facilitates direct comparison for change identification.This approach eliminates reliance on unchanged regions.Extensive experiments on five multimodal remote sensing datasets have demonstrated that DRUA can achieve superior change detection performance against ten state-of-the-art methods. By effectively disentangling both the content and style information of heterogeneous images, DRUA has attained a mean overall accuracy (OA) of 96.30\%, an F1 score of 0.79, and an average Kappa coefficient (KC) of 0.77, all outperforming the second-best method by about 2\% in OA, 0.19 in F1 score, and 0.19 in KC.

## Dataset
The dataset utilized in this study is located in the `dataset` folder.

## Code
The corresponding source code is currently under preparation and will be made publicly available in the future.

