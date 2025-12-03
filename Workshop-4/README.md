**Domotic Circuit Simulator — Workshop 4**

This folder contains the implementation for Workshop #4 of the Object-Oriented Programming course.  
The goal of this workshop is to integrate a layered architecture, a Python GUI, and file-based persistence into the domotic circuit simulator developed in previous workshops.

**Project Structure (Layered Architecture)**
domotic_package/
  presentation/ # GUI layer (PyQt5 windows, dialogs, widgets)
  business/ # Core simulation logic (OOP + SOLID)
  data/ # Persistence layer (save/load)
  main.py # Entry point

**Running the Project**
Requirements
- Python 3.10+
- PyQt5

### Install dependencies
pip install pyqt5
### Run the simulator
python main.py


**Authors:**
- Andres David Hincapié Álvarez
- Samuel Alejandro Bulla Fiquitiva
- Daniel Alejandro Clavijo González
