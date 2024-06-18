# Title: A Deep Learning Based Approach to Image Captioning in Bangla


## Abstract:
This thesis presents a novel deep learning approach for generating image captions in Bangla, integrating techniques from both Natural Language Processing (NLP) and Computer Vision. The work is motivated by the need for accurate Bangla image captioning models to aid those who cannot understand English and to assist visually impaired individuals. Existing models predominantly focus on English, and the accuracy of Bangla captioning models is currently inadequate.

## Key Contributions:

- **Dataset Utilization and Modification:** Utilized the BanglaLekhaImageCaptions dataset, which includes 9,154 Bangladeshi contextual images with captions in Bangla, and the Flickr 8k dataset, comprising 8,145 images with captions in English. Translated the Flickr 8k captions to Bangla using Google Translator API and manual corrections to ensure accuracy.
- **Model Development:** Proposed a combined Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN) architecture. Extracted image features using a pre-trained ResNet50 model, followed by caption generation using a Long Short-Term Memory (LSTM) network.
- **Data Preprocessing:** Implemented thorough preprocessing steps for both image and text data, including feature extraction, punctuation removal, sequence tagging, and vocabulary encoding.
- **Training and Evaluation:** Trained the model on the combined dataset of BanglaLekhaImageCaptions and translated Flickr 8k captions, achieving satisfactory accuracy. Conducted evaluations using BLEU scores to assess the quality of generated captions.

## Challenges Addressed:

- Handling low-resolution and blurry images.
- Capturing human perspective in image captioning.
- Adapting to heterogeneous backgrounds to maintain context accuracy.

## Future Work:
- Exploring more sophisticated model architectures for enhanced performance and developing mobile and web applications to make the technology accessible to disabled individuals.

## Impact:
The research contributes to the field of human-computer interaction and robotics, with potential applications in developing assistive software for disabled individuals and enhancing surveillance and security systems.
