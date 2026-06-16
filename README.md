# FinanSee

## Objetivo do Sistema
FinanSee é uma aplicação web desenvolvida para auxiliar no gerenciamento financeiro e orçamentário pessoal. Em um cenário econômico frequentemente incerto, onde a busca por estabilidade financeira é constante, o FinanSee surge como uma solução eficaz e intuitiva. Nosso objetivo é capacitar os usuários a controlar suas finanças de maneira organizada, prática e segura, facilitando o alcance de metas financeiras e promovendo a educação financeira.

## Descrição do Problema
A gestão financeira pessoal da maior parte da população pode ser considerada descentralizada e predominantemente analógica, agravado por falta de uma educação financeira formal oferecida na educação básica. Os métodos de controle tradicionais, como cadernos físicos, folhas de cálculo manuais acabam sendo pouco intuitivos quando é necessário um nível de disciplina elevado além de não providenciar uma análise direta dos gastos e o que pode ser melhorado.

## Principais Funcionalidades
- RF-1 (Gestão de Acesso Seguro): Criação de contas seguras com validação rigorosa de credenciais (Nome, E-mail, CPF, Telefone, Senha, Renda e Data de Nascimento) e controle de Login/Logout. 
- RF-2 (Gestão de Perfil): Visualização, atualização cadastral e remoção irreversível de contas por parte do utilizador. 
- RF-3 (Controle de Despesas): Registo manual, visualização detalhada, atualização e eliminação de despesas (contendo Nome, Categoria, Valor, Descrição, Data e Status da conta). 
- RF-4 (Categorização Flexível): Criação, edição, listagem, pesquisa e remoção de categorias únicas para a arrumação e organização personalizada dos gastos. 
- RF-5 (Painel Visual e Resumos): Exibição dinâmica de gráficos de resumo de despesas periódicas, cálculo automatizado do gasto mensal acumulado e monitorização de saldo líquido (Renda menos Gastos). 
- RF-6 (Exportação de Dados): Extração de relatórios estruturados do resumo mensal contendo nome, categoria, valor e status das despesas em formato PDF.
- RF-7 (Ciclo de Períodos): Criação automática de novos períodos operacionais a cada início de mês e reajustes dinâmicos de saldo mediante novas transações. 

- RNF-1 (Acessibilidade Universal): Garantir que a aplicação web seja totalmente responsiva e acessível a partir de qualquer dispositivo conectado à Internet.
## Tecnologias Utilizadas 🛠
O FinanSee é desenvolvido utilizando as seguintes tecnologias:

- Backend:
    - [Python3](https://www.python.org/)
    - [Django](https://www.djangoproject.com/)
    - [Django Rest Framework](https://www.django-rest-framework.org/)
- Frontend:
    - [Next.js](https://nextjs.org/)
- Banco de dados:
    - [Postgresql](https://www.postgresql.org/)
- Diagramação:
    - [PlantUML](https://plantuml.com/)
    - [BRMW](https://www.brmodeloweb.com/)
    - [Lucidchart](https://www.lucidchart.com/pages/pt)

## Estrutura do Projeto
### Navegação de Pastas
```
FinanSee/
├── Front/              # Aplicação frontend (Next.js)
│   ├── pages/          # Páginas da aplicação
│   ├── components/     # Componentes reutilizáveis
│   └── ...
├── backend/            # API backend (Django + DRF)
│   ├── api/            # Endpoints da API REST
│   ├── models/         # Modelos de dados
│   ├── views/          # Lógica das views
│   └── ...
├── documents/          # Documentação e diagramas
│   └── *.puml          # Diagramas PlantUML, BRMW e Lucidchart
├── logo/               # Assets de identidade visual
│   └── logo.svg
├── .gitignore
├── LICENSE
└── README.md
```
###  Fluxo Básico de Funcionamento
```
Usuário
 ↓
Frontend (Next.js)
 ↓
API REST (Django REST Framework)
 ↓
Banco de Dados
```

## Instruções de Execução
O projeto conta com um script de inicialização automatizada (start.bat) compatível com *Windows*. Ele gerencia tanto a instalação das dependências quanto a execução dos ambientes de Frontend e Backend simultaneamente. O sistema foi implementado diretamente como MVP funcional, substituindo a necessidade de um protótipo separado. A aplicação permite a navegação entre as principais funcionalidades previstas nos requisitos do projeto.

### 🔹 No Windows (Via Script Automatizado)
1. Abra o prompt de comando (CMD) e navegue até a pasta raiz do projeto:
```bash
   cd FinanSee
```
Execute o arquivo de inicialização:
start.bat

## Integrantes da Equipe
| Nome | Github |
|---|---|
|CARLOS DANNIEL GONÇALVES DA SILVA|[@cdanniel2002](https://github.com/cdanniel2002)
|LEONARDO AUGUSTO SILVA DE SOUSA|[@LeonardAugusto](https://github.com/LeonardAugusto)
|PEDRO CARLOS LIMA PAIVA|[@PedroCarlos30](https://github.com/PedroCarlos30)
|SAMUEL IAGO DE FARIAS CABRAL|[@samuelIago](https://github.com/samuelIago)

## Status de Desenvolvimento
| Funcionalidade | Status | Descrição |
|---|:---:|---|
| Cadastro e autenticação | 🟢 Concluído | Login, registro e controle de sessão |
| Registro de transações | 🟢 Concluído | Lançamento de receitas e despesas |
| Categorização | 🟢 Concluído | Agrupamento por tipo de gasto |
| Dashboard financeiro | 🟢 Concluído | Resumo visual das finanças |
| Metas financeiras | 🟢 Concluído | Definição e acompanhamento de objetivos |
| Relatórios e gráficos | 🟢 Concluído | Visualizações e exportação de dados |
