Descrição

Este é um aplicativo simples de login em Android, onde os usuários podem inserir seu nome de usuário e senha para fazer login. O aplicativo valida as credenciais inseridas pelo usuário comparando-as com uma lista predefinida de pares de nome de usuário e senha. Se as credenciais forem válidas, o usuário é redirecionado para uma segunda atividade.

Funcionalidades Principais

Entrada de nome de usuário e senha.
Validação das credenciais.
Exibição de mensagem de erro em caso de credenciais inválidas.
Adição de novos usuários e senhas.
Estrutura do Código

O código está dividido em duas atividades principais:

MainActivity
Esta é a atividade principal do aplicativo, onde os usuários podem inserir suas credenciais de login. Se as credenciais forem válidas, eles serão redirecionados para a SecondActivity. Caso contrário, uma mensagem de erro será exibida.

SecondActivity
Nesta atividade, os usuários podem adicionar novos usuários e senhas, que serão então adicionados à lista de usuários válidos. Esses novos usuários e senhas serão verificados durante o login subsequente.

Testes
O aplicativo inclui testes unitários simples para garantir que a lógica subjacente funcione corretamente.
