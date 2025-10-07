# 🚗 dotnet-parking-system
Bootcamp Avanade Back-end com .NET e IA, 2025  

![.NET](https://img.shields.io/badge/.NET-6-blue)
![C#](https://img.shields.io/badge/C%23-Visual_Studio-blue)

---

# DIO - Trilha .NET - Fundamentos
[www.dio.me](https://www.dio.me)

## 📝 Desafio de projeto
Neste desafio, usei os conhecimentos que adquiri no módulo de fundamentos da trilha .NET da DIO para desenvolver um sistema de estacionamento funcional, com menu interativo para o usuário.

---

## 🏗 Contexto
Fui responsável por criar um sistema que permite:  
- Adicionar veículos  
- Remover veículos e calcular o valor cobrado pelo período  
- Listar todos os veículos atualmente estacionados

---

## 📌 Proposta
Desenvolvi uma classe chamada **`Estacionamento`**, baseada no seguinte diagrama:  
![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)

A classe possui três variáveis principais:  

- **`precoInicial`**: valor decimal cobrado ao estacionar o veículo  
- **`precoPorHora`**: valor decimal cobrado por hora adicional  
- **`veiculos`**: lista de strings que armazena apenas as placas dos veículos estacionados  

E três métodos principais:  

- **`AdicionarVeiculo`**: adiciona a placa do veículo à lista  
- **`RemoverVeiculo`**: verifica se o veículo está estacionado, pede horas, calcula o valor total e remove da lista  
- **`ListarVeiculos`**: exibe todos os veículos estacionados ou informa se não houver nenhum  

Além disso, implementei um menu interativo com as seguintes opções:  
1. Cadastrar veículo  
2. Remover veículo  
3. Listar veículos  
4. Encerrar

---

## 💻 Tecnologias usadas
- C#  
- .NET 6+  
- Visual Studio ou VS Code

---

## 🚀 Como executar o projeto

1. Clone este repositório:

```
git clone https://github.com/seu-usuario/dotnet-parking-system.git
```
2. Acesse a pasta do projeto:
```
cd dotnet-parking-system
```
3. Compile e execute o projeto usando o .NET CLI:
```
dotnet run
``` 
4.  Siga o menu interativo no console para cadastrar, remover e listar veículos.
