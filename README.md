# modulo-2


ejercicio uno:
crear un programa en java que, dado un numero entero de horas, muestre el equivalente en semana ,dias y horas

package educacionit.com;
import java.util.Scanner;
public class dias{
public static void main (String[] args) {
	Scanner pronostico = new Scanner (System.in);
	int horas;
	int dias;
	int semanas;
	int calculo; 
	System.out.println("calcular tiempo: ");
	calculo = pronostico.nextInt();
	semanas = calculo /168; 
	dias = calculo % 168 / 24;
	horas = calculo % 24;
	System.out.println("EL total es: "+ calculo);
	System.out.println("semanas : "+ semanas);
	System.out.println("dias :" + dias);
	System.out.println("horas : "+ horas);




EJERCICIO DOS:
resolver los enunciados desarrollando el codigo.
Dados n1=5, n2=10, n3=20, infomar



Resolver los enunciados desarrollando el codigo.
Dados n1=10, n2=20 y n3=30, informar:
a) el total.
b) el promedio.
c) el resto entre n2 y n1.

package com.educacionit;

import java.util.Scanner;

public class sumarestamultidivision {

	public static void main(String[] args) {
	

int n1 = 5;
int n2 = 10;
int n3 = 20;
int resultado= n1 + n2 + n3;
double promedio = (n1+n2+n3)/3;
double resto = (n1+n2+n3)%3;
System.out.println("resultado total es :"+ resultado);
System.out.println("el promedio es : "+ promedio);
System.out.println("El resto es: " + resto);


