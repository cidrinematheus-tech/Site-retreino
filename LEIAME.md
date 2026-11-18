# ReTreino Studio – Site institucional

Site de página única (HTML + CSS + JS puro, sem dependências).

## Estrutura de arquivos

```
retreino-site/
├── index.html
├── LEIAME.md
└── assets/
    ├── logo-retreino.jpg
    ├── grupo.jpg, aluna-1.jpg, aluna-2.jpg   (seção "Quem treina com a gente")
    └── estudio-1.jpg, estudio-2.jpg          (seção "Estúdio")
```

Todas as imagens já estão incluídas. Para trocar uma foto, salve a nova com o mesmo nome na pasta `assets/`.
As fotos são exibidas inteiras (sem corte). Se mudar a proporção, ajuste os atributos `width`/`height` e o valor `flex:` da foto no `index.html`.

> Use fotos de alunos somente com autorização deles.

## O que mudou nesta versão

- Logo oficial no cabeçalho; espaço da foto da mulher treinando **removido** do topo.
- Nova seção **Quem treina com a gente** com as 3 fotos reais, sem cortes.

- Faixa superior com o endereço: *Rua Deputado Altair de Oliveira Lima, 79 – em frente ao Horto de Itaipava* (clicável, abre o Google Maps).
- **Pin de localização em destaque** no início do site (com animação), abrindo o mapa.
- Todos os botões de contato ("Comece por você", "Quero conhecer o ReTreino", "Fale com o ReTreino", "Contato" no menu) abrem o **WhatsApp (24) 98109-6118** com mensagem pronta.
- Botão flutuante do WhatsApp no canto da tela.
- Botão **Ver perfil no Instagram** (@cidrinetreinador).
- Currículo: *Mestre em Ciências do Exercício e do Esporte pela UERJ* (texto, destaque e selo).
- Seção "ReTreino Longe" **removida** (menu e botões). No lugar, a seção **Estúdio** com as duas fotos.
- Endereço corrigido para "Oliveira **Lima**" e WhatsApp adicionado ao bloco de contato.

## Como personalizar

- **Mensagem do WhatsApp:** procure por `wa.me/5524981096118?text=` no `index.html`. O texto depois de `text=` é a mensagem (codificada para URL).
- **Instagram:** procure por `instagram.com/cidrinetreinador`.
- **Mapa:** o link usa a busca do Google Maps pelo endereço. Se preferir o pin exato, abra o local no Google Maps, clique em "Compartilhar" > "Copiar link" e substitua os links `google.com/maps/search/...`.

## Como publicar

Envie a pasta inteira (mantendo `assets/`) para qualquer hospedagem estática: Netlify (arrastar e soltar a pasta), GitHub Pages, Vercel, Cloudflare Pages ou hospedagem tradicional via FTP.

## Observação

O Instagram estava como `cidrine_treinador` no arquivo original; usei `cidrinetreinador`, como você pediu. Confirme se é o perfil correto.
