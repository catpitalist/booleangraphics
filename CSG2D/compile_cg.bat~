@ECHO OFF
ECHO BUILD OBJECT FILES
IF NOT EXIST ".\obj\" mkdir ".\obj\"
g++ -O0 -g3 -Wall -c -fmessage-length=0 Ponto.cpp Poligono.cpp Temporizador.cpp ExibePoligonosCSG.cpp

move *.o ".\obj"

ECHO LINKING AND COMPILING
IF NOT EXIST ".\bin\" mkdir ".\bin\"
g++ ".\obj\Ponto.o" ".\obj\Poligono.o" ".\obj\Temporizador.o" ".\obj\ExibePoligonosCSG.o" -o ".\bin\boolean.exe" -lglu32 -lopengl32 -lfreeglut


ECHO ON
