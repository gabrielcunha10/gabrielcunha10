# Olá, eu sou Gabriel

Sou estudante de Ciência da Computação, com interesse em desenvolvimento backend, análise de dados e bancos de dados. Atualmente estou aprofundando meus estudos em Python, SQL, estatística e ferramentas voltadas para ciência de dados.

## Iniciação Científica e Experiência Acadêmica

| Atuação / Projeto                                                  | Período                        | Área                           | Principais Atividades                                                                                                                                                                                             |
| :------------------------------------------------------------------- | :------------------------------ | :------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **LAPIS** — Laboratório de Pesquisa e Inovação em Sistemas | Agosto de 2026 – Atual         | Engenharia de Software          | Atuação em Iniciação Científica (IC) com foco em pesquisa, inovação e desenvolvimento em Engenharia de Software                                                                                            |
| **AgendaCT** (UFPB)                                            | Março de 2026 – Julho de 2026 | Gerenciamento de Banco de Dados | Desenvolvimento e manutenção de funcionalidades utilizando Laravel e SQLite, modelagem e gerenciamento de banco de dados e testes e validações para identificação e correção de erros e inconsistências. |

## Sobre mim

* Estudante de Ciência da Computação
* Atuação em Iniciação Científica no laboratório LAPIS (UFPB)
* Estudando Python com foco em dados e backend
* Interesse em Análise de Dados e Ciência de Dados
* Conhecimento em bancos de dados relacionais e não relacionais
* Desenvolvendo projetos acadêmicos e pessoais para fortalecer meu portfólio

## Tecnologias e ferramentas

<div>
  <img src="https://skillicons.dev/icons?i=python,java,php,laravel,sqlite,mysql,postgresql,mongodb,html,css,js,bootstrap,git,github,vscode" />
  <img src="https://raw.githubusercontent.com/microsoft/PowerBI-Icons/main/SVG/Power-BI.svg" width="48" height="48" alt="Power BI" title="Power BI" />
  <img src="https://cdn.simpleicons.org/googlegemini/8E75B2" width="48" height="48" alt="Google Gemini" title="Google Gemini" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuresqldatabase/azuresqldatabase-original.svg" width="48" height="48" alt="SQL" title="SQL" />
</div>

## Atualmente estudando

* Python para análise de dados
* Estatística aplicada
* SQL e modelagem de banco de dados
* PostgreSQL e MySQL
* MongoDB
* Fundamentos de backend
* Git e GitHub

## Projetos em destaque

### Pipeline de Dados e Analytics — Programa de Gestão de Desempenho (PGD) INSS

