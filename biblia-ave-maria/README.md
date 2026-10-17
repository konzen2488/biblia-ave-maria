# Bíblia Ave Maria — arquivos divididos

O arquivo original foi separado em:
- `index.json`: lista de livros, ordem, caminho do arquivo e quantidade de capítulos.
- `livros/*.json`: um arquivo JSON por livro bíblico.

## Uso no FlutterFlow
1. Publique `index.json` e a pasta `livros/` em um repositório GitHub público.
2. Para listar os livros, consulte o `index.json`.
3. Ao selecionar um livro, faça GET do arquivo indicado em `arquivo`.
4. O arquivo de cada livro contém `nome` e `capitulos`; cada capítulo contém os versículos.

Atenção: o GitHub Raw entrega arquivos estáticos; ele não filtra capítulos no servidor. Cada arquivo por livro reduz o volume transferido em comparação com baixar a Bíblia inteira.
