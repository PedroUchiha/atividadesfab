\\atividade01
import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double numero1;
    Double numero2;
    Double resto;
    
    System.out.println("Digite o primeiro número: ");
    numero1 = entrada.nextDouble();
    
    System.out.println("Digite o segundo número: ");
    numero2 = entrada.nextDouble();
    
    resto = numero1/numero2;
    
    System.out.println("O resultado da sua divisão foi: "+ resto);
    
    
    
  }
}
//Atividades 02
import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double dolar;
    Double real;
    
    System.out.println("Digite o valór em dolar: ");
    dolar = entrada.nextDouble();
    
    real = dolar*4.95;
    
    System.out.println("O valor convertido em reais corresponde a : " + real);

    //Atividades 03
    import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double raio;
    Double resultado;
    
    System.out.println("Digite o raio do círculo: ");
    raio = entrada.nextDouble();
    
    resultado = raio*raio*3.1;
    
    System.out.println("A área do círculo corresponde a :" + resultado);
    
  }
}

//Atividades04
import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double numero1;
    Double numero2;
    Double numero3;
    Double media; 
    
    System.out.println("Digite o primeiro número: ");
    numero1 = entrada.nextDouble();
    
    System.out.println("Digite o segundo número: ");
    numero2 = entrada.nextDouble();
    
    System.out.println("Digite o terceiro número: ");
    numero3 = entrada.nextDouble();
    
    media = (numero1+numero2+numero3)/3;
    
    System.out.println("A média simples dos números inseridos corresponde a : " + media);    
    
   
    
    
    
  }
}

//Atividades05
import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double valorHora;
    Double horasTrabalhadas;
    Double percentualdesconto;
    Double salarioBruto;
    Double salarioLiquido;
    Double descontoInss;
    
    System.out.println("Digite o valor ganho por hora: ");
    valorHora = entrada.nextDouble();
    
    System.out.println("Digite o valor de horas trabalhadas no mês: ");
    horasTrabalhadas = entrada.nextDouble();
    
    System.out.println("Digite o percentual de desconto do INSS em %: ");
    percentualdesconto = entrada.nextDouble();
    
    salarioBruto = valorHora * horasTrabalhadas;
    descontoInss = salarioBruto * (percentualdesconto/100);
    
    salarioLiquido = salarioBruto - descontoInss;
    
    System.out.println("Salário Bruto = " + salarioBruto);
    System.out.println("Desconto INSS: " + descontoInss);
    System.out.println("Salário líquido: " + salarioLiquido);
  }
}

//Atividades 06
import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Integer A;
    Integer B;
    
    System.out.println("Digite o valor de A: ");
    A = entrada.nextInt();
    
    System.out.println("Digite o Valor de B: ");
    B = entrada.nextInt();
    
    System.out.println("Antes da troca: A =" + A);
    System.out.println("B = " + B);
    
    int temp = A;
    A = B;
    B = temp;
    
    System.out.println("Após a troca: ");
    System.out.println("A = " + A);
    System.out.println("B = " + B);
    
  }
}

//Atividades 07

Double x;
   
    System.out.print("Informe um número de 0 a 10: ");
    x = entrada.nextDouble();
    System.out.print("O quadrado de seu número é: "+x*x+" "+"e o cubo de seu número: "+x*x*x);
    */
     

//Atividades 08 
Double f;
    Double c;
    
    
    System.out.print("Digite a temperatura em Fahrenheit: ");
    f= entrada.nextDouble();
    c = (f-32)/1.8;
    System.out.print("Sua temperatura em celcius será: "+c);
    */

//Atividades 09
Double caneta;
    Double valor;
    Double troco;
    Double unidade;
    
    System.out.print("Quantas canetas você comprou?");
    caneta = entrada.nextDouble();
    System.out.print("Qual o valor pago?");
    valor = entrada.nextDouble();
    System.out.print("Quanto ded troco você recebeu?");
    troco = entrada.nextDouble();
    unidade = (valor-troco)/caneta;
    System.out.print("A unidade da caneta está por R$"+unidade);
    */

