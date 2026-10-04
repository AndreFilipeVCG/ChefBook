# Entrega 0 — Definição do Tema e Escopo

**Aluno:** André Filipe Vaz De Carvalhaes Gonzaga

---

## 1. Nome provisório do sistema

**ChefBook**

## 2. Tema do sistema

Sistema para montar um catálogo pessoal de receitas. O usuário pode cadastrar as próprias receitas ou buscar receitas prontas e salvá-las no catálogo. Depois, consegue organizar, pesquisar, filtrar e ordenar as receitas, além de marcar as favoritas e dar uma nota para cada uma.

## 3. Entidade principal

**Receita**

## 4. Principais informações da entidade

- **Nome:** nome da receita
- **Categoria:** prato principal, sobremesa, lanche ou bebida
- **Ingredientes:** lista com o nome e a quantidade de cada ingrediente
- **Modo de preparo:** passo a passo da receita
- **Tempo de preparo:** em minutos
- **Porções:** quantas pessoas a receita serve
- **Dificuldade:** fácil, média ou difícil
- **Imagem:** foto da receita
- **Nota:** avaliação pessoal de 1 a 5
- **Favorita:** se a receita está marcada como favorita
- **Origem:** se foi cadastrada manualmente ou importada da API

## 5. API pública utilizada

**Spoonacular API** — https://spoonacular.com/food-api

A API será usada para buscar receitas pelo nome ou por um ingrediente. O usuário poderá ver os detalhes de uma receita encontrada e importá-la para o seu catálogo. Assim, nome, imagem, ingredientes, tempo de preparo, porções e modo de preparo são preenchidos automaticamente.

---

## Como o sistema atende aos requisitos

- **Cadastrar um item:** formulário para criar uma nova receita
- **Visualizar os itens:** lista de receitas em cards, com imagem e nome
- **Ver detalhes:** página com todas as informações da receita
- **Editar:** alterar qualquer informação de uma receita salva
- **Excluir:** remover uma receita do catálogo
- **Pesquisar:** busca pelo nome da receita ou por ingrediente
- **Filtrar:** por categoria, dificuldade ou somente favoritas
- **Ordenar:** por nome, tempo de preparo ou nota
- **localStorage:** as receitas do catálogo ficam salvas no navegador
- **Recuperar dados:** ao abrir o site de novo, as receitas salvas aparecem
- **Consumir API:** busca de receitas na Spoonacular
- **Usar dados da API:** importar uma receita encontrada direto para o catálogo

---

## Telas previstas

1. **Início / Meu Catálogo** — lista das receitas salvas, com pesquisa, filtros e ordenação
2. **Detalhes da Receita** — informações completas, com opções de editar e excluir
3. **Cadastro / Edição** — formulário da receita
4. **Buscar Receitas** — busca na Spoonacular e opção de importar para o catálogo

