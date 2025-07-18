# CalliECD dataset
## Project Profile
This repository is used for presentations on the CalliECD dataset. Here, we have uploaded 50 images within the CalliECD
dataset, along with the corresponding text descriptions.

# CalliECD
The generation of Chinese calligraphic characters presents a challenging task in computer vision. Under few-shot learning scenarios, the scarcity of calligraphy training data substantially increases the task difficulty. Current generative models commonly exhibit deficiencies, including missing strokes and structural misalignment when generating Chinese handwritten characters. Furthermore, the inherent stylistic diversity and brushwork complexity in Chinese calligraphy further constrain generative model performance. 

To overcome these challenges, we propose an Error Correction Diffusion Model for Multi-Style Chinese Calligraphy Generation, termed CalliECD. We constrain the generation process by integrating style reference information with stylistic features extracted via high-frequency filters, proposing an iterative skeleton extraction network based on a standard Chinese font library mapping. Besides, multi-level feature fusion enables repeated skeleton feature injection across a multi-scale UNet architecture, facilitating joint content-style learning. Significantly, we introduce a real-time error recognition and correction module that substantially enhances character generation accuracy and consistency. 

More crucially, we establish the first multi-class Chinese calligraphy dataset, termed CHC. This dataset encompasses 11 distinct script styles from master calligraphers, containing over 50,000 high-quality single-character images. The dataset annotations provide reliable data support for calligraphy generation research. 

Experimental results show that under few-shot conditions, the CalliECD method significantly outperforms baseline models in both glyph structure accuracy and generalization capability for unseen character generation. 

# code
We will upload the training as well as the test code and the full dataset at an appropriate time!
