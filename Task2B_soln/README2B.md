# Task 2B results :
* By using the HuggingFace pre-trained MarianTransformer architecure, the model attempted to generate a translation set.
* However, the program does have a few bugs :
* * The runtime to translate every single sentence in the test set exceeds the maximum alotted runtime on google colab.
  * Furthermore, the translation of the first sentence itself seems fairly accurate (I used google translate to check the meaning of the predicted translation of the first sentence), however, the returned sentence BLEU score is 0.00. 

## For reference :
english sentence : However, the Canadian dollar import value of this important export item to Japan decreased by 13.0% from Cdn$116.1 million in 2000 to Cdn$101.01 million in 2001.

ground truth : Au cours de la même période, la valeur en dollars canadiens de cet important produit d'exportation vers le Japon a cependant diminué de 13,0 %, passant de 116,1 millions $CAN à 101,01 millions $CAN.

prediction : Toutefois, la valeur des importations canadiennes de cet important article d'exportation au Japon a diminué (de 116,1 millions $CAN en 2000 à 101,01 M$ CAN pour 2001).

google translation of prediction : However, the value of Canadian imports of this important export item to Japan has decreased (from CAN$116.1 million in 2000 to CAN$101.01 million in 2001).
