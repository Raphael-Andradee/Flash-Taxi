

#include "RegistroUsuario.h"
#include <iostream>

using namespace std;

class RegistroUsuario {
private:
	string nombre;
	string email;
	string direccion;
	int contrasena;
	int tel;

public:
	// setter 
	void setnombre(string usuario) {
		nombre = usuario;
	}
	void setEmail(string e) {
		email = e;
	}
	void setDireccion(string localidad) {
		direccion = localidad;
	}
	void setContrasena(int pw) {
		contrasena = pw;
	}
	void setTel(int cel) {
		tel = cel;
	}

	//getter

	string getNombre() {
		return nombre;
	}
	string getEmail() {
		return email;
	}
	string getDireccion() {
		return direccion;
	}
	int getContrasena() {
		return contrasena;
	}
	int getTel() {
		return tel;
	}
};
