# Detectia Metastazei in Imagini Histopatologice

### Student
Anghel Ioan-Tudor-Alexandru
### Profesor Indrumator
Dumitriu Andrei
### Dataset folosit
https://github.com/basveeling/pcam

---

## Motivatia lucrarii
Detectia metastazelor in imagini histopatologice reprezinta un subiect foarte important in domeniul oncologiei, ajutand la tratarea eficienta a pacientilor si la adaptarea prognosticelor. Imbunatatirea acestui proces este de mare interes pentru mine, datorita impactului pozitiv pe care l-ar putea avea asupra pacientilor si asupra specialistilor din domeniu.

## Problema
- Diagnosticarea metastazelor presupune analiza manuala a probelor histopatologice de catre experti;
- Procesul este consumator de timp si susceptibil la erori umane;
- Variatiile tesuturilor canceroase si complexitatea imaginilor analizate fac sarcina sa fie cu atat mai dificila.

## Solutia
- Proiectul de semestru presupune dezvoltarea unui model de inteligenta artificiala, bazat pe Deep Learning, cu scopul de a detecta imagini histopatologice ce contin metastaze;
- Un astfel de model poate fi utilizat pentru a imbunatati acuratetea si viteza de diagnosticare, fiind o unealta utila in revizuirea rezultatelor propuse de un expert;
- Solutia finala este o arhitectura de VGG-16, construita folosind layers din biblioteca Keras, care este descrisa de urmatoarele metrici: 
  - Accuracy: 92.2%
  - Precision: 93.1%
  - Recall: 88.7%
  - Specificity: 94.9%