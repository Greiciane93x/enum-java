/# Enum no Java 
* São tipos de campos que consistem em
um conjunto fixo de constantes
  (static final), sendo como uma lista
  de valores pré-definidos. Pode ser definido um tipo 
  de enumeração usando a palavra chave enum. 
  
Os tipos enum implicitamente estendem 
a classe java.lang.Enum 

> * As instâncias dos tipos enum são criadas e nomeadas junto com a 
> declaração da classe, sendo fixas e imutáveis;
> *  Não é possível instanciar 
> * O construtor é declarado private 
> * Não precisa de modificador private explícito 
> * Por convenção é usado com letras maiúsculas. Por serem objetos constantes e imutáveis. (static final)
> * devem obrigatoriamente ter apenas um nome 
> * Pode incluir variáveis de instância, construtor, métodos de instância, de classe



Exemplo:

>> public class Curso{ <br/> 

>>  private String nome;  <br/> 
>>  private Turno turno; <br/> 
>>  private int horas; <br/> 

>> // getters e setters  <br/> 
>> } <br/> 

-------------------------
 >> public enum Turno { <br/> 
  >>  MANHA("manhã") <br/>
  >>  TARDE("tarde") <br/> 
  >> NOITE("noite") <br/> 

  >> private String descricao; <br/>  

  >> Turno(Stirng descricao){ <br/> 
  >>  this.descricao = descricao; <br/> 
  >> } <br/> 
  >>// get de descricao <br/> 
 >>}

