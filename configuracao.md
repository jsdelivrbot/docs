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

> Lembramos que cada `branch` deve conter um arquivo `leiame.json` para ser exibido como versão da documentação.
> Se você quiser remover um branch da documentação, basta excluir o arquivo leiame.json do mesmo.

## Referência do arquivo leiame.json

| Parâmetro   | Tipo     | Descrição                                                             |
|-------------|:--------:|-----------------------------------------------------------------------|
| path        | string   | Caminho onde encontra-se os arquivos `*.md` dentro de seu repositório |
| branch_name | string   | Nome visual da versão para aparecer no popup de versões no canto superior da tela |
| sidebar     | string   | Caminha do arquivo *.md que será utilizado como sidebar da documentação |
| logo        | string   | URL completa de uma imagem que será utilizada como logo da documentação |
| favicon     | string   | URL completa de uma imagem que será utilizada como favicon das páginas da documentação |
| css         | string   | URL completa de um arquivo css que será injetado nas páginas da documentação. Para customização de visual |
| modules     | array    | Lista de módulos que você pode ativar em sua documentação. Veja [lista de módulos aqui](/modulos) |

> [Lista de módulos](/modulos)