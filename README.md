# classe-java
public class Pregoeiro {
    String nome;
    String sexo;
    String localDeTrabalho;
    int idade;
    float horarioDeChegada;
    boolean exigeProfissionalizacao;
    
    public void printStatus() {
        
        System.out.println("Meu nome é : " + nome);
        System.out.println("Meu sexo é : " + sexo);
        System.out.println("Trabalho na  : " + localDeTrabalho);
        System.out.println("Minha idade é : " + idade);
        System.out.println("Chego todos os dias às : " + horarioDeChegada);
        System.out.println("Exige ser Profissional : " + exigeProfissionalizacao);

    }
    public static void main(String args[]) {
      Pregoeiro objeto1 = new Pregoeiro ();
      objeto1.nome = "Flávia";
      objeto1.sexo = "Feminino";
      objeto1.localDeTrabalho = " Prefeitura de Berilo ";
      objeto1.idade = 30;
      objeto1.horarioDeChegada = 7;
      objeto1.exigeProfissionalizacao = false;
      objeto1.printStatus();
      
      
    } 
}
