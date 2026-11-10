# Propostas

Propostas comerciais em HTML, publicadas via GitHub Pages.

## Estrutura

```
Propostas/
├── _modelos/                 Modelos base (não enviar ao cliente)
│   └── identidade-visual/
├── nome-do-cliente/          Uma pasta por proposta enviada
│   └── index.html
└── index.html                Página em branco (não lista as propostas)
```

## Regras

- Cada proposta fica na própria pasta e gera o próprio link:
  `https://danielbarbosacreator-design.github.io/Propostas/nome-do-cliente/`
- Nome da pasta: nome do cliente em minúsculas, sem acento, com hífen (ex.: `maria-souza`).
- Uma proposta enviada não é sobrescrita por outra. Revisão grande depois do envio vai para `nome-do-cliente/v2/`.
- Cada página é um único arquivo HTML, com imagens embutidas e tag `noindex`.
- Novos modelos (site, vídeo, sistema) entram em `_modelos/` quando o primeiro pedido do tipo chegar.
