# Desafio Técnico - Gestão de Funcionários

## Descrição
Este projeto em Java tem como objetivo realizar operações de gerenciamento de funcionários de uma indústria. O sistema armazena informações como nome, data de nascimento, salário e função dos funcionários, além de realizar diversas operações sobre esses dados.

## Tecnologias Utilizadas
- Java 17+
- API Java de Data e Hora (java.time)
- Collections Framework
- Stream API
- BigDecimal para cálculos monetários

## Funcionalidades Implementadas
1. **Cadastro de funcionários** conforme os dados fornecidos.
2. **Remoção de um funcionário** (João) da lista.
3. **Exibição de todos os funcionários**, com formatação correta de datas e valores monetários.
4. **Ajuste de salários** com um aumento de 10%.
5. **Agrupamento de funcionários por função**.
6. **Exibição dos funcionários por função**.
7. **Listagem dos funcionários que fazem aniversário em outubro e dezembro**.
8. **Identificação do funcionário mais velho**, exibindo seu nome e idade.
9. **Ordenação da lista de funcionários em ordem alfabética**.
10. **Cálculo do total dos salários de todos os funcionários**.
11. **Cálculo de quantos salários mínimos cada funcionário recebe**, considerando o valor de R$1212,00.

## Estrutura do Código
O código está organizado em três classes principais:

- `Pessoa`: Representa uma pessoa com nome e data de nascimento.
- `Funcionario`: Herda de `Pessoa` e adiciona atributos de salário e função, além de métodos para manipulação dos dados.
- `Principal`: Classe principal que executa todas as operações necessárias para atender aos requisitos do desafio.

## Como Executar
1. Certifique-se de ter o Java instalado (Java 17 ou superior).
2. Compile os arquivos Java:
   ```sh
   javac industria-funcionarios.java
   ```
3. Execute o programa:
   ```sh
   java industria-funcionarios
   ```

## Autor
Desenvolvido como parte de um desafio técnico para manipulação de listas e dados em Java.

