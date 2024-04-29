//Elaborar um programa para conjugar verbos 

//regulares no presente, passado e futuro

import java.util.Scanner;

public class Verbos {
    
    public static void main (String[] args) {
        
        Scanner teclado = new Scanner(System.in);
        
        System.out.println("Digite o verbo a ser conjugado:");
        
        String palavra = teclado.nextLine();
        
        String prefixo = palavra.substring(0, palavra.length() - 2); 
        
        if (palavra.endsWith("ar")) {
        
            System.out.println("Conjugação para verbos terminados em 'ar':");
            
            System.out.println("Presente:");
            
            System.out.println("Eu " + prefixo + "o");
            
            System.out.println("Tu " + prefixo + "as");
            
            System.out.println("Ele/Ela " + prefixo + "a");
            
            System.out.println("Passado:");
            
            System.out.println("Eu " + prefixo + "ei");
            
            System.out.println("Tu " + prefixo + "aste");
            
            System.out.println("Ele/Ela " + prefixo + "ou");
            
            System.out.println("Futuro:");
            
            System.out.println("Eu " + prefixo + "arei");
            
            System.out.println("Tu " + prefixo + "arás");

            System.out.println("Ele/Ela " + prefixo + "ará");
            
        } else if (palavra.endsWith("er")) {
        
            System.out.println("Conjugação para verbos terminados em 'er':");
            
            System.out.println("Presente:");
            
            System.out.println("Eu " + prefixo + "o");
            
            System.out.println("Tu " + prefixo + "es");
            
            System.out.println("Ele/Ela " + prefixo + "e");
            
            System.out.println("Passado:");
            
            System.out.println("Eu " + prefixo + "i");
            
            System.out.println("Tu " + prefixo + "este");
            
            System.out.println("Ele/Ela " + prefixo + "eu");
            
            System.out.println("Futuro:");
            
            System.out.println("Eu " + prefixo + "erei");
            
            System.out.println("Tu " + prefixo + "erás");
            
            System.out.println("Ele/Ela " + prefixo + "erá");
            
        } else if (palavra.endsWith("ir")) {
        
            System.out.println("Conjugação para verbos terminados em 'ir':");
            
            System.out.println("Presente:");
            
            System.out.println("Eu " + prefixo + "o");
            
            System.out.println("Tu " + prefixo + "es");
            
            System.out.println("Ele/Ela " + prefixo + "e");
            
            System.out.println("Passado:");
            
            System.out.println("Eu " + prefixo + "i");
            
            System.out.println("Tu " + prefixo + "iste");
            
            System.out.println("Ele/Ela " + prefixo + "iu");
            
            System.out.println("Futuro:");
            
            System.out.println("Eu " + prefixo + "irei");
            
            System.out.println("Tu " + prefixo + "irás");
            
            System.out.println("Ele/Ela " + prefixo + "irá");
            
        } else {
        
            System.out.println("Verbo não reconhecido ou não é regular.");
            
        }
        
        teclado.close();
        
    }
    
}
