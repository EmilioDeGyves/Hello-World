# Hello-World
# Emilio De Gyves / Damián Martínez
Actividad 02/12/2021

**bold text**
*italicized text*

1. GitHub
2. Metodo de crar frecuencias
3. Descargar los nuevos archivos de Series y episodios

- GitHub
- Metodo de crar frecuencias
- Descargar los nuevos archivos de Series y episodios

````c++
#include <iostream>
#include "Serie.h"
#include "Episodio.h"
#include "Series.h"
using namespace std;
//Emilio De Gyves García
//A01351989
//Avance1
//https://youtu.be/lIl4qrpZCHU <--------- Video de Ejecución


//Método que lee los datos que le asignes a episodio
void leeDatosEpisodio(std::string &_titulo, int &_temporada, double &_calificacion) {
	cout << "Ingresa el titulo del episodio:  ";
	cin >> _titulo;
	cout << "Ingresa el numero de temporada:  ";
	cin >> _temporada;
	cout << "ingresa la calificacion del episodio: ";
	cin >> _calificacion;
}

//Método que lee los datos que le asignes a Serie
void leeDatosSerie(std::string &_id, std::string &_Titulo, int &_duracion, std::string &_genero, double &_calificacionPromedio, int &_cantEpisodios) {
	cout << "Ingresa el id: ";
	cin >> _id;
	cout << "Ingresa el Titulo: ";
	cin >> _Titulo;
	cout << "Ingresa la Duracion: ";
	cin >> _duracion;
	cout << "Ingresa el Genero: ";
	cin >> _genero;
	cout << "Ingresa la Calificacion Promedio: ";
	cin >> _calificacionPromedio;
	cout << "Ingresa la Cantidad de Episodios: ";
	cin >> _cantEpisodios;
````
[markdownguide.org](https://markdownguide.org/cheat-sheet/)
![imagen](paisaje.jpg)
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
  
- [x] Estudiar
- [ ] Proyectos
- [ ] Mas proyectos
