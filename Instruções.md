## 1. Estrutura inicial
- [ ] Crie um projeto com a estrutura base do HTML;
- [ ] Estruture a aplicação utilizando HTML semântico;
- header, section, footer;

---

## 2. Requisitos
### Título principal da página
- [ ] Exibir o nome da cidade ou local turístico em destaque;

### Seção de introdução
- [ ] Um subtítulo ou chamada (“Sua próxima viagem”, “Conheça [Cidade]” etc.);
- [ ] Um parágrafo introdutório apresentando o local;

### Imagem principal
- [ ] Incluir uma imagem em destaque do local (com bordas arredondadas);
- [ ] Adicionar uma legenda abaixo da imagem.

### Seção de destaques/atrações
- [ ] Um subtítulo chamativo (ex: “Descubra 3 destinos imperdíveis em [Cidade]”);
- [ ] Um parágrafo com informações gerais sobre os atrativos da cidade;
- [ ] Exibir pelo menos 3 atrações (com um título, um texto e uma imagem)

### Estilização com CSS
- [ ] Definir cores de acordo com o layout;
- [ ] Usar uma fonte de acordo com o layout;
- [ ] Criar espaçamentos (margem/padding) entre seções;
- [ ] Destacar o título principal;
- [ ] Adicionar bordas arredondadas nas imagens;
- [ ] Rodapé simples e centralizado, de acordo com o layout;

---

## 3. Desenvolvendo o projeto
Para desenvolver esse projeto, recomendamos utilizar as principais tecnologias que utilizamos durante o desenvolvimento do primeiro módulo da formação.

Caso você tenha alguma dificuldade você pode ir no nosso 
[fórum](https://forum.example.com)
 e deixar sua dúvida por lá!

Após terminar o desafio, caso você queira, você pode tentar dar o próximo passo e deixar a aplicação com a sua cara. Tente mudar o layout, cores, ou até adicionar novas funcionalidades para ir além! 🚀

---

## 4. Dicas
Boa parte do que você vai precisar para resolver este desafio foi apresentado em aula mas caso precise de mais ajuda, criamos essa seção com algumas dicas e possíveis dúvidas que você pode encontrar neste desafio, mas lembre-se sempre tente resolver o desafio antes de olhar esses pontos.

- Como ajustar tamanho da imagem para ocupar o tamanho do container?

Para que a imagem não fique gigante na página e ocupe apenas o tamanho de tela disponível você pode usar a propriedade width: 100%;

```css
img {
  border-radius: 28px;  /* Adicionar o arredondamento da borda */
  width: 100%; /* imagem ocupa 100% do tamanho disponível pra ela */
}
```
- Como criar a linha de divisão (divider)?
Existem várias formas de criar e estilizar essa linha. Um exemplo de como pode ser feito. No HTML você pode criar uma div com class divider (lembrando que pode ser qualquer nome):

```html
<div class="divider"></div>
```

No CSS você pode adicionar os estilos:

```css
.divider {
  width: 100%;
  height: 1px;
  margin: 36px 0;
  background-color: #d9d9d9;
}
```

Lembrando que se você fez de outra forma não quer dizer que fez errado, como mencionado acima, existem várias formas de criar este elemento, combinado?

- Como adicionar negrito e letras maiúsculas no texto?

Para alterar a espessura da fonte, você pode utilizar a propriedade font-weight. Se quiser deixar o texto em negrito, use o valor bold.

Para transformar o texto em maiúsculo sem ter que digitar todas as letras em maiúsculo, você pode usar a propriedade e valor text-transform: uppercase; . Ex.:

```css
.headline {
  font-size: 16px;
  line-height: 22px;
  font-weight: bold; /* A fonte fica em negrito */
  color: #e1624f;
  text-transform: uppercase; /* A fonte fica com todas as letras em maiúsculo */
}
```
📗 
[Documentação font-weight](https://developer.mozilla.org/en-US/docs/Web/CSS/font-weight)

📗 
[Documentação text-transform](https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform)

- Como mudar estilo da fonte para itálico?

Para mudar o estilo da fonte, você pode usar a propriedade do CSS font-style. Ex.:

```css
.subtitle {
  font-size: 16px;
  line-height: 22px;
  font-style: italic; /* Muda estilo da fonte para itálico */
  text-align: center;
  color: #333333;
  margin-top: 24px;
}
```

- Como corrigir imagem distorcida?

Em alguns casos quando ajustamos a altura da imagem ela pode ficar um pouco distorcida. Uma forma de corrigir esse problema é adicionar a propriedade object-fit no CSS dessa imagem. Ex.:

```css
main div img {
  height: 375px;
  object-fit: cover; /* Ajusta a proporção da imagem*/
  margin-top: 44px;
}
```

📗 
[Documentação object-fit](https://developer.mozilla.org/pt-BR/docs/Web/CSS/object-fit)

- Como criar o bullet da lista com cor diferente do texto?

Se você notar bem, neste desafio vai ver que o bullet da lista tem uma cor diferente da cor do texto. Uma forma de resolver isso é usar o ::marker que é um pseudo-elemento, mas não se preocupe, você ainda vai aprender sobre isso nos módulos futuros, por hora, pode usar a dica abaixo:

```css
ul li::marker {
  color: #333333;
}
```

📗 
[Documentação ::marker](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker)

---

## 4. Entrega
Após concluir o desafio, você deve enviar a URL do seu código no Github.

Além disso, que tal fazer um post no LinkedIn compartilhando o seu aprendizado e contando como foi a experiência? É uma excelente forma de demonstrar seus conhecimentos e atrair novas oportunidades!

Obs: Se você se sentir à vontade, pode postar um print do resultado final e nos marcar! Vai ser incrível acompanhar a sua evolução! 💜

## 5. Considerações finais
Lembre-se que o intuito de um desafio é te impulsionar, por isso, dependendo do desafio, pode ser que você precise ir além do que foi discutido em sala de aula. Mas isso não é algo ruim: ter autonomia para buscar informações extras é uma habilidade muito valiosa e vai ser ótimo pra você treinar ela aqui com a gente!

E lembre-se: tenha calma! Enfrentar desafios faz parte do seu processo de aprendizado!

Se precisar de alguma orientação ou suporte, estamos aqui com você! Bons estudos e boa prática! 💜
