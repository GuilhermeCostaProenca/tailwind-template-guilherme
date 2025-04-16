# 💨 Tailwind Template – Guilherme.Dev

Template minimalista com **HTML + Tailwind CSS**, pronto para projetos simples, landing pages e protótipos rápidos — com organização de código e estrutura profissional.

---

## 🚀 Tecnologias

- [x] HTML5  
- [x] Tailwind CSS 3.x  
- [x] PostCSS  
- [x] Estrutura modular de arquivos  
- [x] Scripts automatizados

---

## 📁 Estrutura

```
tailwind-template-guilherme/
├── .config/
│   ├── tailwind.config.js
│   ├── postcss.config.js
│   └── gitmessage.txt
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
├── CHANGELOG.md
├── LICENSE
├── README.md
├── package.json
```

---

## ⚙️ Scripts

```bash
npm install       # Instala dependências
npm run build     # Gera o CSS final minificado em ./dist
npm run dev       # Modo de desenvolvimento com hot reload
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
