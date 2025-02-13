# TaskManager_B

## 📜 Descriere

**Task_Manager_in_Bash**  is a Bash-based task manager that provides various utilities for file and system management. The project consists of several scripts that automate common operations, file searches, and maintenance activities. It is designed to improve workflow efficiency through automated processes, such as file searching, scheduled deletion, and text manipulation.

---

## 🔹 Funcționalități

### 🗂 File and System Operations

- `afisare_fisiere_user_dimensiune.sh` – Displays files owned by a user along with their sizes.
- `cautare_fisiere.sh` – Searches for files based on user-defined criteria.
- `mutare_fisiere_in_cloud.sh` – Moves files to cloud storage (git)
- `editare_fisiere.sh` – Allows modification of files directly from the terminal.
- `redenumire_fisiere.sh` – Renames a file.
- `stergere fisiere.sh` - Deletes files.

### 🔄 Automation and Maintenance

- `configurare_stergere_periodica.sh` –  Configures scheduled file deletion to free up space.
- `elimin_linii_duplicate_telefon.sh` – Removes duplicate lines from text files and replaces phone numbers with "<PHONE NUMBER>" directly in the file.
- `inlocuire_vechi_nou.sh` – Replaces occurrences of a specific text in files.

### 📊 File Analysis and Management

- `contor_tip_fisier.sh` –  Counts files by type in a directory.
-  `permisiuni_json.sh` – Generates a JSON file with file permissions in a directory.
- `ajutor.sh` – Provides information on how to use the available scripts.

### 📄 Log File
-  `out.log`

---

## 📂 Project Structure

Task_Manager_in_Bash
├── afisare_fisiere_user_dimensiune.sh
├── ajutor.sh
├── cautare_fisiere.sh
├── configurare_stergere_periodica.sh
├── contor_tip_fisier.sh 
├── editare_fisiere.sh 
├── elimin_linii_duplicate_telefon.sh 
├── inlocuire_vechi_nou.sh 
├── main.sh 
├── mutare_fisiere_in_cloud.sh
├──out.log
├──permisiuni_json.sh
├──redenumire_fisiere.sh
├──stergere_fisiere.sh
