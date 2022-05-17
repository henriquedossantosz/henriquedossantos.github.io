<script>
	import Capa from "./Capa.svelte";
	import Secao from "./Secao.svelte";
	import Rodape from "./Rodape.svelte";
	import Divisao from "./Divisao.svelte";
</script>

<Capa />

<Secao titulo="Sobre mim" centralizarTexto={true}>
	<p>
		Aluno do IFSP
	</p>
</Secao>

<Divisao></Divisao>

<Secao titulo="Competências">
		<ul>
			<li>
				<strong>Proficiência:</strong> Exemplos
			</li>
			<li>
				<strong>Aprendizagem</strong> Exemplos
			</li>
		</ul>
</Secao>

<Divisao></Divisao>

<Secao titulo="Experiência">
	<div>
		<h2>Exemplo</h2>
		<span>Exemplo</span>
		<ul>
			<li>Exemplo</li>
			<li>Exemplo</li>
		</ul>
	</div>
</Secao>

<Divisao></Divisao>

<Secao titulo="Conquistas">
	<ul>
		<li>Exemplo</li>
		<li>Exemplo</li>
	</ul>
</Secao>

<Divisao></Divisao>

<Rodape></Rodape>