# Test Case Backend - Perfect Flight

Olá, parabéns por chegar até aqui. O próximo passo é um caso de teste técnico com foco em backend. Crie um repositório em sua conta do GitHub, com a solução proposta logo abaixo.

## Proposta

Crie uma REST API para realizar o cadastro de usuários com o objetivo de enviar notícias diárias sobre tecnologia via e-mail.

O cadastro deve ser feito exclusivamente através do usuário do Github, então integrar com a [API do Github](https://docs.github.com/pt/rest) será fundamental para buscar os dados deste usuário (nome, email, avatar, etc).

Usuários do Github que não tiverem um e-mail disponível, vão precisar informar o e-mail durante o cadastro. Não deve ser permitido cadastrar um usuário sem e-mail.

Deve ser possível criar, atualizar, listar, buscar por e-mail e deletar usuários.

Os dados necessários devem ser pelo menos:

- Email
- Nome
- Avatar (URL da Foto)

Utilizar bancos de dados relacionais e/ou não relacionais é opcional (do mais simples possível, utilize o armazenamento em memória).

A escolha da arquitetura e uso de bibliotecas e frameworks também fica ao seu critério.

Testes unitários e/ou de integração devem estar presentes juntos ao projeto.

### Desafio Extra (Opcional)

Para complementar este projeto, crie uma tarefa agendada que execute uma vez ao dia, selecione todos os e-mails dos usuários disponíveis na base e envie um e-mail com um assunto e corpo aleatório. O serviço de e-mail também pode ser em memória :)

## Dúvidas

Abra um [problema](https://github.com/perfect-flight/test-case-backend/issues/new) que responderemos o mais rápido possível.
