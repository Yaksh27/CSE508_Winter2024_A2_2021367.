IR Assignment 2 


Introduction

Assignment 2 included a challenging assignment focused on developing a multimodal retrieval system using Python. This system leverages both textual and visual data to perform efficient and accurate information retrieval. The assignment emphasizes individual effort, adherence to academic integrity, and the application of specific Python libraries for data preprocessing and feature extraction.

Key Components : 

Libraries and Resources: The project utilizes Python libraries such as NLTK for text preprocessing and BeautifulSoup for web scraping. For image feature extraction, pre-trained Convolutional Neural Network (CNN) architectures like ResNet, VGG16, Inception-v3, and MobileNet, specifically those pre-trained on the ImageNet dataset, are employed to derive meaningful representations from images.

Text Preprocessing: Textual data undergoes extensive preprocessing to ensure uniformity and relevance. This includes converting text to lowercase, tokenization, removal of punctuation and non-alphabetic characters, and filtering out stopwords. These steps are crucial for focusing on significant words and phrases within the corpus.

Image Feature Extraction: The project applies basic image preprocessing techniques such as altering contrast, resizing, adjusting geometrical orientation, and modifying brightness and exposure. A chosen pre-trained CNN architecture extracts relevant features from images. This process is vital for transforming visual information into a format suitable for comparison and retrieval.

Positional Index Creation: For text-based retrieval, the system builds a positional index using nested dictionaries. This index maps words to their positions across documents, facilitating efficient phrase query processing.

Saving and Loading Mechanisms: Both the textual and visual feature extraction results are serialized using Python’s pickle module. This allows for efficient data retrieval and reuse in subsequent query processing.

Functionality

Query Processing: The system supports both image and text retrieval. It finds the most similar images and text reviews based on extracted features and TF-IDF scores, respectively. A similarity measure, such as cosine similarity, is used to rank the results.

Combined Retrieval: A composite score is calculated by averaging the similarity scores from both text and image retrieval. This multimodal approach enhances the retrieval accuracy by leveraging information from both domains.

Challenges and Solutions:


Handling multimodal data presented unique challenges, such as integrating diverse data types and ensuring efficient retrieval across different modalities. 
These were addressed by carefully selecting preprocessing techniques and optimizing the retrieval algorithms. 
The use of pre-trained models for image feature extraction streamlined the process, allowing for focus on developing robust retrieval mechanisms.

Conclusion

This project embodies the complexities and challenges of multimodal information retrieval. Through the integration of text and image data, it showcases the potential for creating more nuanced and effective retrieval systems. The methodologies and approaches adopted highlight the importance of preprocessing, feature extraction, and the innovative use of Python libraries in solving real-world information retrieval problems.

Results : 

1). 
2).


3). 
IMAGE RETRIEVAL : 


TEXT RETRIEVAL : 
 

