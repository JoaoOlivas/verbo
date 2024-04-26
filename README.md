//Elaborar um programa para conjugar verbos 
//regulares no presente, passado e futuro
import java.util.Scanner;


public class verbos {
    
    public static void main (String[] args){
        
        Scanner teclado = new Scanner(System.in);
        
        int prefixoT= 0;
        
        System.out.println (" Digite o verbo a ser conjugado : ");
        
        String palavra = teclado.nextLine();
        
        String verbo= palavra;
     
 String prefixo = verbo.substring(0, verbo.length()-3); 
        
        

System.out.println(" \n as varaiaveis em presente dessa palavra são : Eu " + prefixo+ "ro");

System.out.println(" \n as varaiaveis em presente dessa palavra são : Tu " + prefixo + "res");
        
System.out.println(" \n as varaiaveis em presente dessa palavra são : Ele/Ela " + prefixo + "re");
    
System.out.println(" \n as varaiaveis em  passado  dessa palavra são : Eu " + prefixo + "ria");

System.out.println(" \n as varaiaveis em  passado  dessa palavra são : Tu " + prefixo + "ria");
        
System.out.println(" \n as varaiaveis em  passado  dessa palavra são : Ele/Ela " + prefixo + "ria");

System.out.println(" \n as varaiaveis em futuro dessa palavra são : Eu " + prefixo + "rerei");

System.out.println(" \n as varaiaveis em futuro dessa palavra são : Tu " + prefixo + "rerás");
        
System.out.println(" \n as varaiaveis em futuro dessa palavra são : Ele/Ela " + prefixo + "rerá");
        


} 
 }
