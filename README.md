# Popis projektu

Projekt klasifikace datasetu GTSRB - German Traffic Sign Recognition Benchmark.

## Použité modely

- Logistic Regression
- LinearSVC + PCA
- Random Forest
- KNN
- Decision Tree
- 2D CNN

## Spuštění projektu

pro instalaci knihoven:

Doporučuji si vytvořit venv pro instalaci knihoven.
A pak následně:
pip install -r requirements.txt

Jelikož dataset ve formátu .zip má velikost 300MB, přikládám odkaz pro ruční stažení.
Data jsou k dispozici ke stažení na stránce https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign?resource=download
Datový soubor extrahujte do složky "data" do stejného adresáře jako je .ipynb soubor.

Uporozňuji, že v procesu extrakce archive.zip souboru staženého z odkazu výše, je možné že se proces zasekne na 50%. Pak můžete klidně proces zastavit, jelikož data jsou extrahována všechna a nic nechybí.
Z nějakého důvodu k dokončení extrakce blokují soubory .~lock.nazev.ods# a ty nejsou potřeba, takže proces zastavit až se zasekne na 50% a soubory odstanit ze složky Meta

Celá složka by měla vypadat takto:

projekt/ <br>
│<br>
├── Maršoun_poznavani_znacek.ipynb<br>
├── requirements.txt<br>
├── README.md<br>
├── .gitignore<br>
│<br>
├── data/<br>
│   ├── Meta<br>
│   ├── Test<br>
│   └── Train<br>
│<br>
└── Data.zip<br>