//Atividades 10
System.out.print("Informe a hora (HH:MM): ");
     String hora = entrada.nextLine();

     String[] partes = hora.split(":");
     int horas = Integer.parseInt(partes[0]);
     int minutos = Integer.parseInt(partes[1]);

     int minutosPassados = (horas * 60) + minutos;

     System.out.println("Minutos passados desde o início do dia: " + minutosPassados);
     */

Atividades 11
Double etanol;
    Double gasolina;
   
    System.out.println("Qual o preço da gasolina? ");
    etanol = entrada.nextDouble();
    System.out.println("Qual o preço do etenol? ");
    gasolina = entrada.nextDouble();
    if((etanol*70/100)>gasolina){System.out.println("Abasteça com etnaol!");}else{System.out.println("Abasteça com gasonila!");}
    */

Atividades 12
Double largura;
    Double comprimento;
    Double valor;
    Integer arredondamento;
     
    System.out.println("Informe a largura a ser revestida em metros: ");
    largura = entrada.nextDouble();
    System.out.println("Informe o comprimento a ser resvestido em metros: ");
    comprimento = entrada.nextDouble();
    System.out.print("Informe o valor do metro da cerâmica: ");
    valor = entrada.nextDouble();
    Double resultado = largura*comprimento*valor;
    System.out.println("O valor é: R$"+resultado*10/100);
    */

//Atividades 13
Double a;
    Double b;
    
    System.out.print("Informe o valor de A: ");
    a = entrada.nextDouble();
    System.out.print("Informe o valor de B: ");
    b = entrada.nextDouble();
    Double piaba = a;
    a = b;
    b = piaba;
    System.out.println("O valor de A é: "+a+"e o valor de B é: "+b);
    */

//Atividades 14
Double peso;
    
    System.out.println("informe o seu peso:");
    peso = entrada.nextDouble();
    System.out.println("A quantida ideal de água ser consumida será: "+peso*35/1000+"Litros");
    */

//Atividades 15
System.out.print("Digite o valor de x1: ");
        double x1 = entrada.nextDouble();
        
        System.out.print("Digite o valor de y1: ");
        double y1 = entrada.nextDouble();
        
        System.out.print("Digite o valor de x2: ");
        double x2 = entrada.nextDouble();
        
        System.out.print("Digite o valor de y2: ");
        double y2 = entrada.nextDouble();
        
        double distancia = Math.sqrt(Math.pow((x1 - x2), 2) + Math.pow((y1 - y2), 2));
        
        System.out.println("A distância entre os pontos é: " + distancia);
        */

Atividades 16
Double x;
    Double y;
    Double z;
    
    System.out.println("Informe a sua nota na primeira avaliação:");
    x = entrada.nextDouble();
    System.out.println("Informe a sua nota na segunda avaliação:");
    y = entrada.nextDouble();
    System.out.println("Informe a sua nota na terceira avaliação:");
    z = entrada.nextDouble();
    Double media = x*y*z/3; 
    if (media>=7){System.out.print("Você foi aprovado!"+"e sua média foi de "+media);}else{System.out.print("Você é burro!"+"Sua média foi de apenas: "+media);}
    */

//Atividades 17
Double eleitores;
    Double brancos;
    Double nulos;
    Double validos;
    
    System.out.println("Informe a quantidade de votos brancos:");
    brancos = entrada.nextDouble();
    System.out.println("Informe a quantidade de votos nulos:");
    nulos = entrada.nextDouble();
    System.out.println("Informe a quantidade de votos válidos:");
    validos = entrada.nextDouble();
    eleitores = brancos+nulos+validos;
    System.out.print("A votação contou com "+eleitores+" eleitores"+" tendo: "+(brancos*100/eleitores)+"% de votos brancos"+(nulos*100/eleitores)+"% de votos nulos"+(validos*100/eleitores)+"% de votos validos!");
    */

