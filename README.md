Code repository for:

> Lu, Kerri, Dan M Kluger, Stephen Bates, and Sherrie Wang (2026). “Conformal Prediction Sets for Instance Segmentation”. In: *The Forty-Second Conference on Uncertainty in Artificial Intelligence.* https://arxiv.org/abs/2602.10045

All data can be downloaded from: https://drive.google.com/drive/folders/1ggv4jHeTTUsmywf8WiO3Cay2AxGpRv13?usp=sharing

# Data sources and models

* Field delineation

  * Fields of the World France dataset (https://source.coop/kerner-lab/fields-of-the-world)
  * Predictions are obtained using the Fields of the World v1 "3\_Class\_FULL" model (https://github.com/fieldsoftheworld/ftw-baselines/releases/tag/v1)

* Cell segmentation

  * Cellpose dataset (https://www.cellpose.org)
  * Predictions are obtained using the Cellpose-SAM model (https://github.com/mouseland/cellpose)

* Vehicle detection

  * Cityscapes dataset (https://www.cityscapes-dataset.com)
  * Predictions are obtained using the SAM model (https://github.com/facebookresearch/segment-anything) (https://dl.fbaipublicfiles.com/segment\_anything/sam\_vit\_h\_4b8939.pth)
