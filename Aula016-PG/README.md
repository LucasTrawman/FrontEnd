# Conteúdo:

Lista dos conteúdos:

1. `<form>` tag para formulário, todos os elementos que queremos colocar no formulário irão dentro desta tag;
  * Atributos da tag `<form>`:
    1. `action`: define a rota que os dados do form serão processados
    2. `method`: define como serão processados os dados do form (qual o método). na versão do HTML atual, existem duas opções: GET ou POST;
2. `<input>` usado dentro da tag `<form>`, compõe boa parte do formulário
    1. com o atributo `type` usado na tag `<input>` serve para escolhermos a função do input;
    2. com o atributo `name` identifica os campos do input, é o indice para o envio das informações, sem este atributo os dados não são enviados;
    3. o atributo `id` deve conter o mesmo conteúdo do `for`, que é um atributo usado na tag label;
3. `<label>` atribui um texto descritivo a um campo;
    1.`for` responsável por associar a tag label a um campo pela sua propriedade `id`;
4. todo campo terá um label associado, quando o usuário fizer o clique no label, se ativará o campo associado a esse label;
5. `<textarea>` esta tag diferente dos outros elementos de input permite escrever muitas linhas;
6. `<select>` abre a possibilidade de opções para o usuário, também precisa do parâmetro name para enviar dados;
7. as opções da tag `<select>` são formadas pela tag `<option>`
    * o atributo `value` vinculado a tag `<option>` é o que será enviado pelo formulário;
8. `<button>` permite criar um botão;
    * a propriedade `type` associada a tag `<button>` define o tipo do botão, podendo assumir o valor de `reset`, que reinicia o formulário,
    `submit` que envia os dados e `button` que não assume valor nenhum mas pode ser configurado no JS;


    
