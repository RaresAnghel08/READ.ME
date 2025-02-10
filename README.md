# Proiect de Procesare a Formularelor 230

Acest proiect oferă o soluție eficientă pentru ONG-uri care doresc să extragă datele din formularele 230. Folosind tehnologia OCR (Optical Character Recognition), programul procesează imagini ale formularelor, extrage informațiile relevante și le salvează într-un format structurat. De asemenea, fișierele sunt organizate în foldere specifice, pe baza localităților, pentru o gestionare ușoară.

## Scopul Proiectului

Acest proiect ajută ONG-urile să automatizeze procesul de extragere a datelor din formularele 230, economisind timp și resurse. Prin utilizarea unui script Python bazat pe `easyocr`, datele sunt extrase și salvate într-un fișier text pentru fiecare persoană, iar fișierul imagine este mutat într-o structură de foldere organizată pe localități.

## Funcționalități

- **Extracție de text din imagini**: Folosește biblioteca `easyocr` pentru a recunoaște și extrage informațiile din diferite zone ale formularului.
- **Filtrarea datelor**: Se aplică filtre pentru a extrage doar datele relevante (ex. cifre, litere).
- **Organizarea fișierelor**: Imaginile procesate sunt mutate într-un folder specific localității, iar fișierele text sunt salvate în același folder.
- **Redenumirea fișierelor**: Fișierele sunt redenumite în funcție de numele și prenumele persoanei pentru o gestionare mai ușoară.

---

# Form 230 Processing Project

This project provides an efficient solution for NGOs that wish to extract data from Form 230. Using OCR (Optical Character Recognition) technology, the program processes images of the forms, extracts relevant information, and saves it in a structured format. Additionally, the files are organized into specific folders based on localities for easy management.

## Project Purpose

This project helps NGOs automate the process of extracting data from Form 230, saving time and resources. Using a Python script based on `easyocr`, the data is extracted and saved in a text file for each individual, and the image file is moved into a folder structure organized by locality.

## Features

- **Text extraction from images**: Uses the `easyocr` library to recognize and extract information from different areas of the form.
- **Data filtering**: Filters are applied to extract only relevant data (e.g., numbers, letters).
- **File organization**: Processed images are moved to a folder specific to the locality, and text files are saved in the same folder.
- **File renaming**: Files are renamed according to the person's first name and last name for easier management.
