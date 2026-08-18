# miniguia-estudos-notebooklm
Este projeto constrói um Caderno Temático (Hands-on Cookbook) no NotebookLM para consulta rápida de comandos e sintaxes em AlgorithmsNotesForProfessionals, GitNotesForProfessionals, MongoDBNotesForProfessionals, MySQLNotesForProfessionals, SQLNotesForProfessionals e PythonNotesForProfessionals. O repositório centraliza guias práticos, documenta o processo de Engenharia de Prompts (troubleshooting) e entrega um miniguia de estudos para acelerar o desenvolvimento no dia a dia.


**Contexto e Objetivos**

Tema do Caderno Temático: Desenvolvido como um Hands-on Cookbook (guia prático de receitas) com foco em consultas rápidas e comandos operacionais para o dia a dia de desenvolvimento.

Objetivo de Aprendizagem: Utilizar o NotebookLM para centralizar e sintetizar o conhecimento das principais ferramentas de desenvolvimento em um só lugar. O objetivo é reduzir o tempo de busca por sintaxes e fluxos de trabalho comuns em Algoritmos, Git, MongoDB, MySQL e SQL padrão.

Aplicação Prática: Servir como um material de referência rápida durante a escrita de código, focando em comandos práticos, queries otimizadas e resolução rápida de erros de sintaxe (troubleshooting).

**Curadoria de Fontes**

Para alimentar a base de conhecimento do NotebookLM e garantir respostas precisas, foram selecionados 5 materiais de referência técnica em formato PDF e texto aberto:

**AlgorithmsNotesForProfessionals:** Documentação/PDF sobre lógica de programação, estruturas condicionais (if/else), laços de repetição (for/while) e funções.

**GitNotesForProfessionals:** Guia de comandos práticos para controle de versão, abordando fluxos de trabalho locais (staging, commit, branch) e remotos (push, pull, merge).

**MongoDBNotesForProfessionals (NoSQL):** Guia em PDF sobre bancos não relacionais, focado na sintaxe de operações CRUD e manipulação de documentos BSON/JSON.

**MySQLNotesForProfessionals Reference Manual:** Documentação sobre o banco relacional MySQL, focando na sintaxe de criação de tabelas, índices e tipos de dados nativos.

**SQLNotesForProfessionals (Guia Padrão de Consultas):** Material focado em comandos SQL padrão (SELECT, INSERT, UPDATE, DELETE, JOINs e funções de agregação) para consultas em bancos relacionais.

**PythonNotesForProfessionals:** Documentação e guia em PDF sobre a linguagem Python, focando em estruturas de dados, funções, sintaxe básica e recursos avançados para desenvolvimento.

**Engenharia de Prompts e "Cicatrizes"**

Nesta seção, está documentado como foram ajustados os prompts do NotebookLM para extrair respostas precisas e operacionais a partir das fontes fornecidas.

Prompt Inicial (Testado): "Como fazer buscas em banco de dados e comandos no Git?"

Resultado Obtido: A IA misturou conceitos teóricos de bancos relacionais e não relacionais sem fornecer comandos práticos diretos.

Cicatriz / Dificuldade: Respostas genéricas demais, sem código pronto para cópia rápida (copy-paste).

Prompt (Estratégico): "Atue como um Guia Prático para Desenvolvedores. Com base estritamente nas fontes, crie um passo a passo em blocos de código com a sintaxe exata para: 1. Criar uma query SQL no MySQL com WHERE e ORDER BY; 2. Realizar a mesma consulta no MongoDB; 3. Commitar e enviar as alterações via Git."

Resultado Obtido: Respostas diretas no estilo Cookbook, separadas por sintaxe exata de cada tecnologia.

Refatoração Aplicada: Adição de restrições de formato (ex: "Responda apenas com sintaxe e exemplos curtos") para evitar explicações teóricas longas.

**Miniguia de Estudo**

**1. Resumos estruturados do assunto;**

Lógica e Algoritmos: Conceitos fundamentais de controle de fluxo, estruturas condicionais e laços de repetição aplicados à resolução de problemas operacionais.

Controle de Versão (Git): Fluxo prático de trabalho local e remoto, abordando inicialização, staging (git add), commit (git commit), criação de branches (git branch) e envio (git push).

Bancos de Dados Relacionais (SQL / MySQL): Consultas estruturadas utilizando comandos padrão (SELECT, INSERT, UPDATE, DELETE), junção de tabelas (JOIN) e filtragem condicional (WHERE).

Bancos de Dados Não Relacionais (MongoDB): Operações de CRUD em documentos JSON/BSON utilizando funções nativas (find(), insertOne(), updateMany(), deleteOne()).

Linguagem Python: Fundamentos da linguagem, manipulação de estruturas de dados (listas, dicionários, tuplas), sintaxe básica, criação de funções e recursos avançados para desenvolvimento.


**2. Um glossário com os principais conceitos aprendidos;**

Algoritmo: Sequência finita de instruções lógicas estruturadas para resolver um problema.

Commit: Registro de alterações gravado no histórico do repositório Git.

CRUD: Acrônimo para Create, Read, Update e Delete (Operações básicas de manipulação de dados).

Documento (NoSQL): Estrutura de armazenamento de dados flexível usada no MongoDB, equivalente a uma linha em tabelas relacionais.

Primary Key (PK): Chave única utilizada em bancos de dados relacionais para identificar um registro de forma exclusiva.

Python: Linguagem de programação de alto nível, interpretada e com tipagem dinâmica, focada em legibilidade de código e versatilidade.

**3. Um conjunto de prompts reutilizáveis que possam apoiar futuras revisões sobre o tema;**

Prompt de Consulta Rápida (Syntax Lookup): "Mostre a sintaxe exata para [AÇÃO, ex: criar um índice] no [TECNOLOGIA, ex: MySQL] baseado nas fontes fornecidas."

Prompt Comparativo (SQL vs NoSQL): "Compare como a operação [AÇÃO] é realizada em SQL padrão versus MongoDB, listando as diferenças de sintaxe em formato de tabela."

Prompt de Resolução de Erros (Debugging): "Quais são os erros mais comuns citados na fonte ao executar [COMANDO/CONCEITO] e qual é o passo a passo para solucioná-los?"

Prompt de Idiomas e Funções em Python (Python Lookup): "Com base na documentação do Python, explique o funcionamento e forneça um exemplo prático da função ou estrutura [CONCEITO/FUNÇÃO, ex: list comprehension, decorators ou dict.get()]."
