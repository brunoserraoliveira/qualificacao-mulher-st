# 🌸 Qualificação Profissional - Secretaria da Mulher | Serra Talhada

Landing page desenvolvida para a **Secretaria da Mulher do município de Serra Talhada - PE**. O objetivo do site é promover cursos de qualificação profissional (como Design de Sobrancelhas e Dindin Gourmet) focados em gerar autonomia financeira, independência e novas oportunidades para as mulheres do município.

Projeto desenvolvido e mantido pela equipe do **NTI Serra Talhada**.

---

## 🚀 Tecnologias Utilizadas

Este projeto foi construído focando em performance, simplicidade e facilidade de manutenção:

* **HTML5:** Estruturação semântica.
* **Tailwind CSS (via CDN):** Estilização rápida, responsiva e alinhada à identidade visual da Secretaria da Mulher (tons de roxo e rosa).
* **FontAwesome:** Ícones vetoriais.
* **Docker & Nginx:** Containerização do site utilizando a imagem ultraleve `nginx:alpine` para alta performance em produção.
* **GitHub Actions:** Pipeline de CI/CD para deploy automático.
* **Traefik:** Proxy reverso e gerenciador de certificados SSL (Let's Encrypt) na VPS.

---

## 📁 Estrutura do Projeto

```text
.
├── .github/
│   └── workflows/
│       └── deploy.yml       # Pipeline de CI/CD do GitHub Actions
├── img/                     # Diretório de imagens
│   ├── logo_horizontal.png  # Logo da Prefeitura Municipal
│   └── sec_mulher.jpeg      # Logo da Secretaria da Mulher
├── Dockerfile               # Instruções de montagem da imagem Docker
├── docker-compose.yml       # Arquivo de orquestração para VPS (usando Traefik)
├── index.html               # Código fonte da Landing Page
└── README.md                # Documentação do projeto