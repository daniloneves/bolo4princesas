# Bolo 4 Princesas - Site de Pedidos

Site estático para apresentação do cardápio e envio de pedidos via WhatsApp.

## Visão geral

O projeto foi criado para facilitar pedidos da confeitaria Bolo 4 Princesas, com uma interface simples e responsiva.

Principais recursos:
- Exibição dos bolos com descrição e preço.
- Controle de quantidade por item.
- Resumo automático do pedido com total e taxa de entrega.
- Coleta de dados de entrega (nome, WhatsApp e endereço).
- Geração e abertura automática de mensagem no WhatsApp.
- Header fixo com logomarca em destaque e versão compacta ao rolar a página.

## Estrutura

- `index.html`: página principal com HTML, CSS e JavaScript.
- `logo_bolo_4_princesas.png`: logomarca utilizada no topo.

## Como executar localmente

Por ser um site estático, basta abrir o arquivo `index.html` no navegador.

Opção com servidor local (recomendado):

```bash
python3 -m http.server 8080
```

Depois, acesse:

```text
http://localhost:8080
```

## Publicação

Repositório remoto configurado em:

```text
git@github.com:daniloneves/bolo4princesas.git
```

Fluxo básico para atualizar:

```bash
git add .
git commit -m "Atualiza site"
git push
```
