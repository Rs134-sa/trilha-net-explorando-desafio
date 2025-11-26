# Sistema de Reserva de Hotel em C#

## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de explorar a linguagem C#, da trilha .NET da DIO.

![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)

## Contexto
Você foi contratado para construir um sistema de hospedagem, que será usado para realizar uma reserva em um hotel. Você precisará usar a classe Pessoa, que representa o hóspede, a classe Suíte e a classe Reserva, que fará um relacionamento entre ambos.
## 📖 Sobre o Projeto

O seu programa deverá calcular corretamente os valores dos métodos da classe Reserva, que precisará trazer a quantidade de hóspedes e o valor da diária, concedendo um desconto de 10% caso a reserva seja para um período maior que 10 dias.
Este projeto é a solução para um desafio de código do bootcamp **Trilha .NET** da [Digital Innovation One (DIO)](https://web.dio.me/). O objetivo é construir um sistema simples de reserva de hotel em C#, aplicando conceitos de Programação Orientada a Objetos.

## Regras e validações
1. Não deve ser possível realizar uma reserva de uma suíte com capacidade menor do que a quantidade de hóspedes. Exemplo: Se é uma suíte capaz de hospedar 2 pessoas, então ao passar 3 hóspedes deverá retornar uma exception.
2. O método ObterQuantidadeHospedes da classe Reserva deverá retornar a quantidade total de hóspedes, enquanto que o método CalcularValorDiaria deverá retornar o valor da diária (Dias reservados x valor da diária).
3. Caso seja feita uma reserva igual ou maior que 10 dias, deverá ser concedido um desconto de 10% no valor da diária.
## 🎯 Contexto do Desafio

O sistema de hospedagem deve permitir a realização de reservas, associando hóspedes a uma suíte específica. O programa precisa calcular o valor total da estadia com base no número de dias e no valor da diária, aplicando descontos conforme as regras de negócio.

### ✔️ Regras de Negócio

1.  A capacidade da suíte não pode ser menor que o número de hóspedes. Caso isso ocorra, o sistema deve lançar uma exceção.
2.  O método `ObterQuantidadeHospedes` deve retornar o número exato de hóspedes na reserva.
3.  O método `CalcularValorDiaria` deve retornar o valor total da reserva (Dias Reservados × Valor da Diária).
4.  Se a reserva for para 10 dias ou mais, um desconto de 10% deve ser aplicado sobre o valor total.

## 🛠️ Tecnologias Utilizadas

- **C# 10**
- **.NET 9**
---

## 👨‍💻 Autoria

Feito por [Raiane de Sá](https://github.com/Raiane-S) - Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/raiane-s/)!
