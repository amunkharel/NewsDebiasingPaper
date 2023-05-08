# NewsDebaising
Please go to respective folders and read the README file to run the respective models. 

# Abstract
Due to the presence of political echo chambers, it becomes imperative to detect and remove subjective bias and emotionally charged language from both the text and images of political articles.  However, prior work has focused on solely the text portion of the bias rather than both the text and image portions.  This is a problem because the images are just as powerful of a medium to communicate information as text is.  To that end, we present a model that leverages both text and image bias which consists of four different steps.  Image Text Alignment focuses on semantically aligning images based on their bias through CLIP models.  Image Bias Scoring determines the appropriate bias score of images via a ViT classifier.  Text De-Biasing focuses on detecting biased words and phrases and neutralizing them through BERT models.  These three steps all culminate to the final step of debiasing, which replaces the text and the image with neutralized or reduced counterparts, which for images is done by comparing the bias scores. The results so far indicate that this approach is promising, with the text debiasing strategy being able to identify many potential biased words and phrases, and the ViT model showcasing effective training. The semantic alignment model also is efficient.  However, more time, particularly in training, and resources are needed to obtain better results.  A human evaluation portion was also proposed to ensure semantic consistency of the newly generated text and images.

# Team Members
Cedric Bernard
Xavier Pleimling
Amun Kharel
Chase Vickery

