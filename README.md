# Cuidar de Quem Cuida

Site de orientação para profissionais de saúde da Amazônia sobre burnout, automedicação, pausas ativas, alimentação no plantão e onde pedir ajuda.

Projeto acadêmico dos cursos de Farmácia, Educação Física e Nutrição da Faculdade Serra Dourada, Altamira (PA).

## Arquivos

| Arquivo | Para que serve |
| --- | --- |
| `index.html` | O site inteiro (aparência, conteúdo e lógica), comentado em português |
| `_headers` | Regras de segurança do servidor (Netlify e Cloudflare Pages) |
| `.nojekyll` | Faz o GitHub Pages publicar o arquivo como está |

## Publicar no GitHub Pages

1. No repositório, abra **Settings → Pages**.
2. Em **Source**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`, e salve.
3. Em alguns minutos o site fica disponível em `https://ricardocontapremium-sketch.github.io/cuidar-de-quem-cuida/`.
4. O link do convite para colegas (`SITE_URL` no `index.html`) já aponta para esse endereço. Se mudar o nome do repositório, atualize-o.

O GitHub Pages não lê o arquivo `_headers`. Para ter as regras de segurança nele, siga as instruções no comentário do topo do `index.html`.

## Onde editar o conteúdo

Veja o comentário no topo do `index.html`: ele indica onde ficam as perguntas do teste, as recomendações, as rotinas de pausa e a lista de psicólogos parceiros.

## Privacidade

O site não envia dados a servidor e não guarda nada no aparelho. Não há cookies nem rastreadores.
