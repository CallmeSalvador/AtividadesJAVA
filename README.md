# Atividades de JAVA
 _Resolução de atividades de JAVA da faculdade e cursos por fora_

Exercícios |  Matéria/Curso  |  Professor(a)  | Data
------| -----| ------| -------
BX1 e 2 | estrutura de dados | Renato Carioca | 21/08/2023
AX1 ao 10 | estrutura de dados | Renato Carioca | 14/08/2023
ZX1 ao 30 | linguagem da programação | Jefferson Zannuto | 04 e 05/2023




---

## Exercícios AX1 ao 10 (Revisando o conhecimento em java):
1. Crie um programa que receba dois números inteiros e exiba a soma deles;
2. Faça um programa que leia um número inteiro e exiba se ele é 
positivo, negativo ou igual a zero;
1. Escreva um programa que leia um valor inteiro N e exiba todos 
os números de 1 a N;
1. Crie um programa que receba três números e exiba o maior 
deles;
1. Faça um programa que leia um número e exiba se ele é par ou 
ímpar;
1. Escreva um programa que calcule e exiba a média de três 
notas informadas pelo usuário;
1. Faça um programa que leia um número inteiro N e exiba a 
sequência de Fibonacci até o N-ésimo termo;
1. Crie um programa que leia o nome e a idade de várias pessoas 
e exiba a média das idades; ( não finalizado)
 1. Escreva um programa que exiba os números primos entre 1 e 100;
 1. Faça um programa que leia um número e exiba a tabuada 
desse número até o valor 10;

## Exercícios BX1 E 2 (Revisando o conhecimento em java):
Exercício para contruir classes: 
1. Criar uma classe Java chamada Aluno para modelar estudantes. A classe deve possuir os seguintes 
atributos de dados (propriedades): 
nome – Nome do estudante - (tipo String)
codmat - Código de Matrícula – (tipo int)
cpf – (tipo String)
sexo – (tipo char)
nota_P1 – (double)
nota_P2 – (double)
nota_P3 – (double)
A classe deve conter métodos para construir objetos e um método ImprimeAluno() que irá imprimir os 
dados do estudante. Adicionalmente a classe deve conter um método chamado ImprimeSexo() que irá 
imprimir “Masculino” se o sexo for ‘M’ e “Feminino” se o sexo for ‘F’. 
A função ImprimeSexo() também imprime o nome do estudante. 
Codificar também a função MediaAluno() que retorna a média aritmética das duas maiores notas dentre as 
notas P1, P2 e P3. (Exemplo: notas 2, 6 e 8 => considerar para a média as notas 6 e 8. )
Finalmente, codificar a função Resultado() que retorna “Aprovado” se a média for >= 6.0 ou “Reprovado” 
se a média for inferior a 6.0. 
A classe deve ser criada dentro de um package chamado uscs.
2. Criar uma classe Java TesteAluno que possui um método main() para instanciar estudantes. Criar um 
objeto referenciado pela variável X1 por meio do construtor com os parâmetros: nome = “Paulo”, codmat = 
55123, cpf=”800912345-12” , sexo = ‘M’, nota_P1 = 7.0, nota_P2=6.0 e nota_P3 = 8.0. 
Criar um segundo objeto referenciado pela variável X2 por meio do construtor com os parâmetros: nome = 
“Ana”, codmat = 991239, cpf=”500876123-15” , sexo = ‘F’, nota_P1 = 2.0, nota_P2=6.0 e nota_P3=9.0. 
Para cada objeto chamar a função ImprimeAluno() para imprimir os dados dos dois objetos criados, e as 
funções Media_Aluno() e Resultado() . 
Executar para cada objeto criado a função ImprimeSexo(). 
A classe deve ser criada dentro de um package chamado uscs.

## Exercícios de Recursividade.
1. Fazer uma classe Recursividade com o código abaixo:
public class Recursividade {
 public static void main(String[] args) {
 // aqui vai o código que chama as funções recursivas
 }
 public static int factorial(int n) {
 if (n == 0) {
 return 1;
 } else {
 return n * factorial(n - 1);
 }
 }
 private static int Fibonacci(int num) {
 if (num==0 || num==1)
 return num;
 else
 return (Fibonacci(num-1) + Fibonacci (num-2));
 }
}
2. Escrever dentro de main um programa que mostra o fatorial de 5
3. Escrever dentro de main um programa que mostra o fibonacci de 9
4. Escrever uma função recursiva dentro da classe Recursividade para calcular a potência de um número 
base elevado a um expoente.
5. Escrever dentro de main um programa que mostra a potência de 2 elevado a 4.
6. Escrever uma função recursiva dentro da classe Recursividade para calcular a soma de todos os 
elementos em um array de inteiros.
7. Escrever dentro de main um programa que mostra a soma dos números do array { 1, 2, 3, 4, 5 };

[![Repo Card](https://github-readme-stats.vercel.app/api/pin/?username=CallmeSalvador&repo=Atividade-Java-recursividade&bg_color=000&border_color=30A3DC&show_icons=true&icon_color=30A3DC&title_color=E94D5F&text_color=FFF)](https://github.com/SEUUSERNAME/SEUREPOSITORIO)

# Materias de apoio
_materiais e utilitários importantes para a realização dessas atividades_
