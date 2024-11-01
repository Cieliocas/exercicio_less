# Trabalhando com LESS | Working with LESS

Neste projeto, criei um Linktree customizado como exercício prático para consolidar os conhecimentos adquiridos sobre LESS no Módulo 17. Durante este exercício, transformei o estilo do projeto em LESS, utilizando variáveis, mixins, mapas, e outras funcionalidades importantes.

In this project, I created a customized Linktree as a practical exercise to consolidate the knowledge acquired about LESS in Module 17. During this exercise, I transformed the project's styling into LESS, using variables, mixins, maps, and other essential features.

## 🎯 Objetivo do Exercício | Exercise Objective

1. **Converter o estilo** do projeto disponibilizado no material de apoio para o LESS.
2. **Aplicar os recursos** aprendidos no módulo, incluindo:
   - Variáveis
   - Organização em arquivos divididos
   - Escapings
   - Mapas
3. **Gerenciar o versionamento:** 
   - Criação de uma nova branch chamada `exercicio_less`.
   - Armazenamento dos arquivos LESS nesta branch.
   - Envio do link da branch através da plataforma do curso.

---

1. **Convert the styling** of the project provided in the support material to LESS.
2. **Apply the resources** learned in the module, including:
   - Variables
   - File division and organization
   - Escapings
   - Maps
3. **Manage version control:** 
   - Create a new branch called `exercicio_less`.
   - Store the LESS files in this branch.
   - Submit the branch link through the course platform.

## 📋 Funcionalidades Implementadas | Implemented Features

### Mixin para Propriedades Comuns | Mixin for Common Properties

Criei um **mixin** para centralizar propriedades comuns e facilitar o reaproveitamento de estilos. No LESS, mixins permitem que blocos de código CSS sejam reutilizados ao longo do projeto, economizando tempo e mantendo o código mais organizado. Mixins são como "funções" que aceitam parâmetros e aplicam um conjunto de regras CSS, eliminando a necessidade de repetição.

I created a **mixin** to centralize common properties and facilitate style reuse. In LESS, mixins allow blocks of CSS code to be reused throughout the project, saving time and keeping the code more organized. Mixins work like "functions" that take parameters and apply a set of CSS rules, reducing repetition.

### Mapas de Cores | Color Maps

Usei um **map** no LESS para armazenar todas as cores do projeto em uma única variável. Esse método permite que as cores sejam definidas em um só lugar e acessadas conforme necessário, o que facilita a manutenção e garante consistência. Mapas são coleções de pares de chave-valor, como um dicionário, onde você pode acessar valores específicos conforme o contexto.

I used a **map** in LESS to store all project colors in a single variable. This method allows colors to be defined in one place and accessed as needed, which simplifies maintenance and ensures consistency. Maps are collections of key-value pairs, like a dictionary, where you can access specific values as required.

### Escaping para Variáveis | Escaping for Variables

Utilizei **escaping** no LESS para permitir o uso de caracteres especiais que poderiam interferir no código. Escaping permite a inclusão de valores dinâmicos e nomes que seriam interpretados de outra forma pelo LESS, encapsulando-os de forma segura. No LESS, o símbolo `~` pode ser utilizado para escape, e isso garante que certas palavras ou valores sejam interpretados corretamente.

I utilized **escaping** in LESS to allow the use of special characters that might otherwise interfere with the code. Escaping allows dynamic values and names that would otherwise be interpreted differently by LESS to be encapsulated safely. In LESS, the `~` symbol can be used for escaping, ensuring certain words or values are interpreted correctly.

### Media Query Adaptada para LESS | Media Query Adapted for LESS

Adaptei as **media queries** diretamente no LESS dentro do container principal. No LESS, é possível definir media queries de forma aninhada, o que mantém o código mais legível e organizado. Utilizei variáveis para tamanhos de tela, permitindo ajustes responsivos rápidos e sem precisar alterar o código diretamente em múltiplas partes.

I adapted **media queries** directly within the main container in LESS. LESS allows media queries to be defined in a nested way, keeping the code more readable and organized. I used screen-size variables for easy responsive adjustments without needing to alter code directly in multiple places.

### Quebra de Colunas na Seção Produtos | Column Break in Product Section

Implementei uma divisão de colunas na seção de produtos, utilizando media queries para controlar o layout de acordo com o tamanho da tela. Essa divisão melhora a visualização e usabilidade do projeto, tornando-o mais amigável em dispositivos móveis.

I implemented a column layout in the product section, using media queries to control the layout based on screen size. This layout improves project display and usability, making it more mobile-friendly.

## 📂 Estrutura do Projeto | Project Structure

O projeto está dividido em arquivos menores de LESS para organizar melhor o código. Cada seção possui seu próprio arquivo, que é importado no arquivo principal de estilos, garantindo uma estrutura modular e fácil de manter.

The project is divided into smaller LESS files for better code organization. Each section has its own file, which is imported into the main styles file, ensuring a modular and easy-to-maintain structure.

## 🛠️ Tecnologias Utilizadas | Technologies Used

- HTML5
- CSS3
- LESS

## 🚀 Como Utilizar | How to Use

1. Clone o repositório e altere para a branch `exercicio_less`:
   ```bash
   git clone -b exercicio_less https://github.com/Cieliocas/exercicio_less.git
