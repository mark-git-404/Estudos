---


---

<h1 id="conhecendo-react-native">Conhecendo React Native</h1>
<p>React é um framework, que pode ser escrito em JavaScript e TypeScript, com objetivo de facilitar a criação de  WebSites e Aplicativos Mobile.<br>
Assim, ReactJS programando para Web e React Native, para Mobile.</p>
<h2 id="antes-mesmo-de-utilizar">Antes mesmo de Utilizar!</h2>
<p>Entender as arquiteturas utilizada no React é de extrema importância, pois facilita, e muito, o ensino com React.</p>
<h3 id="jsx">JSX:</h3>
<p>JSX é uma sintaxe de tags utilizada pelo React e é utilizado para estruturar os componentes, e assim montar o app.</p>
<pre><code>&lt;View&gt;
	&lt;Text&gt; Hello Luna &lt;Text&gt;
&lt;View&gt;
</code></pre>
<p>Além disso é possivel adicionar parametros, chamados props, entre os brackets(&lt; &gt;) da tag, por exemplo:</p>
<pre><code>&lt;Text
	onPress = {função Java Script que será chamada}
	style = {{color: 'blue'}}
	&gt; 
	Hello World
 &lt;Text&gt; 
</code></pre>
<p>Nesse caso, os props são <em>onPress e style</em> e recebem uma expressao JavaScript que <strong>sempre</strong> , dentro de um <em>escopo JSX</em>, deve esta dentro de chaves.</p>
<h3 id="classes-e-funções---javascript">Classes e Funções - Javascript:</h3>
<p>JavaScript é uma Linguagem de Programação Orientada a Objetos, por mais estranho que pareça. Isso faz com que o JS contenha algumas funcionalidades que permitam-o, trabalhar de uma forma mais organizada. Entretanto o JS não é uma linguagem altamente tipada.</p>
<p>O TypeScript vem para isso. Ele é uma linguagem desenvolvida pela Microsoft como uma camada acima do JavaScript trazendo tipagem parecida com a do C# ( Linguagem também desenvolvida pela Microsoft ).</p>
<p>Classes em Java Script são definidas, assim:</p>
<pre><code>class Humano
{
	constructor(p_altura, p_massa, p_p) {
		this.altura = p_altura;
		this.massa = p_massa;
		this.sexo = p_sexo;
	}
	
	fala_texto(texto) {
		console.log(texto)	
	}
	
	fala_altura() {
		console.log(this.altura);
	}
	
}
</code></pre>
<p><strong>Agora Vamos destrinchar o codigo!</strong></p>

