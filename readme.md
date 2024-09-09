# Sistema de Gerenciamento Escolar

Este projeto implementa um sistema simples de gerenciamento de alunos, cursos e notas utilizando um banco de dados MySQL.

## Passos para Configuração

1. **Criar o banco de dados**:
    - Execute o comando SQL para criar o banco de dados `Escola` e as tabelas `Alunos`, `Cursos` e `Notas`.

2. **Inserir dados**:
    - Utilize os comandos de `INSERT INTO` para adicionar dados nas tabelas de `Alunos`, `Cursos` e `Notas`.

3. **Consultas**:
    - Foram incluídas consultas para calcular a média das notas por curso e para listar o aluno com a maior nota em cada curso.

4. **Atualizações**:
    - Existem exemplos de atualizações de dados, como alteração da nota de um aluno e do endereço de outro.

5. **Exclusões**:
    - O projeto inclui comandos para excluir um aluno e suas notas associadas, além de excluir um curso e suas notas associadas.

## Estrutura do Banco de Dados

- **Tabela Alunos**:
    - id_aluno (INT, PK)
    - nome (VARCHAR)
    - data_nascimento (DATE)
    - endereco (VARCHAR)

- **Tabela Cursos**:
    - id_curso (INT, PK)
    - nome_curso (VARCHAR)
    - descricao (TEXT)

- **Tabela Notas**:
    - id_nota (INT, PK)
    - id_aluno (FK)
    - id_curso (FK)
    - nota (DECIMAL)

## Requisitos

- **MySQL**: Para rodar os comandos SQL e gerenciar o banco de dados.

## Como Executar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```
2. Acesse o diretório:
    ```bash
    cd nome-do-repositorio
    ```
3. Importe o arquivo SQL no seu banco de dados MySQL.

4. Execute as consultas e alterações conforme necessário.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
