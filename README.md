# Cześć, jestem Kamil! 👋

### 🚀 Full-Stack, Data Science & Embedded Systems Engineer

Jestem inżynierem o wszechstronnych kompetencjach, łączącym świat zaawansowanej analizy danych, systemów mobilnych, nowoczesnego web-devu oraz niskopoziomowego oprogramowania sprzętowego (Bare-Metal). Projektuję systemy zorientowane na wysoką wydajność, bezpieczeństwo danych i automatyzację.

> ⏱️ *Uwaga: Niektóre z poniższych aplikacji webowych są hostowane na darmowych instancjach Render – ich pierwsze uruchomienie po dłuższej nieaktywności może zająć kilkanaście sekund (wybudzanie serwera).*

---

## 🛠️ Moja Skrzynka z Narzędziami (Tech Stack)

| Obszar | Technologie i Narzędzia |
| :--- | :--- |
| **Języki Programowania** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) |
| **Data Science & Computer Vision** | ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) |
| **Backend & WebSockets** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black) WebRTC |
| **Mobile & Cybersec** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) Szyfrowanie Android Keystore & Biometria |
| **Cloud & DevOps** | ![Azure](https://img.shields.io/badge/Azure-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) |
| **Hardware & Embedded** | ARM Cortex-M (Kinetis/STM32) • Keil uVision • CMSIS • Bare-Metal (Rejestry) • I2C • ADC • SPI |

---

## 🌟 Wyróżnione Projekty (Top Projects)

### 🔗 Skylink P2P
**Aplikacja webowa do błyskawicznego, bezpośredniego przesyłania plików między przeglądarkami w architekturze peer-to-peer.**
* **Technologie:** Node.js, Express, Socket.io, WebRTC, Hosting Render.
* **Kluczowe funkcje:** Przesyłanie danych bez udziału centralnego serwera przechowującego pliki. Obsługuje nie tylko bezpośrednie transfery 1-do-1, ale również bezpieczną architekturę multi-cast umożliwiającą jednoczesne rozsyłanie pakietów danych w sieciach lokalnych skupiających do 3-4 użytkowników jednocześnie.
* 🚀 **Przetestuj wersję Live:** [skylinkk-p2p.onrender.com](https://skylinkk-p2p.onrender.com/)

### 🔐 Secret Manager
**Innowacyjna aplikacja bezpieczeństwa na Androida, pełniąca rolę generatora haseł i "Cyfrowego Testamentu", zakamuflowana jako w pełni funkcjonalny kalkulator.**
* **Technologie:** Flutter, Dart, Android Keystore (`FlutterSecureStorage`), lokalna autoryzacja biometryczna.
* **Kluczowe funkcje:** Bezszyfrowy portfel haseł generujący unikalne klucze w locie za pomocą **HMAC-SHA256** (brak przechowywania haseł w bazie), mechanizm *Dead Man's Switch* (ujawnianie sekretu zaufanym osobom po braku aktywności przez X dni), synchronizacja czasu NTP (odporność na zmianę zegara systemowego) oraz asynchroniczne procesy powiadomień w tle.
* 🔗 [Przejdź do wersji Release](https://github.com/KrasKamil/SecretManager-Release)

### 🅿️ Parking Spot AI
**System wizji komputerowej do monitorowania zajętości miejsc parkingowych w czasie rzeczywistym z wbudowanym asystentem nawigacji.**
* **Technologie:** Python, OpenCV, NumPy, algorytm przeszukiwania grafów A*.
* **Kluczowe funkcje:** Autorski, sterowany kreator (wizard) konfiguracji nowego parkingu, wizualna kalibracja wymiarów miejsc za pomocą interfejsu OpenCV GUI, obsługa strumieni wideo, kamer IP i transmisji YouTube (`yt-dlp`), a także wyznaczanie najkrótszej i bezpiecznej ścieżki algorytmem **A\*** do najbliższego wolnego miejsca parkingowego.
* 🔗 [Przejdź do repozytorium](https://github.com/KrasKamil/Parking_spots_detection)

### 🎨 Advanced ASCII Art Generator (ASCII_gen)
**Zaawansowane narzędzie CLI do transformacji obrazów cyfrowych w unikalną sztukę ASCII Art.**
* **Technologie:** Python, Pillow, Requests, PyAutoGUI, tqdm, Unsplash API.
* **Kluczowe funkcje:** Konwersja obrazów z plików lokalnych, zewnętrznych adresów URL oraz dynamiczne pobieranie losowych fotografii wysokiej jakości poprzez API Unsplash. Oferuje precyzyjne mapowanie jasności pikseli na znaki (Character Mapping), generowanie wielokolorowego ASCII Art, automatyczny podgląd w przeglądarce oraz eksport wyników do plików tekstowych lub grafik PNG.
* 🔗 [Przejdź do repozytorium](https://github.com/KrasKamil/PythonProjects)

<details>
<summary>📸 <b>Otwórz porównanie efektu (Przed / Po)</b></summary>
<br />

> ⚙️ *Notatka: Wygenerowana grafika wyjściowa (`mount.png`) została celowo przeskalowana w aplikacji przy użyciu parametru **Scale Factor**, aby zoptymalizować rozmiar pliku i zapewnić płynne ładowanie w przeglądarce.*

| 🖼️ Oryginalne zdjęcie | 👾 Wynik ASCII Art |
| :---: | :---: |
| <img src="https://images.unsplash.com/photo-1774910429313-98034531b71c?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0OTc4MDZ8MHwxfHJhbmRvbXx8fHx8fHx8fDE3NzkxMzAyMTV8&ixlib=rb-4.1.0&q=80&w=1080" width="100%" alt="Oryginalne zdjęcie z Unsplash" /> | <img src="mount.png" width="100%" alt="Wygenerowane ASCII Art - mount.png" /> |

</details>

### 🌡️ Smart Thermo Assistant
**Zaawansowany system domowego asystenta i dashboardu multimedialnego zoptymalizowany pod kątem systemów Windows oraz Raspberry Pi.**
* **Technologie:** TypeScript (Backend Core), Node.js, Express, Python (WinSDK), HTML5/CSS3 (Glassmorphism UI), Chart.js.
* **Kluczowe funkcje:** Integracja z OAuth Spotify (pobieranie metadanych i sterowanie), systemowy skaner urządzeń Bluetooth do wykrywania obecności domowników, moduł monitorowania pogoda (OpenWeatherMap) oraz wbudowane REST API do integracji z powiadomieniami bota Telegram.
* 🔗 [Przejdź do repozytorium](https://github.com/KrasKamil/SmartThermo)

### 📊 Market Brain Station
**Profesjonalny bot do tradingu algorytmicznego z silnikiem wielostrategicznego backtestingu.**
* **Technologie:** Python 3.9+, DuckDB, yfinance, Pandas, NumPy, Telegram API.
* **Architektura:** Event-Driven, wzorce Repository Pattern i Unit of Work.
* **Kluczowe funkcje:** Monitorowanie ponad 176 aktywów finansowych, odporny silnik informacyjny z mechanizmem retry (Tenacity), filtr korelacji ryzyka sektorowego, automatyczne generowanie raportów HTML oraz interaktywny panel sterowania za pomocą bota Telegram z wykresami linii kapitału (Equity Curve).
* 🔗 [Przejdź do repozytorium](https://github.com/KrasKamil/market-brain-station)
---

## 🛠️ Pozostałe Projekty i Doświadczenie Techniczne

<details>
<summary>🌐 <b>Web Development & Systemy Czasu Rzeczywistego</b></summary>

* **Party Game PoC (Fibbage Clone):** Wieloosobowa gra towarzyska czasu rzeczywistego inspirowana "Fibbage". Smartfony graczy służą jako interaktywne kontrolery do wprowadzania kreatywnych odpowiedzi i głosowania, zsynchronizowane za pomocą WebSockets z centralnym ekranem rozgrywki.
  * 🖥️ **Ekran główny (Host):** [fibbage-pl.onrender.com/host](https://fibbage-pl.onrender.com/host)
  * 📱 **Dołączenie gracza (Player):** [fibbage-pl.onrender.com](https://fibbage-pl.onrender.com/)
* **AKRA-animacje:** Wdrożona, w pełni produkcyjna strona internetowa stworzona dla mojej siostry, prezentująca autorską ofertę animacji. Projekt skupia się na estetycznym interfejsie użytkownika, wysokiej wydajności oraz pełnej responsywności (RWD).
  * 🌐 **Zobacz na żywo:** [akraanimacje.com](https://akraanimacje.com)
* **Oravski Hrad - Panel Zarządzania:** Pełnoekranowa aplikacja Full-Stack (Node.js, Express, Socket.IO) realizująca dwustronną komunikację WebSocket w czasie rzeczywistym. Obsługuje globalne ogłoszenia (broadcast) i wiadomości prywatne ("szepty") pomiędzy użytkownikami oraz interaktywną mapę SVG zamku.
* **Custom HLS Player:** Odtwarzacz wideo HTTP Live Streaming (.m3u8) zbudowany na bazie `hls.js`, wspierający adaptację bitrate, dynamiczne logowanie żądań manifestu oraz autorski moduł restrykcji geograficznych na bazie geolokalizacji IP.
</details>

<details>
<summary>☁️ <b>DevOps, Logistyka & Architektura Systemowa</b></summary>

* **CourierSimulator:** Aplikacja symulacyjna dedykowana logistyce i wyznaczaniu tras kurierskich. Skupia się na implementacji struktur obiektowych oraz algorytmów optymalizacyjnych wspomagających efektywne zarządzanie dostawami i operacjami flotowymi.
* **Azure Global 2026 Kraków Workshop:** Kompletne wdrożenia bezpiecznych potoków CI/CD przy użyciu **GitHub Actions** oraz **Terraform**. Architektura oparta na bezhasłowej autoryzacji federacyjnej (OIDC/Federated Identity) pomiędzy GitHubem a platformą Azure, konteneryzacja aplikacji w Azure Container Registry (ACR) i zarządzanie infrastrukturą (IaC).
* **Railway Reservation System:** Kompaktowy system zarządzania rezerwacjami kolejowymi napisany w obiektowym C++, wykorzystujący pliki strukturyzowane JSON do zapisu danych, wzbogacony o pełną walidację wejścia i poprawne wsparcie dla kodowania polskich znaków.
</details>

<details>
<summary>🔌 <b>Embedded Systems (Systemy Wbudowane)</b></summary>

* **Snake Game Bare-Metal (Cortex-M0+):** Klasyczna gra w węża napisana w języku C (standard C99) na mikrokontroler **FRDM-KL05Z (NXP Kinetis)**. Projekt zrealizowany bez bibliotek wysokopoziomowych (bare-metal) bezpośrednio na rejestrach CMSIS. Wykorzystuje I2C zrealizowane programowo (bit-banging) do komunikacji z wyświetlaczem LCD 16x2, przetwornik ADC do obsługi dwuosiowego joysticka analogowego oraz systemowy zegar przerwaniowy `SysTick`.
</details>

<details>
<summary>🧮 <b>Algorytmy, Narzędzia CLI & Automatyzacja</b></summary>

* **Mean Shift Implementation from Scratch:** Implementacja nienadzorowanego algorytmu klasteryzacji Mean Shift napisana od zera w czystym **NumPy**. Wykorzystuje logikę płaskiego jądra jednostajnego (Flat Kernel), moduł automatycznego scalania zbiegających się środków skupień (Centroid Pruning) i pełną zgodność z interfejsem API `scikit-learn` (`fit`/`predict`), zweryfikowaną testami w `pytest`.
* **cv-gen (CLI CV Builder):** Narzędzie wiersza poleceń Node.js wykorzystujące bezgłową przeglądarkę **Puppeteer (Chromium)** do automatycznego generowania nowoczesnych i czytelnych dla systemów rekrutacyjnych (ATS-friendly) dokumentów CV w formacie PDF z plików strukturyzowanych JSON.

</details>

---

---
📫 **Jak się ze mną skontaktować?** [Mój Profil na GitHubie](https://github.com/KrasKamil)
