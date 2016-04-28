# Configuração
---
Esta página irá orienta-lo a como configurar o seu repositório e tirar o melhor proveito do leiame.org.

Primeiro é preciso que seja criar um arquivo `leiame.json` no raiz de seu repositório. Veja abaixo um exemplo deste arquivo:

```json
{
    "path"       : "/",
    "branch_name": "Beta",
    "sidebar"    : "/sidebar.md",

    "modules": [
        "auto_title_index",
        "external_link_blank"
    ]
}
```

* Lembramos que cada `branch` deve conter um arquivo `leiame.json` para ser exibido como versão da documentação. Se você quiser remover um branch da documentação, basta excluir o arquivo leiame.json do mesmo.