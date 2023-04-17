
package Dados;


public class Pessoa{

    private int idade;
    private int dia;
    private int mes;
    private int ano;
    private String nome;
    
   
    public Pessoa(int dia, int mes, int ano, String nome){
        this.dia = dia;
        this.mes = mes;
        this.ano = ano;
        this.nome = nome;
    
    }

    
    public void Calculaidade(int mesAtual, int diaAtual, int anoAtual){
        if(mesAtual >=  mes && diaAtual>=  dia){
            idade = anoAtual- ano;
        }else{
            idade = (anoAtual- ano)-1;
        }
    
}       
    public int informaIdade(){
        return idade;
    }

    public String to_string(){
        return "\nNome =  " +nome +"\nDia em que nasceu = " +dia + "\nmes em que nasceu = " +mes + "\nano em que nasceu = "+ano;
               
    }

} 

    
 
