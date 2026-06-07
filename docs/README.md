<img width="1600" style="height:auto; border-radius: 12px;" alt="banner Cadê Meu Pet?" src="assets/images/cadê meu pet.png" />

# Documentação do Projeto — Cadê Meu Pet? <small>(TIDocs)</small>

> Documentação completa da disciplina de **Trabalho Interdisciplinar** dos cursos de Tecnologia da Informação da [PUC Minas](https://pucminas.br), publicada como site via GitHub Pages (veja [`index.html`](index.html)). Um [exemplo de TIDocs](https://webtech-puc-minas.github.io/ti1-template/) está disponível no repositório do [WebTech PUC Minas](https://github.com/webtech-pucminas).

[![Licença: CC BY 4.0](https://img.shields.io/badge/Licença-CC--BY--4.0-lightgrey?style=for-the-badge)](LICENSE)
[![Site hospedado](https://img.shields.io/badge/Site-online-success?style=for-the-badge)](https://cademeupet.onrender.com)

---

## 📑 Sumário

1. [Introdução](#1-introdução)
2. [Problema e Solução](#2-problema-e-solução)
3. [Requisitos do Projeto](#3-requisitos-do-projeto)
4. [Gestão de Projeto](#4-gestão-de-projeto)
5. [Wireframes](#5-wireframes)
6. [User Flow](#6-user-flow)
7. [Organização do Projeto](#7-organização-do-projeto)
8. [Documentação Técnica](#8-documentação-técnica)
9. [Guia de Instalação e Uso](#9-guia-de-instalação-e-uso)
10. [Guia de Utilização do Site](#10-guia-de-utilização-do-site)
11. [Referências Bibliográficas](#11-referências-bibliográficas)

---

## 1. Introdução

### 1.1 Sobre o projeto

O **Cadê Meu Pet?** é uma plataforma online que ajuda tutores a encontrar animais de estimação perdidos e conecta a comunidade em torno dessa causa, promovendo também a adoção de animais que precisam de um novo lar.

### 1.2 Objetivos

Oferecer um espaço onde tutores registrem animais desaparecidos e a comunidade colabore na busca e localização, promovendo ainda a conscientização sobre identificação, registro e cuidado responsável de pets.

### 1.3 Justificativa

Milhões de animais se perdem todos os anos no Brasil. Uma plataforma centralizada e acessível reduz o tempo de separação entre tutores e pets e diminui o sofrimento de ambas as partes, ao mobilizar a comunidade de forma organizada.

### 1.4 Público-alvo e Personas

| Perfil | Quem é | O que busca na plataforma |
|---|---|---|
| **Donos de animais perdidos** | Público diverso, com conhecimento básico de navegação web | Simplicidade e acessibilidade para anunciar e acompanhar a busca pelo próprio pet |
| **Membros da comunidade** | Voluntários, grupos de proteção animal e pessoas engajadas em causas sociais | Uma forma eficiente de compartilhar informações e ajudar na localização de animais |
| **Organizações de resgate e abrigos** | ONGs e abrigos especializados em resgate e reabilitação | Ferramentas confiáveis que ampliem o alcance das ações de busca e adoção |

| Persona | Perfil resumido | Objetivo principal |
|---|---|---|
| **Pedro**, 22 anos | Estudante e entusiasta da comunidade, ativo em redes sociais | Encontrar o animal perdido, avisar o tutor e contribuir compartilhando informações |
| **Heitor**, 27 anos | Vendedor observador, percorre a vizinhança e usa mapas online na busca | Localizar o próprio pet, divulgar fotos/detalhes e contar com o apoio da comunidade |
| **Ana**, 17 anos | Aprendiz e voluntária, comunicativa e engajada em causas sociais | Divulgar informações sobre pets perdidos e colaborar voluntariamente com a busca |

---

## 2. Problema e Solução

**Problema:** milhões de animais de estimação são perdidos todos os anos no Brasil, gerando angústia para os tutores e colocando em risco a segurança e o bem-estar dos próprios animais.

**Solução:** uma plataforma onde tutores publicam anúncios detalhados sobre pets desaparecidos — com foto, localização, descrição e contato — para que outros usuários colaborem na busca e o reencontro aconteça mais rápido.

### 2.1 Histórias de Usuário

- Como **tutor**, quero cadastrar meu animal perdido para encontrá-lo.
- Como **tutor**, quero alterar o status, editar ou excluir meu anúncio para mantê-lo atualizado.
- Como **tutor**, quero entrar em contato com quem encontrou meu pet.
- Como **usuário**, quero buscar e filtrar animais perdidos por tipo ou status para localizar o de interesse.
- Como **usuário**, quero ver quantos animais já foram reencontrados para entender o impacto do site.
- Como **usuário**, quero publicar a foto do pet para facilitar sua identificação.
- Como **usuário ou tutor**, quero editar os dados do meu perfil para mantê-los atualizados.
- Como **usuário ou tutor**, quero criar, editar e excluir relatos para compartilhar e gerenciar histórias de reencontro.

---

## 3. Requisitos do Projeto

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

## 4. Gestão de Projeto

### 4.1 Design Thinking

![matriz de alinhamento](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/51339850-d8ed-419d-bb37-73b028ed7249)
![mapa de stakeholders](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/bf980e98-c6f1-4288-8b80-d5d0f77d307b)
![persona 1](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/3cd761b4-f616-48bd-a10c-117eb03a9f82)
![persona 2](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/45c61d43-67c3-4ee7-a1e0-60198d874c39)
![persona 3](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/dc3a5e59-58f0-45fa-8e4f-c0cc3e98d403)
![mural de possibilidades](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/e6a4e569-03f7-4f23-833d-c3ca24a106f0)
![mapa de priorização](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/e4ccf493-47c8-4401-a96c-a0e05e46bb5f)

### 4.2 Metodologia Scrum

O projeto foi conduzido em **sprints curtos** com metas e entregas específicas, *daily scrums* para sincronizar a equipe e retrospectivas regulares para aprimorar continuamente o processo.

**Sprint 1 — Ideação e protótipos**

| Tarefa | Responsável |
|---|---|
| Protótipo das telas no Figma | Marcos, Alexandre, Carlos e Henrique |
| Documentação inicial do projeto | João Gabriel |

![quadro kanban sprint 1](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/c414a6b6-c6e5-4029-9651-7b7ed37f304d)

**Sprint 2 — Construção em HTML, CSS e JavaScript**

| Artefato | Responsável |
|---|---|
| Métricas de animais reunidos com seus tutores | Marcos |
| Cadastro de usuário e tutor na plataforma | Alexandre |
| Busca e filtro de animais perdidos por tipo | Carlos |
| Cadastro do animal perdido | Henrique |
| Edição de perfil e atualização de status do animal | João Gabriel |

![quadro kanban sprint 2](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/3b37b2ed-e0ab-48d9-a1ba-649e0bcc6433)

**Sprint 3 — Integração das páginas e do JSON Server**

| Artefato | Responsável |
|---|---|
| Integração das páginas à tela inicial e navegação entre elas | Marcos |
| Restrição de funcionalidades a usuários cadastrados | Alexandre |
| Contato entre usuário e criador do anúncio | Carlos |
| Tela de alteração de cadastro | Henrique |
| Edição de perfil pelo usuário | João Gabriel |

![quadro kanban sprint 3](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/d4ace2d6-6652-48da-8a81-6f6507c10651)

**Sprint 4 — Reta final**

| Tarefa | Responsável |
|---|---|
| Hospedagem do site | Marcos e Henrique |
| Documentação final | Alexandre |
| Slide e vídeo de apresentação (pitch) | Carlos e João Gabriel |

![quadro kanban sprint 4](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/8327f70a-5e9b-4a24-8bfe-ab058d408a00)

### 4.3 Ferramentas

| Finalidade | Plataforma | Link |
|---|---|---|
| Processo de Design Thinking | Figma | [Acessar](https://www.figma.com/file/kIKNbYDNAJAC2btmjOb3zP/Untitled?type=design&node-id=0%3A1&mode=design&t=A09p9qmoB4UIzsRM-1) |
| Repositório de código | GitHub | [Acessar](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/) |
| Projeção inicial das telas | Figma | [Acessar](https://www.figma.com/file/8Ekahg6I0uWMj7boDvXYoi?type=design) |
| Wireframe / User Flow final | Figma | [Acessar](https://www.figma.com/design/mCIkWXsfOaR7kXdzdGCT5F/Untitled?node-id=0-1&t=BaHhOG1Ngoqo74p2-0) |
| Projeção do User Flow | Miro | [Acessar](https://miro.com/welcomeonboard/NmttR1ZoTWlUeXRaV2hscjJNZjZYY2g4ZDN4QlRUN3hSOWJLVjhmV1l2ZUpXbVpEa2pjdU5xeTAwbnNnb2ZCenwzNDU4NzY0NTg1Mzk5MDE4MDIyfDI=?share_link_id=495361633666) |
| Apresentação do projeto | Canva | [Acessar](https://www.canva.com/design/DAGB9QYXE1k/z5-R_lBn_G3hDf2q8SXGaQ/edit) |
| Apresentação do projeto final | Canva | [Acessar](https://www.canva.com/design/DAGJC1dlcj4/jTF46fAZzt9mFX5HqhGiSg/edit) |
| Documento do projeto | Google Docs | [Acessar](https://docs.google.com/document/d/1hpAhHAtS2Vk12tVPDKL7mzTtkeb1Q0KWXFew_AXYG2U/edit?usp=sharing) |
| Hospedagem | Replit | [Acessar](https://replit.com/@mafpinto/plf-es-2024-1-ti1-0385200-cade-meu-pet) |
| Hospedagem | Render | [Acessar](https://cademeupet.onrender.com) |

---

## 5. Wireframes

### 5.1 Wireframe inicial

**Home**
![home](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/49a97c85-ca32-47e7-b616-dd4b952ac413)
![home mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/23952317-a464-4bba-96ac-90fc26842a67)

**Menu**
![menu mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/e3ab276c-ed0b-4496-9c2a-7ac88c34a28d)

**Cadastro de usuário e login**
![cadastrar](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/909376be-3d41-4e28-b9b2-b1d7c42245ee)
![cadastrar mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/50e391f2-4f1f-4549-88c8-1bf4def4afba)

**Anúncios da conta logada**
![conta do usuário](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/c5a72081-5b3b-49b4-aad9-c20f53d827c0)
![conta do usuário mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/5ec8fb8b-3be1-468a-84be-05e7120f3b16)

**Desaparecidos e Localizados**
![desaparecidos e localizados](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/ef28375a-ca78-462b-803e-6c4087fe40ca)
![desaparecidos e localizados mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/366773a2-3381-484d-80d8-36639921f962)

**Filtros**
![filtro](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/93e0ee5b-c58d-4292-a2a7-d8b30cd1251c)
![filtro mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/39c34a97-1df2-4191-a8c5-2808453dfe79)

**Ferramentas**
![ferramentas](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/fbe6479f-971b-4737-9fba-f0dc61afeae4)
![ferramentas mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/f3e93ad3-dee1-4f8a-a255-c888207fe859)

**Blog**
![blog](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/8da45e20-f95f-434a-8e05-444fd714e2d7)
![blog mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/703d7f78-014e-4790-87a4-11afe8407207)

**Cadastro de Anúncio**
![anunciar](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/1cd2f687-d2c4-46cb-89fb-eebf02698e3e)
![anunciar mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/e7444989-cf22-4f13-b315-b8b5f6fd946b)

**FAQ**
![faq](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/7b948456-0634-4082-91c1-96f88071e456)
![faq mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/d6a9f712-d1a8-40f9-bfe5-6e7d962cca1f)

### 5.2 Resultado final

**Home**
![home p1](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/bf7e2e48-8816-4ea8-b1d0-c1ac30677fb7)
![home p2](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/a1f198d1-985d-4fe9-9daf-c8b0b1bb6e6a)
![home mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/44d0642b-b340-4bac-8b62-323bf7497924)

**Menu**
![menu](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/ad588a37-7a54-4a46-a46b-98bbe6b58125)

**Cadastro de Relato**
![cadastro de relato](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/6a9d188f-ab78-46be-9ada-29d9fbeff477)
![cadastro de relato mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/a549e625-5b67-41c0-8aa4-e3614d14a71e)

**Meus Relatos**
![meus relatos](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/bb4d72da-d29c-4e03-974f-a03e7aed39e6)
![meus relatos mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/227b6494-8247-4c9d-9976-3dda61d319a4)

**Cadastro de Usuário**
![cadastro de usuário](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/e2fbda82-36f0-4761-b9d7-b2d7942e1ff2)
![cadastro de usuário mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/933c1323-164c-4783-8ca8-bc5e9355d3f2)

**Login**
![login](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/1959f491-0864-400e-acba-415844ccc089)
![login mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/bcd40118-7b57-4a7c-bdf3-5ca2eca4ea33)

**Meus Anúncios**
![meus anúncios](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/934df7a0-0230-4486-b854-458bf095c55b)
![meus anúncios mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/8da41544-aea3-431c-aaf2-5a4c7c9ecc6d)

**Desaparecidos e Localizados**
![desaparecidos e localizados](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/ae2932f0-d38c-4c1a-a2eb-a963bf1be12f)
![desaparecidos e localizados mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/dd2b5425-ad56-4d73-9e47-94ec291610e0)
![desaparecidos e localizados detalhe](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/a30a7783-5f41-4988-bac7-9a7e64131859)

**Ferramentas**
![ferramentas](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/d51cce43-365f-4644-a7a4-b88cf7845e55)
![ferramentas mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/f74c3de2-3130-432d-ba90-db3dc4e072b4)

**Blog**
![blog](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/f4cca130-f943-443f-8c95-9e2dc3ffc8c9)
![blog mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/503d600b-5b4a-4abb-8ef1-f71c924bf92a)

**Cadastro de Anúncio**
![cadastro de anúncio](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/e2d5432e-7ab9-4a60-949b-689123021de8)
![cadastro de anúncio mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/0bffe516-5e3c-4d60-a882-5ee490320d79)

**FAQ**
![faq](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/156dcadf-3324-45c8-b906-e3cc983fffba)
![faq mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/92ac6789-c00a-455c-8a16-f9ca75b0490c)

**Rodapé**
![rodapé](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/a93b3a4e-3122-4d73-8033-bbd51a31195a)
![rodapé mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/4d830a03-084a-4ff4-a6b8-cd8e7755c5e6)

**Editor de Perfil**
![editor de perfil](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/343506a0-e1f7-4abe-9a4a-efb1c5d4231e)
![editor de perfil mobile](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/164196107/4c890678-78a9-4519-9fb3-2a441f6b9722)

### 5.3 Paleta de cores

![paleta de cores](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/5b5ec059-1507-4e61-9f4a-1902d6af7b3e)

### 5.4 Fontes

![fonte secundária](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/a35322fb-66d3-4bbc-9238-57d192d62494)

---

## 6. User Flow

**Início**
![user flow início](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/c20a903c-9567-47bf-bf99-b13ebacbaefc)

**Final**
![user flow final](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2024-1-ti1-0385200-cade-meu-pet/assets/159904717/86019633-bcb8-417b-829d-fd3fb8424e2c)

---

## 7. Organização do Projeto

```
Cad-Meu-Pet/
├── .cache/                 # Cache do Nix, Replit e TypeScript
├── .upm/                   # Gerenciamento de pacotes UPM (store.json)
├── codigo/                 # Front-end: HTML, CSS, JavaScript e imagens (ver codigo/README.md)
├── db/                     # db.json — banco de dados consumido pelo JSON Server
├── divulgação/             # Apresentação em slides e vídeo promocional
├── docs/
│   ├── assets/             # Recursos da documentação (imagens, css, js, vendor)
│   ├── Documentação do projeto.pdf
│   ├── Ata de acordo Sem Cliente Externo.pdf
│   ├── LICENSE             # Licença da documentação (CC BY 4.0)
│   ├── README.md           # Este arquivo
│   └── index.html          # Site da documentação (GitHub Pages)
├── node_modules/           # Dependências instaladas via npm
├── templates/              # Modelos e planejamentos usados nas sprints
├── .gitignore
├── .replit                 # Configuração da plataforma Replit
├── replit.nix              # Ambiente de desenvolvimento Nix
├── replit_zip_error_log.txt
├── CITATION.cff            # Como citar este projeto
├── LICENSE                 # Licença do projeto (CC BY 4.0)
├── README.md               # Visão geral do projeto
├── index.js                # Ponto de entrada do servidor (JSON Server + Express)
├── package.json            # Metadados e dependências
└── package-lock.json       # Versões exatas das dependências instaladas
```

---

## 8. Documentação Técnica

### 8.1 Estrutura do código

A árvore completa do diretório `codigo/` — com as pastas `html/`, `img/`, `javascript/` e `style/` — está documentada em [`codigo/README.md`](../codigo/README.md), para evitar duplicidade entre os dois arquivos.

### 8.2 Configurações e dependências

| Arquivo / pasta | Função |
|---|---|
| `.replit` | Define como o ambiente Replit deve executar o projeto |
| `replit.nix` | Configura dependências e ambiente Nix usados pelo Replit |
| `.gitignore` | Define arquivos e pastas ignorados pelo Git |
| `CITATION.cff` | Informa como citar o projeto em trabalhos acadêmicos |
| `package.json` | Metadados, scripts e dependências do projeto Node.js |
| `package-lock.json` | Registro exato das versões instaladas, garantindo builds consistentes |
| `node_modules/` | Pacotes npm instalados, necessários para a execução do projeto |
| `.cache/nix`, `.cache/replit`, `.cache/typescript` | Caches do Nix, do Replit e do compilador TypeScript |
| `.upm/store.json` | Registro de pacotes gerenciados pelo UPM |

---

## 9. Guia de Instalação e Uso

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

## 10. Guia de Utilização do Site

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

## 11. Referências Bibliográficas

- [O Scrum e o GitHub Projects para gerenciamento de projetos — Folha PE](https://www.folhape.com.br/colunistas/tecnologia-e-games/o-scrum-e-o-github-projects-para-gerenciamento-de-projetos/41913/)
- [Vídeo de referência 1 — YouTube](https://youtu.be/VvkT4I7WrmM)
- [Vídeo de referência 2 — YouTube](https://youtu.be/zh90BESE-W8)
- [Vídeo de referência 3 — YouTube](https://youtu.be/7hZMGSamsYA)
- [Vídeo de referência 4 — YouTube](https://youtu.be/NXm7Ms_1Qjk)
- [Saúde e cuidados com cachorros — Petz](https://www.petz.com.br/blog/cachorros/saude-e-cuidados-cachorros/saude-pet/)
- [Alimentação saudável para pets — PetShop Control](https://www.petshopcontrol.com.br/blog/alimentacao-saudavel-para-pets-o-que-voce-precisa-saber/)

---

<div align="center">
  <img width="70%" alt="banner institucional PUC Minas" src="assets/images/banner-institucional.svg"/>
</div>
<p align="center">Fonte do banner institucional: <a href="https://github.com/joaopauloaramuni">João Paulo Carneiro Aramuni</a></p>
