# Cartella Draft

Questa cartella contiene le bozze dei post non ancora pubblicati.

## Come usare i draft

### Creare un nuovo draft
Crea un file in questa cartella senza la data nel nome:
```
_drafts/titolo-del-post.md
```

### Visualizzare i draft in locale
```bash
bundle exec jekyll serve --drafts
```

### Pubblicare un draft
Quando sei pronto a pubblicare:
1. Sposta il file da `_drafts/` a `_posts/`
2. Rinomina aggiungendo la data: `YYYY-MM-DD-titolo-del-post.md`
3. Verifica il front matter (layout, categories, tags, ecc.)

## Note
- I draft non vengono mai pubblicati nel sito di produzione
- Non servono date nei nomi dei file draft
- La data di pubblicazione sarà quella in cui sposti il file in `_posts/`
