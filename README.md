Temporary anonymous code repository for "Conformal Prediction Sets for Instance Segmentation."

All data can be downloaded from: https://drive.google.com/drive/folders/1ggv4jHeTTUsmywf8WiO3Cay2AxGpRv13?usp=sharing

# Data sources and models 
- Field delineation
  - Fields of the World France dataset (https://source.coop/kerner-lab/fields-of-the-world)
  - Predictions are obtained using the Fields of the World v1 "3_Class_FULL" model (https://github.com/fieldsoftheworld/ftw-baselines/releases/tag/v1)
- Cell segmentation
  - Cellpose dataset (https://www.cellpose.org)
  - Predictions are obtained using the Cellpose-SAM model (https://github.com/mouseland/cellpose)
- Vehicle detection
  - Cityscapes dataset (https://www.cityscapes-dataset.com)
  - Predictions are obtained using the SAM model (https://github.com/facebookresearch/segment-anything) (https://dl.fbaipublicfiles.com/segment_anything/sam_vit_h_4b8939.pth)
