
# InPETU Java Backend

## Sobre o projeto

O **InPETU Java Backend** é um projeto acadêmico desenvolvido com Java, com o objetivo de implementar a lógica de funcionamento de um sistema de gerenciamento de espaços e agendamentos do InPETU Hub.

O sistema permite realizar operações de cadastro, consulta, edição e listagem de contatos, espaços e agendamentos, aplicando regras de negócio para garantir a consistência das informações.

## Funcionalidades

### Contatos
- Cadastrar contatos.
- Consultar contato pelo ID.
- Editar informações de um contato.
- Listar todos os contatos.
- Impedir o cadastro de contatos com IDs duplicados.
- Impedir a alteração do ID de um contato.

### Espaços
- Cadastrar espaços.
- Consultar espaço pelo ID.
- Editar informações de um espaço.
- Listar todos os espaços.
- Impedir o cadastro de espaços com IDs duplicados.
- Impedir a alteração do ID de um espaço.
- Impedir a exclusão de espaços que possuem agendamentos vinculados.

### Agendamentos
- Cadastrar agendamentos vinculados a contatos e espaços existentes.
- Consultar agendamento pelo ID.
- Editar informações de um agendamento.
- Listar todos os agendamentos.
- Impedir o cadastro de agendamentos com contatos ou espaços inexistentes.
- Verificar conflitos de horários.
- Impedir agendamentos duplicados para o mesmo contato ou espaço no mesmo período.
- Impedir a alteração do ID de um agendamento.

## Tecnologias utilizadas

- **Java:** linguagem utilizada no desenvolvimento do backend.
- **IntelliJ IDEA:** ambiente de desenvolvimento.
- **Git e GitHub:** controle de versão e compartilhamento do código.
