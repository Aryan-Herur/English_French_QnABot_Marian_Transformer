## Task 2B results :
* By using the HuggingFace pre-trained MarianTransformer architecure, the model attempted to generate a translation set.
* However, the program does have a few bugs :
* * The runtime to translate every single sentence in the test set exceeds the maximum alotted runtime on google colab.
  * Furthermore, the translation of the first sentence itself seems fairly accurate (I used google translate to check the meaning of the predicted translation of the first sentence), however, the returned sentence BLEU score is 0.00. 
