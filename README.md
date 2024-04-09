# tolerancia_falhas_com_postegres


# Sistema de Tolerância a Falhas com PostgreSQL

Este repositório contém um projeto prático para a disciplina de Tolerância a Falhas, focado na implementação de um sistema de banco de dados com alta disponibilidade e recuperação de falhas usando PostgreSQL.

## Descrição

O projeto utiliza Docker para configurar um ambiente de banco de dados com uma instância primária do PostgreSQL e uma réplica, para demonstrar conceitos de tolerância a falhas e recuperação de desastres.

## Pré-requisitos

Para executar este projeto, você precisará ter o Docker e o Docker Compose instalados em sua máquina. As instruções de instalação podem ser encontradas na [documentação oficial do Docker](https://docs.docker.com/get-docker/).

## Estrutura de Arquivos

- `docker-compose.yml`: Arquivo de configuração do Docker Compose para inicializar as instâncias do PostgreSQL.
- `00_init.sql`: Script SQL para inicialização do banco de dados primário.
- `config`: Arquivo de configuração adicional (descrever uso conforme necessário).
- `test`: Arquivo para testes (descrever uso conforme necessário).

## Configuração e Execução

1. Clone este repositório para sua máquina local.

2. Navegue até o diretório do projeto e execute o seguinte comando para iniciar as instâncias do banco de dados:



3. Para verificar o estado dos contêineres, use:



4. (Incluir mais instruções conforme necessário para interação com o sistema ou execução de testes.)

## Contribuições

Este projeto é parte de uma atividade acadêmica. Contribuições e feedback são bem-vindos através de issues ou pull requests.

## Licença

(Defina uma licença ou declare como de domínio público, conforme apropriado para seu caso.)

## Contato

- Nome do Aluno: Gustavo Garcia Pereira
- E-mail: gusgurtavo@gmail.com
- Instituição: UFN

---

