# Bitcoin tarihsel veri grafiği ile gözetimli ve gözetimsiz öğrenme
This project was made for Aygaz Machine Learning Bootcamp.

Kullanılan kaggle veri kümesi: https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data

Kaggle Linki: https://www.kaggle.com/code/seymagunduz/btc-data-mlproject/edit

## Gözetimli Öğrenme
Gözetümlü öğrenme algoritması olarak Karar Ağaçları (Decision Trees) kullanılmıştır.

Projenin çıktısı:

Mean Squared Error: 21690974.018393066
R^2 Score: 0.9442286991184929
![image](https://github.com/user-attachments/assets/12b0e9d3-b844-458e-ac89-c2ce40c76a38)

## Gözetimsiz Öğrenme
Gözetimsiz öğrenme algoritmalarından (k-Means) Kümeleme kullanılmıştır.

Projenin çıktısı:

Silhouette Skoru: 0.6657006311976724

## Sonuç
Bu model için birçok algoritma denenmiştir. Fakat en etkili olanı Karar Ağaçları (Decision Trees) algoritması olmuştur. 
 * Aşırı Öğrenmeye Karşı Dayanıklılık
Ağaçların derinliğini sınırlamak (örneğin, maksimum derinlik belirleyerek) aşırı öğrenmeyi (overfitting) önlemeye yardımcı olur. Bu, modelin genelleme yeteneğini artırır.
* Hızlı Eğitim ve Tahmin
Eğitim süresi genellikle kısadır ve büyük veri setlerinde bile hızlı bir şekilde tahmin yapabilir. Bu, zaman açısından avantaj sağlar.
* Esneklik
Karar ağaçları, hem sınıflandırma hem de regresyon problemlerinde kullanılabilir. Bu, onları çok yönlü bir araç haline getirir
