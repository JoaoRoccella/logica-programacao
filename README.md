# Lógica de Programação
Lógica de programação com JavaScript


## Problema 1: Cálculo da média de um aluno

## Problema 2: Simulação de uma urna eletrônica

Crie um programa que simule o funcionamento de uma urna eletrônica, utilizando uma estrutura de repetição para permitir múltiplas votações.

1. O programa deve apresentar as seguintes opções de voto:

```
| 1 | Candidato 1
| 2 | Candidato 2
| 3 | Candidato 3
| 5 | Voto em branco
| 8 | Voto nulo
| 0 | Encerrar a votação
```

2. O programa deve solicitar ao usuário que digite o número do seu voto e armazenar a opção de voto em uma variável. 

3. Se o usuário escolher uma das opções de candidato, o programa deve incrementar o contador de votos do respectivo candidato. 

4. Se o usuário escolher a opção voto em branco, o programa deve incrementar o contador de votos em branco. 

5. Se o usuário escolher a opção voto nulo, o programa deve incrementar o contador de votos nulos. 

6. Se o usuário escolher a opção encerrar a votação, o programa deve sair do laço e exibir o resultado final da votação: 
* quantidade e percentual de votos de cada candidato
* quantidade e percentual de votos em branco e votos nulos
* candidato ganhador, com o seu total de votos e percentual **acrescidos os votos em branco**.
  
7. O programa deve continuar a permitir a votação até que o usuário escolha a opção para encerrar a votação.