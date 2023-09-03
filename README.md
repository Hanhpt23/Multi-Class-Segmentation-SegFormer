# Multi-Class Segmentation using SegFormer
This file is sourced from [Finetune SegFormer](https://github.com/NielsRogge/Transformers-Tutorials/blob/master/SegFormer/Fine_tune_SegFormer_on_custom_dataset.ipynb). During the learning process, I encountered challenges in defining the model. As a result, I created this version, which proved effective for my needs.
## Modifications from the original file
1. Upload the 'ade20k-id2label.json' file
2. Dataloader
3. Data inference


## In this project, we will learn:
1. Install the transformers library from [HuggingFace](https://huggingface.co/docs/transformers/model_doc/segformer)
2. Fine-tuning SegFormerForSemanticSegmentation for a small dataset taken from ADE20K
4. Assessing the results using multi-class segmentation metrics

## Validation during the training
<div align="center">
  <img src="images/image.png" width="400" />
  <img src="image/prediction.png" width="400" />
</div>
</p>
<p align="center">
  <img src="images/image.png" width="400" />
  <img src="image/prediction.png" width="400" />
  Figure 1: Input image and prediction from the model.
</p>


<!-- ![image](images/val_batch0_labels.jpg) -->
<div align="center">
  <img src="images/image.png" width="400" />
  <img src="image/prediction.png" width="400" />
</div>
<p align="center">
  Figure 1: Prediction from the model on the PPE dataset
</p>


