English description available [HERE](README.md) / Angielska wersja dostępna [TUTAJ](README.md)

[Wersja](#-instalacja-i-aktualizacja-github-standard) | [Licencja](#-autorzy-i-współpraca) | [Wsparcie Języków](#-kluczowe-funkcje-programu)


**ES-DE Translator** to niezależne, zaawansowane narzędzie stworzone dla społeczności retro-emulacji. Program pozwala na **automatyczne i masowe tłumaczenie opisów gier (`gamelist.xml`)** oraz **opisów systemów/konsol w motywach** dla popularnego frontendu **ES-DE (EmulationStation Desktop Edition)**.

Narzędzie wykorzystuje silnik tłumaczący Bing, oferując nowoczesny interfejs w stylu Neon GUI oraz pełne wsparcie dla 71 języków (w tym natywne, kompletne tłumaczenie na język polski).

---

## 🔥 Kluczowe Funkcje programu

| Funkcja | Opis |
| :--- | :--- |
| **Tłumaczenie Gier** | Automatyczny przekład tagów `<desc>` w plikach `gamelist.xml` bez naruszania struktury ROM-ów. |
| **Tłumaczenie Motywów** | Automatyczne wyszukiwanie i tłumaczenie wyłącznie pól `<systemDescription>` w plikach motywów ES-DE. |
| **Inteligentny Cache** | Zapisuje postęp po każdym udanym tłumaczeniu. Pozwala na błyskawiczne wznawianie pracy bez utraty limitów. |
| **Podgląd na Żywo** | Okno podglądu pokazujące oryginał i tłumaczenie z możliwością ręcznej korekty (edycji) w trakcie pracy programu. |
| **Neonowe GUI (v33)** | Dwa unikalne układy (Neon A - Biblioteka oraz Neon B - Konsola) z animowanym ekranem powitalnym i efektami poświaty.<img width="1920" height="1008" alt="Zrzut ekranu 11-10-2026 14 09 15" src="https://github.com/user-attachments/assets/11457fb4-d3df-4a43-8959-a4717d7d759d" />

<img width="1920" height="1008" alt="Zrzut ekranu 11-10-2026 14 08 42" src="https://github.com/user-attachments/assets/a09e0034-3464-4d66-8495-dc0ad40ca4b8" />
<img width="1920" height="1008" alt="Zrzut ekranu 11-10-2026 14 08 00" src="https://github.com/user-attachments/assets/658975eb-3e9a-4418-bcb3-a01793578649" />
<img width="1920" height="1008" alt="Zrzut ekranu 11-10-2026 14 06 14" src="https://github.com/user-attachments/assets/86642090-a4c8-423f-ae2b-94fd04f8be16" />

| **System Audio & Retro Klimat** | Wbudowany odtwarzacz muzyki retro (MP3) w tle oraz 10 personalizowanych efektów dźwiękowych (WAV/MP3) dla zdarzeń. |
| **Automatyzacja Językowa** | Interfejs automatycznie tłumaczy się na wybrany język przy pierwszym uruchomieniu i generuje pliki `.ini`. |

---

## 🛠️ Podstawowe Użycie (Krok po Kroku)

1. **Wybierz folder:** Wskaż katalog zawierający pliki `gamelists` lub folder `themes` nakładki ES-DE.
2. **Ustaw język:** Wybierz język docelowy (np. Polski). Język źródłowy pozostaw na pozycji `Auto`.
3. **Skanuj:** Kliknij przycisk skanowania biblioteki, aby program wykrył gry lub motywy.
4. **Rozpocznij:** Kliknij **Rozpocznij**. W razie potrzeby możesz użyć przycisku **Wstrzymaj / Zakończ** – dzięki pamięci cache wrócisz do pracy w dowolnym momencie za pomocą funkcji **Wznów**.

> ⚠️ **WAŻNE:** Program nigdy nie modyfikuje Twoich ROM-ów ani nie pobiera gier. Przed uruchomieniem masowego tłumaczenia na dużych bibliotekach, zaleca się wykonanie własnej kopii zapasowej plików `gamelist.xml`.

---

## 🚀 Bezpieczeństwo i Architektura

* **Czysty folder programu:** Od wersji v33 pliki użytkownika, ustawienia oraz pamięć cache są przechowywane w bezpiecznej lokalizacji `%LOCALAPPDATA%\ES-DE Translator`, dzięki czemu aktualizacja programu nie grozi nadpisaniem Twoich danych.
* **Tryb Przenośny (Portable):** Jeśli wolisz trzymać wszystko w jednym miejscu (np. na pendrive lub dysku zewnętrznym), wystarczy utworzyć pusty plik `portable.txt` obok pliku `.exe`.
* **Kod Źródłowy:** Program powstał we współpracy z AI (ChatGPT oraz Claude). Udostępniony kod pozwala na pełną weryfikację bezpieczeństwa aplikacji przed jej uruchomieniem.

---

## 📦 Instalacja i Aktualizacja (GitHub Standard)

Program dystrybuowany jest w formie wygodnego, automatycznego instalatora `.exe`. Po pobraniu wystarczy kliknąć plik dwukrotnie, aby zainstalować aplikację na komputerze.

### Jak zaktualizować program?
1. Kliknij przycisk **Aktualizuj** bezpośrednio w programie.
2. Aplikacja automatycznie sprawdzi plik `update.json` umieszczony w tym repozytorium na GitHubie.
3. Po wykryciu nowej wersji wybierz opcję **Tak** — program otworzy folder instalacyjny Twojej aplikacji.
4. Przejdź do zakładki **Releases** w tym repozytorium GitHub i pobierz najnowszy instalator `.exe`.
5. Zamknij starą wersję programu, uruchom nowy instalator i przejdź proces instalacji (nowy plik nadpisze stary program).

> 🛡️ **Bezpieczeństwo danych:** Instalator podmienia wyłącznie plik wykonawczy programu. Twoje dane, konfiguracja, tłumaczenia w folderze `language`, spersonalizowane pliki w `user_assets` oraz pamięć cache pozostaną całkowicie bezpieczne i nienaruszone!

---

## 🤝 Autorzy i Współpraca

* **Twórca projektu:** `sony766`
* **Wsparcie AI:** 
  * [ChatGPT (OpenAI)](https://chatgpt.com) — projekt i silnik aplikacji.
  * [Claude (Anthropic)](https://claude.ai) — neonowe GUI v33, ekrany powitalne, ikony oraz system językowy.

---
*Projekt ma charakter społecznościowy i open-source. Nie jest oficjalnie powiązany z twórcami ES-DE ani firmą Microsoft.*
