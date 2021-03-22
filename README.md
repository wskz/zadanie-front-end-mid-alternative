# WSKZ zadanie rekrutacyjne - Front-end developer 

Zadanie ma na celu sprawdzenie poziomu kandydata wiedzy z zakresu HTMLa, CSSa i JSa.

Projekt używa Node oraz modułów npm.

## Fork repozytorium

Link do repozytorium: https://github.com/wskz/zadanie-front-end-mid-alternative

Repozytorium posiada uprawnienia odczytu. W celu ukończenia zadania wymagany jest fork do prywatnego repozytorium.

Po skończeniu zadania proszę nadać uprawnienia odczytu dla `grzegorz.topolewski@wskz.pl`, `anna.antaswskz@gmail.com`, `pawel.usinowicz@wskz.pl`

## Jak rozpocząć

Ponieważ projekt bazuje na Node, ważne jest aby Kandydat posiadał zainstalowany Node na lokalnym komputerze.

Dodatkowo projekt posiada już wymagane moduły npm, aby je zainstalować:

```
npm install
```

Celem ułatwienia pracy nad zadaniem zalecana jest instalacja dodatku do VSC (Visual Studio Code) 'Live Server'

## CSS

- Kandydat zobowiązany jest do pisania CSSa używając preprocesora Sass/Scss. W projekcie zostało utworzone zadanie Gulp 'sass'.

- Kandydat jest zobowiązany do pisania CSS w architekturze BEM.

- W projekcie została utworzona podstawowa struktura folderów dla Sass/Scss (w oparciu o SMACSS)
```
  src/
    scss/
      base/
      layout/
      module/
      state/
      theme/ (opcjonalnie)
```
# JS

- Kandydat może zdecydować czy chce pisać JavaScript natywnie, czy woli użyć TypeScripta.
- Inne biblioteki nie są dozwolone (np. jQuery).
- W projekcie zostało utworzone zadanie Gulp 'scripts'

## Porady

- Postaraj się wykazać dobrą znajomościa Gita:
  - Postaraj się tworzyć commity do każdej istotnej części zadania
  - Postaraj się używać dobrych opisów do commitów
- Postaraj się pisać modularny i efektywny Sass/Scss (używaj zmiennych, mixinów)
- Dozwolone jest użycie frameworków CSS (preferowany Boostrap 4+). W przypadku wyboru frameworka istotna jest optymalizacja narzędzia pod względem performance niepotrzebnego kodu narzędzia
- Pisząc HTML używaj prawidłowego nazewnictwa opartego o BEM
- Pisząc JavaScript postaraj się wykazać znajomość ES6+
- Możesz doinstalować dodatkowe narzędzia używając npm, typu lintery SCSS oraz TS
- Projekt będzie oceniany pod kątem:
  - jakości kodu
  - performance
  - cross-browser
  - responsywności
  - odwzorowania pixel perfect
  - dostępności

## Zadania

### 1. Refaktoryzacja Landing home page
- przejrzyj demo stronę `app/index-demo.html`
- użyj `app/index.html` do dalszej pracy
- zrefaktoryzuj stronę index-demo.html:
  - użyj preprocesora Sass/Scss
  - pisz markup oparty o BEM
  - użyj frameworka CSS (preferowany Bootstrap 4+)
  - elementy interaktywne (wymagane jest napisanie JS tylko dla poniższych punktów) możesz stworzyć dostosowując komponentu UI frameworka CSS, pure JavaScript lub TypeScript. Użycie innych narzędzi i frameworków JS jest niedozwolone (np. jQuery):
    - slider
    - menu dektopowe
    - menu mobilne
  - Pisząc kod JavaScript lub TypeScript postaraj się napisać go w OOP lub w postaci pluginu (który może zostać przeniesiony na każdą dowolną stronę)
- upewnij się, że strona jest w pełni responsywna
- na stronie istnieją błędy (patrz poniższe punkty). Postaraj się naprawić jak najwięcej z nich. Każdy znaleziony i poprawiony błąd musi zostać opisany w pliku #src/errors-table/errors.html
  - responsywności
  - JavaScript
  - markup
  - stylowania

- **opcjonalne zadania:** - Stwórz modal reklamowy, który pojawi się automatycznie na stronie homepage po 3000ms (modal ma posiadać zdjęcie w tle, tytuł i akapit tekstu). Modal ma pojawiać się tylko dla nowych użytkowników, jeżeli odwiedzę stronę kolejny raz to modal się już nie pokazuje (użyj mechanizm cookies).
- **opcjonalne zadania:** - Demo strony posiada bardzo dużo nieużytego CSSa, co powoduje obniżenie performance. Stwórz zadanie Gulp, które przeskanuje pliki html, js i css (plik: # app/css/all.css, już po przekonwertowaniu z scss/sass) i przygotuje wersję clean-css.css w folderze app/css/. Pamiętaj, aby upewnić się, że nowy wygenerowany clean-css.css obsługuję klasy CSS dla napisanego Javascriptu

## Przesłanie zadania do oceny

Zadanie musi zostać umieszczone jako projekt na prywatnym repozytorium Kandydata, z opcją odczytu dla: `grzegorz.topolewski@wskz.pl`, `anna.antas@wskz.pl`, `pawel.usinowicz@wskz.pl`

Poinformuj proszę  email `anna.antaswskz@gmail.com` w momencie zakończenia zadania

**Powodzenia**
Zespół WSKZ