# garatuja do Guilherme

## [HTML] 

HTML é, para mim, uma linguagem de marcação altamente intuitiva. Possui comandos claros e relativamente simples, exigindo apenas a compreensão de suas funcionalidades mais básicas para dar vida a diversas ideias.

<p>EXEMPLO:</p>

<pre>
<code>
&lt;body&gt;
  &lt;aside&gt;
    &lt;div class="thumb"&gt;
      &lt;img src="https://pbs.twimg.com/media/F02860mXoAIe2wG.jpg" alt="Sonic"&gt;
    &lt;/div&gt;
  &lt;/aside&gt;
&lt;/body&gt;
</code>
</pre>

criamos uma imagem do sonic, com nome de classe "thumb".

## [CSS]

CSS é uma linguagem de marcação feita para estilizar o HTML.
<p>EXEMPLO:</p>

<pre>
<code>
.thumb {
    border-radius: 50%;
}
</code>
</pre>

aqui, modificamos a classe "thumb" para diminuir seu raio na metade, tornando-a em um círculo.

## [COMPARAÇÃO DE LINGUAGEM]

| Comparação | TypeScript | JavaScript | Java |
|------------|------------|------------|------|
| **Função** | Pedaço de código que faz uma tarefa, com tipo definido. | Pedaço de código que faz uma tarefa, sem tipo fixo. | Não tem função sozinha, tudo fica dentro da classe. |
| **Método** | Função que está dentro de uma classe. | Função dentro de um objeto ou classe. | Função que fica dentro da classe. |
| **Variável** | Precisa dizer o tipo (`string`, `number`...). | O tipo muda sozinho durante o programa. | Precisa dizer o tipo sempre. |
| **Classe** | Modelo para criar objetos, com tipos definidos. | Modelo para criar objetos, sem tipos fixos. | Base da linguagem, tudo gira em torno de classes. |
| **Objeto** | Algo criado a partir da classe, seguindo os tipos. | Conjunto de informações em formato chave e valor. | Algo criado a partir de uma classe. |
| **Get** | Pega o valor de uma variável da classe. | Pega o valor de uma informação do objeto. | Método para pegar valor de variável privada. |
| **Set** | Muda o valor de uma variável da classe. | Muda o valor de uma informação do objeto. | Método para mudar valor de variável privada. |
| **Construtor** | Método especial chamado ao criar o objeto, com tipos definidos. 

## [CONCEITOS EXTRA]

| Conceito | TypeScript |
|----------|------------|
| **Construtor** | Método especial chamado ao criar o objeto, com tipos definidos. |
| **Herança** | Uma classe pode herdar de outra usando `extends`, mantendo os tipos. |
| **Encapsulamento** | Controle de acesso usando `private`, `public` e tipos. |
| **Polimorfismo** | Mesmo método pode ter comportamentos diferentes com tipagem. |


## [PERGUNTAS E RESPOSTAS]

| Pergunta               | Resposta                                  |
|----------              |---------                                  |
| O que é POO?           | Paradigma baseado em objetos              |
| Encapsulamento         | Esconder detalhes internos, EX: "private" |
| this                   | Referência ao objeto atual                |
| private                | Acessável apenas dentro da classe         |
