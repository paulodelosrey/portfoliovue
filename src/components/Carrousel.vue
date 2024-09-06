<template>
    <div class="carousel-container">
        <div class="carousel rounded-box">
          <div class="carousel-item">
              <div class="text-overlay">
                  <a href="https://github.com/paulodelosrey/forohub" target="_blank" rel="noopener noreferrer"><h2>API Rest Java & Sprigboot: Forohub</h2></a>
              </div>
                <img
                    src="/public/forohub.jpg"
                    alt="Forohub" />
            </div>
            <div class="carousel-item">
                <img
                    src="/public/letspracticeenglish.jpg"
                    alt="Let's practice english" />
                <div class="text-overlay">
                    <a href="https://letspracticespeaking.netlify.app/" target="_blank" rel="noopener noreferrer"><h2>Let's practice Speaking: Astro & React</h2></a>
                </div>
            </div>
            <div class="carousel-item">
                <img
                    src="/public/literalura.jpg"
                    alt="Literalura" />
                <div class="text-overlay">
                    <a href="https://github.com/paulodelosrey/literalura-oracle" target="_blank" rel="noopener noreferrer"><h2>Literalura: Consumo de API con persitencia</h2></a>
                </div>
            </div>
            <div class="carousel-item">
                <img
                    src="/public/stickyresume.jpg"
                    alt="Sticky Resume" />
                <div class="text-overlay">
                    <a href="https://stickyresume.netlify.app/" target="_blank" rel="noopener noreferrer"><h2>Sticky Resume: Plantilla para tu portafolio</h2></a>
                </div>
            </div>
            <div class="carousel-item">
                <img
                    src="/public/convertidor.jpg"
                    alt="Convertidor de Moneda Java" />
                <div class="text-overlay">
                    <a href="https://github.com/paulodelosrey/convertidor-de-moneda-java" target="_blank" rel="noopener noreferrer"><h2>Convertidor de Moneda Java</h2></a>
                </div>
            </div>
            <div class="carousel-item">
                <img
                    src="/public/textencoder.jpg"
                    alt="Text encoder" />
                <div class="text-overlay">
                    <a href="https://textencoder.netlify.app/" target="_blank" rel="noopener noreferrer"><h2>Text encoder: Astro & Tailwind</h2></a>
                </div>
            </div>
            
        </div>
    </div>
</template>

<style>
    .carousel-container {
        width: 100%;
        overflow-x: auto;
        padding: 20px 0;
    }

    .carousel {
        display: flex;
        gap: 20px;
        width: max-content;
    }

    .carousel-item {
        position: relative;
        flex: 0 0 auto;
        width: 300px;
    }

    img {
        display: block;
        width: 100%;
        height: 400px;
        object-fit: cover;
    }

    .text-overlay {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: rgba(0, 0, 0, 0.5);
    }

    .text-overlay > a {
        text-decoration: none;
    }

    .text-overlay > a > h2 {
        color: white;
        font-size: 24px;
        text-align: center;
        transition: all 0.3s ease;
    }

    .text-overlay > a > h2:hover {
        color: black;
        font-weight: bolder;
        font-size: 30px;
        background-color: white;
        padding: 10px;
    }

    /* For Webkit browsers like Chrome/Safari */
    .carousel-container::-webkit-scrollbar {
        height: 8px;
    }

    .carousel-container::-webkit-scrollbar-track {
        background: #f1f1f1;
    }

    .carousel-container::-webkit-scrollbar-thumb {
        background: #888;
        border-radius: 4px;
    }

    .carousel-container::-webkit-scrollbar-thumb:hover {
        background: #555;
    }

</style>

<script>
export default {
    name: 'Carrousel',
}
</script>
