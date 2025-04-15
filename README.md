# OrizonX Frontend
<!-- Visão geral da OrizonX e objetivo do projeto -->
> Este repositório contém a **frontend** oficial da **OrizonX**, uma iniciativa criada por **Caique Ortega** e **Marcos Risson**.

**OrizonX** é um grupo de desenvolvedores que busca adquirir experiência prática e crescer profissionalmente. O foco é construir projetos reais para aprender na prática, aplicando o conhecimento e criando soluções simples e funcionais.

O compromisso é com o aprendizado contínuo, a exploração de novas tecnologias e a evolução por meio da prática. A meta é construir uma trajetória sólida, aprendendo constantemente e explorando novas abordagens, enquanto se entrega valor em cada projeto.

## Índice
<!-- Adicionar links para as seções do README conforme o projeto avança. -->
| Seção                                                  | Descrição                                                   |
|--------------------------------------------------------|-------------------------------------------------------------|
| [1. Status do Projeto](#status-do-projeto)             | Etapas atuais e progresso do desenvolvimento                |
| [2. Tecnologias Utilizadas](#tecnologias-utilizadas)   | Stack de ferramentas e bibliotecas usadas no projeto        |
| [3. Instalação e Execução Local](#instalacao-e-execucao-local) | Instruções para configurar o ambiente local e rodar o projeto |
| [4. Arquitetura do Projeto](#arquitetura-do-projeto)    | Estrutura do projeto e decisões arquiteturais               |
| [5. Licença](#licenca)                                 | Informações sobre direitos de uso e distribuição            |
| [6. Equipe de Desenvolvimento](#equipe-de-desenvolvimento) | Informações sobre os membros responsáveis pelo projeto    |


## <a id="status-do-projeto">1. Status do Projeto</a>
<!-- Adicionar o status e progresso do projeto aqui, como badges de CI/CD ou informações de build. -->
> 🚧 _**Status:** Em desenvolvimento. A estrutura do frontend está sendo planejada e implementada progressivamente._

- **Build**  `⏳*Pendente*`
- **Integração Contínua (CI)**  `⚙️Não implementada`

### Etapas atuais:
- [x] Criação do repositório  
- [x] Inicialização de uma documentação (`README.md`)  
- [ ] Estruturação inicial com **Next.js** e **TypeScript**  
- [ ] Configuração do ambiente (**ESLint**, **Prettier**)  
- [ ] Configuração de **CI/CD**  
- [ ] Definição das páginas e rotas
- [ ] Implementação responsiva  
- [ ] Otimização de performance e SEO
<!-- Futuros updates conforme o projeto avança -->

## <a id="tecnologias-utilizadas">2. Tecnologias Utilizadas</a>
<!-- Adicionar uma lista das ferramentas, bibliotecas e frameworks adotados no projeto. -->
> 🛠️ *As tecnologias utilizadas no projeto serão listadas aqui conforme o **desenvolvimento avança**.*

- **`Next.js`**: Framework React para a criação do frontend.
- **`React`**: Biblioteca para construção da interface.
- **`Tailwind CSS`**: Utilizado para estilização rápida e customizável.
- **`TypeScript`**: Superset do JavaScript com tipagem estática.
- **`ESLint & Prettier`**: Ferramentas de qualidade e formatação de código.

## <a id="instalacao-e-execucao-local">3. Instalação e Execução Local</a> 
<!-- Adicionar as instruções para configuração do ambiente local e execução do projeto. -->
> 💡 *Esta seção será atualizada conforme a estrutura do projeto evolui. As instruções abaixo servem como base para configuração inicial.*

### Pré-requisitos
[`Node.js 18.x^`](https://nodejs.org/) 
[`npm`](https://www.npmjs.com/)
[`Git`](https://git-scm.com/downloads)

### Instalação

```bash
# Clone o repositório
git clone https://github.com/Orizon-X/orizonx-frontend.git

# Acesse o diretório do projeto
cd orizonx-frontend

# Instale as dependências
npm install

# Rode o servidor de desenvolvimento
npm run dev
```

## <a id="arquitetura-do-projeto">4. Arquitetura do Projeto</a> 
<!-- Descrever a estrutura de pastas e decisões arquiteturais tomadas para o desenvolvimento do projeto. -->
> 📂 *A arquitetura do projeto está sendo definida à medida que o desenvolvimento avança. Abaixo, está um esboço inicial da estrutura de pastas e das principais decisões arquiteturais.*

```bash
📂 orizonx-frontend/
├── 📂 public/                  
│   └── 📂 assets/              # Imagens, fontes, ícones e outros arquivos estáticos         
├── 📂 src/                     
│   ├── 📂 app/                 # Páginas e layouts com Server Components
│   ├── 📂 components/          # Componentes compartilhados UI
│   ├── 📂 hooks/               # Hooks customizados
│   ├── 📂 lib/                 # Lógica de negócio e helpers
│   ├── 📂 services/            # APIs e serviços externos
│   ├── 📂 utils/               # Utilitários gerais
│   ├── 📂 styles/              # Estilos globais e específicos
│   ├── 📂 types/               # Tipos e interfaces
│   └── 📂 constants/           # Configurações reutilizáveis
├── 📃 .env                     # Variáveis de ambiente
├── 📃 .eslintrc.js             # Configurações do ESLint
├── 📃 .prettierrc.js           # Configurações do Prettier
├── 📃 tsconfig.json            # Configurações do TypeScript
└── 📃 package.json             # Dependências e scripts do projeto
```

## <a id="licenca">5. Licença</a> 
<!-- Informar sobre o tipo de licença que será adotado para o projeto, quando definido. -->
> 📄 *A licença deste projeto ainda **não foi definida**.*

Assim que a aplicação atingir uma etapa mais avançada de desenvolvimento, será adotada uma licença compatível com os objetivos da equipe e da Orizonx.

## <a id="equipe-de-desenvolvimento">6. Equipe de Desenvolvimento</a>
<!-- Listar os membros da equipe, suas funções e links para redes sociais, caso aplicável. -->
> *Projeto idealizado e desenvolvido pela equipe da Orizonx!*

<table >
  <tr>
    <td align="center">
      <img src="https://github.com/caiqueortega.png?size=100" width="100">
    </td>
    <td>
      <strong>Caique Ortega</strong><br />
      <i>Tech Lead & Full Stack</i><br />
    </td>
    <td align="center">
      <i>
        Co-founder & CEO<br />
        <strong>at Orizonx</strong>
      </i>
    </td>
    <td>
      <a href="https://github.com/caiqueortega">
        <img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white" />
      </a><br>
      <a href="https://www.linkedin.com/in/caiqueortega">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/marcosrisson.png?size=100" width="100">
    </td>
    <td>
      <strong>Marcos Risson</strong><br />
      <i>Front-End Developer</i><br />
    </td>
    <td align="center">
      <i>
        Co-founder & CTO<br />
        <strong>at Orizonx</strong>
      </i>
    </td>
    <td>
      <a href="https://github.com/marcosrisson">
        <img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white" />
      </a><br>
      <a href="https://www.linkedin.com/in/marcosrisson">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
      </a>
    </td>
  </tr>
</table>
