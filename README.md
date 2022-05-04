Atividade Colabotiva 2.03
Resposta das questões propostas do livro Batista & Moraes (2013), página 23:
Questões de 1 a 8.

1. Explique qual a função da Máquina Virtual Java (JVM).
	A função da Máquina Virtual Java (JVM) é interpretar o código intermediário compilado, o bytecode. Para em seguida ser convertido em código de máquina.

2. Qual a diferença entre JRE e JDK? 
	O JRE (Java RunTime Environment) contém todas as ferramentas necessárias para o usuário comum executar uma aplicação java, como a JVM e as bibliotecas disponíveis.  

3. Crie um programa Java que imprima o seguinte texto “Terminei a primeira aula com um programa Java!”.
	
public class MeuPrograma {
    public static void main(String [] args) {
        System.out.println("Terminei a primeira aula com um programa java!!");
    }
}


4. Compile o programa desenvolvido no exercício anterior. A seguir apague o arquivo .class gerado e tente executar o programa. O que aconteceu? 

Eu me deparei com duas situações.
1 - Que ao excluir o arquivo “MeuPrograma.class” ao executar o programa novamente em void main (String[] args) ele executa o procedimento normalmente sem qualquer problema e o arquivo deletado ele é criado novamente quando executado o programa.

2 - Que ao excluir o arquivo “MeuPrograma.class” ao executar o programa novamente ele pede para compilar novamente e depois executar o void main (String[] args) ele executa o procedimento normalmente se qualquer problema e o arquivo deletado ele é criado novamente quando executa o programa.

5. Mude o nome do método “main” para “start”, compile e execute. O que aconteceu?

Após trocar o método “main” por “start” e compilar e executar em seguida ele informa que o campo de parâmetro se encontra vazio.

6. Crie um programa Java para imprimir duas linhas de texto usando duas linhas de código “System.out”, onde aparecerá o seu nome na primeira linha e na segunda linha aparecerá o time para o qual você torce.

public class MeuPrograma {
	public static void main(String [] args) {
		System.out.println("Bruno Lacerda!!");
		System.out.println("Nao tenho time");
	}
}

7. Experimente escrever todo o programa anterior em maiúsculo, compile e execute. O que aconteceu?

Após colocar todo o código anterior em maiúsculo não é possível compilar e muito menos executar o programa. Pois ele fica aguardando se atribuído class, interface ou enum.

8. Experimente salvar o arquivo com um nome diferente do nome da classe, compile e execute. O que aconteceu?

O nome do programa foi alterado para atividade_1.java pediu para ser compilado novamente e após ser executado ele funcionou normalmente como o anterior
