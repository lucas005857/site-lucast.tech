# Site Lucas Torres Tecnologia

Arquivos do site [lucast.tech](https://www.lucast.tech): uma página única (`index.html`) com início, sobre, serviços, aplicativos, livro, cinema, certificações, notícias e contato. A página "Sites da Infância" (os primeiros sites criados por Lucas) fica dentro do mesmo arquivo, em [lucast.tech/infancia](https://www.lucast.tech/infancia).

Tecnologia acessível feita em Vitória, ES, Brasil, com foco em acessibilidade.

## Como funciona
- É um site estático: HTML, CSS e JavaScript na mesma página, sem etapa de instalação ou build.
- As páginas (como `/infancia` ou `/sobre`) são seções do `index.html`. O arquivo `_redirects` manda qualquer endereço para o `index.html`, e o JavaScript mostra a seção certa.
- Para ver localmente, abra o `index.html` no navegador.

## Arquivos
| Arquivo | Para que serve |
|---|---|
| `index.html` | O site inteiro (HTML, CSS e JS na mesma página) |
| `logo.png` | Logo / ícone |
| `sitemap.xml` | Mapa do site para buscadores |
| `robots.txt` | Regras para robôs de busca |
| `llms.txt` | Resumo do site para IAs |
| `_redirects` | Regras de redirecionamento da hospedagem (Netlify) |

## Publicação
A hospedagem é feita na Netlify, apontando para a raiz desta pasta. Ao mudar o `index.html`, publique de novo e confira `sitemap.xml` e `llms.txt` se algum endereço mudou.

## Contato
Site oficial: https://www.lucast.tech
