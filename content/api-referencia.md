# Referência da API

## `kite.init(nome)`

Cria um novo projeto.

```js
kite.init("meu-projeto");
```

## `kite.run(opcoes)`

Executa o projeto atual.

| Parâmetro | Tipo | Descrição |
|---|---|---|
| `watch` | boolean | reconstrói ao salvar |
| `port` | number | porta do servidor local |

```js
kite.run({ watch: true, port: 4000 });
```

---

Precisa de algo que não está aqui? Abra uma issue no repositório do projeto.
