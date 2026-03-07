# RUNIX Soluções em Tecnologia

> Site institucional da RUNIX — hospedado via GitHub Pages com Jekyll.

🌐 **[runix.net.br](https://runix.net.br)**

---

## Sobre

Site institucional da **RUNIX Soluções em Tecnologia**, empresa especializada em infraestrutura de TI, virtualização, backup, hardening, monitoramento e suporte técnico para empresas.

---

## Estrutura do Repositório

```
runix.github.io/
├── index.html          # Página principal
├── legal.md            # Política de Privacidade
├── _config.yml         # Configurações do Jekyll
├── _data/              # Dados YAML do Jekyll
├── assets/
│   └── img/
│       ├── logo.png    # Logo da RUNIX
│       └── favicon.ico
├── CNAME               # Domínio personalizado (runix.net.br)
└── README.md           # Este arquivo
```

---

## Tecnologias

- **Jekyll** — gerador de site estático
- **GitHub Pages** — hospedagem gratuita
- **Cloudflare** — DNS e proteção

---

## Desenvolvimento Local

Para rodar o site localmente:

```bash
# Instalar dependências
bundle install

# Rodar servidor local
bundle exec jekyll serve

# Acesse em http://localhost:4000
```

> Requer Ruby e Bundler instalados. Veja o [Gemfile](Gemfile) para as versões utilizadas.

---

## Deploy

O deploy é automático. Basta fazer push na branch `master`:

```bash
git add .
git commit -m "sua mensagem"
git push origin master
```

O GitHub Actions publica automaticamente em **runix.net.br** em instantes.

---

## Contato

- 🌐 [runix.net.br](https://runix.net.br)
- 📧 contato@runix.net.br
- 💬 [WhatsApp](https://wa.me/5592994675374)

---

© 2026 RUNIX Soluções em Tecnologia
