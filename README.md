# Faqe Urimi për Ditëlindje 🎉

Kjo është një faqe e thjeshtë për të uruar ditëlindjen në një mënyrë të personalizuar dhe unike. Faqja përmban një mesazh dashurie që shfaqet pasi klikohet butoni i urimit, duke krijuar një eksperiencë të veçantë për personin që e pranon.

## Përmbajtja

- **index.html**: Skedari HTML kryesor që përmban strukturën e faqes dhe mesazhin e personalizuar.
- **style.css**: Skedari i stilit CSS që përcakton paraqitjen vizuale të faqes.
- **JavaScript i integruar**: Një funksion JavaScript që mundëson shfaqjen e mesazhit të fshehur pasi klikohet butoni.

## Pamje e Faqes

Faqja është e stiluar me ngjyra të ngrohta dhe elegante për të krijuar një ambient të ngrohtë dhe festiv. Ajo përmban një titull të madh me urimin për ditëlindje, një buton që aktivizon mesazhin e fshehur dhe mesazhin personal të dashurisë për personin e veçantë.

## Si të Përdoret

1. **Shkarko ose klono** projektin nga GitHub.
2. Hap skedarin `index.html` në një shfletues për të parë faqen.
3. Kliko butonin e urimit për të zbuluar mesazhin e fshehtë të dashurisë.

## Përshkrimi i Skedarëve dhe Funksionalitetit

### 1. Skedari `index.html`

Kjo skedë përmban elementet kryesore të faqes, përfshirë titullin, butonin dhe mesazhin e fshehur.

### 2. Skedari `style.css`

- **Sfondi**: Ka një gradient të këndshëm nga rozë në ngjyrë fuchsia për një pamje festive.
- **Fontet**: Fontet përdoren për të krijuar një atmosferë elegante dhe të ngrohtë, me ndihmën e [Google Fonts](https://fonts.google.com/).

### 3. JavaScript

Një funksion JavaScript i thjeshtë për t'u përdorur për shfaqjen e mesazhit të fshehur.

```javascript
function revealMessage() {
  document.getElementById("message").style.display = "block";
}
