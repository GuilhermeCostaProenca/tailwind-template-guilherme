# 💨 Tailwind Template – Guilherme.Dev

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

## ⚙️ Scripts

```bash
npm install       # Instala dependências e ativa Husky
npm run build     # Gera o CSS final minificado em ./dist
npm run dev       # Modo de desenvolvimento com hot reload
npm run commit    # Abre menu interativo para padronizar commits
```

> ⚠️ Commits devem ser feitos sempre com `npm run commit`, pois o Husky bloqueia commits manuais

---

## 🔀 Git Flow (Padrão Profissional)

Este template utiliza **Git Flow**, com as seguintes branches:

- `main` → versão estável, releases com tag (`v0.1.0`, `v1.0.0`...)
- `develop` → desenvolvimento contínuo
- `feature/nome` → novas funcionalidades
- `release/vX.X.X` → preparação de nova versão
- `hotfix/nome` → correções emergenciais

### Primeiros passos para clonar e começar:

```bash
git clone https://github.com/SEU_USUARIO/tailwind-template-guilherme.git
cd tailwind-template-guilherme
npm install

# Configure o modelo de commit (local)
git config commit.template .config/gitmessage.txt

# Crie sua branch de funcionalidade
git checkout -b feature/nova-pagina
```

---

## 📋 Histórico de mudanças

Veja em [CHANGELOG.md](./CHANGELOG.md)

---

## 🧠 Sobre

Criado por [Guilherme Costa Proença](https://github.com/GuilhermeCostaProenca)  
Distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

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

Para ativar o modelo de commit localmente:

```bash
git config commit.template .config/gitmessage.txt
```

---

## ✅ Status de boas práticas

- [x] Husky instalado com prepare automático
- [x] Hook `pre-commit` funcionando e testado
- [x] Commitizen configurado via `cz`
- [x] Script de commit adicionado: `npm run commit`
- [x] Commits com padrão feitos e registrados
- [x] Script `test` simbólico para CI ativo
- [ ] GitHub Actions ainda não implementado (próximo passo)
