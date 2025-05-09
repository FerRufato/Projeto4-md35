# Projeto de Exemplo com JPA e Hibernate

Este é um projeto de exemplo que utiliza **Java**, **JPA** e **Hibernate** para gerenciar operações de persistência em um banco de dados **PostgreSQL**.

## Tecnologias Utilizadas

- **Java**
- **Maven** (para gerenciamento de dependências)
- **JPA** (Jakarta Persistence API)
- **Hibernate** (implementação do JPA)
- **PostgreSQL** (banco de dados relacional)

## Estrutura do Projeto

- `src/main/java`: Contém o código-fonte principal, incluindo as classes de domínio, DAOs e lógica de persistência.
- `src/test/java`: Contém os testes unitários para validar as funcionalidades do projeto.
- `src/main/resources/META-INF/persistence.xml`: Configuração do JPA e Hibernate.
- `bin/META-INF/persistence.xml`: Configuração alternativa para o JPA com Jakarta.

## Configuração do Banco de Dados

Certifique-se de que o **PostgreSQL** esteja instalado e configurado corretamente. O projeto utiliza as seguintes credenciais para conexão com o banco de dados:

- **URL**: `jdbc:postgresql://localhost:5432/loja`
- **Usuário**: `postgres`
- **Senha**: `admin`

Você pode alterar essas configurações no arquivo `persistence.xml`, localizado em `src/main/resources/META-INF`.

## Funcionalidades

O projeto implementa as seguintes funcionalidades:

1. **Gerenciamento de Clientes**:
   - Cadastrar, consultar, alterar, excluir e listar todos os clientes.
   
2. **Gerenciamento de Vendas**:
   - Cadastrar vendas, finalizar, cancelar e consultar vendas com coleções associadas.

## Como Executar

1. **Clone o repositório**:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_REPOSITORIO>
