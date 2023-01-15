# py-app-builder
Obfuscate and package python projects/scripts into one single executable file


Table of Contents
* [Prerequists](#Prerequists)
* [Usage](#Usage)
* [Output](#Output)



### Prerequists
  1) Make sure you installed project requirments in venv folder same project directory
  2) copy py_app_builder to same project folder and run
  3) sudo chmod -R 777 <project_dir>
### Usage
```bash
  command:
  py_app_builder.exe <entry_script.py>
```
### Output
```bash
[Windows]
  <project_dir>/dist/<main.exe>
  
 [Linux]
  <project_dir>/dist/<main>
  ```
