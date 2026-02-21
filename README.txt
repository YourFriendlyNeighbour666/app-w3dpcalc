## INSTRUKCJA OBSŁUGI SKRYPTU RUSTY3DPRINT.PY
---------------------------------------------

### WPROWADZENIE
`Rusty3DPrint.py` to skrypt Pythona służący do zarządzania profilami drukarek 3D, materiałów i części, obliczania kosztów druku 3D i zapisywania tych danych w bazie danych. Ten przewodnik pomoże Ci w procesie od konfiguracji środowiska po uruchomienie skryptu.

### WYMAGANIA
- Python zainstalowany na systemie (zalecany Python 3.x).
- Opcjonalnie dostęp do internetu, jeśli wymagane jest pobieranie dodatkowych bibliotek.

### KONFIGURACJA
1. **INSTALACJA PYTHONA**:  
   - Windows: Pobierz z python.org i postępuj zgodnie z instrukcjami instalatora.
   - Linux: Python jest zwykle wstępnie zainstalowany. Jeśli nie, użyj menedżera pakietów (np. `sudo apt-get install python3`).
   - macOS: Pobierz z python.org lub użyj polecenia `python3` w Terminalu.

2. **PRZYGOTOWANIE ŚRODOWISKA**:  
   - Upewnij się, że wszystkie wymagane pliki są w tym samym katalogu co skrypt.

### UŻYWANIE SKRYPTU
1. **URUCHOM TERMINAL**:  
   - Windows: Naciśnij Win + R, wpisz cmd i naciśnij Enter.
   - Linux/macOS: Otwórz aplikację Terminal.

2. **PRZEJDŹ DO LOKALIZACJI SKRYPTU**:  
   - Użyj polecenia `cd`, aby przejść do folderu zawierającego `Rusty3DPrint.py`.

3. **TWORZENIE PROFILI**:  
   - Uruchom skrypt poleceniem `python Rusty3DPrint.py` i postępuj zgodnie z instrukcjami na ekranie, aby utworzyć profile drukarek, materiałów i części.

4. **OBLCIZANIE KOSZTÓW**:  
   - Skrypt automatycznie obliczy koszty na podstawie wprowadzonych danych i wyświetli szczegółowe informacje o kosztach.

5. **ZAPIS DO BAZY DANYCH**:  
   - Możesz wybrać, czy zapisać obliczone dane do pliku JSON, który służy jako baza danych.

### ROZWIĄZYWANIE PROBLEMÓW
- W przypadku błędów związanych z Pythonem, upewnij się, że Python jest poprawnie zainstalowany i skonfigurowany.
- W razie problemów z plikami JSON, sprawdź ich format i upewnij się, że są one poprawnie zapisane.

Credits: Coop Rusty&Bomber

---

## README FOR USING RUSTY3DPRINT.PY
-------------------------------------

### INTRODUCTION
`Rusty3DPrint.py` is a Python script for managing 3D printer, material, and part profiles, calculating 3D printing costs, and storing this data in a database. This guide will assist you from setting up your environment to running the script.

### PREREQUISITES
- Python installed on your system (Python 3.x recommended).
- Optionally, internet access if additional libraries need to be downloaded.

### SETUP
1. **INSTALL PYTHON**:  
   - Windows: Download from python.org and follow the installer instructions.
   - Linux: Python is usually pre-installed. If not, use your package manager (e.g., `sudo apt-get install python3`).
   - macOS: Download from python.org or use the `python3` command in the Terminal.

2. **PREPARE ENVIRONMENT**:  
   - Ensure that all necessary files are in the same directory as the script.

### USING THE SCRIPT
1. **LAUNCH THE TERMINAL**:  
   - Windows: Press Win + R, type cmd, and press Enter.
   - Linux/macOS: Open the Terminal app.

2. **NAVIGATE TO SCRIPT LOCATION**:  
   - Use the `cd` command to navigate to

 the folder containing `Rusty3DPrint.py`.

3. **CREATING PROFILES**:  
   - Run the script with `python Rusty3DPrint.py` and follow the on-screen instructions to create printer, material, and part profiles.

4. **CALCULATING COSTS**:  
   - The script automatically calculates costs based on the entered data and displays detailed cost information.

5. **SAVING TO DATABASE**:  
   - You can choose to save the calculated data to a JSON file which acts as a database.

### TROUBLESHOOTING
- If you encounter Python-related errors, ensure Python is correctly installed and configured.
- For issues with JSON files, check their format and ensure they are correctly written.

Credits: Coop Rusty&Bomber

---

This README covers the essential aspects of using the `Rusty3DPrint.py` script, including setup, usage, and troubleshooting.