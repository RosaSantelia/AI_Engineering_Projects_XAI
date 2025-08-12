# AI_Engineering_Projects_XAI
My AI Engineering Master's Projects - ExplainableAI

# 🏦⚖️ Progetto di Explainable AI per la Compliance Normativa in Ambito Bancario

## Descrizione del Progetto

Banca Virtuosa, leader nel settore finanziario, mira a migliorare la trasparenza e la spiegabilità dei propri modelli di intelligenza artificiale utilizzati per la classificazione di dati finanziari critici.

Il presente progetto si propone di migliorare la trasparenza e la comprensibilità dei modelli di intelligenza artificiale impiegati da Banca Virtuosa per la classificazione di dati finanziari critici. Attraverso l’applicazione di tecniche avanzate di Explainable AI (XAI), quali Integrated Gradients, Grad-CAM, LIME e SHAP, si intende analizzare le decisioni di un modello di rete neurale pre-addestrata (DenseNet) adattata al dataset MNIST, al fine di:

- Visualizzare le caratteristiche salienti che influenzano le predizioni del modello;

- Identificare e comprendere errori e possibili bias nel processo decisionale;

- Garantire conformità con la normativa vigente in materia di trasparenza e governance dell’AI nel settore finanziario;

- Promuovere un uso più affidabile e interpretabile dell’intelligenza artificiale, rafforzando la fiducia di clienti e stakeholder.

L’approccio include un’analisi comparativa tra differenti tecniche di interpretabilità e una valutazione dettagliata delle performance del modello su specifiche classi di interesse, con l’obiettivo di fornire una solida base per interventi di miglioramento continuo.

### Requisiti
Python 3.8+ PyTorch Torchvision Captum (per XAI) scikit-learn matplotlib seaborn numpy lime

### Panoramica Tecnica:

- Modello: DenseNet121 pre-addestrato adattato per 10 classi MNIST

- Dataset: MNIST, immagini in 3 canali (RGB) ridimensionate a 224x224

Tecniche XAI:

- Grad-CAM per evidenziare regioni rilevanti nella rete convoluzionale

- Integrated Gradients per l’importanza pixel-wise

- Occlusion Maps per valutare la sensibilità del modello a porzioni dell’immagine

- LIME Tabular per spiegazioni locali su feature flattened
