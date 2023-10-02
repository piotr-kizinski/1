# Praca domowa: HTML i CSS

Stwórz stronę z formularzem kontaktowym zawierającym tytuł wiadomości, adres email oraz treść.
Na górze strony powinien znaleźć się przypięty nagłówek z logo firmy, na samym dole stopka z nazwą, niezależnie od wysokości okna przeglądarki.

![contact page](../.doc-assets/contact.jpg)

**Kryteria**:

- [ ] poprawna struktura HTML
- [ ] walidacja 
  - [ ] tytuł jest wymagany i powinien zawierać przynajmniej 3 znaki
  - [ ] email jest wymagany i powinien mieć poprawny format adresu email
  - [ ] treść jest wymagana i powinna zawierać przynajmniej 3 znaki, ale nie więcej niż 500
  - [ ] błędnie wypełnione pola powinny zostać oznaczone na czerwono
- [ ] nagłówek
  - [ ] zawsze widoczny na samej górze strony
- [ ] stopka
  - [ ] na samym dole strony, kiedy cała treść jest widoczna
  - [ ] pod formularzem, kiedy treść nie mieści się pionowo, przewijany razem z treścią
  - [ ] 🧐 znak copyright
- [ ] 🧐 treść poprawnego formularza zawarta w zapytaniu do serwera wysłanym po naciśnięciu przycisku 
  
  np. `https://localhost:1234/api/contact?title=Urgent&from=customer@example.com&message=Please%20help!`
- [ ] estetyka 😉
  - [ ] elementy tekstowe powinny używać czcionki bezszeryfowej
