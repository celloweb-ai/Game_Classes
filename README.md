
# 3️⃣ Escrevendo as classes de um Jogo — DIO

> Repositório de estudo para o desafio **"Escrevendo as classes de um Jogo"**: crie uma classe genérica que represente um herói e implemente o método `atacar` com saídas diferentes conforme o tipo do herói.

## 🧩 Objetivo

Criar uma classe que represente um **Herói** com as propriedades:

- `nome`
- `idade`
- `tipo` (ex.: `guerreiro`, `mago`, `monge`, `ninja`)

E com o método:

- `atacar()` → deve exibir: `"o {tipo} atacou usando {ataque}"`

| Tipo      | Ataque correspondente       |
|-----------|-----------------------------|
| `mago`    | magia                       |
| `guerreiro` | espada                    |
| `monge`   | artes marciais              |
| `ninja`   | shuriken                    |

> Exemplos de saída: `mago atacou usando magia`, `guerreiro atacou usando espada`.

---

## 📁 Conteúdo do repositório

Este repositório inclui implementações em **JavaScript (Node.js)** e **Python**, além de testes simples:

```
.
├── LICENSE
├── README.md
├── .gitignore
├── package.json
├── src
│   ├── javascript
│   │   └── hero.js
│   └── python
│       └── hero.py
└── tests
    ├── javascript
    │   └── test.js
    └── python
        └── test_hero.py
```

---

## 🚀 Como executar

### Opção A) JavaScript (Node.js)
1. Instale o Node.js (v16+ recomendado).
2. Execute:

```bash
npm start
```

Isso roda `src/javascript/hero.js` e imprime quatro exemplos de ataque.

Para rodar o teste simples:

```bash
npm test
```

### Opção B) Python (3.10+)

```bash
python3 src/python/hero.py
```

Para rodar o teste simples (usando `unittest`):

```bash
python3 -m unittest tests/python/test_hero.py
```

---

## 🧠 Detalhes de implementação

- **Mapeamento de ataques**: um dicionário/objeto mapeia `tipo` → `ataque`.
- **Robustez**: se o tipo não for reconhecido, o método retorna `"um ataque básico"`.
- **Mensagens**: o método `atacar()` retorna a string e também imprime (no JS e Python).

---

## 🛠️ Como criar seu repositório no GitHub

Suba este projeto para o GitHub com os passos abaixo (via linha de comando):

```bash
# 1) Inicialize o repositório local
git init

# 2) Configure seu nome e e-mail (se necessário)
git config user.name "Seu Nome"
git config user.email "seu.email@exemplo.com"

# 3) Adicione todos os arquivos
git add .

# 4) Faça o primeiro commit
git commit -m "Desafio DIO: classe Hero e método atacar"

# 5) Crie o repositório no GitHub
#   - Via GitHub Web: crie um repo vazio e copie a URL
#   - Ou via GitHub CLI (gh):
# gh repo create seu-usuario/dio-jogo-classes --public --source . --remote origin --push

# 6) Se criou via Web, adicione o remote e faça o push
git remote add origin https://github.com/seu-usuario/dio-jogo-classes.git
git branch -M main
git push -u origin main
```

> Dica: Se houver um repositório do expert, você pode fazer **fork** e manter a referência ao código original.

---

## 📎 Links e artefatos

- Template Figma (exemplo/placeholder): `https://www.figma.com/file/SEU_TEMPLATE`
- Base de dados (se aplicável): `./data/` _(adicione aqui seus arquivos)_

---

## 📜 Licença

Este projeto está licenciado sob a **MIT License**. Sinta-se à vontade para usar e adaptar.

---

## 🙌 Contribuições

Sugestões são bem-vindas! Abra uma *issue* ou envie um *pull request*.
