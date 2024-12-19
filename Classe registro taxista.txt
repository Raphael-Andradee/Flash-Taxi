#include "RegistroTaxista.h"
#include <iostream>

using namespace std;

class RegistroTaxista {
private:
	string nombre;
	string email;
	int contraseña;
	int licencia;
	int tel;

public:
	// setter 
	void setnome(string usuario) {
		nombre = usuario;
	}
	void setEmail(string e) {
		email = e;
	
	}
	void setLicencia(int lic) {

		licencia = lic;
	}
	void setcontraseña(int pw) {
		contraseña = pw;
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
	int getContraseña() {
		return contraseña;
	}
	int getLicencia() {
		return licencia;
	}
	int getTel() {
		return tel;
	}
};