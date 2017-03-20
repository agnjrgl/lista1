# lista1

1.
QUESTAO 1
------------------------------------------------------------------------------
2.
Não há como acessar i[5], pois quando criado, i tinha cinco posições, sendo elas de 0 a 4. Logo temos um erro.
Um modo de corrigir esse erro, é mudar o valor de i[5], para i[4], i[3], i[2], i[1] ou i[0]. Uma possibilidade abaixo:

public class Questao2{
	public static void main(String argv[]){
		int[] i = new int[5];
		System.out.println(i[4]);
	}
}

Como não foi atribuido nenhum valor para int[4], temos na tela apenas 0.
------------------------------------------------------------------------------
3.
O valor de b eh zero.
------------------------------------------------------------------------------
4.
desenho
------------------------------------------------------------------------------
5.
O m2 quando instanciado, usou o construtor que não atribui valor ao m1, assim, na linha m5=m2.m1 não há acesso.
Para corrigir devemos usar um objeto instanciado pelo construtor com parametro como m3:

Mixer m5 = m3.m1

Assim, na tela, temos:
hi hi hi
------------------------------------------------------------------------------
6. 
Nome do correntista:Fulano
CPF do correntista:999
Conta: 111-1
Agencia: 111-2
Saldo: 1000.0
Nome do correntista:Ciclano
CPF do correntista:888
Conta: 222-1
Agencia: 222-2
Saldo: 0.0
Beltrano ** Cliente Especial ** 
Saldo: 3000.0
Limite: 1000.0
Saldo: 4000.0
------------------------------------------------------------------------------
7.
F - Método sempre inicia com letra minuscula
V
V
V
V
V
------------------------------------------------------------------------------
o this. é um ponteiro que aponta para ele próprio.
