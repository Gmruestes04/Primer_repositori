# Fitxa tècnica: Configuració de l'entorn de desenvolupament en Python

## Objectiu

Configurar un entorn de treball bàsic per començar a programar en Python, creant un entorn virtual personalitzat i executant un primer script de prova des del terminal i l'IDE.

## Materials i requisits

- Sistema operatiu (Linux, macOS o Windows)
- Python 3.x instal·lat a la màquina
- Visual Studio Code o PyCharm
- Terminal / Linia de comandes

## Procediment

1. **Verificar la instal·lació de Python:** Comprovar des del terminal quina versió de Python hi ha instal·lada al sistema.
2. **Crear la carpeta del projecte:** Generar un directori de treball dedicat al projecte de Python.
3. **Crear i activar un entorn virtual (`venv`):** Isolar les dependències del projecte per evitar conflictes amb altres llibreries del sistema.
4. **Escriure l'script inicial:** Crear un fitxer `main.py` amb un codi d'exemple.

Per configurar l'entorn virtual i executar el primer script, s'utilitzen les comandes següents al terminal:

```bash
# Crear la carpeta del projecte i accedir-hi
mkdir projecte-python && cd projecte-python

# Crear l'entorn virtual
python3 -m venv venv

# Activar l'entorn virtual (en Linux/macOS)
source venv/bin/activate

# Executar l'script de prova
python3 main.py
![Entorn de desenvolupament Python](https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png)

## Comprovacions

- [ ] Comprovar que la comanda `python3 --version` retorna la versió correctament.
- [ ] Verificar que l'entorn virtual s'activa (apareix `(venv)` a l'inici de la línia del terminal).
- [ ] Executar el fitxer `main.py` i comprovar que la sortida per pantalla és l'esperada.

## Incidències i solucions

| Incidència / Error | Solució aplicada |
| :--- | :--- |
| `python3: command not found` | Instal·lar el paquet de Python 3 mitjançant el gestor de paquets (`sudo apt install python3`). |
| Error de permisos en activar `venv` | Donar permisos d'execució al script d'activació o utilitzar `bash` explícitament. |

## Recursos

- [Documentació oficial de Python](https://docs.python.org/3/)
- [Guia d'entorns virtuals en Python](https://docs.python.org/3/tutorial/venv.html)