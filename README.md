<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:C2185B,100:F06292&height=220&section=header&text=OFICINA%20MEC%C3%82NICA&fontSize=42&fontColor=FFFFFF&fontAlignY=38&desc=SAEP%20%E2%80%A2%20SENAI&descSize=20&descAlignY=60"
    width="100%"
    alt="Banner rosa Oficina Mecânica — SAEP / SENAI"
  >
</p>

<p align="center">
  <strong>✦ ORGANIZAÇÃO • GESTÃO • TECNOLOGIA ✦</strong>
</p>

<p align="center">
  Mais organização. Mais controle. Mais resultados.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-880E4F?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flask-AD1457?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/MySQL-C2185B?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/HTML5-D81B60?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-EC407A?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F8BBD0?style=for-the-badge&logo=javascript&logoColor=880E4F" alt="JavaScript">
</p>

---

## 🌸 Sobre o projeto

O **Oficina Mecânica** é um sistema web desenvolvido no contexto acadêmico do **SAEP / SENAI**, com o objetivo de facilitar o gerenciamento das atividades de uma oficina mecânica.

A aplicação utiliza Python no backend, páginas HTML na interface e MySQL para armazenar e organizar os dados, proporcionando uma estrutura para administrar clientes, veículos e agendamentos de serviços.

---

## 🎀 Funcionalidades

| Recurso | Descrição |
|---|---|
| 🔐 Autenticação | Login e controle de acesso por sessão |
| 👥 Clientes | Cadastro, consulta, edição e exclusão |
| 🚘 Veículos | Gerenciamento de veículos vinculados aos clientes |
| 📅 Agendamentos | Organização de serviços e datas |
| 📊 Dashboard | Visualização de informações gerais do sistema |
| 🗄️ Banco de dados | Persistência das informações utilizando MySQL |
| 🔒 Segurança | Hash de senhas com Bcrypt |

---

## 💗 Tecnologias utilizadas

- 💗 **Python:** linguagem utilizada no backend.
- 🌸 **Flask:** framework para criação da aplicação web.
- 💕 **MySQL:** banco de dados relacional.
- 🎀 **mysql-connector-python:** integração entre Python e MySQL.
- 💖 **Bcrypt:** geração e verificação de hashes de senhas.
- 🌷 **HTML5:** estrutura das páginas.
- 🌸 **CSS3:** estilização da interface.
- 💗 **JavaScript:** interatividade no frontend.
- 🎀 **Jinja2:** renderização dinâmica dos templates.

---

## 🗂️ Estrutura do projeto

```text
oficina/
├── __pycache__/
├── static/
│   ├── css/
│   ├── js/
│   └── img/
│       ├── banner.png
│       └── banner-oficina.png
├── templates/
│   ├── agendamentos.html
│   ├── base.html
│   ├── clientes.html
│   ├── dashboard.html
│   ├── login.html
│   ├── principal.html
│   └── veiculos.html
├── agendamento.py
├── app.py
├── autenticacao.py
├── banco.py
├── clientes.py
├── db.sql
├── guia_passo_a_passo_aula.md
├── rotas.py
└── veiculos.py
```

---

## 🚀 Como executar o projeto

### 🌸 1. Pré-requisitos

Antes de iniciar, instale:

- Python 3
- MySQL Server
- Navegador atualizado

### 💗 2. Instale as dependências

Abra o terminal na pasta do projeto e execute:

```bash
pip install flask mysql-connector-python bcrypt
```

### 🎀 3. Configure o banco de dados

Inicie o MySQL e execute o arquivo `db.sql` utilizando o MySQL Workbench ou outro cliente compatível.

Verifique se o banco de dados, o usuário e a senha correspondem às configurações definidas em `banco.py`.

### 🌷 4. Execute a aplicação

No terminal, dentro da pasta `oficina`, execute:

```bash
python app.py
```

### 💕 5. Acesse o sistema

Abra o navegador no endereço local configurado pela aplicação. Com a configuração padrão do Flask, acesse:

```text
http://127.0.0.1:5000
```

---

## 💖 Banco de dados

O banco de dados organiza as informações utilizadas pelo sistema. Entre as entidades previstas estão:

- **Usuários:** informações de acesso.
- **Clientes:** dados cadastrais.
- **Veículos:** informações dos veículos e seus proprietários.
- **Agendamentos:** serviços, datas, status e valores estimados.

O arquivo `db.sql` contém o script utilizado para configurar o banco de dados.

---

## 🎀 Principais arquivos

| Arquivo | Responsabilidade |
|---|---|
| `app.py` | Inicialização da aplicação |
| `banco.py` | Conexão com o MySQL |
| `autenticacao.py` | Autenticação de usuários |
| `clientes.py` | Operações de clientes |
| `veiculos.py` | Operações de veículos |
| `agendamento.py` | Operações de agendamentos |
| `rotas.py` | Definição das rotas |
| `db.sql` | Script do banco de dados |

---

## 🌷 Objetivo acadêmico

Aplicar conhecimentos de Desenvolvimento de Sistemas na construção de uma aplicação web, integrando backend, frontend, banco de dados relacional e mecanismos de autenticação.

---

## 🏫 Instituição

<p align="center">
  <img src="https://img.shields.io/badge/SENAI-E91E63?style=for-the-badge&logoColor=white" alt="SENAI">
  <br>
  <strong>Serviço Nacional de Aprendizagem Industrial</strong>
  <br>
  <em>Projeto acadêmico desenvolvido no contexto do SAEP.</em>
</p>

---

<p align="center">
  <strong>💗 Oficina Mecânica 💗</strong>
  <br>
  <em>Tecnologia a serviço da mecânica!</em>
  <br><br>
  <img src="https://img.shields.io/badge/Desenvolvido%20com-Pink%20Vibes-EC407A?style=flat-square" alt="Desenvolvido com Pink Vibes">
</p>
