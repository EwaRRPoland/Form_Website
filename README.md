# Form_Website  -  Simple page with form and list.

## Stworzony kod w języku JavaScript, który jest częścią formularza na stronie internetowej. 

1.Na początek, definiuję funkcję ``Math.sum``, która przyjmuje dowolną liczbę argumentów i zwraca ich sumę.

2.Następnie mamy dwie funkcje: ``areLetters`` i ``validatePhone``. Pierwsza z nich sprawdza, czy ciąg zawiera tylko litery, a druga, czy zawiera tylko cyfry. Oba te sprawdzenia są wykorzystywane w obsłudze zdarzeń ``keypress`` dla odpowiednich pól formularza.

3.Formularz ma pola o identyfikatorach ``firstName``, ``lastName``, ``ageEmployee``, ``position`` i ``phone``. Pobierane są wartości tych pól.

4.Tworzony jest obiekt pracownika, który zawiera imię, nazwisko, wiek, stanowisko i numer telefonu.

5.Sprawdzane jest, czy wiek nowo dodanego pracownika jest wyższy od obecnego najwyższego wieku przechowywanego w ``sessionStorage``. Jeśli tak, aktualizowany jest najwyższy wiek.

6.Obiekt pracownika jest dodawany do tablicy ``arrayEmployees``.

7.Tablica pracowników jest sortowana alfabetycznie po nazwisku.

8.Na stronie jest tworzona tabela, a nagłówki tabeli to “Imię”, “Nazwisko”, “Wiek”, “Stanowisko” i “Telefon”.

9.Obliczamy średni wiek pracowników, wyświetlamy średni wiek wszystkich pracowników pod listą pracowników.
