# NEFASTO — demonstração interativa

Uma demonstração simples de um bot com estética gótica, feita com HTML, CSS e JavaScript puro.

## Como testar no Android

1. Baixe e extraia `NEFASTO.zip` no celular.
2. Abra `index.html` em um navegador compatível, se o gerenciador de arquivos permitir.
3. Digite `!menu`, `!ajuda`, `!sobre` ou `!perfil` e toque em **Enviar**.
4. Teste também uma mensagem desconhecida, como `oi`, para ver a resposta de ajuda.
5. Os botões de atalho acima da caixa de mensagem enviam comandos de exemplo.

Se o Android não abrir o HTML diretamente, use um editor/ambiente web que permita criar arquivos HTML (por exemplo, um editor HTML online), cole o conteúdo de `index.html` e execute a prévia.

## Comandos

- `!menu` — lista os comandos.
- `!ajuda` — instruções.
- `!sobre` — informações sobre o projeto e seu estado.
- `!perfil` — mostra um perfil fictício.
- Qualquer texto desconhecido — apresenta ajuda.

## Limitações desta versão

- Não está conectado ao WhatsApp.
- Não usa servidor, tokens, pagamentos ou credenciais.
- As mensagens existem apenas na página aberta; atualizar a página reinicia a conversa.
- É um protótipo de aprendizagem, não um bot de produção.

## Próximos passos sugeridos

1. Aprender a editar o HTML e o CSS.
2. Publicar a página como site estático (por exemplo, usando GitHub Pages).
3. Depois, estudar um backend e uma integração oficial/adequada com WhatsApp, sem expor tokens no navegador.
