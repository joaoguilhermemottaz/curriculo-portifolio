portifolio

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <link rel="stylesheet" href="styles.css">

    <link href="/fontawesome-free-6.6.0-web/css/fontawesome.css" rel="stylesheet" />
    <link href="/fontawesome-free-6.6.0-web/css/brands.css" rel="stylesheet" />
    <link href="/fontawesome-free-6.6.0-web/css/solid.css" rel="stylesheet" />
    
</head>

<body>

    <div class="container">
        <div class="esquerda">
            <h1>João Guilherme</h1>
            <img src="WhatsApp Image 2024-08-27 at 9.06.26 AM.jpeg"></img>


            <h2>
                <i class="fa-solid fa-address-book"></i>
                Contato</h2>
            <div class="informacoes">
                <p>
                    <i class="fa-brands fa-linkedin"></i>
                    Linkedin:
                    <a href="https://www.linkedin.com/in/jo%C3%A3o-guilherme-motta-zelenkovas-1bb29a253/">Linkkedin</a>
                </p>
            
                <p>
                    <i class="fa-solid fa-phone"></i>
                    Telefone: <a href="https://web.whatsapp.com/">(43) 99139-6809<a></p>
                <p>
                    <i class="fa-solid fa-envelope"></i>
                    Email: <a href="https://www.icloud.com/mail/">joaomottaz@icloud.com</a></p>
                <p>
                    <i class="fa-brands fa-instagram"></i>
                    Instagram: <a href="https://www.instagram.com/">joao_mottazl</a></p>
            </div>

            <h2>
                <i class="fa-solid fa-kitchen-set"></i>
                Habilidades e Competências</h2>
            <div class="informacoes">
                <p>Sou um jovem de 20 anos, solteiro, cristão, estudante, moro com a minha família e em busca de
                    crescimento profissional e pessoal</p>
                <p>Decidido e otimista. Sou motivado por novos desafios e me concentro em resultados</p>



                <h2>
                    <i class="fa-solid fa-language"></i>
                    Idiomas</h2>
                <div class="informacoes">
                    <p>Português</p>
                    <p>Inglês Basico</p>
                </div>
            </div>
        </div>

        <div class="direita">
            <h2>
                <i class="fa-solid fa-user-tie"></i>
                Experiencias Profissionais</h2>
            <div class="informacoes">
                <p>Grupo Kinder: Monitor infantil</p>
                <p>Periodo: 3 Meses</p>
                <p>Microlins Centro: Monitor dos professores e dos alunos;</p>
                <p>Periodo: 4 Anos</p>


                <h2>
                    <i class="fa-solid fa-school"></i>
                    Formação Academica</h2>
                <div class="informacoes">
                    <p>Cursando Engenharia de Software</p>
                    <p>Universidade Positivo</p>
                    <p>Período Matutino</p>
                    <p>Ensino Médio Concluido</p>
                    <p>Data: 19/12/2021</p>
                </div>
            </div>
        </div>
    </div>
</body>

</html>



css


html, body {
    width: 100%;
    height: 100%;
    margin: 0;
    padding: 0;
}

.container {
    display: flex;
}

.informacoes {
    flex-direction: column;
    gap: 5px;
}

.esquerda {
    width: 30vw;
    background-color:#CEE4EA;

    padding: 55px;
}

.direita {
    width: 70vw;
    padding-left: 30px;
    background-color:#CEE4EA;
}

img {
    height: 300px;
    width: 300px;
}
