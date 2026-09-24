# Sistema de Notas do Aluno

## Descriação

Este programa calcula a média de duas notas e informa se o aluno foi aprovado ou reprovado.

## Tecnologias Utilizadas

**Python 3.14 (64-bit)**

## Como Instalar e Executar

Você pode utilizar o Visual Studio Code (vscode) para executar o programa: 


Este código cria um sistema simples para calcular a média de um aluno. O programa solicita ao usuário duas notas, realiza o cálculo da média através da função calcular_media() e exibe o resultado na tela.

Após calcular a média, o programa verifica se o aluno atingiu a nota mínima de 7,0. Caso a média seja igual ou superior a 7,0, o aluno será exibido como APROVADO. Caso contrário, será exibido como REPROVADO.

def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2
print("=== Sistema de Notas do Aluno ===")

n1 = float(input("Digite a primeira nota: "))
n2 = float(input("Digite a segunda nota: "))

media = calcular_media(n1, n2)

print(f"A média final é: {media:.2f}")

if media >= 7.0:
    print("Status: APROVADO!")
else:
    print("Status: REPROVADO.")

Esse código é essencial para o funcionamento do programa e pode ser executado em ambientes compatíveis com Python, como o Python 3.14 (64-bit) ou versões mais recentes instaladas no computador.


# Exemplo de Uso ou Demonstração
![Exemplo](imag.png)


# Autor e Contato

**Thiago Alberto de Souza**
**Estudante da Cruzeiro do Sul**