# Tipografia
- Assim como as cores influenciam nos nossos sentimentos, as fontes também.
- Surgiu no século XV quando prensas mecânicas eram usadas para produzir livros/jornais.
- Antes, os livros eram escritos todos à mão por monges copistas.
- Quem invento a prensa mecânica foram os chineses, mas ficou popularmente conhecida com o 

## Fonte, letra e família
### Glifos, letras, caracteres
- Signos (símbolos) alfabéticos projetados para a reprodução mecânica.
- Glifo == letra == caractere.

### Família tipográfica
- Conjunto de glifos que possuem as mesmas características mecânicas.

### Fontes
- Conjunto de glifos que forma uma família tipográfica. Conjunto de glifos de uma determinada família == fonte.

### As fontes falam?
- As fontes também passam emoções.
- Chamamos de legibilidade palavras ou frases que podemos entender facilmente.
- Leiturabilidade é a capacidade de leitura de uma fonte, se conseguimos ler com fluidez.
- Fontes serifadas: guiam o leitor na leitura de textos grandes. Utilizado bastante em livros. 
- Fontes não serifadas (sans-serif): Trasmitem a sensação de limpeza, clareza e organização. É como se o cérebro criace uma linha imaginária que nos guia na leitura.
- Curiosidade: o nosso cérebro não lê letra-por-letra, mas a palavra como um todo. Ele só precisa da primeira e última letra estejam no lugar correto.
- Monoespaçadas: todas as letras possuem a mesma largura. Facilita muito a leitura das palavras. Também são chamadas de *fonte de terminal* ou *fonte de console*.
- Fontes de Script: tentam imitar a escrita humana. Nunca deve ser usada em textos longos. 
- Fontes Display: Todas as fontes que fogem das outras categorias são chamadas fontes display.

# Aplicando isso na prática
- Para alterar a família tipográfica da fonte utiliza:
`font-family: Arial, Helvetica, sans-serif;`
- Você está dizendo para o navegador para dar preferência a primeira fonte, caso não encontre dê prioridade para a próxima. A última normalmente é a família genérica.
- Tamanhos das fotes:
    - **cm**: centímetro.
    - **in**: polegadas.
    - **pt**: pontos.
    - **pc**: paicas.
    - **px**: píxels.
    - **em**: medida referencial em relação ao tamanho original da fonte. Normalmente o tamanho das fotes são de 16px, isso equivale a 1em.
- Para deixar a fonte em itálico:
`font-style: italic;`
- Para deixar em negrito:
`font-weight: bold;`
- Todas as configurações de fontes são:
```
p {
    font-family: Arial, Helvetica, sans-serif; /* Tipografia da fonte */
    font-size: 1em; /* Tamanho da fonte */
    font-style: italic; /* Deixa a fonte em itálico */
    font-weight: bold; /* Configuração para deixar a fonte em negrito */
}
```
- Podemos simplificar e usar: 
```
p {
    font: italic bold 1em Arial, Helvetica, sans-serif;
}
```
- Lembrando que segue essa mesma ordem.
- Podemos alinhar as fontes também.
    - `text-align: center;`
    - `text-align: justify;`
    - `text-align: left;`
    - `text-align: right;`

