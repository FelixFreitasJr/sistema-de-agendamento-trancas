# Sistema de Agendamento para Trancistas
Este é um sistema de agendamento e gerenciamento de clientes, produtos e estoque, desenvolvido em React para uma trancista.

## Funcionalidades
- Agendamento de Clientes: Um fluxo simples e intuitivo para clientes solicitarem pré-agendamentos.

- Cálculo Dinâmico de Preços: O preço do serviço é ajustado automaticamente com base no tipo de trança, tamanho desejado e dia da semana.

- Painel do Administrador: Área restrita para a trancista gerenciar:

  - Configurações: Alterar o nome da empresa, logo e valor da hora.

  - Produtos: Adicionar, editar e remover tipos de tranças, com controle de materiais e margem de lucro.

  - Estoque: Gerenciar os materiais disponíveis.

  - Agendamentos: Visualizar, confirmar ou cancelar os pré-agendamentos dos clientes.

- Sistema de Armazenamento em Nuvem: Utiliza o Google Firestore para salvar todos os dados em tempo real.

## Como Executar o Projeto
Para visualizar e testar o sistema no seu computador, siga os passos abaixo:

1. Crie um arquivo chamado index.html e adicione o código de inicialização do React.

2. Crie um arquivo chamado App.js e cole todo o código do sistema neste arquivo.

3. Abra o arquivo index.html no seu navegador para ver a aplicação em funcionamento.

## Tecnologias Utilizadas
- React.js: Para a criação da interface de usuário.

- Tailwind CSS: Para o design e estilização responsivos.

- Firebase Firestore: Para o armazenamento de dados em tempo real.

## Próximos Passos
- Implementar a confirmação de agendamentos.

- Adicionar um painel de análise de lucro.

- Desenvolver funcionalidades de notificação.

Licença
Este projeto está sob a licença MIT.
