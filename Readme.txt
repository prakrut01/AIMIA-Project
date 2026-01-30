AIM: To conduct a comprehensive comparative study evaluating modern deep learning architectures (specifically EfficientNet-B3 and Vision Transformers) against a traditional ResNet-50 baseline for multi-label classification of thoracic diseases from chest X-rays, while systematically analyzing the impact of critical training factors including loss functions (Weighted BCE vs. Focal Loss) and image resolutions (512px vs. 384px).

In this project we have trained 3 models which are Baseline paper's Resnet 50 model stored in baseline_model. We have trained Efficient net model stored in efficient_net folder and Vit model stored in ViT folder.

I have created a small dataset which has 140 images and a .csv file containing the multilable classification information for testing of the models.
We have test_final.ipynb file which tests both the efficient and ViT based trained models on the small dataset.

All the training code of these models are in folder named Model_training_codes, all the testing codes of these models on original test dataset are in folder named Model_testing_codes. 


