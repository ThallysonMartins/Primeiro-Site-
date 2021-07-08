# Primeiro-Site

<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <title>Barbearia Alura</title>
        <link rel="stylesheet" href="style.css">
     </head>
        
    <body>
        <header>
            <h1 class="titulo-principal">Barbearia Alura</h1>
        </header>
        <img id="banner" src="banner.jpg">
        <div class="principal">
            <h2 class="titulo-centralizado">Sobre a Barbearia Alura</h2>

            <p>Localizada no coração da cidade a <strong>Barbearia Alura</strong> traz para o mercado o que há de melhor para o seu cabelo e barba. 
            Fundada em 2019, a Barbearia Alura já é destaque na cidade e conquista novos clientes a cada dia.</p>

            <p id="missao"><em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes"</strong>.</em></p>

            <p>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. 
            O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
        </div>

        <div class="beneficios">
            <h3 class="titulo-centralizado">Beneficios</h3>

            <ul>
                <li class="intens">Atendimento aos Clientes</li>
                <li class="intens">Espaço diferenciados</li>
                <li class="intens">Localização</li>
                <li class="intens">Profissionais Qualificados</li>
            </ul>

            <img src="beneficios.jpg" class="imagembeneficios"> 
        </div>
    </body>
</html>


# CSS


body {
	
}

#banner {
	width: 100%;
}

.principal {
 	padding: 30px;
 	background: #CCCCCC
}

.titulo-principal{
	padding-left: 20px;
}

.titulo-centralizado {
	text-align: center
}

p {
	text-align: center;
}

#missao {
	font-size: 20px
}

em strong {
	color: red;
}

.intens {
	font-style: italic;
}

.beneficios {
	padding: 20px;
	background: #FFFFFF
} 


ul {
	display: inline-block;
	vertical-align: top;
	width: 20%;
	margin-right: 15%; 
}

.imagembeneficios {
	width: 50%;
}
