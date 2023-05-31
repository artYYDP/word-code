# Adicionando um campo de código no Microsoft Word: Um guia prático
## Domine a inclusão de campos de código no Word: Um guia passo a passo

> <sup>Você baixar esse documento em PDF <a href="https://github.com/artYYDP/word-code/blob/main/pdf/Adicionando%20um%20campo%20de%20c%C3%B3digo%20no%20Microsoft%20Word%20-%20Um%20guia%20pr%C3%A1tico.pdf">clicando aqui!</a></sup>

No mundo em que vivemos hoje, estamos imersos nas novas tecnologias, o que faz com que o mundo tecnológico nos impacte de maneiras indiretas. Isso é especialmente relevante para profissionais da área de tecnologia, que muitas vezes precisam formatar documentos no Word e enfrentam a falta de recursos que possam auxiliá-los nessa tarefa.

Neste documento, abordaremos uma das maneiras de inserir trechos de código de programação no Word, de forma que não fiquem apenas como texto comum.  

## Passo-a-passo

1. Instale um plugin chamado <a href="https://appsource.microsoft.com/pt-BR/product/office/WA104382008?corrid=f650c752-e3fd-88aa-e981-f6344a39628b&src=office&exp=kyyw">**Easy Code Formatter**</a>, que pode ser acessado no próprio site da <a href="https://appsource.microsoft.com/pt-BR/home?exp=kyyw">Microsoft</a>.
2. Depois de permitir e logar na sua conta da Microsoft, o plugin deverá exibir um documento como padrão. Pode fechá-lo e abrir outro novo ou o documento que deseja colocar o código.
3. Vá até a parte superior do seu documento e selecione a aba **Easy Code Formatter**.

<img src="https://github.com/artYYDP/word-code/blob/main/img/Word-Code-01.png">

4. Antes de mais nada, precisamos configurar como o código será exibido no documento. Clique no botão **Code formatter settings**.

<img src="https://github.com/artYYDP/word-code/blob/main/img/Word-Code-02.png">

5. Irá aparecer uma janela ao lado direito do seu documento. Clique na "engrenagem" para continuar.

<img src="https://github.com/artYYDP/word-code/blob/main/img/Word-Code-03.png">

6. Há algumas opções de configuração:
   - **Themes:** é o tema que você deseja usar no seu projeto. No meu caso usarei o tema **Desert**;
   - **Fonts:** que tipo de fonte terá o seu código. No meu caso usarei a fonte **Consolas** e o tamanho **10**;
   - **Higlighting:** caso você queira destacar uma parte específica do seu código, você poderá usar essa função para mudar a cor de fundo da seleção. No meu caso eu não irei alterar nada;
   - **Line Numbering:** caso você queira colocar o número da linha dentro do código, você pode fazer com essa função. No meu caso vou deixar **desativado**.

<img src="https://github.com/artYYDP/word-code/blob/main/img/Word-Code-04.png">

7. Agora, depois de configurado, vamos aplicar no seu texto para que ele pareça um código. Para fazer isso, cole o código no documento do Word (ou, caso você já tenha um código no documento, selecione o mesmo).

<img src="https://github.com/artYYDP/word-code/blob/main/img/Word-Code-05.png">

8. Vá na aba do plugin, ou, caso esteja aberto no lado direito, clique em **Format text as code**.

<img src="https://github.com/artYYDP/word-code/blob/main/img/Word-Code-06.png">

<img src="https://github.com/artYYDP/word-code/blob/main/img/Word-Code-07.png">

```php
<?php
 
// Exemplo de função em PHP para somar dois números
function somar($a, $b) {
    $resultado = $a + $b;
    return $resultado;
}
 
// Variáveis para teste
$num1 = 5;
$num2 = 3;
 
// Chamada da função e exibição do resultado
$soma = somar($num1, $num2);
echo "A soma de $num1 e $num2 é igual a $soma.";
 
?>
```

Pronto! Dessa forma o seu documento ficará muito mais bonito visualmente.

Enjoy!
