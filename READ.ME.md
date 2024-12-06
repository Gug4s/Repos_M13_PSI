# PSI_M13_REPOSITORIO
Repositório do Módulo 13 

Dentro deste READ.ME vou documentar o código do repositório, que neste caso foi a biblioteca SQLite3, que por si é uma versão mais leve da linguagem de programação SQL (Structured Query Language), contudo, esta versão do SQL armazena os dados dentro de um ficheiro binário, de modo a tornar os dados mais compactos e mais simples, sendo normalmente utilizada em aplicações/programas leves e com poucos dados ou dados pouco importantes. 

# Estrutura do Repositório

epbjc/
├── src/
│   ├── app/
│   │   └── main.py                                   # Criação das tabelas: 'alunos','materiais' e 'professores'.
│   ├── create/
│   │   ├── alunos_create.py                          # Query INSERT para inserir dados na tabela 'alunos', foi usada a biblioteca "random" para inserir dados aleatórios como exemplos dentro da Base de Dados.
│   │   ├── materiais_create.py                       # Query INSERT para inserir dados na tabela 'materiais', foi usada a biblioteca "random" para inserir dados aleatórios como exemplos dentro da Base de Dados.
│   │   └── professores_create.py                     # Query INSERT para inserir dados na tabela 'professores', foi usada a biblioteca "random" para inserir dados aleatórios como exemplos dentro da Base de Dados. 
│   ├── read/
│   │   ├── alunos_read.py                            # Query SELECT para extrair dados na tabela 'alunos'.
│   │   ├── materiais_read.py                         # Query SELECT para extrair dados na tabela 'materiais'. 
│   │   └── professores_read.py                       # Query SELECT para extrair dados na tabela 'professores'.
│   ├── update/
│   │   ├── alunos_update.py                          # Query UPDATE para atualizar dados na tabela 'alunos', porém não foi utilizada.
│   │   ├── materiais_update.py                       # Query UPDATE para atualizar dados na tabela 'materiais', porém não foi utilizada. 
│   │   └── professores_update.py                     # Query UPDATE para atualizar dados na tabela 'professores', porém não foi utilizada.
│   └── delete/
|       ├── alunos_delete.py                          # Query DELETE para apagar dados na tabela 'alunos'.
|       ├── materiais_delete.py                       # Query DELETE para apagar dados na tabela 'materiais'.
|       └── professores_delete.py                     # Query DELETE para apagar dados na tabela 'professores'.
├── sqlite-database/
│   ├── epbjc.db                                      # Base de Dados principal para guardar as tabelas criadas, porém não foi possível conectar a esta base de dados, e então foi criada outra base de dados denominada 'epbjc.db'.
│   ├── epbjc_backup_1.db                             # Primeiro backup da Base de Dados, porém não foi usado.
│   ├── epbjc_backup_2.db                             # Segundo backup da Base de Dados, porém não foi usado.
│   └── epbjc_backup_3.db                             # Terceiro backup da Base de Dados, porém não foi usado.
├── migracao/
│   ├── 
│   ├── 
│   ├── 
│   └── 
├── testes/
│   ├── 
│   ├── 
│   ├── 
│   └── 
└── README.md                                          # Ficheiro READ.ME dentro da pasta para documentar o código usado.
```


