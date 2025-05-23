# OpenCL + OpenMP Adder in C++


Dieses Projekt demonstriert die Verwendung von OpenCL für parallele Verarbeitung auf der
GPU und OpenMP für die Parallelisierung auf der CPU, um zwei Arrays von Ganzzahlen zu addieren.

 Funktionen:
Verwendet OpenCL, um große Arrays parallel auf der GPU zu addieren

Verwendet OpenMP, um dieselbe Addition auf der CPU durchzuführen

Vergleicht die Leistung zwischen GPU- und CPU-Ausführung

Überprüft die Konsistenz der Ergebnisse

Kompilierung und Ausführung:-

Voraussetzungen:

-GCC oder Clang mit OpenMP-Unterstützung
-OpenCL SDK (z. B. von Intel, NVIDIA oder AMD)
-C++17-kompatibler Compiler

Kompilieren:
g++ -std=c++17 -fopenmp opencl_openmp_adder.cpp -lOpenCL -o adder

Ausführen:
./adder

Hinweise:
-Eine funktionierende OpenCL-Installation (Treiber und Header-Dateien) ist erforderlich.
-Ausführungszeit und Ergebnisvalidierung werden auf die Konsole ausgegeben (stdout).
