# 💨 Tailwind Template – Guilherme.Dev

[![](https://img.shields.io/badge/setup-init--project-blue?style=flat-square)](#)
[![](https://github.com/GuilhermeCostaProenca/tailwind-template-guilherme/actions/workflows/ci.yml/badge.svg)](https://github.com/GuilhermeCostaProenca/tailwind-template-guilherme/actions)

Template minimalista com **HTML + Tailwind CSS**, pronto para projetos simples, landing pages e protótipos rápidos — com organização de código e estrutura profissional.

---

## 🚀 Tecnologias

- [x] HTML5  
- [x] Tailwind CSS 3.x  
- [x] PostCSS  
- [x] Estrutura modular de arquivos  
- [x] Scripts automatizados  
- [x] Git Flow e versionamento semântico  
- [x] Commitizen com Husky configurado  
- [x] GitHub Actions com CI básico configurado

---

## 📁 Estrutura

```
tailwind-template-guilherme/
├── .config/
│   ├── tailwind.config.js
│   ├── postcss.config.js
│   └── gitmessage.txt
├── .husky/
│   └── pre-commit
├── .github/
│   └── workflows/
│       └── ci.yml
├── src/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── img/
├── public/
│   └── index.html
├── docs/
│   └── decisoes.md
├── .gitignore
├── .gitattributes (opcional)
├── CHANGELOG.md
├── LICENSE
├── README.md
├── package.json
└── package-lock.json
```

---

## 🚀 Como usar este template

1. Clique em **Use this template** no GitHub
2. Clone o repositório gerado
3. Instale as dependências:

```bash
npm install
```

4. Inicie o projeto limpo com:

```bash
npm run init:project
```

Esse comando irá:
- Atualizar o nome do projeto
- Resetar o changelog
- Apagar arquivos desnecessários do template

---

## ▶️ Rodar localmente

```bash
npm run dev
```

Acesse em: [http://localhost:5173](http://localhost:5173)

---

## ⚙️ Scripts disponíveis

```bash
npm install       # Instala dependências e ativa Husky
dev              # Modo de desenvolvimento com hot reload
build            # Gera o CSS final minificado em ./dist
commit           # Abre menu interativo para padronizar commits
init:project     # Limpa arquivos do template e inicia um novo projeto
```

> ⚠️ Commits devem ser feitos sempre com `npm run commit`, pois o Husky bloqueia commits manuais

---

## 🔀 Fluxo de desenvolvimento (Git Flow)

- `main` → versão estável com tags (`v0.1.0`, `v1.0.0`...)
- `develop` → branch principal de desenvolvimento
- `feature/nome` → novas funcionalidades
- `release/vX.X.X` → preparação de nova release
- `hotfix/nome` → correções emergenciais

### Comece com:

```bash
git checkout -b feature/nova-feature
```

---

## 📋 Histórico de mudanças

Veja em [CHANGELOG.md](./CHANGELOG.md)

---

## 📝 Modelo de Commit – `.config/gitmessage.txt`

```
feat(scope): mensagem curta

# Explicação mais detalhada (opcional)
#
# Tipos:
# feat     → nova funcionalidade
# fix      → correção de bug
# docs     → mudanças na documentação
# style    → formatação, CSS, espaço, vírgula
# refactor → refatoração sem alterar funcionalidade
# chore    → tarefas internas, config, setup
```

Para ativar o modelo localmente:

```bash
git config commit.template .config/gitmessage.txt
```

---

## ✅ Status de boas práticas

- [x] Estrutura modular separada por tipo (CSS, JS, imagens)
- [x] Git Flow aplicado com branches organizadas
- [x] Husky instalado e ativo com hook de pre-commit
- [x] Commitizen configurado para padronização
- [x] GitHub Actions com CI de instalação e build
- [x] Script de inicialização de projeto (`init:project`)

---

## 📬 Contato

Feito por [Guilherme Costa Proença](https://github.com/GuilhermeCostaProenca)  
Entre em contato via [LinkedIn](https://linkedin.com/in/guilhermecostaproenca)

---
