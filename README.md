# stratto-imagens

Hospedagem pública das imagens dos carrosséis de [@stratto.tech](https://www.instagram.com/stratto.tech/).

Este repositório existe por um motivo técnico: a API do Instagram **baixa** cada imagem
de uma URL pública — ela não aceita envio direto de arquivo. Então os JPEG precisam
estar acessíveis na internet no momento da publicação.

Aqui **só** existem imagens. O sistema que planeja, escreve e publica o conteúdo fica
em um repositório privado separado.

Servido por GitHub Pages em `https://peresdev777.github.io/stratto-imagens/`.

## Organização

```
AAAA-Wnn/<id-do-post>/01.jpg ... 06.jpg
```

Uma pasta por semana, uma subpasta por post, um arquivo por slide na ordem do carrossel.
