# SpeedItUp-TheMovieLibrary
Изготвил: Анелия Лявова
Град: Пловдив
Училище: МГ "Академик Кирил Попов"

Език: C#
Представяне: Visual Studio Console
Използвани технологии: Entity Framework

Условие: Да се напише код, който да обработва данни за филмотека до 132 филма. За всеки филм да има информация за неговото заглавие, жанр, дата на премиерата и главните актьори. Важно е кодът да може да сортира филмите по заглавие и/или по актьор, и/или по жанр. Също така, ако измежду тях има заглавието "Матрицата" – винаги при сортирането да бъде на първо място.

Приложението е създадено във Visual Studio, като се състои от три проекта в един Solution, които са взаимосвързани:
 - Business, в който е основната логика 
 - Data, от който се управляват данните от базата данни
Базата данни е създадена и се управлява чрез Entity Framework.
 - MovieLibrary, в който има три класа, единият от които (Controller.cs) е пряко свързан с функциите в Business. Display.cs има за цел да извежда съобщения и информация, получена от другите проекти, на конзолата, и разбира се, Program.cs.

Интерфейсът е изключително user-friendly, така че приложението само ще ви помогне да се ориентирате при работата с него.

Към момента в базата данни е налична тази информация:
Title: Inception | Genre: Science Fiction, Action, Thriller | Release date: 16.7.2010 г. 0:00:00 | Actors: Leonardo DiCaprio, Joseph Gordon-Levitt, Ellen Page
Title: The Dark Knight | Genre: Action, Crime, Drama | Release date: 18.7.2008 г. 0:00:00 | Actors: Christian Bale, Heath Ledger, Aaron Eckhart
Title: The Shawshank Redemption | Genre: Drama | Release date: 23.9.1994 г. 0:00:00 | Actors: Tim Robbins, Morgan Freeman, Bob Gunton
Title: The Matrix | Genre: Science Fiction, Action | Release date: 31.3.1999 г. 0:00:00 | Actors: Keanu Reeves, Laurence Fishburne, Carrie-Anne Moss
Title: Avatar | Genre: Science Fiction, Action, Adventure | Release date: 18.12.2009 г. 0:00:00 | Actors: Sam Worthington, Zoe Saldana, Sigourney Weaver


