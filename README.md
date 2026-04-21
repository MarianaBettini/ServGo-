# Projeto ServGo 

Este repositório contém o desenvolvimento de um sistema de console em Python para gestão de serviços. Ele é uma plataforma de compra e venda de serviços, abrangendo desde fretes, serviços domésticos e mecânicos até cabeleireiros e manicures. A iniciativa visa promover maior inserção de pequenos negócios no mercado, ampliando suas oportunidades de destaque por meio da plataforma. 

## 👥 Integrantes:
* Gabriely Leal;
* Gaciane Lima;
* Mariana Neves.

## 🚀 Tecnologias Utilizadas:
* **Linguagem:** Python 3.10+ (utilizando a estrutura `match/case`) 
* **IA:** Gemini 3.1 Pro (Auxílio no desenvolvimento)

## 🧠 Sobre a Lógica do Sistema:
O sistema foi modelado para gerenciar o fluxo entre **Clientes** e **Prestadores de Serviço**. Estruturamos a hierarquia de classes em três níveis (Pessoa → Usuário → Cliente/Prestador), garantindo que todas as entidades principais herdem as características básicas de uma `Pessoa`.

### Requisitos Técnicos Implementados:
* **Dataclasses:** Utilizadas para entidades de transferência de dados (DTOs).
* **POO Avançada:** Herança de 3 níveis, herança múltipla e polimorfismo (Duck Typing).
* **Tratamento de Exceções:** Uso de blocos `try/except/else/finally` com exceções personalizadas.
* **Coleções:** Uso de dicionários e List Comprehensions para filtros.

## 🧑‍💻 Diferenças Técnicas: Python vs. C:
Paralelos importantes entre as estruturas aprendidas em **C** e a sintaxe do **Python**:

1. **Dataclasses vs. Structs:** Ambas agrupam dados em um único objeto. No C, as structs exigem definição rígida de tamanho, enquanto em Python os objetos são dinâmicos. A `@dataclass` também automatiza o construtor (`__init__`).
2. **Type Hints vs. Tipagem Estática:** Em C, a tipagem é obrigatória no compilador. No Python, os Type Hints auxiliam na documentação e no desenvolvimento, mantendo a flexibilidade da linguagem.
3. **Match/Case vs. Switch/Case:** Ambas lidam com múltiplas escolhas de forma limpa. O `match/case` do Python 3.10 permite comparar padrões estruturais complexos, indo além do `switch` básico do C.

## 🤖 O Que Achamos Mais Desafiador Na Transição Para o Python?


## 🛠️ Como Executar
1. Certifique-se de ter o Python 3.10 ou superior instalado.
