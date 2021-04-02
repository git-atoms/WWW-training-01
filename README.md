## Tworzenie stron WWW

*(Samokształcenie: kurs z Udemy)*


---

<br>

### Rozdział pierwszy: Wstęp

<br>
<br>

1. Czego nauczysz się w kursie?
2. Projekty, które zrobimy w kursie.
3. Discord czyli dodatkowa pomoc i więcej :)
4. Krótkie ogłoszenie

> * [Strona prowadzącego](https://mmcschool.pl/)
>
> * [YouTube prowadzącego](https://www.youtube.com/channel/UCcaDo69KhpkjtA8iR7agM_g)

<br>
<br>

5. Jak oglądać kurs w lepszej jakości niż 720p?
6. Darmowe materiały naukowe
7. Z jakiej przeglądarki korzystać?

<br>

> Zalecane przeglądarki to:<br>
> * Chrome
> * Opera
> * Brave

<br>
<br>

---

<br>
<br>

### Rozdział drugi: Poznajmy HTML!

<br>
<br>

1. **Zanim zaczniemy... :)**
2. **HTML - wprowadzenie**
3. **Visual Studio Code**
4. **Lista wtyczek i ustawień do VSC**
5. **Podstawowa struktura HTML**

<br>

> W sekcji

```html
<head>

</head>
```
> umieszczamy
> * nasze metatagi, czyli wszystkie niezbędne dane (choćby dla przeglądarki /wyszukiwarki),
> * wszystkie informacje na temat styli naszych CSS
> * tytuł zakładki (tab) w przeglądarce:

```html
<head>
    <title>Moja strona</title>
</head>
```

<br>

> Komentowanie w HTML

```html
<!-- Tak wygląda komentarz w HTML -->
```
> w VisualStudio Code i w WebStorm, skrótem do komentarza jest CTRL + /


<br>

> W sekcji
```html
<body>
</body>
```
> umieszczamy
> * obrazki (img)
```html
<img src="" alt="">
```
<br>

> * linki (a)
```html
<a href=""></a>
```
<br>

> * paragrafy = nasz tekst (p)
```html
<p>
</p>
```
<br>

> * formularze (input)
```html
<input type="text" name="" id="">
```



<br>
<br>


6. **Semantyka i najczęściej używane tagi HTML**


>TAGI
```html
<!-- Najważniejszy w całej strukturze -->
<html>


<!-- Tag od "myślenia", umieszczamy w nim metadane i skrypty -->
<head>


<!-- "Ciało" naszej strony WWW, umieszczamy w nim treść, obrazy, formularze, itd -->
<body>


<!-- Dobry przyjaciel, w którym możemy trzymać inne tagi -->
<div>


<!-- Paragraf, umieszczamy w nim tekst -->
<p>


<!-- Nagłówki -->
<h1-h6>


<!-- Umieszczamy w nim obrazy -->
<img>


<!-- Umieszczamy w nim linki -->
<a>


<!-- Dla CSS ale możemy też użyć <link> -->
<style>


<!-- Dla JavaScript -->
<script>
```

<br>

> SEMANTYKA<br>
> Zbiór dobrych zasad /praktyk, stosowanych przy tworzeniu strony WWW<br>
 
 * Dla deweloperów<br>
 "Zielone światło / czerwone światło" - międzynarodowe zasady /praktyki.<br>

<br>

 * Dla osób niewidomych<br>
Stosując się do zasad semantyki, ułatwiamy np. korzystanie ze stron WWW osobom niewidomym (via Screen Reader).<br>

<br>

 * Dla programistów<br>
 Jeden standard pisania przez nas kodu, pomaga tworzyć lepsze aplikacje innym.

<br>

 * Dla SEO<br>
Nasza strona będzie wyżej notowana (wyszukiwarki lepiej dopasują treść) i przez to ma szansę odwiedzić nas więcej osób.<br>
np. nagłówek H1 powinien być użyty tylko raz na stronę albo raz na sekcję.

<br>
<br>

7. **Główne tagi HTML cz. 1**

>Elementy blokowe - zajmują całą dostępną szerokość swojego rodzica (parent).

```html
<div></div>
```

```html
<p></p>
```

<br>

>Elementy liniowe - zajmuje tylko tyle przestrzeni ile faktycznie potrzebuje.

```html
<span></span>
```

<br>

A [tutaj jest](https://developer.mozilla.org/pl/docs/web/HTML) bardzo fajna dokumentacja HTML.<br>
MDN - **M**ozilla **D**eveloper **N**etwork


<br>
<br>


8. Główne tagi w HTML cz. 2

>Aby było semantycznie używamy obecnie następujących tagów klas:

```html
<nav></nav>
<header></header>

<!-- Najważniejsza sekcja -->
<main></main>
<section></section>
<article></article>

<!-- Poboczna sekcja np. na reklamy -->
<aside></aside>
<footer></footer>
```
>Tag **main** może być tylko jeden. Jeśli występuje kilka razy to błąd.

<br>
<br>


9. Metatagi
10. Formularze
11. Formatowanie i zabawa z tekstem
12. Listy w HTML
13. Tabele w HTML
14. Tagi SCRIPT
15. Pozostałe tagi HTML
16. DOCTYPE & HTML lang
17. Wprowadzenie do zadania: Stwórz podobną stronę
18. Rozwiązanie zadania