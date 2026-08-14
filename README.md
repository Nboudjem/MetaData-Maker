# MetaData-Maker
The aim of the program is to provide a standardized way to  easily make and store metadata from experiments.

The program DOES NOT aim to replace logbook, its function is to provide 
a file that gives an overview of the measurement session and 
information on where the data and logbook are stored. 
The files should be considered to be "metadata of metadata

run with: python metamaker_b09.py

The program uses non-standard Python3 packages:

tkinter

reportlab

when running the program from source, it might be required to install them In linux:

sudo apt-get install python-tk

pip install reportlab

It is possible to make stand-alone executable by typing:

pyinstaller metamaker_b09.py -F

the executable can be found from pwd/dist. therefore, it might be necessary to install pyinstaller
Linux:

pip install pyinstaller
