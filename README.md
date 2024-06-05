# 05/06/2024
## Interview 1
- Cosa si intende per polimorfismo?
- Data una scrittura del tipo "A object = ...;", possiamo dire con certezza di che tipo è la variabile object?
- Data una scrittura del tipo "A object = new B();", si tratta di codice compilabile? Se si, sotto quali condizioni?
- Nel contesto del framework Spring, cosa si intendono ed a cosa servono Service, Repository e Controller?
- Cosa si può dire di un metodo con la seguente intestazione?
```java
  String process(String x) throws NoElementException 
```
  - Se esiste un'eccezione di tipo T che estende NoElementException, posso lanciarla in questo metodo?
  - Se T estende RuntimeException ma non NoElementException, posso lanciarla?
-
```java
  int sum(int[] array) {
    for(int i = 1; i <= array.length; ++i) {
      result += array[i-1];
    }
    return result;
  }
```
  
# 31/05/2024
## Interview 1
- Qual è la differenza fra classe astratta ed interfaccia?
- Cos'è il polimorfismo?
- Cosa si intende per "incapsulamento"?

## Interview 2
- Qual è la differenza fra le annotazioni @Controller e @RestController di Spring?
- Cosa si intende per "incapsulamento"?
- Cosa si può dire di un metodo con la seguente signature?
```java
  void abc(String x, String y)
```

## Interview 3
- Perchè dobbiamo estendere JpaRepository quando creiamo un repository per una specifica entità? Di che parametri necessitiamo?
- Qual è la differenza fra i metodi *save* e *saveAndFlush*?
- Date due variabili di tipo String *a* e *b*, qual è la differenza fra lo scrivere *a == b* e *a.equals(b)*?

