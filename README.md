# IndoHerb Dataset
---
This repo is the official dataset of [IndoHerb: Indonesia medicinal plants recognition using transfer learning and deep learning](https://doi.org/10.1016/j.heliyon.2024.e40606)

## Abstract
The rich diversity of herbal plants in Indonesia holds immense potential as alternative resources for traditional healing and ethnobotanical practices. However, the dwindling recog-nition of herbal plants due to modernization poses a significant challenge in preserving this valuable heritage. The accurate identification of these plants is crucial for the continuity of traditional practices and the utilization of their nutritional benefits. Nevertheless, the manual identification of herbal plants remains a time-consuming task, demanding expert knowledge and meticulous examination of plant characteristics. In response, the application of computer vision emerges as a promising solution to facilitate the efficient identification of herbal plants. This research addresses the task of classifying Indonesian herbal plants through the implementation of transfer learning of Convolutional Neural Networks (CNN). To support our study, we curated an extensive dataset of herbal plant images from Indonesia with careful manual selection. Subsequently, we conducted rigorous data preprocessing, and classification utilizing transfer learning methodologies with five distinct models: ResNet, DenseNet, VGG, ConvNeXt, and Swin Transformer. Our comprehensive analysis revealed that ConvNeXt achieved the highest accuracy, standing at an impressive 92.5 %. Additionally, we conducted testing using a scratch model, resulting in an accuracy of 53.9 %. The experimental setup featured essential hyperparameters, including the ExponentialLR scheduler with a gamma value of 0.9, a learning rate of 0.001, the Cross-Entropy Loss function, the Adam optimizer, and a training epoch count of 50. This study's outcomes offer valuable insights and practical implications for the automated identification of Indonesian medicinal plants, contributing not only to the preservation of ethnobotanical knowledge but also to the enhancement of agricultural practices through the cultivation of these valuable resources. <br />

## Information
IndoHerb dataset is a new dataset of medicinal plants from Indonesia, collected independently through the Google Images search engine. To ensure that the plant images correspond to the classification, we cross-referenced the medicinal plants with the list provided by the Medicinal Plant Maintenance Installation at the Baturaja Health Research and Development Center, Indonesian Ministry of Health. Subsequently, the images were systematically collected from the web. Finally, the dataset underwent validation and meticulous selection by a professor of biology—an expert in Plant Taxonomy and Ethnobotany—to authenticate the collected images of Indonesian medicinal plants. The datasets is tested using the transfer learning method from the convolutional neural network.

During the dataset collection process, the initial step involved determining which species of medicinal plants from Indonesia would be utilized for research. To identify these species, searches were conducted on various websites that provided the names of medicinal plant species from Indonesia, resulting in the collection of 100 species for research. Following this, an image search was conducted for each species of medicinal plants using the Google Images search engine.

From the search results, images that met the criteria for each species were manually selected from the top search results. This manual selection was necessary because, at times, there were discrepancies, such as instances where identical images appeared from different sources. While this issue was minimized in the study, inadvertent selections of identical images were left unchanged. Additionally, some images were excluded due to quality issues, such as scribbles or watermarks. Another challenge involved less-known or rarely found species, resulting in a limited number of search results (e.g., approximately 30 images meeting the criteria). To address this, an image augmentation process was implemented on the obtained images, including horizontal flips, vertical flips, and rotations. Ultimately, all images were resized to 128 × 128. The final IndoHerb dataset comprises 10,000 images across 100 species, with each species containing 100 images.

Fig. 1 Example images from five selected species of IndoHerb dataset.
 
<img src="https://github.com/user-attachments/assets/12bea63d-5ba6-4eac-bf87-36bde73bff7b" alt="contoh image dataset" width="500" height="500">

## References
```
Ikrar Musyaffa, M. S., Yudistira, N., Rahman, M. A., Basori, A. H., Firdausiah Mansur, A. B., & Batoro, J. (2024). IndoHerb: Indonesia medicinal plants recognition using transfer learning and deep learning. Heliyon, 10(23), e40606.
```

## Citation
```
@article{musyaffa2024indoherb,
  title={Indoherb: Indonesia medicinal plants recognition using transfer learning and deep learning},
  author={Musyaffa, Muhammad Salman Ikrar and Yudistira, Novanto and Rahman, Muhammad Arif and Basori, Ahmad Hoirul and Mansur, Andi Besse Firdausiah and Batoro, Jati},
  journal={Heliyon},
  year={2024},
  publisher={Elsevier}
}
```
