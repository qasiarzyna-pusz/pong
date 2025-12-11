# Pong

Klasyczna gra Pong z wieloma piłkami. Gra została stworzona w czystym JavaScript z wykorzystaniem Canvas API.

## 🎨 Design

Gra wykorzystuje **Cyberpunk Dreams Color Palette** - futurystyczną paletę kolorów inspirowaną estetyką cyberpunk:
- **Wild Strawberry** (#ff3d94) - akcenty i elementy interaktywne
- **Medium Red Violet** (#b5307e) - elementy UI
- **Daisy Bush** (#6a2a98) - tło gradientowe
- **Meteorite** (#3f1c6d) - głębsze odcienie tła
- **Violet** (#200b4b) - najciemniejsze elementy

## ✨ Funkcjonalności

### Podstawowe mechaniki
- ✅ Canvas 400x600 pikseli z animowanymi piłkami
- ✅ Fizyka odbić od krawędzi i paletki
- ✅ System 3 żyć
- ✅ Licznik punktów
- ✅ Mechanizm końca gry z możliwością restartu

### Zaawansowane funkcje
- 🎯 **Wiele piłek** - nowa piłka pojawia się co 5 punktów
- 🎨 **Losowe kolory piłek** - każda piłka ma unikalny kolor
- 🎮 **Wieloplatformowe sterowanie**:
  - Mysz - ruch za kursorem
  - Klawiatura - strzałki ← →
  - Dotyk - obsługa urządzeń mobilnych
- 🎪 **Klasa Ball** - obiektowe podejście do tworzenia piłek
- 💫 **Dynamiczne odbicia** - kąt odbicia zależy od miejsca trafienia w paletkę
- 📊 **Live stats** - na żywo wyświetlane punkty, życia i liczba aktywnych piłek

## 🎯 Zasady gry

1. **Cel**: Odbijaj piłki paletką i zdobywaj jak najwięcej punktów
2. **Punkty**: +1 punkt za każde odbicie piłki od paletki
3. **Życia**: Tracisz życie gdy wszystkie piłki spadną na dół
4. **Progresja**: Co 5 punktów pojawia się nowa piłka, zwiększając trudność
5. **Koniec gry**: Gra kończy się po utracie wszystkich 3 żyć

## 🎮 Sterowanie

| Urządzenie | Kontrola |
|------------|----------|
| **Komputer** | Strzałki ← → lub mysz |
| **Tablet/Telefon** | Dotyk ekranu |

## 🚀 Jak uruchomić

1. Otwórz plik HTML w przeglądarce
2. Gra uruchamia się automatycznie
3. Steruj paletką i odbijaj piłki!
4. Po przegranej kliknij "ZAGRAJ PONOWNIE"

## 📋 Wymagania techniczne

- Nowoczesna przeglądarka z obsługą:
  - Canvas API
  - ES6 (klasy, arrow functions)
  - Touch events
  - Keyboard events

## 🔮 Plany rozszerzenia aplikacji

### Faza 1: System graczy i rankingów 🏆
- [ ] Formularz logowania z imieniem gracza
- [ ] Timer mierzący czas gry
- [ ] Tablica wyników (localStorage)
- [ ] Ranking TOP 10 graczy sortowany po punktach i czasie
- [ ] Wyświetlanie rekordu osobistego

### Faza 2: Zaawansowane mechaniki 🎯
- [ ] Poziomy trudności (łatwy/średni/trudny)
- [ ] Power-upy spadające z góry:
  - Większa paletka
  - Wolniejsze piłki
  - +1 życie
  - Bonus punktów (x2, x3)
  - Przyciąganie piłek
- [ ] Combo system - mnożnik za serie odbić
- [ ] Przeszkody/cegły do zbijania (tryb Arkanoid)

### Faza 3: Efekty audio-wizualne 🎵
- [ ] Efekty dźwiękowe (odbicie, punkt, utrata życia)
- [ ] Muzyka w tle
- [ ] Particle effects przy odbiciu
- [ ] Animacje power-upów
- [ ] Screen shake przy utracie życia

### Faza 4: Tryby gry 🎮
- [ ] Tryb czasowy - zdobądź jak najwięcej punktów w 60s
- [ ] Tryb survival - tylko jedno życie

### Faza 5: Optymalizacja i UX 📱
- [ ] Responsywny design dla różnych rozdzielczości
- [ ] Pauza gry (klawisz ESC lub przycisk)
- [ ] Ustawienia gry (dźwięk on/off, trudność)
- [ ] Animacje przejść między ekranami

## 🛠️ Technologie

- **HTML5 Canvas** - rendering grafiki
- **Vanilla JavaScript** - logika gry
- **CSS3** - stylowanie i animacje
- **OOP** - klasa Ball dla zarządzania piłkami

## 📝 Licencja

Projekt edukacyjny - wolne użytkowanie.

## 👨‍💻 Autor
Katarzyna Puszkarczuk

GitHub: @qasiarzyna-pusz

Projekt stworzony jako demonstracja możliwości Canvas API i programowania gier w JavaScript.

---
**Miłej zabawy! 🎮✨**
