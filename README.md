float promedio(Lista *lista){
	int i, Largo_De_Lista;
	int sumar=0;
  Largo_De_Lista=Fin(lista);
	for(i=0;i<Fin(lista);i++){
		sumar=sumar+Recuperar(i,lista);
	}
	return sumar/(Largo_De_Lista);
}
