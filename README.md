## 💻 Remote Judge

Remote Judge é uma plataforma web projetada para o ensino e prática de programação competitiva e resolução de problemas. Ela simula um juiz online, permitindo que professores criem exercícios, e alunos submetam códigos em diversas linguagens para avaliação automática com base em casos de teste.

-----

## ✨ Funcionalidades Principais

### 🧑‍🎓 Para Alunos

  * **Resolução de Problemas:** Acesso a uma lista de exercícios de programação para praticar. (Ver `dashboard.html`)
  * **Visualização de Problema:** Descrição completa do problema, incluindo fórmula, formato de entrada/saída e exemplos. (Ver `problema.html`)
  * **Submissão de Código:** Editor de código integrado para submissão da solução em diferentes linguagens. (Ver `problema.html`)
  * **Status da Submissão:** Visualização do status da submissão (Aceito, Pendente, Não Submetido) na lista de exercícios. (Ver `dashboard.html`)
  * **Gerenciamento de Perfil:** Visualizar e editar informações de perfil (nome, e-mail) e alterar a senha. (Ver `perfil.html`, `editar-perfil.html`, `alterar-senha.html`)

### 👨‍🏫 Para Professores

  * **Painel de Gerenciamento:** Visão geral e acesso rápido às ferramentas de criação e gestão de exercícios. (Ver `professor.html`)
  * **Criação de Exercício:** Formulário detalhado para definir o título, descrição, formato de entrada/saída, nível de dificuldade e, crucialmente, os **casos de teste**. (Ver `criar_exercicio.html`)
  * **Gestão de Exercícios:** Tabela para visualizar, editar e excluir problemas já cadastrados. (Ver `professor.html`)

### 🔑 Autenticação e Acesso

  * **Login:** Acesso seguro com e-mail e senha. (Ver `index.html`)
  * **Cadastro:** Criação de conta com opção de se registrar como **Aluno** ou **Professor**. Regras de senha claras são fornecidas. (Ver `cadastro.html`)
  * **Recuperação de Senha:** Fluxo para solicitar a recuperação da senha via e-mail. (Ver `recuperar-senha.html`)

-----

## 🛠️ Estrutura do Projeto (HTML)

O projeto é estruturado em arquivos HTML que representam as principais telas da aplicação.

| Arquivo HTML | Descrição da Tela | Público-Alvo |
| :--- | :--- | :--- |
| `index.html` | Tela de **Login** | Todos |
| `cadastro.html` | Tela de **Criação de Conta** | Todos |
| `recuperar-senha.html` | Fluxo de **Recuperação de Senha** | Todos |
| `dashboard.html` | **Painel do Aluno** (Lista de exercícios) | Alunos |
| `problema.html` | **Visualização/Resolução de Problema** e Submissão de código | Alunos |
| `professor.html` | **Painel do Professor** (Lista de exercícios criados) | Professores |
| `criar_exercicio.html` | Formulário para **Criar Novo Exercício** (com casos de teste) | Professores |
| `perfil.html` | **Visualização do Perfil** do usuário | Todos |
| `editar-perfil.html` | Formulário para **Editar Nome e E-mail** | Todos |
| `alterar-senha.html` | Formulário para **Alterar Senha** | Todos |

-----

## 🚀 Como Executar

Esta parte do projeto é uma maquete/mockup em **HTML/CSS puro** e não contém *backend* ou funcionalidades dinâmicas de servidor.

Para visualizar as telas:

1.  **Clone o Repositório:**
    ```bash
    git clone [LINK_DO_SEU_REPOSITÓRIO]
    ```
2.  **Navegue até a Pasta:**
    ```bash
    cd remote-judge
    ```
3.  **Abra os Arquivos:**
    Simplesmente abra qualquer arquivo `.html` (por exemplo, `index.html` ou `dashboard.html`) no seu navegador web preferido.

-----
