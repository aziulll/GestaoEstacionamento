# Desafio de Projeto | Decola Tech 2024
Gestão Estacionamento utilizando com .NET

O código apresenta uma classe em C# chamada Estacionamento que simula operações de um estacionamento, como adicionar veículos, remover veículos com base em uma placa e calcular o custo do estacionamento.

A classe Estacionamento mantém informações sobre os preços de estacionamento (precoInicial e precoPorHora) e uma lista de veículos estacionados (veiculos). Os principais métodos incluem:

**AdicionarVeiculo():**
Solicita ao usuário a placa de um veículo para estacionar.
Adiciona a placa à lista de veículos estacionados.

**RemoverVeiculo():**
Solicita ao usuário a placa do veículo a ser removido.
Se a placa existe na lista, solicita a quantidade de horas estacionadas, calcula o custo e remove o veículo.
Exibe uma mensagem com o custo total.

**ListarVeiculos():**
Exibe a lista de veículos estacionados.
