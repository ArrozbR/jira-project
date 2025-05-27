# Swag Labs - Extensões e Melhorias

Este projeto é uma modificação e extensão da aplicação de demonstração "Swag Labs" da Sauce Labs. O objetivo principal é aprimorar a experiência do usuário inicial e adicionar funcionalidades comuns encontradas em aplicações web reais, como a criação de contas.

## User Stories Implementadas

Este projeto foca na implementação das seguintes User Stories:

1.  **US1: Remover a página de login como tela inicial para o usuário**
    * **Como um** novo usuário (ou usuário não autenticado/visitante),
    * **Eu quero** ser direcionado para uma página inicial pública (ou página de boas-vindas/exploração) ao invés da página de login quando acesso a aplicação pela primeira vez ou quando não estou logado,
    * **Para que** eu possa descobrir o que a aplicação oferece e explorar seu conteúdo público antes de precisar criar uma conta ou me autenticar.

2.  **US2: Criar uma funcionalidade para criação de conta dentro do Swag Labs**
    * **Como um** novo usuário que deseja utilizar o Swag Labs,
    * **Eu quero** poder me registrar e criar uma nova conta fornecendo as informações necessárias (como nome de usuário, senha e, opcionalmente, outros dados),
    * **Para que** eu possa ter credenciais de acesso válidas e, futuramente, simular o processo de compra e outras interações como um usuário autenticado na plataforma.

## Funcionalidades Principais

* **Página Inicial Pública:** Ao acessar a aplicação, usuários não autenticados são direcionados para uma página de boas-vindas/exploração em vez da tela de login.
* **Navegação para Login/Registro:** A partir da página inicial pública, os usuários podem facilmente navegar para as páginas de login ou registro.
* **Criação de Conta:** Implementada uma nova funcionalidade que permite aos usuários criar suas próprias contas para acessar o Swag Labs.
    * Formulário de registro com campos para nome de usuário e senha.
    * Validações básicas de formulário.
    * Simulação de persistência de conta (para fins de demonstração, pode ser em sessão ou localStorage).
* **Acesso Restrito:** Páginas que exigem autenticação continuam protegidas e redirecionam para o login se acessadas sem uma sessão ativa.