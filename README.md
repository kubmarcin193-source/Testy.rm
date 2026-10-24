# RatMed TRIAGE PRO — testy 3.0.4

Gotowa aplikacja: **index.html**. Działa lokalnie lub na GitHub Pages, bez procesu budowania. Kod, style, biblioteki i przykładowe wywiady są wbudowane w HTML. Folder `materialy-erc-2025` zawiera 66 oryginalnych dokumentów PDF. Zachowano też poprzednią wersję aplikacji.

## Wgranie na GitHub

1. Rozpakuj ZIP na komputerze. **Nie wrzucaj samego ZIP-a do repozytorium** — GitHub nie rozpakowuje go i nie uruchomi z niego strony.
2. Wybierz Add file → Upload files. Przeciągnij zawartość folderu `github`, zachowując folder `materialy-erc-2025`.
3. Zatwierdź pliki. Paczka zawiera 71 plików; każdy ma mniej niż 25 MiB. Duża część rozmiaru to oryginalne PDF-y.
4. Aby uruchomić stronę, w Settings → Pages wybierz Deploy from a branch, gałąź z plikami oraz katalog /(root). Dostępność Pages zależy od typu konta i widoczności repozytorium.

## Co testować

Zapis po „Dalej”, scalanie całej karty i ochrona ręcznych poprawek; parametry przy przyjęciu oraz osobne pomiary kontrolne; dwuczęściowy wydruk A4; uporządkowany opis EKG; panel możliwych rozpoznań EKG z uzasadnieniem i dodatkowymi odprowadzeniami, widoczny wyłącznie dla opisującego (bez drukowania hipotez); 23 zagadnienia o blokach i sześć rzeczywistych zdjęć EKG offline z podpisami, źródłami i licencjami; kolejne leki i działania, historia, kalkulatory, test wiedzy i telefon. SBAR usunięto. Wersja aplikacji: 3.0.4.

Dane wpisywane podczas pracy są w pamięci przeglądarki; ta paczka nie zawiera jej eksportów ani zapisów pacjentów. Lokalny plik i adres GitHub Pages mają osobne magazyny — dane przenosi się eksportem/importem. Do testów używaj danych fikcyjnych.

## Źródła medyczne

Treści ERC zachowują odnośniki i rejestr errat. Trzy erraty z 2026 mają znane metadane bez odczytanej pełnej treści korekt; stan jest widoczny w aplikacji. Materiały RatMed i dodatkowe 422 przypadki testowe są przeniesione z archiwum bez ponownego audytu klinicznego. Paczka do testowania programu nie potwierdza walidacji klinicznej.

Oficjalne PDF-y pozostają materiałami ich wydawców. Oryginalne źródła i informacje znajdują się wewnątrz dokumentów oraz w Nauka → Źródła i erraty. Nie dołączono nowej licencji do cudzych publikacji.

SHA-256 plików i lista zawartości są w `manifest.json`.
