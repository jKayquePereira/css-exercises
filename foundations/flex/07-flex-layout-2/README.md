# O Santo Graal do Layout

Neste último exercício de flexbox, você recriará um layout de site incrivelmente comum. É tão comum que costuma ser chamado de layout [Santo Graal](https://www.google.com/search?q=holy+grail+layout&tbm=isch&sclient=img)... e com o flexbox é realmente bonito fácil de retirar.

Assim como no exercício anterior, deixamos um pouco mais para você fazer.

### Dicas
- Você precisará alterar a direção flexível para empurrar o rodapé para baixo.
- Você precisará adicionar alguns divs como contêineres para que as coisas se alinhem corretamente.
- `flex-wrap` ajudará a alinhar os cartões corretamente.
- Certifique-se de definir quanto espaço os cartões devem ocupar, para que o `flex-wrap` funcione conforme o esperado.

## Resultado desejado

![resultado desejado](./desired-outcome.png)

O número de cartas alinhadas nessa seção mudará com base na largura da tela, então não se preocupe em obter _exatamente_ uma grade 2x3 ou 3x2.

Em uma tela menor ficará assim:

![menor](./desired-outcome-smaller.png)

Observação: os emojis podem aparecer como um ou vários símbolos de texto (por exemplo, ☆♂) se você não tiver uma família de fontes baseada em emojis instalada em seu sistema operacional. Isso não afeta o exercício e pode ser ignorado.

### Autoverificação
- O texto do cabeçalho tem tamanho 32px e peso 900.
- O texto do cabeçalho é centralizado verticalmente e a 16px da borda da tela.
- O rodapé é empurrado para a parte inferior da tela (o rodapé pode ficar _abaixo_ da parte inferior da tela se o conteúdo da seção 'cartões' transbordar e/ou se sua tela for mais curta).
- O texto do rodapé é centralizado horizontal e verticalmente.
- A barra lateral e os cartões ocupam todo o espaço disponível acima do rodapé.
- A barra lateral tem 300px de largura (e não encolhe).
- Os links da barra lateral têm tamanho 24px, são brancos e não possuem decoração de texto sublinhado.
- A barra lateral possui preenchimento de 16px.
- Há um preenchimento de 48px ao redor da seção 'cartões'.
- Os cartões são organizados horizontalmente, mas se transformam em várias linhas quando ficam sem espaço na página.