[Repositório no GitHub](https://github.com/gabrielcunha10/inss-pgd-data-pipeline) | [Dashboard no Power BI](https://app.powerbi.com/view?r=eyJrIjoiMjNlNzBmOWQtMzVlNC00MjBhLTk0MDEtYTBhZThiZWYyNTAwIiwidCI6IjhjODgwZTJhLTM2MDAtNDVmZi1hZDM5LWJhMDRlZGM4MWYyNSJ9&pageName=bcd18bc650e27d173dae)

Pipeline de Engenharia de Dados e Analytics ponta a ponta que automatiza a ingestão contínua de microdados abertos do governo federal via API pública, executa limpeza, enriquecimento e padronização com Python/Pandas, carrega a base consolidada em um banco relacional em nuvem (**PostgreSQL no Neon Tech**) e mantém um dashboard interativo no **Power BI** atualizado de forma autônoma via **GitHub Actions** e **Power Automate**.

O projeto analisa o histórico do Programa de Gestão e Desempenho (PGD) aplicado ao quadro de atendimento do INSS, cobrindo mais de 650 mil registros consolidados desde outubro de 2023.

**Principais etapas e funcionalidades:**

* Ingestão incremental automatizada de microdados abertos via API pública CKAN
* Pipeline de ETL com tratamento de encodings, mapeamento dinâmico de mais de 30 variantes de cabeçalhos e aplicação de pontes temporais determinísticas
* Anonimização criptográfica com HMAC-SHA256 para conformidade com a LGPD
* Garantia de qualidade com 29 testes automatizados em Pytest seguindo o padrão Write-Audit-Publish (WAP)
* Modelagem e carga transacional idempotente em lotes no PostgreSQL Serverless (Neon Tech)
* Orquestração desacoplada com Prefect 3 e GitHub Actions
* Atualização automatizada do modelo semântico via Webhook no Power Automate e Power BI Service
* Geração autônoma de relatórios e insights executivos MoM utilizando a API do Google Gemini
* Captura automatizada de telas em alta resolução com Playwright headless e validação de integridade por hash SHA-256

**Tecnologias e ferramentas utilizadas:**

<div>
  <img src="https://skillicons.dev/icons?i=python,postgresql,docker,githubactions" />
  <img src="https://raw.githubusercontent.com/microsoft/PowerBI-Icons/main/SVG/Power-BI.svg" width="48" height="48" alt="Power BI" title="Power BI" />
  <img src="https://cdn.simpleicons.org/googlegemini/8E75B2" width="48" height="48" alt="Google Gemini" title="Google Gemini" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuresqldatabase/azuresqldatabase-original.svg" width="48" height="48" alt="SQL" title="SQL" />
</div>

* Python (Pandas, Pytest, Playwright, Prefect)
* SQL / PostgreSQL (Neon Tech)
* Docker
* GitHub Actions
* Power BI & Power Automate
* Google Gemini API (GenAI)

**Destaque do projeto:**
Construção de uma solução completa de engenharia e análise de dados para o setor público, integrando ingestão resiliente via API, governança, segurança com LGPD, testes de qualidade, banco em nuvem, orquestração automatizada e inteligência analítica em dashboard executivo.

---

### Desafio Final Workshop 2026.1 — Fábrica de Software

Projeto desenvolvido no Desafio Final do Workshop 2026.1 da Fábrica de Software, simulando um fluxo real de desenvolvimento de uma solução baseada em dados.

O desafio teve como objetivo aplicar, de forma prática, conhecimentos de modelagem de banco de dados, SQL, análise de dados com Python, Machine Learning e criação de dashboards no Power BI.

O cenário proposto foi a construção de uma solução para a concessionária fictícia **VelozCar**, voltada ao controle de aluguel de veículos, clientes, pagamentos e manutenções.

**Resultado:**
Projeto avaliado com **nota máxima**, demonstrando domínio das etapas propostas e boa aplicação prática dos conceitos trabalhados.

**Principais etapas do projeto:**

* Modelagem conceitual e lógica do banco de dados
* Criação de schema e tabelas no MySQL
* Definição de chaves primárias, estrangeiras e restrições
* Inserção, atualização e consulta de dados com SQL
* Consultas com agregações e JOINs
* Análise de dados com Python
* Tratamento de dados, criação de gráficos e análise estatística
* Treinamento de modelo de classificação com Machine Learning
* Criação de dashboard no Power BI
* Geração de insights e conclusões a partir dos dados

**Tecnologias e ferramentas utilizadas:**

<div>
  <img src="https://skillicons.dev/icons?i=mysql,python" />
  <img src="https://raw.githubusercontent.com/microsoft/PowerBI-Icons/main/SVG/Power-BI.svg" width="48" height="48" alt="Power BI" title="Power BI" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuresqldatabase/azuresqldatabase-original.svg" width="48" height="48" alt="SQL" title="SQL" />
</div>

* BRModelo
* MySQL
* Python
* pandas
* numpy
* matplotlib
* scikit-learn
* Power BI

**Destaque do projeto:**
Integração de diferentes etapas de um projeto de dados, desde a modelagem e estruturação do banco até a análise, aplicação de Machine Learning e visualização dos resultados em dashboard.

---

### Barbearia Paladinos

Sistema web desenvolvido em PHP para auxiliar na organização dos agendamentos e atendimentos da Barbearia Paladinos.

O projeto foi desenvolvido como parte de uma ação extensionista, a partir da identificação de uma necessidade real da barbearia: melhorar o controle de horários, reduzir conflitos de agendamento e facilitar o atendimento aos clientes. Antes da proposta, os agendamentos eram realizados principalmente por WhatsApp e ligações, o que dificultava o gerenciamento da agenda.

**Principais funcionalidades:**

* Cadastro e login de clientes
* Cadastro de barbeiros e serviços
* Agendamento de horários
* Controle de horários disponíveis e reservados
* Painel administrativo
* Gerenciamento de clientes, barbeiros, serviços e agendamentos
* Página de fale conosco
* Mensagem de confirmação após o agendamento
* Interface responsiva
* Banco de dados MySQL

**Tecnologias utilizadas:**

<div>
  <img src="https://skillicons.dev/icons?i=php,mysql,html,css,js,bootstrap" />
</div>

**Destaque do projeto:**
Aplicação prática de desenvolvimento web para resolver uma necessidade real de organização em um pequeno negócio, relacionando tecnologia, extensão universitária e melhoria da rotina de trabalho.

**ODS relacionado:**
ODS 8 — Trabalho decente e crescimento econômico.

---

## Contato

* LinkedIn: [Gabriel da Cunha Prudencio](https://br.linkedin.com/in/gabriel-da-cunha-prudencio-b21059359)
* Email: [gabrielcunha066@gmail.com](mailto:gabrielcunha066@gmail.com)
