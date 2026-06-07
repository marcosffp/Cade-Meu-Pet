# Código-fonte

> Front-end estático do **Cadê Meu Pet?** — páginas HTML, estilos CSS, scripts JavaScript e imagens consumidas pela aplicação. Veja a [documentação geral do projeto](../README.md) e a [documentação completa](../docs/README.md) para mais contexto.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📁 Estrutura de pastas

```
codigo/
├── html/                                   # Páginas HTML do site
│   ├── blog.html
│   ├── cadastro_animal_perdido.html
│   ├── cadastro_relato.html
│   ├── cadastro_usuario.html
│   ├── desaparecidos_localizados.html
│   ├── editor_perfil.html
│   ├── faq.html
│   ├── ferramentas.html
│   ├── home.html
│   ├── login.html
│   ├── meus_anuncios.html
│   ├── meus_relatos.html
│   ├── politica.html
│   ├── quem_somos.html
│   └── termos.html
│
├── img/                                    # Imagens utilizadas no site
│   ├── alexandre.jpeg
│   ├── auncio_pet.png
│   ├── carlos.jpeg
│   ├── gato.jpg
│   ├── humberto-arellano-N_G2Sqdy9QY-unsplash.jpg
│   ├── joao.jpeg
│   ├── joe-caione-qO-PIF84Vxg-unsplash.jpg
│   ├── marcos.jpeg
│   ├── matthew-henry-2Ts5HnA67k8-unsplash.jpg
│   ├── nova_logo.png
│   ├── pet_tutora.jpg
│   ├── teste.png
│   └── volponi.jpeg
│
├── javascript/                             # Scripts de interação de cada página
│   ├── blog_faq_ferramentas.js
│   ├── cadastro_animal_perdido.js
│   ├── cadastro_relato.js
│   ├── cadastro_usuario.js
│   ├── desaparecidos_localizados.js
│   ├── editor_perfil.js
│   ├── faq.js
│   ├── home.js
│   ├── login.js
│   ├── meus_anuncios.js
│   └── meus_relatos.js
│
├── style/                                  # Folhas de estilo, uma por página
│   ├── blog.css
│   ├── cadastro_animal_perdido.css
│   ├── cadastro_relato.css
│   ├── cadastro_usuario.css
│   ├── desaparecidos_localizados.css
│   ├── editor_perfil.css
│   ├── faq.css
│   ├── ferramentas.css
│   ├── home.css
│   ├── login.css
│   ├── meus_anuncios.css
│   ├── meus_relatos.css
│   ├── politicas.css
│   ├── quem_somos.css
│   └── termos.css
│
└── README.md
```

> Cada página HTML possui sua própria folha de estilo em `style/` com o mesmo nome base. Páginas com lógica própria têm um script correspondente em `javascript/`; páginas de conteúdo estático mais simples (ex.: `blog`, `faq` e `ferramentas`) compartilham um único script (`blog_faq_ferramentas.js`). As páginas consomem dados de `db/db.json` por meio do JSON Server (ver [`index.js`](../index.js) na raiz do projeto).
