# Desafio de Projeto – Estacionamento (.NET Fundamentos - DIO)

Bem-vindo ao **Desafio de Projeto** da **Trilha de .NET – Fundamentos** da DIO!  
Neste desafio, foi solicitado a criação de um sistema simples de gerenciamento de estacionamento utilizando os conceitos básicos da linguagem **C#** e da plataforma **.NET**.

---

## 📌 Objetivo

Desenvolver uma aplicação de console que simule as operações básicas de um estacionamento:
- Adicionar veículos (por placa)
- Remover veículos e calcular o valor a ser pago
- Listar todos os veículos atualmente estacionados

O foco está na aplicação de conceitos fundamentais como:
- Classes e objetos
- Estruturas de controle (`if`, `foreach`, etc.)
- Coleções (`List<T>`)
- Entrada e saída de dados no console
- Manipulação de tipos numéricos (`decimal`, `int`)

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: C#
- **Plataforma**: .NET (versão compatível com o SDK mais recente)
- **IDE recomendada**: Visual Studio, Visual Studio Code ou qualquer editor de sua preferência
- **Conceitos abordados**:
  - Programação orientada a objetos (POO)
  - Encapsulamento
  - Métodos e propriedades
  - Tratamento básico de entrada do usuário

---

## 📁 Estrutura do Projeto

```
DesafioFundamentos/
│
├── README.md
├── .gitignore
└── DesafioFundamentos
    ├── Program.cs
    ├── DesafioFundamentos.csproj
    └── Models
        └── Estacionamento.cs      
```

---

## 🧩 Diagrama de Classe
```md
+----------------------------------+
|          Estacionamento          |
+----------------------------------+
| - precoInicial: decimal          |
| - precoPorHora: decimal          |
| - veiculos: List<string>         |
+----------------------------------+
| + AdicionarVeiculo()             |
| + RemoverVeiculo()               |
| + ListarVeiculos()               |
+----------------------------------+
```
---

## 🧪 Como Executar

1. **Clone ou baixe** este repositório.
2. Abra o terminal na pasta do projeto.
3. Execute o seguinte comando para rodar a aplicação:

```bash
dotnet run
```

4. Siga as instruções no console para:
   - Adicionar veículos
   - Remover veículos (e ver o valor calculado)
   - Listar veículos estacionados
   - Sair do sistema

---

## 💡 Exemplo de Funcionamento

```
Escolha uma opção:
1 - Adicionar veículo
2 - Remover veículo
3 - Listar veículos
4 - Sair

Digite a opção: 1
Digite a placa do veículo para estacionar:
ABC1234

Veículo estacionado com sucesso!

Digite a opção: 3
Os veículos estacionados são:
ABC1234

Digite a opção: 2
Digite a placa do veículo para remover:
ABC1234
Digite a quantidade de horas que o veículo permaneceu estacionado:
3
O veículo ABC1234 foi removido e o preço total foi de: R$ 15,00
```

*(Considerando `precoInicial = 5` e `precoPorHora = 3.33`)*

---

## 📚 Aprendizados

O que aprendi neste desafio:
- Criar e manipular classes em C#
- Trabalhar com coleções para armazenar dados em memória
- Interagir com o usuário via console
- Aplicar lógica condicional e repetitiva
- Realizar cálculos com tipos decimais com precisão financeira

---

## 📝 Licença

Este projeto é educacional e pode ser usado livremente para fins de aprendizado.
