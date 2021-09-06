# Comandos SQL Server

### Criar tabela:
CREATE TABLE [Nome da tabela](
[Nome da coluna] [Tipo de variavel] NOT NULL,
[Nome da coluna] [Tipo de variavel] NULL,
)

### Adicionar chave primaria:
ALTER TABLE [Nome da tabela] ADD CONSTRAINT [Nome da chave] PRIMARY KEY ([Nome da coluna]);
**Obs.: Para o nome da chave, é utilizado PK_[NomeDaTabela]**
**Obs.: A chave primaria pode ser composta, necessitando colocar uma virgula para separar as colunas**

### Adicionar chave estrangeira:
ALTER TABLE [Nome da tabela] ADD CONSTRAINT [Nome da chave] FOREIGN KEY([Nome da coluna])
REFERENCES [Nome da tabela de referencia] ([Nome da coluna da tabela de referencia])
**Obs.: Para o nome da chave, é utilizado FK_[NomeDaTabela]_[NomeDaTabelaDeReferencia]**

### Adicionar valor padrão:
Em uma coluna com valor booleano, é possível colocar um valor padrão caso não informado, 0 para false e 1 para true:
ALTER TABLE [Nome da tabela] ADD CONSTRAINT [Nome da chave] DEFAULT ([valor booleano]) FOR [Nome da coluna]

### Comando GO
Serve para mudar seção

### Tipos de variáveis:
int = inteiros;  
float = variaveis flutuantes;  
varchar([Quantidade de caracteres]) = strings;  
bit = valor booleano;  