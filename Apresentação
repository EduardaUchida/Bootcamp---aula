<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Eduarda Uchida | Portfólio</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
:root{
    --gold:#d4af37;
    --dark:#0d1117;
    --dark2:#161b22;
    --text:#f0f6fc;
    --gray:#8b949e;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:var(--dark);
    color:var(--text);
}

header{
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:20px;
}

.hero{
    max-width:900px;
}

.hero h1{
    font-size:4rem;
    color:var(--gold);
}

.hero h2{
    margin:15px 0;
    color:var(--gray);
    font-weight:400;
}

.hero p{
    line-height:1.8;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    padding:12px 30px;
    background:var(--gold);
    color:#000;
    text-decoration:none;
    border-radius:8px;
    font-weight:600;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-3px);
}

section{
    padding:80px 10%;
}

.title{
    text-align:center;
    color:var(--gold);
    margin-bottom:40px;
    font-size:2rem;
}

.about{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:30px;
}

.card{
    background:var(--dark2);
    padding:25px;
    border-radius:15px;
    border:1px solid rgba(212,175,55,.2);
}

.skills{
    display:flex;
    flex-wrap:wrap;
    gap:15px;
    justify-content:center;
}

.skill{
    background:var(--dark2);
    padding:12px 20px;
    border-radius:30px;
    border:1px solid var(--gold);
}

.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:25px;
}

.project{
    background:var(--dark2);
    border-radius:15px;
    padding:25px;
    transition:.3s;
}

.project:hover{
    transform:translateY(-5px);
}

footer{
    text-align:center;
    padding:30px;
    background:var(--dark2);
}

.social{
    margin-top:20px;
}

.social a{
    color:var(--gold);
    text-decoration:none;
    margin:0 15px;
}

#typed{
    color:var(--gold);
}
</style>
</head>
<body>

<header>
    <div class="hero">
        <h1>Eduarda Uchida</h1>

        <h2>
            <span id="typed"></span>
        </h2>

        <p>
            Profissional de Tecnologia com experiência em suporte de TI,
            Service Desk e atendimento ao usuário. Atualmente cursando
            Análise e Desenvolvimento de Sistemas, buscando crescimento
            nas áreas de Infraestrutura, Desenvolvimento e Análise de Sistemas.
        </p>

        <a href="#contato" class="btn">Entrar em Contato</a>
    </div>
</header>

<section>
    <h2 class="title">Sobre Mim</h2>

    <div class="about">
        <div class="card">
            <h3>🎓 Formação</h3>
            <p>
                Técnica em Informática e estudante de
                Análise e Desenvolvimento de Sistemas.
            </p>
        </div>

        <div class="card">
            <h3>💼 Experiência</h3>
            <p>
                Atuação em Service Desk, suporte ao usuário,
                Active Directory, Azure, Microsoft 365,
                resolução de incidentes e atendimento corporativo.
            </p>
        </div>

        <div class="card">
            <h3>🚀 Objetivo</h3>
            <p>
                Evoluir profissionalmente na área de tecnologia,
                contribuindo com soluções eficientes e inovação.
            </p>
        </div>
    </div>
</section>

<section>
    <h2 class="title">Competências</h2>

    <div class="skills">
        <div class="skill">Service Desk</div>
        <div class="skill">Active Directory</div>
        <div class="skill">Azure</div>
        <div class="skill">Microsoft 365</div>
        <div class="skill">Suporte Técnico</div>
        <div class="skill">Java</div>
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Redes</div>
        <div class="skill">Git</div>
        <div class="skill">GitHub</div>
    </div>
</section>

<section>
    <h2 class="title">Projetos</h2>

    <div class="projects">

        <div class="project">
            <h3>Sistema de Países Olímpicos</h3>
            <p>
                Projeto desenvolvido em Java contendo
                informações sobre países participantes
                das Olimpíadas.
            </p>
        </div>

        <div class="project">
            <h3>Portfólio Profissional</h3>
            <p>
                Página responsiva para apresentação
                profissional e divulgação de projetos.
            </p>
        </div>

        <div class="project">
            <h3>Projetos Acadêmicos</h3>
            <p>
                Desenvolvimento de aplicações e soluções
                durante a graduação em ADS.
            </p>
        </div>

    </div>
</section>

<section id="contato">
    <h2 class="title">Contato</h2>

    <div class="card" style="text-align:center;">
        <p>Email: eduardauchida99@gmail.com</p>

        <div class="social">
            <a href="https://github.com/EduardaUchida" target="_blank">GitHub</a>
            <a href="https://linkedin.com" target="_blank">LinkedIn</a>
        </div>
    </div>
</section>

<footer>
    © 2026 Eduarda Uchida | Desenvolvido com HTML, CSS e JavaScript
</footer>

<script>
const textos = [
    "Analista de Suporte",
    "Estudante de ADS",
    "Técnica em Informática",
    "Apaixonada por Tecnologia"
];

let textoAtual = 0;
let letra = 0;

function digitar(){
    const elemento = document.getElementById("typed");

    if(letra < textos[textoAtual].length){
        elemento.innerHTML += textos[textoAtual].charAt(letra);
        letra++;
        setTimeout(digitar,80);
    }else{
        setTimeout(apagar,1500);
    }
}

function apagar(){
    const elemento = document.getElementById("typed");

    if(elemento.innerHTML.length > 0){
        elemento.innerHTML =
        elemento.innerHTML.slice(0,-1);

        setTimeout(apagar,40);
    }else{
        textoAtual = (textoAtual + 1) % textos.length;
        letra = 0;
        digitar();
    }
}

digitar();
</script>

</body>
</html>
