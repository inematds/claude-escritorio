# Prompt 2 — a sua marca vira um design system

**O que é design system:** o "manual da marca" que o Claude guarda e usa sozinho — cores, fontes, logo,
espaçamento e estilo das imagens. Você monta uma vez; toda peça depois nasce com a sua cara.

**Do que o Claude precisa (uma fonte só já basta para começar):**
- um PDF ou apresentação da marca que você acha bonita;
- prints das páginas principais do seu site;
- o logo (de preferência em versão clara e escura) e o nome das fontes, se souber;
- se a marca está em código (site em React, por exemplo), o repositório.

**Onde:** numa conversa (anexe os arquivos) ou em Configurações › Capabilities › Design systems › Manage.
O site separado claude.ai/design fecha em 14/12/2026; quem tem design system lá migra pela página Artifacts.

```
Anexei [o PDF da marca / prints do meu site / meu logo]. Crie um design system da minha marca para eu usar
em documentos, apresentações e peças de design.

1. Extraia: paleta (com código de cor e para que serve cada cor), fontes de título e de texto, uso do logo
   (fundo claro e escuro), espaçamentos, cantos, estilo de ícone e estilo de foto/ilustração.
2. Me mostre uma página de amostra: capa de apresentação, um slide de conteúdo, um post quadrado e um botão.
3. Liste o que você NÃO achou nos arquivos (ex.: "não há versão do logo para fundo escuro") e me pergunte
   antes de inventar.
4. Escreva 5 regras curtas de "faça / não faça" desta marca.
```

**Revise uma vez:** o design system sai aproximado. Confira as cores com o código oficial (se tiver) e
corrija o que estiver errado pedindo na conversa ("o azul certo é #1E40AF").

Modelo do que conferir: `../design-system-modelo.md`.
