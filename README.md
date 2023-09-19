# ODR - Ocular Disease Recognition with Ensembling

Retinal pathologies are a major cause of childhood blindness and require rapid detection to reduce the workload of ophthalmologists. Deep learning algorithms are ideal for this field due to their dependence on pattern recognition. Each disease has varying stages of severity and specific lesions with unique morphological features. We present three ensemble models including binary and multi-class classifiers for different ocular diseases and stages of Diabetic Retinopathy. The models are built by studying lesion characteristics, data processing steps, identifying necessary libraries, and experimenting with various methods.

## Methodology
Three ensemble models were built individually using four pre-trained models. Fig 2 represents the approach followed in this method. The first Ensemble model is a binary classification model which has labels ‘Disease’ and ‘Normal.’ To build this ensemble model ResNet50, EfficientNet V2 S, and ResNext50 were trained individually on the ODIR dataset. The second Ensemble model is a multi-classification model which has labels 'Age Macular Degeneration', 'Cataract', 'Diabetic Retinopathy', 'Glaucoma', 'Myopia', and 'Normal'. To build this ensemble model the above same pre-trained models were used on the ODIR dataset. The third Ensemble model is also a multi-classification model which has labels ‘Normal’, ‘Stage 1’, ‘Stage 2’, ‘Stage 3’, and ‘Stage 4’. To build this ensemble model the above same pre-trained models were used on the Diabetic Retinopathy dataset.

![image](https://github.com/shubhu163/ODR/assets/71623089/6842f790-de2f-4b99-a1de-5e6a80e20eb7)

![image](https://github.com/shubhu163/ODR/assets/71623089/4144eb57-cc08-4f2f-becc-35f964edc44b)

