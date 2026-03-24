# Checkpoint 1

## Descrição

O projeto consiste em um aplicativo Android criado em Kotlin utilizando Jetpack Compose. Ele conta com navegação entre quatro telas: Login, Menu, Perfil e Pedidos.

## Objetivo da prova

A proposta é evoluir o projeto inicial aplicando conceitos de navegação entre telas, como o envio e o recebimento de parâmetros com a biblioteca Navigation Compose.

## Explicação de cada evolução implementada

1. Parâmetros obrigatórios na tela de Perfil: A tela passou a exigir o recebimento de um "nome" vindo do Menu para poder ser aberta.

2. Parâmetros opcionais na tela de Pedidos: A tela não precisa de dados para iniciar. Caso não receba um nome de cliente, exibe "Cliente Genérico".

3. Inserção de valor em parâmetro opcional: O botão do Menu foi ajustado para enviar um nome, substituindo o texto padrão "Cliente Genérico" na tela de Pedidos.

4. Passagem de múltiplos parâmetros: A tela de Perfil agora recebe duas informações simultaneamente (nome e idade) e apresenta ambas juntas.
