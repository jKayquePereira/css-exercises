# Um estilo 'modal' comum
Este é outro padrão muito comum na web. A solução para esta é _simples_... mas pode não ser imediatamente óbvia para você. Você precisará editar um pouco o HTML para colocar tudo onde precisa estar.

### Uma dica
Dependendo de como você aborda isso, pode ser necessário revisitar a propriedade `flex-shrink` para evitar que um item flexível seja quebrado. Além disso, preste atenção à estrutura do HTML, procure especificamente adicionar um contêiner adicional ao redor do cabeçalho, botão, texto principal, cancelar e continuar divs; e procure mover o div do cabeçalho para abranger o botão também.

## Resultado desejado

![resultado desejado](./desired-outcome.png)

### Autoverificação

- O ícone azul está alinhado à esquerda.
- Há espaço igual em ambos os lados do ícone (os espaços entre o ícone e a borda do cartão, e entre o ícone e o texto, são iguais).
- Há preenchimento ao redor da borda do modal.
- O cabeçalho, o texto e os botões estão alinhados entre si.
- O cabeçalho está em negrito e tem um tamanho de texto um pouco maior que o texto.
- O botão Fechar está alinhado verticalmente com o cabeçalho e no canto superior direito do cartão.