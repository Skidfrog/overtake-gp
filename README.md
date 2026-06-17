\# Overtake.GP · Data Analytics



Anàlisi de dades d'un mitjà digital de motorsport a Instagram.

Projecte final del Bootcamp Data Analytics · Barcelona Activa · Juny 2026.



\## Què és aquest projecte?

Overtake.GP és un compte d'Instagram dedicat al motorsport (MotoGP, Moto2, Moto3),

creat el desembre de 2023. Aquest projecte analitza el seu creixement,

engagement, contingut i audiència mitjançant tècniques de data analytics

i models d'intel·ligència artificial.



\## Resultats principals

\- Creixement: +494% (4.580 → 27.198 seguidors)

\- Engagement: 10,1% vs 0,45% de mitjana sectorial

\- Líder en creixement relatiu entre 7 comptes del sector

\- Projecció Holt-Winters: \~30.000 seguidors a finals de 2026

\- Marc Márquez: actiu editorial principal (NER + CLIP)



\## Estructura
overtake-gp/



├── data/



│   ├── raw/          → dades originals (CSV, JSON)



│   └── processed/    → dades processades



├── src/



│   └── app.py        → dashboard Streamlit



├── notebook/



│   └── Overtake\_analisi\_v4\_1.ipynb  → notebook principal



├── docs/



│   └── Projecte especialitzacio.pdf



├── requirements.txt



└── README.md



\## Fonts de dades

| Font | Contingut | Període |

|------|-----------|---------|

| InstaTrack | Seguiment diari de 7 comptes de motorsport | Des. 2023 → Jun. 2026 |

| Metricool | 419 posts individuals d'Overtake.GP | Ago. 2025 → Jun. 2026 |

| Metricool API | Instantània demogràfica de l'audiència | Maig 2026 |



\## Com executar-lo



\### Instal·lar dependències

```bash

pip install -r requirements.txt

```



\### Executar el dashboard Streamlit

```bash

streamlit run src/app.py

```



\### Executar el notebook

Obre `notebook/Overtake\_analisi\_v4\_1.ipynb` amb Jupyter Notebook o JupyterLab.



\## Eines utilitzades

\- \*\*Python\*\* · pandas · numpy · matplotlib · seaborn · plotly

\- \*\*Models IA\*\* · BERT-NER (Hugging Face) · CLIP (OpenAI)

\- \*\*Estadística\*\* · Spearman · Mann-Whitney · Kruskal-Wallis · Holt-Winters

\- \*\*Streamlit\*\* · dashboard interactiu

\- \*\*GitHub\*\* · control de versions



\## Autor

Jordi Lamarca · Bootcamp Data Analytics · Barcelona Activa · 2026