//Atividades 18
Integer idade;
    
    System.out.println("Informe a sua idade: ");
    idade = entrada.nextInt();
    if (idade>=16){System.out.println("Voto facultativo");}if(idade<16){System.out.println("Idade insuficiente para votar!");}if(idade>18){System.out.println("Voto obrigaatório!");}
    */

//Atividades 19
double saldo = 1000.00; 
        String extrato = "";

        while (true) {
            System.out.println("Bem-vindo ao Caixa Eletrônico");
            System.out.println("Escolha uma das opções abaixo:");
            System.out.println("1 - Exibir saldo");
            System.out.println("2 - Exibir extrato");
            System.out.println("3 - Realizar depósito");
            System.out.println("4 - Realizar saque");
            System.out.println("5 - Sair");
            System.out.print("Opção: ");

            int opcao = scanner.nextInt();

            switch (opcao) {
                case 1:
                    System.out.println("Seu saldo é: R$ " + saldo);
                    break;

                case 2:
                    if (extrato.isEmpty()) {
                        System.out.println("Não há transações para exibir.");
                    } else {
                        System.out.println("Extrato:");
                        System.out.println(extrato);
                    }
                    break;

                case 3:
                    System.out.print("Digite o valor para depósito: R$ ");
                    double deposito = scanner.nextDouble();
                    saldo += deposito;
                    extrato += "Depósito de: R$ " + deposito + "\n";
                    System.out.println("Depósito realizado com sucesso.");
                    break;

                case 4:
                    System.out.print("Digite o valor para saque: R$ ");
                    double saque = scanner.nextDouble();
                    if (saque > saldo) {
                        System.out.println("Saldo insuficiente para realizar o saque.");
                    } else {
                        saldo -= saque;
                        extrato += "Saque de: R$ " + saque + "\n";
                        System.out.println("Saque realizado com sucesso.");
                    }
                    break;

                case 5:
                    System.out.println("Obrigado por utilizar o Caixa Eletrônico. Até logo!");
                    System.exit(0);

                default:
                    System.out.println("Opção inválida. O programa será encerrado.");
                    System.exit(1);
            }

            System.out.println(); // Linha em branco para separar as operações
        
    

*/

//Atividades 20
String produto = "";
        int quantidade;
        double preco = 0.0;

        System.out.println("Padaria do Jão:");
        System.out.println("Escolha um produto");
        System.out.println("1 - Pão");
        System.out.println("2 - Queijo");
        System.out.println("3 - Café");
        System.out.print("Opção: ");
        int opcao = entrada.nextInt();

        switch (opcao) {
            case 1:
                produto = "Pão";
                preco = 1.50;
                break;
            case 2:
                produto = "Queijo";
                preco = 20.00;
                break;
            case 3:
                produto = "Café";
                preco = 5.00;
                break;
            default:
                System.out.println("Opção inválida.");
                System.exit(1);
        }

        System.out.print("Digite a quantidade adquirida de " + produto + ": ");
        quantidade = entrada.nextInt();

        double total = quantidade * preco;
        double desconto = 0.0;

        if (quantidade <= 5) {
            desconto = total * 0.02;
        } else if (quantidade <= 10) {
            desconto = total * 0.03;
        } else if (quantidade < 30) {
            desconto = total * 0.05;
        } else {
            desconto = total * 0.10;
        }

        double totalAPagar = total - desconto;

        System.out.println("Produto: " + produto);
        System.out.println("Quantidade adquirida: " + quantidade);
        System.out.println("Preço unitário: R$ " + preco);
        System.out.println("Total: R$ " + total);
        System.out.println("Desconto: R$ " + desconto);
        System.out.println("Total a pagar: R$ " + totalAPagar);
        */

