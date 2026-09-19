[🇵🇱 Powrót do wyboru języka](./README.md)
# Czym jest Utaun?
Utaun to oprogramowanie dla systemu Windows, które generuje banki głosów CV (Spółgłoska-Samogłoska) dla UTAU przy użyciu wyłącznie bezdusznego modelowania sinusoidalnego złożonego (synteza mowy CSM).  
Obsługuje automatyczne generowanie archiwów ZIP z bankiem głosów w folderze Dokumenty, a także bezpośredni eksport do różnych programów kompatybilnych z UTAU.  

# Funkcje  

* Automatycznie generuje plik ZIP z bankiem głosów w folderze Dokumenty lub eksportuje go bezpośrednio do kompatybilnego oprogramowania podczas uruchamiania.  
* Generuje samogłoski (A, I, U, E, O, N) poprzez wyłącznie bezduszne modelowanie sinusoidalne złożone (synteza mowy CSM).  
* Umieść dołączone foldery spółgłosek i dźwięków dźwięcznych w katalogu Dokumenty, aby wygenerować banki głosów CV.  
* Automatycznie generuje wiersze m, n, y i w wewnątrz programu.  
* Obsługuje aliasy w hiraganie + angielskie aliasy romaji (wszystkie wymowy są japońskie).  
* Automatycznie generuje pliki `oto.ini`, `character.txt` i `readme.txt`.  
* Jednocześnie konwertuje obrazy PNG do formatów JPG i BMP (Uwaga: dla `character.txt` używany jest format JPG).  
* Kodowanie plików `readme.txt` i `character.txt` można wybrać pomiędzy **Shift-JIS (ANSI)** a **UTF-8** (Uwaga: UTF-8 zapewnia kompatybilność z OpenUTAU i innymi).  
* Umożliwia zmianę częstotliwości podstawowej (wysokości głosu).  
* Swobodnie konfigurowalna nazwa banku głosów (nazwa postaci).  
* **Obsługuje tryb jasny i ciemny.**  
* **Pozwala wybrać miejsce docelowe eksportu.**  

# Przeznaczenie  

* Kiedy chcesz stworzyć banki głosów UTAU przy użyciu bezdusznych lub sztucznych głosów.  
* Do produkcji banków głosów, jeśli nagrywanie własnym głosem jest dla Ciebie trudne lub niewygodne.  
* Badanie materiałów audio opartych na modelowaniu sinusoidalnym złożonym (synteza mowy CSM).  
* Prototypowanie własnych banków głosów.  
* Rozpakowanie wygenerowanego pliku ZIP w celu użycia go bezpośrednio jako zasobów ludzkiego wokaloidu (symulacja ludzkiego głosu).  
* Użycie jako materiałów audio do remiksów wideo (np. OtoMAD, YTPMV).  

# Jak używać Utaun  

① Pobierz najnowszą wersję Utaun z sekcji **[GitHub Releases](#Releases)**.  
② Jeśli pobierasz wersję w formacie folderu ZIP, **umieść foldery „Consonant/Voiced Sound” oraz plik `oto.ini` bezpośrednio w folderze „Dokumenty” (obsługiwane są również Dokumenty OneDrive).** (Uwaga: są one umieszczane automatycznie w przypadku korzystania z instalatora).  
③ Umieść plik `Utaun.exe` w dowolnym wybranym przez siebie folderze.  
④ Uruchom `Utaun.exe` i postępuj zgodnie z instrukcjami wyświetlanymi na ekranie, aby utworzyć bank głosów.  
⑤ Jako lokalizację zapisu danych możesz wybrać wyjściowy plik ZIP (Dokumenty itp.) lub bezpośredni eksport folderu do UTAU i OpenUTAU.  
*Uwaga: Funkcja automatycznej aktualizacji będzie dostępna w przyszłych wersjach.*  

### Interfejs użytkownika (UI)  
![Test Image 3](IMG_4239.jpeg)  

# Kompatybilność i użycie wygenerowanych banków głosów  

* **UTAU**  
  Eksportuj bezpośredno jako nierozpakowany folder banku głosów do folderu `voice` z poziomu aplikacji i używaj go natychmiast.  
* **OpenUTAU**  
  Eksportuj bezpośrednio jako nierozpakowany folder banku głosów do folderu `Singers` z poziomu aplikacji i używaj go natychmiast.  
* **UtauTTS**  
  Wypakuj wyeksportowany plik ZIP i umieść go w folderze `voice` programu `utauTTS`.  
* **UtauV**  
  Przeciągnij i upuść plik ZIP do okna uruchomionej aplikacji UtaunV.  
* **UTAlet (Wersja internetowa)**  
  Przeciągnij i upuść plik ZIP na ekran oficjalnej strony internetowej.  
*Uwaga: Instrukcje dotyczące konkretnego użytkowania w każdym programie lub środowisku webowym można znaleźć w ich odpowiednich plikach pomocy, podręcznikach lub oficjalnej dokumentacji.*  

# Wymagania systemowe  

* Windows 10 do 11 (obsługa 64-bit / 32-bit)  
**(Uwaga: Wersja 32-bitowa służy jako baza ze względu na rozmiar plików, ale program działa bez problemów również w systemie Windows 64-bit.)**  

# Nieobsługiwane funkcje  

* Samogłoski dźwięczne (あ゙, い゙, ゔ, え゙, お゙)  
* Wariacje ekspresyjne, takie jak szepty, oddechy lub składowe tchnienia  
* Dźwięki spalatyzowane (np. kya, kyu, kyo / sha, shu, sho)  
* VCV (Samogłoski ciągłe)  
* CVVC  
* Inne specjalne wymowy  

# Warunki korzystania  

Następujące działania są surowo zabronione w odniesieniu do samej aplikacji Utaun (`Utaun.exe`):  
* Modyfikacja  
* Edycja  
* Przeróbka  
* Komercyjne wykorzystanie  
* Ponowna dystrybucja  
* Dekompilacja (rozmontowywanie)  

# Treści wygenerowane  

(Banki głosów, pliki `.wav`, `icon.jpg` / `icon.bmp`, `oto.ini` itp.)  
Ty (dystrybutor) możesz swobodnie ustalać własne warunki korzystania dla wygenerowanych treści.  
Prosimy o wpisanie preferowanych warunków licencji w pliku `readme.txt`.  

Informacje o aktualizacjach i szczegóły można znaleźć na stronie **Releases** w serwisie GitHub.  

# Releases  
[Download Polish Version of Utaun →](https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇵🇱)
