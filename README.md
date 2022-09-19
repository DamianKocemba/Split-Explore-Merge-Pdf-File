## ENG: Split-Explore-Merge-Pdf-File
The script combines two pdf files - Official notice about changes into Land and Mortgage Register and Certified copy of the entry in Land and Mortgage Register. These files are generated automaticlly by other programs and are related to one place (town/village). Firstly, the files are splited up into separate documents by "jednostka rejestrowa" and are saved in temporary directory with the file names based on number of "jednostka rejestrwa". Next, Certified copys and Official notice are joined (based on file name) into one file ( in order to print easily).
(Not all Official notices have Certified copy but every Certified copy should have Official noticed enclosed).
Finally, temporary files and directories are deleted.

Additional informations:
- the script is written by Google Colabortory (Colab)
- because of the privacy law (numbers of Land and Mortgage Registers, names, surnames, addresses) the originall files are not enclosed


## PL: Rozdzielenie-Przeszukiwanie-Łączenie-Plików-Pdf
Skrypt łączy dwa pliki pdf - Zawiadomienia o zmianie do Ksiąg Wieczystych oraz Wypisy z rejestru gruntów. Pliki te zostały wygenerowane automatycznie przez zewnętrzny program i dotyczą jednego obrębu ewidencyjnego. Najpierw następuje rozdzielenie odpowiednio Zawiadomień i Wypisów, względem jednostek rejestrowych, na osobne dokumenty do folderów tymczasowych i nadanie im nazwy z numerem tej jednostki. Następnie, do każdego Wypisu następuje dopasowanie (po nazwie pliku) odpowiedniego Zawiadomienia i połączenie wszystkich dopasowanych dokumentów w jeden plik (w celu łatwego drukowania).
(Nie każde Zawiadomienie będzie miało Wypis, ale każdy Wypis powinien mieć Zawiadomienie).
Na koniec, pliki oraz foldery tymczasowe zostają usunięte.

Dodatkowe informacje:
- skrypt napisano z wyorzystaniem Google Colabortory (Colab)
- ze względu na ochronę danych osobowych (numery KW, imiona, nazwiska, adresy) nie załączono oryginalnych plików pdf
