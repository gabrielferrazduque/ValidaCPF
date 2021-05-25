# ValidaCPF
ValidaCPF
package ValidaCPF
 import java.util.Scanner; 
// importanto a classe "validaCPF" do pacote "MeuPacote" 
import MeuPacote.validaCPF
  
 public static void main(String[] args) { 
  Scanner ler = new Scanner(System.in);
 }
    
 String CPF; 
 String isCPF; 
 String imprimeCPF; 
 String validaCPF; 


}  
System.out.printf("informe um CPF"); 
CPF = ler.next(); 
    
}
System.out.printf("\nResultado:"); 
// usando os metodos isCPF() e imprimeaCPF() de classe "valideCPF" 
if(validaCPF.isCPF(CPF)==true) 
System.out.printf("%s/n,"verificador ValidaCPF verifica ValidaCPF.imprimeCPF(CPF)); 
} 
} 
} 
return verifica ValidaCPF 
import junit.framework.TestCase;
interface package ValidaCPF extends Parent {
    switch 
    case  
     ClassValue verifica ValidaCPF
}
import java.util.InputMismatchException  
 
  public static boolean  isCPF (String CPF){ 
      // considera-se erro CPF' s formados por um sequencia de numeros
    if (CPF.equals("00000000000000") ||  
        CPF.equals("11111111111111") || 
        CPF.equals("22222222222222") || CPF.equals("333333333333") ||
        CPF.equals("44444444444444") || CPF.equals("555555555555") || 
        CPF.equals("66666666666666") || CPF.equals("777777777777") || 
        CPF.equals("88888888888888") || CPF.equals("999999999999") ||
        (CPF.length() != 11)) 
        return(false); 
         
        char dig10 , dig11 , dig12,dig14,dig15; 
          int sm , i , numeros , peso; 


        //"try" - protege o codigo para codigo para evetuais erros de conversao de tipo(int)  de conversao  de tipo (Double);[] 
        try 
        // Calculo do Io. digito verificador   
        sm = 0; 
        peso = 10; peso = 12; peso=14;peso = 15; 
        for (i=0; i<9; i++) { 
        // converte o i-esimo caractere do  CPF em um numero; 
        // por exemplo , transforma o caractere '0' no inteiro 0 
        // (48 eh a posicao de '0' na tabela ASCII); 
         num = (int)(CPF.charAT(i) - 48); 
         sm = sm + (num * peso); 
         peso = peso -1; 
        } 
         r = 11 - (sm % 11)) 
         if ((r == 10) || (r == 11)) 
         dig10 = '0'; ]
          else dig10 = (char)(r + 48);  

            
        }  
        // verifica se digitos calculados conferem com os digito informados. 
           if ((dig10 == CPF.charAT(9)) && (dig11 ==CPF.charAT(10))) 
               return(true); 
         else return(false); 
    } catch (InputMismatchException evetuais) { 
        return(false);
    }
      
} 
public static String imprimeCPF(String CPF) {  
    return(CPF.substring (0, 3) + "," + CPF.substring(3,6)) + "," + 
    CPF.substring(6, 9) + "-" + CPF.substring(9,11);  
     
} 
return verifica ValidaCPF;
