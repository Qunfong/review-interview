# Leerplan Senior Java Reviewer

Een 8-weeks leer- en toetsplan om code te reviewen op het niveau van een senior Java-developer.

## Publiceren op GitHub Pages

1. Maak een nieuwe repository op GitHub, bijvoorbeeld `java-review-leerplan`.
2. Upload `index.html`, `.nojekyll` en deze `README.md` naar de root van de `main`-branch.
3. Ga naar **Settings → Pages**.
4. Kies bij **Source** voor **Deploy from a branch**, branch `main`, map `/ (root)`, en klik **Save**.
5. Na ongeveer een minuut staat de site op `https://<gebruikersnaam>.github.io/java-review-leerplan/`.

Via de command line:

```bash
git init
git add index.html .nojekyll README.md
git commit -m "Leerplan Senior Java Reviewer"
git branch -M main
git remote add origin https://github.com/<gebruikersnaam>/java-review-leerplan.git
git push -u origin main
```
