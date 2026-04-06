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

| Pasta  | Tecnologia |
| ------ | ---------- |
| `php/` | PHP        |
| `sql/` | SQL        |

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

Feito com ☕ por [Miguel](https://miguelito.dev)
