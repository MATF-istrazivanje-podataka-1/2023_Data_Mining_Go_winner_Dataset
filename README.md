# Analiza skupa podataka CS:GO Round Winner Classification
 Autor: Bogdan Stojadinović 73/2020

U ovom seminarskom radu prikazan je proces rada sa podacima iz skupa preuzetog sa sajta Kaggle i možete im pristupiti pomoću <a href='https://www.kaggle.com/datasets/christianlillelund/csgo-round-winner-classification'>linka</a>. Skup podataka sadrži informacije o rundama igrice CS:GO, a prikupljeni su od strane Skybox-a kao deo njihovog CS:GO AI Challenge-a. Ukupno ima 122 411 instanci, svaka koja je opisana sa 97 atributa.

Cilj ovog rada je provesti detaljnu analizu skupa podataka i primeniti različite tehnike mašinskog učenja kako bismo napravili model koji može predvideti pobednika runde u CS:GO-u. Ukoliko želite da saznate nešto više o igrici CS:GO to možete učiniti na sledećem <a href='https://en.wikipedia.org/wiki/Counter-Strike:_Global_Offensive'>linku</a>.

Sve potrebne biblioteke mozete instalirati sa komandom:

``pip install numpy pandas matplotlib scikit-learn seaborn joblib``

## Korišćeni algoritmi
- Klasifikacija: DecisionTreeClassifier, RandomForestClassifier  KNeighborsClassifier
- Klasterovanje: KMeans, Bisecting KMeans, GaussianMixture
- Pravila pridruživanja: Apriori

## Napomena
Pre pokretanja model_comparison.ipynb potrebno je izvršiti kompletan decision_tree.ipynb i kompletan k_nearest_neighbors.ipynb kako bi se istrenirali svi modeli i napravili fajlovi trees.joblib i knn.joblib koji su bili preveliki da bih ih postavio na github