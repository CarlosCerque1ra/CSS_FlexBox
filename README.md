# *FlexBox
Propriedades principais do Flexbox:
<br>
1. **Propriedades do contêiner (container flex)**
display: <br>
flex;: Define o contêiner como um flex container.<br>
flex-direction: Define a direção dos itens (por padrão, é row, ou seja, da esquerda para a direita). Pode ser row, column, row-reverse ou column-reverse.<br>
justify-content: Alinha os itens ao longo do eixo principal (horizontal ou vertical, dependendo da direção do flex). Exemplo: flex-start, flex-end, center, space-between, space-around.<br>
align-items: Alinha os itens no eixo perpendicular ao eixo principal. Exemplo: flex-start, flex-end, center, baseline, stretch.<br>
flex-wrap: Define se os itens devem quebrar em várias linhas ou não (quando o conteúdo excede o tamanho do contêiner). Exemplo: nowrap, wrap, wrap-reverse.<br>

**3. Propriedades dos itens flexíveis (flex items)**<br>
flex-grow: Define como os itens devem crescer para preencher o espaço disponível. Por exemplo, se um item tiver flex-grow: 1, ele ocupará todo o espaço restante no contêiner.<br>
flex-shrink: Define como os itens devem encolher quando o espaço é limitado.<br>
flex-basis: Define o tamanho inicial de um item antes de o espaço ser distribuído.<br>
align-self: Permite que itens individuais sobreponham o valor de align-items do contêiner. Exemplo: auto, flex-start, flex-end, center, baseline, stretch.<br>
