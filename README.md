# Detekcija lažnih oglasa za posao

Praktična analiza kvaliteta i predobrade tekstualnih podataka za binarnu
klasifikaciju oglasa na klase `real` i `fake`.

Notebook se nalazi u `detect-fake-jobs.ipynb`, a skup podataka u
`fake_real_job_postings.csv`.

Za pretrained DistilBERT eksperiment potrebni su dodatni paketi:

```bash
python -m pip install -r requirements-transformers.txt
```

Pri prvom pokretanju preuzimaju se `distilbert-base-uncased` tokenizer i
pretrained težine. Fine-tuning na CPU-u traje približno osam minuta.
