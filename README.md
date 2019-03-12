# Teste de PHP
OBEJTIVO

Criar um sistema simples de controle de usuário, utilizando PHP, sem a utilização de nenhum framework, onde será possível Criar/Editar/Excluir/Listar usuários.

O sistema também deve possuir a possibilidade de vincular/desvincular várias cores ao usuário.

BANCO DE DADOS

A estrutura abaixo será utilizada para armazenar os dados, podendo ser alterada a qualquer momento para melhor funcionamento do sistema:

    usuário: root
    senha: testePHP
    db: testePHP
    IP: 192.168.10.
    host: localhost
    
    tabela: users
        id      int not null auto_increment primary key
        name    varchar(100) not null
        email   varchar(100) not null

    tabela: colors
        id      int not null auto_increment primary key
        name    varchar(50) not null

SERVIDOR

Crie uma pasta com seu nome e coloque todos os arquivos dentro e envia por SCP utilizando as informações a seguir:
    
    usuário: testephp
    senha: phprocks
    IP: 192.168.10.
    pasta: /home/testephp

INÍCIO

Utilize PDO para conexão e interação com o banco de dados.

BOA SORTE

Use seu conhecimento, consulte a documentação e o google, caso ainda houver dúvidas, só gritar!
