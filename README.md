# PrimerExamenII Solución Parte Practica via git bash

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII (main)
$ git checkout Rojas_Angelica
Switched to branch 'Rojas_Angelica'

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII (Rojas_Angelica)
$ mkdir Primer_Examen_Rojas_Angelica

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII (Rojas_Angelica)
$ cd Primer_Examen_Rojas_Angelica

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII/Primer_Examen_Rojas_Angelica (Rojas_Angelica)
$ mkdir "La_terminal" "Git_github" "Estructura_de_las_computadoras" "Contabilidad" "Memorias" "Memorias2" "Sistemas_operativos" "Procesos"

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII/Primer_Examen_Rojas_Angelica (Rojas_Angelica)
$ touch registros.txt

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII/Primer_Examen_Rojas_Angelica (Rojas_Angelica)
$ cd Memorias

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII/Primer_Examen_Rojas_Angelica/Memorias (Rojas_Angelica)
$ mkdir "MemoriaSecundaria" "MemoriaPrincipal"

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII/Primer_Examen_Rojas_Angelica/Memorias (Rojas_Angelica)
$ touch ram.txt rom.txt registros.txt cache.txt ssd.txt dvd.txt disco_extraible.txt

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII/Primer_Examen_Rojas_Angelica/Memorias (Rojas_Angelica)
$ mv ssd.txt dvd.txt disco_extraible.txt "./MemoriaSecundaria"

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII/Primer_Examen_Rojas_Angelica/Memorias (Rojas_Angelica)
$ mv ram.txt rom.txt cache.txt "./MemoriaPrincipal"

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII/Primer_Examen_Rojas_Angelica/Memorias (Rojas_Angelica)
$ ls -R
.:
MemoriaPrincipal/  MemoriaSecundaria/  registros.txt

./MemoriaPrincipal:
cache.txt  ram.txt  rom.txt

./MemoriaSecundaria:
disco_extraible.txt  dvd.txt  ssd.txt

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII/Primer_Examen_Rojas_Angelica/Memorias (Rojas_Angelica)
$ cd ..

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII/Primer_Examen_Rojas_Angelica (Rojas_Angelica)
$ rmdir Contabilidad

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII/Primer_Examen_Rojas_Angelica (Rojas_Angelica)
$ mv registros.txt "./Memorias"

USER@DESKTOP-TTGDH4R MINGW64 ~/DH/Practica Examen Intro/PrimerExamenII/Primer_Examen_Rojas_Angelica (Rojas_Angelica)
$ cp -r  Memorias Memorias2