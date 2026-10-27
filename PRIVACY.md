# Polityka prywatności – Inbox

*Obowiązuje od 27 października 2026 r. · [English below](#privacy-policy--inbox)*

Inbox to program pocztowy instalowany na komputerze. Autor: Mike Bronka
([www.mikebronka.com](https://www.mikebronka.com)), kontakt: mbronka@gmail.com.

## W skrócie

Inbox nie zbiera żadnych danych o użytkownikach. Nie ma kont w naszej usłudze, serwerów
pośredniczących, telemetrii, statystyk ani reklam. Twoja poczta przechodzi wyłącznie między
Twoim komputerem a serwerami Twojego dostawcy poczty.

## Co program przechowuje i gdzie

- Pobrane wiadomości, ustawienia kont, hasła i tokeny logowania są zapisane tylko na Twoim
  komputerze, w bazie zaszyfrowanej (AES-256). Klucz do niej trzyma system operacyjny
  (Menedżer poświadczeń Windows, Pęk kluczy macOS, Secret Service w Linuksie).
- Nic z tego nie jest wysyłane autorowi ani nikomu innemu.
- Usunięcie konta w programie usuwa z komputera jego pobraną pocztę i dane logowania.

## Połączenia, które wykonuje program

- **Twoje serwery poczty** (IMAP i SMTP, zawsze szyfrowane) – pobieranie i wysyłanie poczty.
- **Obrazki w wiadomościach** – program sam pobiera obrazki z internetu dla wiadomości HTML,
  bez ciasteczek i bez adresu strony odsyłającej; znane piksele śledzące są blokowane.
- **Sprawdzanie aktualizacji** – program pobiera z GitHuba plik z numerem najnowszej wersji.
  GitHub widzi przy tym adres IP, jak przy każdym pobraniu.

## Konta Google (logowanie przez Google)

Jeśli zalogujesz się przez Google, program prosi o:

| Uprawnienie | Do czego |
|---|---|
| adres e-mail i imię (`openid`, `email`, `profile`) | nazwanie konta w programie |
| `https://mail.google.com/` | pobieranie, porządkowanie i wysyłanie Twojej poczty (IMAP/SMTP) |
| `gmail.settings.basic` | włączanie i wyłączanie odpowiedzi automatycznej (autorespondera) |
| `drive.file` | zapisywanie wybranych przez Ciebie załączników na Twoim Dysku Google; program widzi tylko pliki, które sam zapisał |
| `calendar.events` | dodawanie do Twojego Kalendarza Google wydarzeń z zaproszeń, które dostajesz pocztą – tylko po kliknięciu „Dodaj do Kalendarza Google” |

- Dane z kont Google są używane wyłącznie do tych funkcji, na Twoim komputerze, na Twoje
  polecenie. Nie są przesyłane autorowi ani osobom trzecim, nie są sprzedawane, nie służą do
  reklam ani do trenowania modeli sztucznej inteligencji, i nikt ich nie czyta.
- Hasło do konta Google zostaje u Google – program dostaje od Google token, który trzyma w
  zaszyfrowanej bazie.
- Dostęp możesz odebrać w każdej chwili: usuwając konto w programie (program sam wycofuje
  token u Google) albo na stronie [myaccount.google.com/connections](https://myaccount.google.com/connections).

Korzystanie z danych otrzymanych z interfejsów Google jest zgodne z
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
w tym z wymogami ograniczonego użycia (Limited Use).

## Twoje prawa

Wszystkie dane są tylko u Ciebie – możesz je w każdej chwili usunąć, usuwając konto w
programie albo sam program. Autor nie ma do nich dostępu, więc nie może ich też udostępnić.
Pytania: mbronka@gmail.com.

## Zmiany

Zmiany tej polityki są publikowane w tym miejscu, z nową datą.

---

# Privacy Policy – Inbox

*Effective 27 October 2026*

Inbox is a desktop e-mail program. Author: Mike Bronka
([www.mikebronka.com](https://www.mikebronka.com)), contact: mbronka@gmail.com.

## In short

Inbox collects no data about its users. There are no accounts with us, no relay servers, no
telemetry, no analytics and no ads. Your mail travels only between your computer and your
mail provider's servers.

## What the program stores, and where

- Downloaded messages, account settings, passwords and sign-in tokens are stored only on your
  computer, in an encrypted database (AES-256) whose key is kept by the operating system
  (Windows Credential Manager, macOS Keychain, Secret Service on Linux).
- None of it is sent to the author or anyone else.
- Removing an account in the program removes its downloaded mail and sign-in data from the computer.

## Connections the program makes

- **Your mail servers** (IMAP and SMTP, always encrypted) – receiving and sending mail.
- **Pictures in messages** – the program itself downloads pictures for HTML mail, without
  cookies or referrer; known tracking pixels are blocked.
- **Update check** – the program downloads a file with the latest version number from GitHub,
  which sees the IP address as with any download.

## Google accounts (Sign in with Google)

If you sign in with Google, the program asks for:

| Permission | Used for |
|---|---|
| e-mail address and name (`openid`, `email`, `profile`) | naming the account in the program |
| `https://mail.google.com/` | downloading, organising and sending your mail (IMAP/SMTP) |
| `gmail.settings.basic` | turning the automatic reply (vacation responder) on and off |
| `drive.file` | saving attachments you choose to your Google Drive; the program sees only files it saved itself |
| `calendar.events` | adding events from invitations you receive by mail to your Google Calendar – only when you click “Add to Google Calendar” |

- Data from Google accounts is used only for these features, on your computer, at your
  request. It is not sent to the author or third parties, not sold, not used for advertising
  or to train AI models, and no one reads it.
- Your Google password stays with Google – the program receives a token from Google and keeps
  it in the encrypted database.
- You can withdraw access at any time: by removing the account in the program (which revokes
  the token at Google) or at [myaccount.google.com/connections](https://myaccount.google.com/connections).

Inbox's use and transfer of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Your rights

All data stays with you – delete it at any time by removing the account or the program. The
author has no access to it and therefore cannot share it. Questions: mbronka@gmail.com.

## Changes

Changes to this policy are published here with a new date.
