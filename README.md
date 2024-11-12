# Desafios do Projeto Pokémon com React

Este documento detalha os desafios principais deste projeto, que têm o objetivo de ensinar conceitos essenciais de React, como manipulação de estado, renderização condicional e componentização.

---

### Desafio 1: Carregar Pokémons na Renderização Inicial

- **Objetivo**: Implementar a funcionalidade de buscar e carregar a lista inicial de Pokémons quando a página é carregada pela primeira vez.
- **Descrição**: No hook `useEffect`, chame a função `getAllPokemons` com o valor de `limit`. Ao completar a chamada, atualize o estado dos Pokémons com os dados recebidos. Este desafio está indicado no comentário `// Desafio: Carregar pokemons`.

---

### Desafio 2: Componentizar o `PokemonCard`

- **Objetivo**: Criar um componente `PokemonCard` que receba as propriedades de cada Pokémon e exiba suas informações.
- **Descrição**: Na renderização da lista de Pokémons, utilize `PokemonCard` para exibir cada item, garantindo a reutilização do card em toda a aplicação. Este desafio está indicado no comentário `/* PokemonCard: Desafio */`.

---

### Desafio 3: Exibir a Quantidade de Pokémons Encontrados

- **Objetivo**: Mostrar ao usuário a quantidade de Pokémons listados após filtragem ou carregamento inicial.
- **Descrição**: Adicione uma função que conte o número atual de Pokémons no estado e exiba essa quantidade de forma dinâmica no layout. Este desafio está indicado no comentário `/* Desafio, exibir a quantidade de pokemons */`.

---

### Desafio 4: Carregar Mais Pokémons (Limit)

- **Objetivo**: Implementar a funcionalidade de “carregar mais” Pokémons, incrementando o limite de exibição e atualizando a lista ao clicar em um botão.
- **Descrição**: Crie a função `handleLoadMorePokemons` para aumentar o limite de busca (`limit`) ao ser acionada. Atualize o estado com os novos Pokémons carregados. Este desafio está indicado no comentário `// Desafio: Carregar limit de pokemons`.

---

### Desafio 5: Filtrar Pokémons por Tipos

- **Objetivo**: Permitir que o usuário filtre os Pokémons exibidos com base no tipo selecionado.
- **Descrição**: Utilize a função `handleFilterPokemonsByType` para buscar apenas os Pokémons que correspondam ao tipo escolhido pelo usuário e atualizar o estado da lista com os resultados filtrados. Este desafio está indicado no comentário `// Desafio: Filtrar pokemons por typos`.

---

### Desafio 6: Componentizar o `PokemonTypesCard`

- **Objetivo**: Componentizar o cartão de tipos de Pokémon, tornando cada tipo um componente reutilizável.
- **Descrição**: Crie o componente `PokemonTypesCard`, que recebe o nome e a imagem de cada tipo de Pokémon. Esse componente será usado para exibir os tipos no layout, facilitando a manutenção e personalização do código. Este desafio está indicado no comentário `/* Componetizar: Desafio - PokemonTypesCard */`.

---

Esses desafios estão organizados para construir uma aplicação React robusta e modular, promovendo aprendizado e práticas recomendadas de desenvolvimento de componentes. Boa codificação!
