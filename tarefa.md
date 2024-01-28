## Programação procedural

Programação com estrutura de baixo para cima
Não tem classes nem herança
São sequencial, vem uma coisa depois da outra
Dificulta o reuso de código
Baseia-se principalmente em métodos/funções

# Exemplo:

def latir(cachorro):
	print(f"{cachorro['nome']} diz: Au au!")

def aniversario(cachorro):
	cachorro['idade'] += 1
	print(f"{cachorro['nome']} agora tem {cachorro['idade']} ano(s) de idade!")


## Programação orientada a objetos

Utiliza classes
Facilita o reuso de código
As classes podem ser instanciadas
Cada classe pode possuir vários métodos (são a mesma coisa que funções)

# Exemplo:

class Cachorro():
	def __init__(self, nome, idade):
		self.nome = nome
		self.idate = idade
	
	def latir(self):
		print(f”{self.nome} dizer: au au!”)

	def fazer_aniversario(self):
		self.idade += 1
		print(f”{self.nome} agora tem {self.idade} ano(s) de idade.”)
		



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