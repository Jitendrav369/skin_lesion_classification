# skin_lesion_classification
Data Dictionary
Data too large to load to GitHub and can be found here: https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000

Folder	Source	Contents
HAM10000_images_part_1	Kaggle/ISIC	contains the first set of the 10,015 images
HAM10000_images_part_2	Kaggle/ISIC	contains the second set of the 10,015 images
image_data	validation	HAM10000 Images
image_data_train	HAM10000 Images	contains 50% of the HAM10000 images for training; code in notebook
image_data_test	HAM10000 Images	contains 25% of the HAM 10000 images for testing; code in notebook
image_data_train_augmented	image_data_train	dataset of 26,000+ images created from augmenting the image_data_train; code in notebook
image_data_test_balanced	image_data_test	dataset of 196 images created from balancing the image_data_test; code in notebook
image_data_validation_balanced	image_data_validation	dataset of 196 images created from balancing the image_data_validation; code in notebook
HAM10000_metadata.csv	Kaggle/ISIC	decriptive data pertaining to each image
pre_processed_data_from_isic	Kaggle/ISIC	single array data of the pixels in the images
