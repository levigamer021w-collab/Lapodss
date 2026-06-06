<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lapodss</title>

    <style>
        :root {
            --bg: #0b0b10;
            --card: #141420;
            --roxo: #a855f7;
            --roxo2: #7c3aed;
            --texto: #ffffff;
            --cinza: #aaaaaa;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            background: var(--bg);
            color: var(--texto);
        }

        #ageModal, #cartModal {
            position: fixed;
            inset: 0;
            background: rgba(0, 0, 0, 0.95);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 99999;
        }

        #cartModal {
            background: rgba(0, 0, 0, 0.85);
            display: none;
        }

        .modal-box {
            background: #161623;
            padding: 30px;
            border-radius: 20px;
            max-width: 450px;
            width: 95%;
            text-align: center;
            border: 1px solid #2c2c40;
            max-height: 85vh;
            display: flex;
            flex-direction: column;
        }

        .modal-box h2 {
            color: var(--roxo);
            margin-bottom: 15px;
            font-size: 24px;
        }

        .modal-box p {
            margin-bottom: 25px;
            color: #ccc;
            font-size: 16px;
            line-height: 1.4;
        }

        /* Lista interna do carrinho */
        .cart-items-container {
            overflow-y: auto;
            flex-grow: 1;
            margin-bottom: 20px;
            text-align: left;
            padding-right: 5px;
        }

        .cart-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #202030;
            padding: 12px;
            border-radius: 10px;
            margin-bottom: 10px;
            border: 1px solid #2c2c40;
        }

        .cart-item-info h4 {
            font-size: 14px;
            color: #fff;
        }

        .cart-item-info p {
            font-size: 12px;
            color: var(--cinza);
            margin: 2px 0 0 0;
        }

        .cart-item-actions {
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .btn-qty {
            background: #3a3a50;
            color: white;
            border: none;
            width: 28px;
            height: 28px;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
        }

        .btn-remove {
            background: #ef4444 !important;
            color: white;
            border: none;
            padding: 6px 10px;
            border-radius: 6px;
            cursor: pointer;
            font-size: 12px;
        }

        .cart-total {
            font-size: 18px;
            font-weight: bold;
            color: #fff;
            margin-bottom: 15px;
            display: flex;
            justify-content: space-between;
            border-top: 1px solid #2c2c40;
            padding-top: 15px;
        }

        .modal-box button {
            padding: 14px 20px;
            border: none;
            border-radius: 12px;
            cursor: pointer;
            margin: 6px 0;
            font-weight: bold;
            font-size: 16px;
            width: 100%;
            display: block;
            transition: opacity 0.2s;
        }

        .modal-box button:active {
            opacity: 0.8;
        }

        .btn-sim, .btn-whats {
            background: var(--roxo);
            color: white;
        }

        .btn-whats {
            background: #25d366;
        }

        .btn-nao, .btn-fechar {
            background: #2a2a35;
            color: white;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 30px;
            background: #101018;
            border-bottom: 1px solid #222;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo-box {
            width: 45px;
            height: 45px;
            background-image: url('https://busy-coral-xb2aiqny.edgeone.app/0E5C0495-FC0F-4FA3-AA1A-9EC317BE92C0.png'); /* <-- Link oficial da sua logo */
            background-size: contain;
            background-position: center;
            background-repeat: no-repeat;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(168, 85, 247, 0.4);
        }

        nav {
            display: flex;
            gap: 20px;
        }

        nav a {
            text-decoration: none;
            color: white;
        }

        .hero {
            padding: 80px 20px;
            text-align: center;
            background: radial-gradient(circle, #1a1a2c, #0b0b10);
        }

        .hero h1 {
            font-size: 3rem;
            color: var(--roxo);
            margin-bottom: 15px;
        }

        .hero p {
            color: #ccc;
            margin-bottom: 20px;
        }

        .hero button {
            padding: 12px 25px;
            background: var(--roxo);
            border: none;
            border-radius: 10px;
            color: white;
            cursor: pointer;
            font-weight: bold;
            width: auto;
        }

        .search {
            margin-top: 25px;
        }

        .search input {
            width: 90%;
            max-width: 450px;
            padding: 12px;
            border: 1px solid #333;
            border-radius: 10px;
            background: #161623;
            color: white;
            outline: none;
        }

        section {
            padding: 50px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .titulo {
            text-align: center;
            margin-bottom: 30px;
            color: var(--roxo);
        }

        .produtos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 20px;
        }

        .card {
            background: var(--card);
            border-radius: 15px;
            overflow: hidden;
            border: 1px solid #222;
            display: flex;
            flex-direction: column;
        }

        .card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            background-color: #1a1a2e;
        }

        .card-content {
            padding: 15px;
            display: flex;
            flex-direction: column;
            flex-grow: 1;
        }

        .card-content h3 {
            font-size: 1.1rem;
            margin-bottom: 5px;
        }

        .preco {
            color: var(--roxo);
            font-size: 1.2rem;
            margin: 10px 0;
            font-weight: bold;
        }

        select {
            width: 100%;
            padding: 12px;
            border: 1px solid #333;
            border-radius: 8px;
            margin-bottom: 12px;
            background: #202030;
            color: white;
            outline: none;
        }

        .btn-acao {
            width: 100%;
            padding: 12px;
            border: none;
            border-radius: 10px;
            background: var(--roxo2);
            color: white;
            cursor: pointer;
            font-weight: bold;
        }

        .carrinho {
            position: fixed;
            right: 20px;
            bottom: 20px;
            background: var(--roxo);
            padding: 15px 20px;
            border-radius: 12px;
            cursor: pointer;
            box-shadow: 0 0 20px rgba(168, 85, 247, 0.6);
            z-index: 999;
            font-weight: bold;
        }

        footer {
            padding: 30px;
            text-align: center;
            color: #888;
            border-top: 1px solid #222;
        }

        @media(max-width:768px){
            header {
                flex-direction: column;
                gap: 15px;
                padding: 15px;
            }
            nav {
                flex-wrap: wrap;
                justify-content: center;
                gap: 15px;
            }
            .hero h1 {
                font-size: 2.2rem;
            }
            .produtos {
                grid-template-columns: 1fr;
            }
            .carrinho {
                right: 15px;
                bottom: 15px;
                font-size: 14px;
                padding: 12px 16px;
            }
        }
    </style>
</head>
<body>

    <div id="ageModal">
        <div class="modal-box">
            <h2>🔞 Área Restrita</h2>
            <p>Você confirma que possui 18 anos ou mais?</p>
            <button type="button" class="btn-sim" onclick="aceitarIdade()">Sim, sou maior de idade</button>
            <button type="button" class="btn-nao" onclick="recusarIdade()">Não</button>
        </div>
    </div>

    <div id="cartModal">
        <div class="modal-box">
            <h2>🛒 Seu Carrinho</h2>
            <div class="cart-items-container" id="cartModalItems">
                </div>
            <div class="cart-total">
                <span>Total:</span>
                <span id="cartModalTotal">R$ 0,00</span>
            </div>
            <button type="button" class="btn-whats" onclick="enviarParaWhatsApp()">Enviar Pedido no WhatsApp</button>
            <button type="button" class="btn-fechar" onclick="fecharCarrinho()">Continuar Comprando</button>
        </div>
    </div>

    <header>
        <div class="logo">
            <div class="logo-box"></div>
            <h2>Lapodss</h2>
        </div>
        <nav>
            <a href="#produtos">Produtos</a>
            <a href="#sobre">Sobre</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <section class="hero">
        <h1>Pods Premium</h1>
        <p>Entrega rápida • Qualidade garantida</p>
        <button type="button" onclick="rolarParaProdutos()">Ver Produtos</button>
        
        <div class="search">
            <input 
                type="text" 
                id="busca" 
                placeholder="Buscar produto ou marca..." 
                onkeyup="buscar()"
                autocorrect="off" 
                autocapitalize="none">
        </div>
    </section>

    <section id="produtos">
        <h2 class="titulo">Produtos Disponíveis</h2>
        <div class="produtos" id="listaProdutos"></div>
    </section>

    <section id="sobre">
        <h2 class="titulo">Sobre</h2>
        <p style="text-align:center; color:#aaa; max-width: 600px; margin: 0 auto; line-height: 1.6;">
            Loja especializada em pods descartáveis premium das melhores marcas do mercado.
        </p>
    </section>

    <section id="contato">
        <h2 class="titulo">Contato</h2>
        <p style="text-align:center; color:#aaa;">
            WhatsApp: (11) 98460-1576
        </p>
    </section>

    <footer>
        © 2026 Lapodss
    </footer>

    <div class="carrinho" onclick="abrirCarrinho()">
        🛒 <span id="qtd">0</span> | Finalizar
    </div>

    <script>
        // Imagens ilustrativas contextualizadas com dispositivos vape/pod descartáveis elegantes para evitar fotos aleatórias
        const DB_PRODUTOS = [
            // OXBAR
            { id: 1, nome: "Oxbar 35K", preco: 93.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSpWkp5ZaWjLKGLEyWWs-mC1--9iifco9q6Y30B91JQnA&s=10", sabores: ["Jewel Mighty Mint", "Jewel Cane Mint"] },
            { id: 2, nome: "Oxbar 30K", preco: 87.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ91Yy8L0TyweM55g1px7_VJZId8rgOmgpTZ-ZlGOTaQw&s", sabores: ["Red Ice"] },

            // ELFBAR
            { id: 3, nome: "Elfbar Duke 35K", preco: 100.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQtE8It-JrEllR-VNcbE5fKhN9k92gYcnPKvQpnSEvexQ&s", sabores: ["Blueberry Ice", "Icy Mint", "Watermelon Ice", "Watermelon Lemon Ice", "Peach Mango Watermelon", "Pineapple Ice", "Bubbaloo Tutti Frutti", "Coconut Strawberry Ice", "Kiwi Passion Fruit Guava", "Strawberry Kiwi", "Grape Ice"] },
            { id: 4, nome: "Elfbar Trio 40K", preco: 108.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKLlojrfm2Dp6FyThU2krzr8UbbOMcwptn0xfV6rCuDA&s=10", sabores: ["Watermelon Ice", "Strawberry Orange Lime", "Sakura Grape", "La Grape", "Scary Berry", "Black Mint", "Cool Menthol", "Sour Apple Ice", "Peach Twist", "Sour Strawberry Dragonfruit", "Orange Blast", "Blue Razz Ice", "Blueberry Pom Slushy", "Pomegranate Blast", "Pineapple Lime"] },
            { id: 5, nome: "Elfbar GH 23K", preco: 98.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSFl1WYSYAOHJRp63nzmmLYOCISsi5R2gOz2l-kFkfBWg&s=10", sabores: ["Ice Mint", "Spring Mint", "Sakura Grape", "Miami Mint", "Watermelon Ice", "Green Apple Ice", "Blue Razz Ice", "Grape Ice", "Green Apple", "Strawberry Banana", "Strawberry Ice"] },
            { id: 6, nome: "Elfbar ice King 40K", preco: 110.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSHuBmNuygP7lvfyA4afDYFF2e44eiyeyYUa9R6DV4KGw&s=10", sabores: ["Strawberry Watermelon", "Wild Berry Slush", "Passion Flash", "Peach Blue Slush", "Hawaiian Slush", "Strawberry Spark", "Green Apple Splash"] },
            { id: 7, nome: "Elfbar 33K", preco: 105.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcScFgjMn1fQ4qWf938RvQkz2T-Srrtl0xKX258Jg5wryw&s", sabores: ["Pine Needles", "Pear Soda", "Blue Razz Ice", "Granny Cherry"] },

            // IGNITE
            { id: 8, nome: "Ignite V55", preco: 79.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTHqes7RcWIhuJUC6Bf4oSADR5ZvScgAcYptJMdaV-WcA&s=10", sabores: ["Miami Mint", "Grape Apple Açaí", "Vanilla Creme", "Menthol", "Watermelon Ice", "Icy Mint", "Strawberry Ice", "Strawberry Banana", "Aloe Grape", "Minty Melon", "Strawberry Watermelon", "Blueberry Ice", "Strawberry Kiwi", "Grape Ice", "Melon Mix"] },
            { id: 9, nome: "Ignite V80 Pro", preco: 90.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS5I29xIAEBkZcf-_l68VBez_bqidcN16xqagLfoDvyIA&s", sabores: ["Blueberry Lemon"] },
            { id: 10, nome: "Ignite V150 Pro", preco: 88.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSFy1rSlJzcB2qxJQA0hJLDHMHYBKr97LLKAPDyRuQ7bw&s=10", sabores: ["Strawberry Apple Watermelon", "Cherry Watermelon Ice", "Green Apple Peach Kiwi", "Dragon Fruit Lemonade", "Peppermint & Cream"] },
            { id: 11, nome: "Ignite V155 slim", preco: 97.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS_4NWobCK6vGlW0QyCdDTaAfDQ9f_diBkqmne_kDjFGw&s=10", sabores: ["Green Apple", "Watermelon Ice", "Strawberry Watermelon Ice", "Strawberry Ice", "Strawberry Banana", "Tropical Açaí", "Watermelon Dragon Fruit", "Banana Ice", "Blueberry Ice"] },
            { id: 12, nome: "Ignite V250", preco: 100.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKsU5-dWnx0L1HyJdLREa-ryqzlzGFEDTjeEcyvc8_fw&s=10", sabores: ["Watermelon Ice", "Grape Ice", "Strawberry Banana", "Menthol", "Strawberry Ice", "Strawberry Kiwi", "Green Apple"] },
            { id: 13, nome: "Ignite V300", preco: 115.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSor-CnM38PNcFMfM4ERkoJmK1JEooOCjK49c6e03Dzvg&s=10", sabores: ["Banana Ice", "Watermelon Mix", "Icy Mint", "Grape Ice"] },
            { id: 14, nome: "Ignite V300 Slim", preco: 115.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQpSpyuO3NASNPGPDFb20sN4r-9O_IMxyK-ys_EcVF7Ow&s=10", sabores: ["Grape Ice", "Menthol", "Strawberry Banana", "Aloe Grape", "Blueberry Ice", "Pineapple Ice", "Watermelon Ice", "Watermelon Mix", "Strawberry Kiwi", "Icy Mint", "Strawberry Ice"] },
            { id: 15, nome: "Ignite V400 Ice", preco: 110.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTa64We2Ty1A6zHuh2mi0yr0uIpiib7QQfzJS8jiWExsA&s=10", sabores: ["Strawberry Banana Ice", "Strawberry Apple Watermelon", "Strawberry Watermelon", "Menthol", "Grape Peach", "Icy Mint", "Grape Ice", "Strawberry Kiwi", "Watermelon Ice", "Strawberry Ice", "Blueberry Ice", "Blue Razz Lemon", "Cola Ice"] },
            { id: 16, nome: "Ignite V400 Sweet", preco: 110.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTb-vFKusG_2kGP-X30MMxi117-pny4n-evW95-eoQn9A&s=10", sabores: ["Strawberry Apple Watermelon"] },
            { id: 17, nome: "Ignite Frozen 20K", preco: 93.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQYNLnb5_wYtztGyYlgCnbwx270G1J-h48L6FcZF0m7ow&s=10", sabores: ["Grape Ice", "Icy Mint", "Menthol", "Strawberry Ice", "Strawberry Kiwi", "Watermelon Ice"] },

            // BLACK SHEEP
            { id: 18, nome: "Black Sheep 25k", preco: 98.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQN6XRAYlWZ3Et_5Swi-iAMqqX9GUiGIgLd1iabhBiRdA&s", sabores: ["Blueberry Bubble", "Grape", "Passion Fruit", "Mint One", "Mango Grape", "Sour Green Apple", "Cola Lime", "Strawberry Bubble", "Strawberry Kiwi"] },
            { id: 19, nome: "Black Sheep 30K", preco: 107.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRO9EocgUNJfyq-OFA4kdZ07ICxCjMjAkfyJWKnHEDSQ&s=10", sabores: ["Grape + Grape", "Grape + Fresh Mint", "Grape + Strawberry Banana"] },

            // NIKBAR
            { id: 20, nome: "Nikbar 10K", preco: 67.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRUD8KBsFTWhRhzgx9wx7oyARiw874re0x_WWgxBnXAXw&s=10", sabores: ["Strawberry Ice", "Strawberry Kiwi", "Passion Sour Kiwi", "Menthol", "Icy Mint", "Aloe Grape", "Cherry Watermelon Ice Cream", "Stone Freeze", "Watermelon Ice", "Grape Ice", "Fresh Mint", "Sakura Grape", "Watermelon Sour", "Miami Mint", "Strawberry Banana", "Strawberry Apple Watermelon", "Grape Strawberry Ice", "Grape Apple Ice", "Green Apple", "Pineapple Ice", "Watermelon Bubblegum", "Blueberry Ice", "Banana Ice"] },
            { id: 21, nome: "Nikbar 30K", preco: 91.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQgKHk1_9vwzdk0Nt-7nefBqBkP3pmR3-psfK0kCtCWUQ&s=10", sabores: ["Fresh Mint", "Strawberry Kiwi", "Icy Mint", "Strawberry Apple Watermelon", "Blueberry Ice", "Strawberry Ice", "Grape Ice", "Miami Mint", "Watermelon Ice", "Cherry Banana", "Sour Apple Ice", "Sakura Grape", "Passion Fruit Sour Kiwi", "Menthol"] },
            { id: 22, nome: "Nikbar 40K", preco: 97.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLpGakPT8PjsoPBES-yl_kFs18v3486jO2tOvFbuObeQ&s=10", sabores: ["Menthol", "Miami Mint", "Icy Mint", "Grape Ice", "Bergamot Lime Mint", "Blue Razz Lemon"] },

            // LOST MARY
            { id: 23, nome: "Lost Mary 20K", preco: 92.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTbSZbj0AvQm1mFFhh4QcrdMSPOQ6hqB2KeZ6btZlJovg&s=10", sabores: ["Lime Grapefruit"] },
            { id: 24, nome: "Lost Mary 35K", preco: 90.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSe15EX0pRFhLhvaP6ZWz9ce8q9lbAyUapB3sv8FQqlxg&s=10", sabores: ["Icy Mint", "Menthol"] },
            { id: 25, nome: "Lost Mary Dura 35K", preco: 95.00, imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSwIoOe8CL3TUqVUuCteoEJ1igYdwhgJn2VJx-fB-Gm7Q&s=10", sabores: ["Blue Razz Ice", "Pomegranate Cherry Pineapple", "Hawaiian Mint", "Summer Orange", "Green Apple Ice", "Menthol", "Pineapple Ice", "Mango Ice", "Hawaiian Juice", "Grapefruit Passion Guava", "Watermelon Ice", "Grape Ice", "Strawberry Watermelon Ice", "Strawberry Ice", "Miami Mint", "Strawberry Kiwi"] }
        ];

        let carrinho = [];
        
        try {
            carrinho = JSON.parse(localStorage.getItem("lapodss_carrinho")) || [];
        } catch(e) {
            carrinho = [];
        }

        window.addEventListener('DOMContentLoaded', () => {
            renderizarProdutos();
            
            try {
                if (localStorage.getItem("lapodss_maior18") === "sim") {
                    fecharModal();
                }
            } catch(e) {}
            
            atualizarBotaoFlutuante();
        });

        function renderizarProdutos() {
            const container = document.getElementById("listaProdutos");
            if(!container) return;
            container.innerHTML = "";

            DB_PRODUTOS.forEach(prod => {
                let opcoesSabores = prod.sabores.map(sab => `<option value="${sab}">${sab}</option>`).join("");
                let cardHTML = `
                    <div class="card" data-nome="${prod.nome.toLowerCase()}">
                        <img src="${prod.imagem}" alt="${prod.nome}">
                        <div class="card-content">
                            <h3>${prod.nome}</h3>
                            <div class="preco">R$ ${prod.preco.toFixed(2).replace('.', ',')}</div>
                            <select id="select-${prod.id}">
                                ${opcoesSabores}
                            </select>
                            <button type="button" class="btn-acao" onclick="add('${prod.nome}', ${prod.preco}, 'select-${prod.id}')">
                                Adicionar ao Carrinho
                            </button>
                        </div>
                    </div>
                `;
                container.innerHTML += cardHTML;
            });
        }

        function salvarCarrinho() {
            try {
                localStorage.setItem("lapodss_carrinho", JSON.stringify(carrinho));
            } catch(e) {}
        }

        function aceitarIdade() {
            try {
                localStorage.setItem("lapodss_maior18", "sim");
            } catch(e) {}
            fecharModal();
        }

        function fecharModal() {
            const modal = document.getElementById("ageModal");
            if(modal) modal.style.display = "none";
        }

        function recusarIdade() {
            window.location.href = 'https://google.com';
        }

        function rolarParaProdutos() {
            const elemento = document.getElementById('produtos');
            if(elemento) elemento.scrollIntoView({ behavior: 'smooth' });
        }

        function add(nome, preco, selectId) {
            let elementoSelect = document.getElementById(selectId);
            if(!elementoSelect) return;
            
            let sabor = elementoSelect.value;
            let item = carrinho.find(i => i.nome === nome && i.sabor === sabor);

            if (item) {
                item.qtd++;
            } else {
                carrinho.push({ nome, preco, sabor, qtd: 1 });
            }

            salvarCarrinho();
            atualizarBotaoFlutuante();
            alert(`${nome} (${sabor}) adicionado!`);
        }

        function atualizarBotaoFlutuante() {
            let qtd = 0;
            carrinho.forEach(item => { qtd += item.qtd; });
            const elemQtd = document.getElementById("qtd");
            if(elemQtd) elemQtd.innerText = qtd;
        }

        function buscar() {
            let busca = document.getElementById("busca").value.toLowerCase();
            let cards = document.querySelectorAll(".card");
            cards.forEach(card => {
                let nome = card.getAttribute("data-nome");
                card.style.display = (nome && nome.includes(busca)) ? "flex" : "none";
            });
        }

        /* --- NOVAS FUNÇÕES DO MODAL INTERATIVO DO CARRINHO --- */

        function abrirCarrinho() {
            if (carrinho.length === 0) {
                alert("Seu carrinho está vazio.");
                return;
            }
            renderizarItensCarrinho();
            document.getElementById("cartModal").style.display = "flex";
        }

        function fecharCarrinho() {
            document.getElementById("cartModal").style.display = "none";
        }

        function renderizarItensCarrinho() {
            const container = document.getElementById("cartModalItems");
            const totalElem = document.getElementById("cartModalTotal");
            container.innerHTML = "";
            let total = 0;

            carrinho.forEach((item, index) => {
                let subtotal = item.preco * item.qtd;
                total += subtotal;

                container.innerHTML += `
                    <div class="cart-item">
                        <div class="cart-item-info">
                            <h4>${item.nome}</h4>
                            <p>Sabor: ${item.sabor}</p>
                            <p>R$ ${item.preco.toFixed(2).replace('.', ',')} un.</p>
                        </div>
                        <div class="cart-item-actions">
                            <button class="btn-qty" onclick="alterarQtd(${index}, -1)">-</button>
                            <span>${item.qtd}</span>
                            <button class="btn-qty" onclick="alterarQtd(${index}, 1)">+</button>
                            <button class="btn-remove" onclick="removerItem(${index})">X</button>
                        </div>
                    </div>
                `;
            });

            totalElem.innerText = `R$ ${total.toFixed(2).replace('.', ',')}`;
        }

        function alterarQtd(index, valor) {
            carrinho[index].qtd += valor;
            if (carrinho[index].qtd <= 0) {
                carrinho.splice(index, 1);
            }
            salvarCarrinho();
            atualizarBotaoFlutuante();
            if (carrinho.length === 0) {
                fecharCarrinho();
            } else {
                renderizarItensCarrinho();
            }
        }

        function removerItem(index) {
            carrinho.splice(index, 1);
            salvarCarrinho();
            atualizarBotaoFlutuante();
            if (carrinho.length === 0) {
                fecharCarrinho();
            } else {
                renderizarItensCarrinho();
            }
        }

        function enviarParaWhatsApp() {
            if (carrinho.length === 0) return;
            
            let mensagem = "🛒 *Novo Pedido - Lapodss*\n\n";
            let total = 0;
            
            carrinho.forEach(item => {
                let subtotal = item.preco * item.qtd;
                total += subtotal;
                mensagem += `• *${item.nome}*\n  Sabor: ${item.sabor}\n  Qtd: ${item.qtd}x | R$ ${subtotal.toFixed(2).replace('.', ',')}\n\n`;
            });
            
            mensagem += `💰 *Total do Pedido: R$ ${total.toFixed(2).replace('.', ',')}*`;
            window.open("https://wa.me/5511984601576?text=" + encodeURIComponent(mensagem), '_blank');
        }
    </script>
</body>
</html>