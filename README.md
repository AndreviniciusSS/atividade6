- Faça um Programa que peça o raio de um círculo, calcule e mostre sua área.

import java.util.Scanner;

class Main {
  
  public static void main(String[] args) {

Scanner console = new Scanner(System.in);

   
  
  double pi, raio, area;
System.out.println("Digite o raio de um circulo");

raio = 10;
pi = 3.14;
 area = pi * (raio * raio);
 System.out.println("A area do circulo e: " + area);
