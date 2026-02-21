<<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>La Carta de Foxy</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            background-color: #000;
            font-family: 'Courier New', Courier, monospace;
            overflow: hidden;
        }

        .contenedor {
            position: relative;
            width: 100vw;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
        }

        .pantalla {
            position: absolute;
            width: 100%;
            height: 100%;
            object-fit: contain;
            transition: opacity 0.5s ease-in-out;
        }

        #foxy-nuevo {
            opacity: 0;
            z-index: 10;
            transform: scale(1);
            transition: opacity 0.1s ease-in-out, transform 0.8s ease-in-out;
        }

        .visible { opacity: 1 !important; }
        .foxy-cerca { transform: scale(1.05) !important; }

        #pagina-carta {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: #f4e4bc;
            background-image: url('https://www.transparenttextures.com/patterns/paper-fibers.png');
            z-index: 100;
            display: none;
            flex-direction: column;
            align-items: center;
            padding: 40px;
            box-sizing: border-box;
            box-shadow: inset 0 0 100px rgba(0,0,0,0.2);
            overflow-y: auto;
        }

        .texto-carta {
            color: #3d2b1f;
            font-size: 1.2rem;
            line-height: 1.6;
            max-width: 600px;
            text-align: left;
        }

        .boton-cerrar {
            margin-top: 30px;
            padding: 10px 20px;
            background: #3d2b1f;
            color: #f4e4bc;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <audio id="sonidoGolpe" src="golpes.mp3"></audio>
    <audio id="sonidoPuerta" src="puerta_abre.mp3"></audio>
    <audio id="sonidoTierno" src="foxy_tierno.mp3"></audio>
    <audio id="sonidoCarta" src="sacar_carta.mp3"></audio>

    <div class="contenedor" id="escenaPrincipal" onclick="ejecutarMagia()">
        <img src="puerta.png" id="puerta" class="pantalla">
        <img src="puerta3.png" id="foxy-nuevo" class="pantalla">
    </div>

    <div id="pagina-carta">
        <div class="texto-carta">
            <h2 style="text-align: center;">Para vos, boludo...</h2>
            <p>Che, no sabés lo que me costó llegar hasta acá sin que me vea el guardia. Te dejo esto porque corte que sos copado.</p>
            <p>Espero que te guste la sorpresa que armamos. No te olvides de cerrar la puerta antes de dormir, flashás confianza y después pasa lo que pasa.</p>
            <p style="text-align: right;">— Foxy</p>
        </div>
        <button class="boton-cerrar" onclick="document.getElementById('pagina-carta').style.display='none'">Cerrar Carta</button>
    </div>

    <script>
        let pasoActual = 0;
        const foxy = document.getElementById('foxy-nuevo');
        const puerta = document.getElementById('puerta');
        
        // Referencias a los nuevos sonidos
        const sonidoGolpe = document.getElementById('sonidoGolpe');
        const sonidoPuerta = document.getElementById('sonidoPuerta');
        const sonidoTierno = document.getElementById('sonidoTierno');
        const sonidoCarta = document.getElementById('sonidoCarta');

        const contenedor = document.getElementById('escenaPrincipal');
        const cartaAbierta = document.getElementById('pagina-carta');

        function ejecutarMagia() {
            if (pasoActual !== 0) return;
            pasoActual = 1;

            sonidoGolpe.play();

            setTimeout(() => {
                // Suena la puerta al abrirse
                sonidoPuerta.play();
                puerta.src = "puerta2.png"; 

                setTimeout(() => {
                    // Aparece Foxy y suena el ruidito tierno
                    sonidoTierno.play();
                    foxy.classList.add('visible');

                    setTimeout(() => {
                        foxy.classList.add('foxy-cerca');

                        setTimeout(() => {
                            foxy.src = "foxy.png";

                            setTimeout(() => {
                                // Foxy saca la carta y suena el ruido de papel
                                sonidoCarta.play();
                                foxy.src = "foxy6.png";
                                
                                setTimeout(() => {
                                    pasoActual = 2; 
                                    contenedor.onclick = abrirCartaReal;
                                }, 500);

                            }, 4000); 

                        }, 800); 
                    }, 1000);
                }, 3000); 
            }, 2000); 
        }

        function abrirCartaReal() {
            cartaAbierta.style.display = 'flex';
        }
    </script>
</body>
</html>
