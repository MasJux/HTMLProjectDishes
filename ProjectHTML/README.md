# Projekt zaliczeniowy z przedmiotu: _**Aplikacje internetowe**_

# Temat projektu: Serwis kulinarny
## Skład grupy: Piotr Janik, Maciej Ziółkowski, Patryk Midura
## Specyfikacja projektu
### Cel projektu : Stworzenie serwisu kulinarnego umożliwiającego założenie konta użytkownika, dzięki któremu będzie można dodawać przepisy w trzech kategoriach: śniadanie, obiad, kolacja. Każdy przepis będzie mógł zostać oceniony przez innych użytkowników.
#### Cele szczegółowe:
   1. Zachęcenie użytkowników do gotowania
   2. Umożliwienie dzielenia się przepisami z innymi użytkownikami
   3. Umożliwienie obiektywnej oceny każdego przepisu przez użytkownika
### Funkcjonalności:
   1. Panel logowania
   2. Panel rejestracji
   3. Dodawanie przepisu poprzez formularz
   4. Ocena dowolnego przepisu przez zalogowanego użytkownika
### Interfejs serwisu

<details>
	<summary>Ekran główny</summary>
	
![alt text][index]

</details>
	
<details>
       <summary>Logowanie</summary>

![alt text][logowanie]

</details>

<details>
       <summary>Rejestracja</summary>

![alt text][rejestracja]

</details>

<details>
       <summary>Reset hasła</summary>

![alt text][reset]

</details>

<details>
       <summary>Formularz dodawania przepisu</summary>

![alt text][addRecipe]

</details>

<details>
       <summary>Przepisy użytkownika</summary>

![alt text][userRecipes]

</details>

<details>
       <summary>Podstrona śniadania</summary>

![alt text][breakfast]

</details>

<details>
       <summary>Przykładowy przepis</summary>

![alt text][recipe]

</details>
         
### Baza danych

<details>
	<summary>Diagram ERD</summary>
	
![alt text][ERD]

</details>

<details>
	<summary>Skrypt do utworzenia struktury bazy danych</summary>

https://drive.google.com/file/d/141Z3xMK0YaWVQEObaNQoUpOjWKFbY09b/view?usp=sharing

</details>

## Wykorzystane technologie
- Bootstrap 4
- HTML5
- CSS
- JavaScript (SweetAlert)
- PHP 7.3.27
- MySQL
- jQuery
- AJAX

## Proces uruchomienia aplikacji (krok po kroku)
1. Pobieramy wszystkie pliki z github'a.
2. Uruchamiamy XAMPP oraz moduły odpowiednio: Apache i MySQL. 
3. Kliamy na przycisk "Explorer", przechodzimy do folderu "htdocs" i tam tworzymy folder "project" i do niego wrzucamy wszystkie pobrane pliki.
4. Wpisujemy w przeglądarce "localhost/phpmyadmin", tworzymy bazę danych o nazwie "recipeproject".
5. Do naszej nowo utworzonej bazy importujemy tabele z pliku "recipeproject.sql", który znajduje się w folderze "sql".
6. Po zaimportowaniu wpisujemy w przeglądarce "localhost/project" i cieszymy się działającą stroną!

### Potrzebne nazwy użytkowników do uruchomienia aplikacji
Nie są wymagane żadne specjalne nazwy do prawidłowego funkcjonowania aplikacji. <br>
Po uruchomieniu jej możemy się od razu zarejestrować i korzystać z pełnej funkcjonalności serwisu.

Login i hasło do bazy danych<br>
Użytkownik: root<br>
Hasło: (pozostawiamy puste)

[Przydatny link przy tworzeniu plików *.md ](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[ERD]: https://i.ibb.co/wr5BFdg/schemat.png "Schemat ERD"
[index]: https://i.ibb.co/1LnfD2F/index.png "Strona główna"
[logowanie]: https://i.ibb.co/gmcDwCW/logowanie.png "Panel logowania"
[rejestracja]: https://i.ibb.co/cLndQNx/rejestracja.png "Panel rejestracji"
[reset]: https://i.ibb.co/C18gqbD/reset.png "Panel resetowania hasła"
[userRecipes]: https://i.ibb.co/bsNpcXK/user-Recipes.png "Przepisy użytkownika"
[addRecipe]: https://i.ibb.co/1qyxcKh/add-Recipe.png "Dodaj przepis"
[breakfast]: https://i.ibb.co/Lv4FWM5/breakfast.png "Podstrona śniadania"
[recipe]: https://i.ibb.co/k0sWtXR/recipe.png "Przykładowy przepis"
