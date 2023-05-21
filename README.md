README programu Zapytanie Curl curl -s https://mdn.github.io/learning-area/javascript/oojs/json/superheroes.json | jq '.members[].name'

Circuit braker -  bezpiecznik powoduje ,że niedziałąjąca część aplikacji nie uruchamia się dzięki temu nie tworzą się nowe błędy.Można skupić się dzięki temu na rozwiązywaniu problemu w konkretnej części aplikacji.

cascading failure- pozwala zapobiegać błędom które mogą doprowadzić do awari całej aplkacji.Błąd w początkowej części programu może doprowadzić do błędów w dalszych modułach aplikacji.

greaceful degradation -Błędy w aplikacji pomimo ,któryvh aplikacja może działać lub mogą działać niektóre funkcjie.Dzięki temu można kożystać z aplikacji pomimo problemów.
