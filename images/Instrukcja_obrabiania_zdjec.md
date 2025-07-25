# Instrukcja obrabiania zdjęć na bloga

Ta instrukcja jest dla mnie, żebym pamiętał jak przygotować zdjęcia, które wrzucam na bloga.

## Zrobienie zdjęcia

Zdjęcia na blogu są trzy rodzaje:
- TH - thumbnail. Proporcja 3:1. Rozdzielczość 900:300
- (opcjonalne) duże zdjęcie nad wpisem, po otwarciu wpisu (określane w path: w .md od wpisu). Proporcja 3:1. Rozdzielczość taka, żeby proporcja była zachowana, ale szerokość nie większa niż 3840
- (opcjonalne) zdjęcia w tekście. Rozdzielczość nie większa niż 4k (3840x2160).

Podczas robienia zdjęć muszę pamiętać, żeby zdjęcie, albo jego fragment, który zamierzam użyć, było bardzo szerokie (w proporcji 3:1). Może być panoramiczne.

# TH oraz duże tło postu

## 1. Wgranie zdjęcia do Gimp

Zaczynamy w Gimp od dużego zdjęcia w dowolnych proporcjach. Otwieramy zdjęcie oryginalnym rozmiarze. 

## 2. Przycięcie do odpowiedniej proporcji

Dalej używamy **Crop Tool**, żeby zdjęcie miało dowolny rozmiar (największy możliwy), ale miało odpowiednią proporcję (3:1). W narzędziu ustawiamy Fixed aspect ratio, zaznaczamy finalny obszar, a na końcu klikamy Enter.

## 3. Poprawienie kolorów

Wedle uznania. Najczęściej dotykam Brightness&Contrast oraz Levels.

## 4. Przeskalowanie w dół, do odpowiedniego rozmiaru

W zależności czy to jest TH czy głównie zdjęcie posta, (jeśli ma być też główne zdjęcie, lepiej zacząć od większego - głównego) wybieramy opcję Image -> Scale image. Proporcję mamy już zachowaną (z kroku 2). Upewniamy się, że proporcja jest zachowana (spinka pomiędzy rozmiarami) i ustawiamy górny rozmiar.
- Dla głównego zdjęcia, jeśli szerokość jest większa niż 3840, **zmniejszamy do 3840**. Jeśli jest mniejsza, to nie skalujemy w górę.
- Dla TH, ustawiamy szerokość na 900px. **Wszystkie TH mają rozdzielczość 900x300px**.

Quality ustawiamy na **NoHalo**. To jest najlepsza opcja do skalowania w dół (zmniejszania). Jeśli bym powiększał, lepiej wybrać LoHalo.

## 5. Eksport

Eksportuję zdjęcie w formacie **webp**. Ustawiam jakość na **80%**.

- TH nazywam w formacie: <rok>-<miesiąc>-<dzień>-TH.webp
- główne zdjęcie: <rok>-<miesiąc>-<dzień>-<nazwa_posta>.webp

# Inne zdjęcia występujące w poście

Podobnie jak wszystko wyżej. Różnica jest taka, że nie obowiązuje proporcja 3:1. Rozdzielczość maksymalna to 4k (3840x2160), ale jeśli zdjęcie miałoby być jakieś niestandardowo szerokie albo wysokie, można rozważyć zmianę rozmiaru, jak i zwiększenie jakości (więcej niż 80%).