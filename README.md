1
a) Uma classe em Python é um tipo especial de estrutura que serve como um molde para criar objetos. Ela define que atributos, funcionalidades e métodos os objetos vão ter. Na programação orientada a objetos a classe ajuda a organizar o código, agrupando as informações e funções relacionadas em blocos lógicos, facilitando o reaproveitamento e a manutenção.

b) Um objeto é uma instância concreta de uma classe, algo criado a partir do molde definido pela classe. Num programa cada objeto pode ter valores e comportamentos próprios, mesmo que baseados na mesma classe.

c) Atributos são as informações armazenadas dentro de um objeto, como características, ja os métodos são funções definidas dentro da classe, servem para executar ações relacionadas ao objeto.

d) Herança é quando uma classe pode aproveitar características e métodos de outra classe para evitar repetir o código. Uma classe filha pode herdar tudo da classe mãe e só adicionar ou modificar o que for necessário.

e) Encapsulamento é proteger e organizar os dados de uma classe controlando quem pode acessar ou modificar esses dados, isso é feito usando atributos públicos, protegidos com um underline e privados com dois underlines para limitar o acesso.

2
class user:
 def__init__(self,name,cpf):
  cpf = input("digite o seu cpf: ")
  name = input("digite o seu nome: ")
  adress = input("digite seu endereço: ")
  password = input("digite sua senha: ")
