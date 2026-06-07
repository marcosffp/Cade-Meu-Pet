<img width="1600" style="height:auto; border-radius: 12px;" alt="banner Cadê Meu Pet?" src="docs/assets/images/cadê meu pet.png" />

# Cadê Meu Pet?

> Plataforma online que conecta tutores de animais perdidos à comunidade, facilitando o anúncio, a busca e o reencontro de pets desaparecidos.

[![Licença: CC BY 4.0](https://img.shields.io/badge/Licença-CC--BY--4.0-lightgrey?style=for-the-badge)](LICENSE)
[![Site hospedado](https://img.shields.io/badge/Site-online-success?style=for-the-badge)](https://cademeupet.onrender.com)

---

## 🛠️ Stack Principal

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![JSON Server](https://img.shields.io/badge/JSON_Server-2965f1?style=for-the-badge&logo=json&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Replit](https://img.shields.io/badge/Replit-667881?style=for-the-badge&logo=replit&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)

---

## 👥 Equipe

| Alunos integrantes | Professores responsáveis |
|---|---|
| Alexandre Ottoni Righas | Gabriel Barbosa da Fonseca |
| Carlos José Gomes Batista Figueiredo | Michelle Hanne Soares de Andrade |
| Henrique Lima Volponi | |
| João Gabriel Silva Custódio | |
| Marcos Alberto Ferreira Pinto | |

> Projeto acadêmico da disciplina de Trabalho Interdisciplinar — cursos de Tecnologia da Informação da [PUC Minas](https://pucminas.br). A documentação completa do projeto está na pasta [`docs`](docs/README.md).

---

## 📑 Sumário

- [Sobre o projeto](#-sobre-o-projeto)
- [Problema e solução](#-problema-e-solução)
- [Público-alvo e personas](#-público-alvo-e-personas)
- [Requisitos do projeto](#-requisitos-do-projeto)
- [Histórias de usuário](#️-histórias-de-usuário)
- [Estrutura de pastas](#-estrutura-de-pastas)
- [Instalação e execução](#-instalação-e-execução)
- [Guia de utilização do site](#-guia-de-utilização-do-site)
- [Documentação completa](#-documentação-completa)

---

## 📖 Sobre o projeto

O **Cadê Meu Pet?** é uma plataforma online que ajuda tutores a encontrar animais de estimação perdidos e conecta a comunidade em torno dessa causa. Tutores cadastram anúncios com os dados do pet desaparecido, e qualquer pessoa pode visualizar, filtrar e ajudar na busca — reduzindo o tempo de separação e o sofrimento de quem perdeu um animal.

Além de centralizar os anúncios de busca, o projeto promove a conscientização sobre identificação e registro de pets, e incentiva a colaboração voluntária da comunidade no processo de reencontro.

---

## 🧩 Problema e Solução

**Problema:** milhões de animais de estimação são perdidos todos os anos no Brasil, gerando angústia para os tutores e colocando em risco a segurança e o bem-estar dos próprios animais. Faltava uma forma centralizada e acessível de mobilizar a comunidade nessa busca.

**Solução:** uma plataforma onde tutores publicam anúncios detalhados sobre pets desaparecidos — com foto, localização, descrição e contato — para que outros usuários colaborem na busca e o reencontro aconteça mais rápido.

---

## 🎯 Público-alvo e Personas

| Perfil | Quem é | O que busca na plataforma |
|---|---|---|
| **Donos de animais perdidos** | Público diverso, com conhecimento básico de navegação web | Simplicidade e acessibilidade para anunciar e acompanhar a busca pelo próprio pet |
| **Membros da comunidade** | Voluntários, grupos de proteção animal e pessoas engajadas em causas sociais | Uma forma eficiente de compartilhar informações e ajudar na localização de animais |
| **Organizações de resgate e abrigos** | ONGs e abrigos especializados em resgate e reabilitação | Ferramentas confiáveis que ampliem o alcance das ações de busca e adoção |

| Persona | Perfil resumido | Objetivo principal |
|---|---|---|
| **Pedro**, 22 anos | Estudante e entusiasta da comunidade, ativo em redes sociais | Encontrar o animal perdido, avisar o tutor e contribuir compartilhando informações |
| **Heitor**, 27 anos | Vendedor observador, percorre vizinhança e usa mapas online na busca | Localizar o próprio pet, divulgar fotos/detalhes e contar com o apoio da comunidade |
| **Ana**, 17 anos | Aprendiz e voluntária, comunicativa e engajada em causas sociais | Divulgar informações sobre pets perdidos e colaborar voluntariamente com a busca |

---

## 📋 Requisitos do Projeto

### Requisitos Funcionais (RF)

| ID | Descrição | Prioridade |
|---|---|---|
| RF-001 | Tutor cadastra o animal perdido | Alta |
| RF-002 | Usuário busca animais perdidos | Média |
| RF-003 | Usuário e tutor filtram animais por tipo e status | Baixa |
| RF-004 | Sistema exibe métricas de animais reunidos com seus tutores | Alta |
| RF-005 | Tutor publica imagem do pet via URL | Média |
| RF-006 | Usuários e tutores excluem o próprio anúncio | Alta |
| RF-007 | Usuário entra em contato com o tutor ao encontrar o pet | Alta |
| RF-008 | Usuário e tutor editam os dados do próprio perfil | Média |
| RF-009 | Tutor altera o status do animal para "encontrado" | Média |
| RF-010 | Usuários e tutores criam relatos de reencontro | Média |
| RF-011 | Usuários e tutores editam relatos de reencontro | Média |
| RF-012 | Usuários e tutores excluem relatos de reencontro | Média |

### Requisitos Não Funcionais (RNF)

| ID | Descrição | Prioridade |
|---|---|---|
| RNF-001 | Site desenvolvido em HTML, CSS e JavaScript | Alta |
| RNF-002 | Banco de dados via JSON Server sobre Node.js | Média |
| RNF-003 | Suporte aos principais navegadores | Baixa |
| RNF-004 | Layout responsivo | Média |
| RNF-005 | Suporte a múltiplos dispositivos (desktop e mobile) | Média |
| RNF-006 | Arquitetura preparada para crescimento de usuários e dados | Média |
| RNF-007 | Validação de e-mail já cadastrado em até 5 segundos | Média |
| RNF-008 | Validação de senha em até 5 segundos | Média |

---

## 🗣️ Histórias de Usuário

- Como **tutor**, quero cadastrar meu animal perdido para encontrá-lo.
- Como **tutor**, quero alterar o status, editar ou excluir meu anúncio para mantê-lo atualizado.
- Como **tutor**, quero entrar em contato com quem encontrou meu pet.
- Como **usuário**, quero buscar e filtrar animais perdidos por tipo ou status para localizar o de interesse.
- Como **usuário**, quero ver quantos animais já foram reencontrados para entender o impacto do site.
- Como **usuário**, quero publicar a foto do pet para facilitar sua identificação.
- Como **usuário ou tutor**, quero editar os dados do meu perfil para mantê-los atualizados.
- Como **usuário ou tutor**, quero criar, editar e excluir relatos para compartilhar e gerenciar histórias de reencontro.

---

## 📁 Estrutura de pastas

```
Cad-Meu-Pet/
├── codigo/             # Front-end: HTML, CSS, JavaScript e imagens (ver codigo/README.md)
├── db/                 # Banco de dados JSON consumido pelo JSON Server
├── divulgação/         # Material de apresentação e vídeo promocional
├── docs/               # Documentação completa do projeto (ver docs/README.md)
├── templates/          # Documentos e planejamentos das sprints
├── index.js            # Ponto de entrada do servidor (JSON Server + Express)
├── package.json        # Metadados e dependências do projeto
├── .replit / replit.nix# Configuração do ambiente Replit
└── CITATION.cff        # Como citar este projeto
```

---

## 🚀 Instalação e Execução

### Acessando o site hospedado

- Link principal (Render): **https://cademeupet.onrender.com**
- Por ser um plano gratuito, o serviço hiberna após inatividade — aguarde de 30 a 50 segundos no primeiro acesso para o site carregar.
- Caso o link do Render esteja indisponível (limite de requisições do plano gratuito), utilize a versão hospedada no [Replit](https://replit.com/@mafpinto/plf-es-2024-1-ti1-0385200-cade-meu-pet).

### Pré-requisitos

- Conta gratuita no [Replit](https://replit.com/) (necessária para rodar o projeto na nuvem).

### Passo a passo (via Replit)

1. **Acesse o projeto** pelo [link do Replit](https://replit.com/@mafpinto/plf-es-2024-1-ti1-0385200-cade-meu-pet) e clique em **Fork** para criar sua própria cópia.
2. **Abra o projeto forkado** — o Replit detecta o `package.json` e instala as dependências automaticamente.
3. Caso a instalação automática falhe, abra o terminal integrado e rode:
   ```bash
   npm install
   ```
4. **Execute o projeto** clicando em **Run**. O Replit inicia o servidor e abre a aplicação na aba *Webview*.
5. Para uma visualização completa, abra a aplicação em **New Tab** — por padrão, a *Webview* é otimizada para mobile.

> **Logs e erros:** em caso de falhas na execução, consulte o console na parte inferior da interface do Replit.

---

## 🌐 Guia de Utilização do Site

> A maior parte das funcionalidades exige cadastro. Usuários não autenticados são redirecionados à página de cadastro ao tentar utilizá-las. O site é totalmente responsivo — no mobile, a navegação fica no menu "hambúrguer" do cabeçalho.

| Página | Principais funcionalidades |
|---|---|
| **Home** | Botões "Perdi meu Pet" e "Achei um Pet", contador de animais reunidos e carrossel de fotos; seção de relatos com depoimentos da comunidade (curtir, ver mais, criar relato) |
| **Desaparecidos e Localizados** | Filtros por status, localização e tipo de animal; cards de anúncio com foto, status, tipo, localização, descrição, contato e gênero |
| **Cadastro de Anúncio** | Formulário com status, tipo, gênero, nome, localização, contato, descrição e URL da imagem do pet |
| **Cadastro de Relato** | Registro de reencontros com nome do pet, data, localização, descrição e URL da imagem |
| **Meus Anúncios / Meus Relatos** | Listagem dos próprios cadastros, com opções de visualizar, editar e excluir cada item |
| **Cadastro de Usuário / Login** | Cadastro com validação de e-mail único e senha forte (número, símbolo, maiúscula, minúscula, mínimo de caracteres); login redireciona ao perfil |
| **Editor de Perfil** | Atualização de nome, e-mail e senha, seguindo os mesmos critérios de validação do cadastro |
| **Ferramentas / Blog / FAQ** | Conteúdo de apoio para tutores, dicas sobre cuidados com pets e respostas a perguntas frequentes |

O **rodapé** das páginas reúne links para a equipe de desenvolvedores, termos de uso, política de privacidade, redes sociais e contato.

---

## 📚 Documentação completa

A documentação acadêmica completa — introdução, gestão de projeto, wireframes, user flow, documentação técnica e referências — está disponível em [`docs/README.md`](docs/README.md) e publicada via GitHub Pages em [`docs/index.html`](docs/index.html).

---

<div align="center">
  <img width="70%" alt="banner institucional PUC Minas" src="docs/assets/images/banner-institucional.svg"/>
</div>
<p align="center">Fonte do banner institucional: <a href="https://github.com/joaopauloaramuni">João Paulo Carneiro Aramuni</a></p>
