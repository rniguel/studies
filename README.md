# 📚 Studies

> Centralizador dos meus projetos de estudo, organizados por linguagem e tecnologia.

**Repositório principal:** [github.com/rniguel/studies](https://github.com/rniguel/studies)

**Portfólio:** [miguelito.dev](https://miguelito.dev)

---

## 🎯 Propósito

Organizar todos os meus projetos de estudo em um só lugar. Cada tecnologia tem sua pasta, e cada projeto é um **submodule** do Git — ou seja, cada um mantém seu próprio repositório, mas fica centralizado aqui.

> A estrutura cresce conforme novos estudos são adicionados.

---

## 🛠️ Tecnologias

| Pasta         | Tecnologia    |
| ------------- | ------------- |
| `javascript/` | JavaScript    |
| `php/`        | PHP           |
| `sql/`        | SQL           |
| `tools/`      | Tools         |

---

## 📦 Submodules — Como funciona?

Cada projeto dentro deste repositório é um **Git submodule**. Isso significa que ele é um repositório independente linkado dentro deste repositório principal. Na prática:

- Cada projeto tem seu próprio histórico de commits
- Fica tudo organizado em um só lugar
- Para clonar com todos os projetos, use:

```bash
git clone --recurse-submodules https://github.com/rniguel/studies.git
```

Se já clonou sem os submodules:

```bash
git submodule update --init --recursive
```

---

## ➕ Adicionar novo projeto

Para adicionar um novo projeto de estudo como submodule:

```bash
# Adicionar um novo submodule
git submodule add <url-do-repositorio> <caminho/local>

# Exemplo: adicionar um projeto de AI
git submodule add https://github.com/rniguel/meu-projeto-ai.git ai/meu-projeto-ai
```

Depois de adicionar, commite a alteração:

```bash
git add .gitmodules <caminho/local>
git commit -m "feat: add <nome-do-projeto> submodule"
```

---

Feito com ☕ por [Miguel](https://miguelito.dev)
