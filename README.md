## Programação procedural

* Programação com estrutura de baixo para cima
* Não tem classes nem herança
* São sequencial, vem uma coisa depois da outra
* Dificulta o reuso de código
* Baseia-se principalmente em métodos/funções

# Exemplo:

```Java
def latir(nome):
    print(nome + " diz: Au au!")

def fazer_aniversario(nome, idade):
    idade += 1
    print(nome + " tem " + str(idade) + " anos de idade")
    return idade

# nome e idade do cachorro
nome = "Fifi"
idade = 0

# Método para o cachorro Fifi latir
latir(nome)

# Fazendo o cachorro fazer aniversário
idade = fazer_aniversario(nome, idade)
```

## Programação orientada a objetos

* Utiliza classes
* Facilita o reuso de código
* As classes podem ser instanciadas em objetos
* Cada classe pode possuir vários métodos (são a mesma coisa que funções)


# Exemplo:
```
void latir() {
    System.out.println(nome + " diz: Au au!");
}

void fazer_aniversario() {
    idade += 1;
    System.out.println(nome + " tem " + idade + " anos de idade");
}

public static void main(String[] args) {
    Main cachorro = new Main();
    cachorro.nome = "Fifi";
    cachorro.latir();
    cachorro.fazer_aniversario();
}
```
		


```
INÍCIO
	1. Cancelar o despertador
	2. Levantar da cama
	3. Ir até o banheiro
	4. Lavar o rosto
	5. Fazer café
	6. Se não for final de semana;
		1. Ligar o computador
		2. Estudar
		3. Tomar café
	7. Se for final de semana
		1. Ligar o computador
		2. Jogar
		3. Tomar café
FIM
```