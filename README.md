### OCR järelkorrektsiooni testimine GPT-mudelitega

Toorandmed tuleb pakkida lahti kausta `data/raw`.
GPT käivitamiseks tuleb luua fail `./env` ja sinna kirjutada rida `MY_API_KEY=` (võrdusmärgi järele panna oma API võti).

- Treeningandmete ettevalmistus toorandmete põhjal toimub notebookis `training_data.ipynb`
- Mudelite peenhäälestus viidi läbi OpenAI platvormil
- Hindamine toimub notebookis `eval.ipynb`
