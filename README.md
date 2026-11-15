# Sorteador de números

Site responsivo de sorteio de números, desenvolvido com HTML,
CSS e JavaScript, seguindo um design existente no Figma.

## 1. Estrutura inicial

- Criar o arquivo `index.html` com a estrutura HTML padrão.
- Criar o arquivo `style.css` para os estilos da página.
- Vincular o `style.css` ao `index.html`.
- Configurar a estrutura das seções principais.

## 2. Estrutura da página

- Conter um título principal.
- Ter uma seção explicando como o sorteador funciona.
- Ter uma área para o usuário inserir:
  - A quantidade de números a serem sorteados.
  - O valor mínimo do intervalo.
  - O valor máximo do intervalo.
- Oferecer a opção de não repetir números.

## 3. Funcionalidades principais

- Permitir que o usuário informe a quantidade de números.
- Permitir que o usuário informe os valores mínimo e máximo.
- Ter um botão "Sortear" que exiba os números sorteados.
- Impedir números repetidos quando a opção de não repetir
  estiver ativada.

## 4. Validações do formulário

- Não permitir campos vazios.
- O valor máximo deve ser maior que o valor mínimo.
- Quando a opção de não repetir estiver marcada, a quantidade
  solicitada não pode ser maior que o intervalo disponível.
- Exibir mensagens de erro amigáveis quando essas condições
  não forem atendidas.

## 5. Exibição dos resultados

- Exibir os números sorteados de forma clara e organizada.
- Criar uma animação para o sorteio dos livros.
- Atualizar o resultado a cada novo sorteio.