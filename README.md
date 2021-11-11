# Projeto-trabalho-dupla-dragon-bool
# O projeto consiste em criar um cadastro de pessoas que possam comparecer a um evento em tempos de pandemia, onde determinado espaço deva conter X número de pessoas, além de álcool em gel distribuídos nos locais viáveis. As classes utilizadas serão: Program, Pessoa e Evento. Os métodos utilizados serão: Main e Soma. 

using System;
  class Program {
    public static void Main(string[] args){
      
      Console.WriteLine("Escolha, em m², o espaço que queira para sua exposição: ");
      float espaco = float.Parse(Console.ReadLine());

      if (espaco => 20.0 and <= 25.0){
          Console.WriteLine("Espaço disponível até 9 pessoas na área");
      }
      else {
          Console.WriteLine("área não disponível para as dimensões do evento");
      }

      if (espaco >= 15.0 and <= 19.9) {
          Console.WriteLine("Espaço disponível para até 7 pessoas na área");
      }

      Console.ReadKey();
    }
  }
  
  using System;
  class Program{
    public static void Main(string[] args){

      // PERMITE QUE FAÇA INPUT OU OUTPUT DE DADOS
      Console.WriteLine ("Entre com uma opcao para a entrada no evento");
      int opcao = Int32.Parse(Console.ReadLine());

      switch (opcao){
        case 1:
          Console.WriteLine("Palestra sobre empreendedorismo");
          break;
        case 2:
          Console.WriteLine("Palestra sobre marketing nas empresas");
          break;
        case 3:
          Console.WriteLine("Como começar um negócio com R$1.000,00 para chegar a R$1.000.000,00 de lucro");
          break;
        default:
          Console.WriteLine("Vamos para a parte de exposições");
          break;
      }
    }
  }

