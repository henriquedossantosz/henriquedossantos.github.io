<script>
    import CaixaDeIcones from "./CaixaDeIcones.svelte";
</script>

<div class="fundo">
    <div class="centro">
        <img src="./img/henrique_foto.jpg" alt="Foto de Henrique" class="foto">
        <h1>Henrique Vieira</h1>
        <h2>Aluno do IFSP</h2>
        <h3>学生</h3>
        <CaixaDeIcones/>
    </div>
</div>

<style>
    .fundo {
        width: 100%;
        min-height: 100vh;
        background-color: #222b42;
    }
    .centro {
        color: white;
        text-align: center;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
    .foto {
        border-radius: 50%;
        width: 250px;
    }
</style>