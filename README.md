# DIO - Trilha .NET - Fundamentos
www.dio.me

## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de fundamentos, da trilha .NET da DIO.

## Contexto
Você foi contratado para construir um sistema para um estacionamento, que será usado para gerenciar os veículos estacionados e realizar suas operações, como por exemplo adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

## Proposta
Você precisará construir uma classe chamada "Estacionamento", conforme o diagrama abaixo:
![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)

A classe contém três variáveis, sendo:

**precoInicial**: Tipo decimal. É o preço cobrado para deixar seu veículo estacionado.

**precoPorHora**: Tipo decimal. É o preço por hora que o veículo permanecer estacionado.

**veiculos**: É uma lista de string, representando uma coleção de veículos estacionados. Contém apenas a placa do veículo.

A classe contém três métodos, sendo:

**AdicionarVeiculo**: Método responsável por receber uma placa digitada pelo usuário e guardar na variável **veiculos**.

**RemoverVeiculo**: Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: **precoInicial** * **precoPorHora**, exibindo para o usuário.

**ListarVeiculos**: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".

Por último, deverá ser feito um menu interativo com as seguintes ações implementadas:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar


## Solução
Nome do Projeto: Sistema de Estacionamento

Descrição do Projeto:
O Sistema de Estacionamento é uma aplicação simples que permite gerenciar um estacionamento. O projeto foi desenvolvido na linguagem de programação C# e faz uso de conceitos básicos de programação para interagir com o usuário e realizar operações como adicionar veículos ao estacionamento, remover veículos e listar os veículos estacionados.

Funcionalidades Principais:

    Adicionar Veículo: Permite ao usuário adicionar um veículo ao estacionamento, solicitando que ele insira a placa do veículo. A placa é então adicionada a uma lista de veículos estacionados e é exibida uma mensagem de confirmação.

    Remover Veículo: Permite ao usuário remover um veículo do estacionamento, mediante a inserção da placa do veículo. A aplicação verifica se o veículo está realmente estacionado, pede a quantidade de horas que o veículo permaneceu no estacionamento, calcula o valor total com base nas tarifas de estacionamento (preço inicial e preço por hora), remove o veículo da lista e exibe o valor total da estadia.

    Listar Veículos: Exibe a lista de veículos atualmente estacionados no estacionamento, caso haja veículos registrados. Se não houver veículos, é exibida uma mensagem informando que o estacionamento está vazio.

Detalhes Técnicos:

    O projeto utiliza uma classe Estacionamento que contém as funcionalidades mencionadas.
    O preço inicial e a taxa por hora são configurados ao criar uma instância da classe Estacionamento.
    As placas dos veículos são armazenadas em uma lista na classe.
    A interface com o usuário é feita por meio da console, onde são exibidas mensagens e lidas as entradas do usuário.

Este projeto pode ser utilizado como base para um sistema de estacionamento mais completo, adicionando recursos adicionais, como persistência de dados, relatórios e funcionalidades mais avançadas de gerenciamento de estacionamento.
