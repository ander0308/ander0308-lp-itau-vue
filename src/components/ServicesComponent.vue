<template>
    <section class="s-services">
        <div class="container">
            <div class="text animate__animated animate__fadeInLeft animate__slower">
                <span>serviços exclusivos</span>
                <h2>Gerencie suas finanças sem sair de casa</h2>
                <p>Veja como você pode cuidar das suas finanças pelo app Itaú de forma segura, 
                    rápida e o melhor, no corforto da sua casa.</p>

                <div class="services">
                    <ul>
                        <li>
                            <img src="../assets/img/icon-conta.svg" alt="">
                            <p>Acompanhar sua conta, fazer transferências e pagamentos de onde estiver</p>
                        </li>
                        <li>
                            <img src="../assets/img/icon-emprestimo.svg" alt="">
                            <p>Soluções de empréstimos e renegociação para organizar suas finanças</p>
                        </li>
                        <li>
                            <img src="../assets/img/icon-investimento.svg" alt="">
                            <p>Diversas opções de investimentos, de acordo com o seu perfil de investidor</p>
                        </li>
                        <li>
                            <img src="../assets/img/icon-cartao.svg" alt="">
                            <p>Acompanhe a fatura do seu cartão de crédito e faça compras online com seu cartão virtual.</p>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="image">
                <img src="../assets/img/cellphone.png" class="animate__animated animate__fadeInUp animate__slow" alt="">
            </div>
        </div>
        <div class="bg-lateral">
        </div>
    </section>
</template>

<style scoped>

    .s-services {
        width: 100%;
        padding-top: 13.5rem;
        padding-bottom: 12rem;
        position: relative;
    }
    
    .bg-lateral{
        width: 33%;
        height: 96.4rem;
        background-color:#F4F4F4;
        position: absolute;
        top: 0;
        right: 0;
        z-index: -1;
    }
    .container{
        width: 100%;
        max-width: 1246px;
        margin: 0 auto;
        padding: 0 15px;
        display: flex;
        align-items: flex-start;
        justify-content: space-between;
    }

    .container .text span{
        display: block;
        font-weight: bold;
        font-size: 14px;
        line-height: 110%;
        letter-spacing: 0.04em;
        text-transform: uppercase;
        color: #EC7000;
        margin-bottom: 3.5rem;
    }

    .container .text h2{
        width: 100%;
        max-width: 59.4rem;
        font-weight: bold;
        font-size: 5.6rem;
        line-height: 110%;
        color: #33303E;
        margin-bottom: 2.4rem;
        letter-spacing: -0.01em;
    }

     .container .text P{
        width: 100%;
        max-width: 51.6rem;
        font-size: 1.8rem;
        line-height: 150%;
        color: #4E4B59;
     }

    .container .text .services {
        margin-top: 6.9rem;
    }

     .container .text .services ul li{
        display: flex;
        align-items: flex-start;
        margin-top: 3.6rem;
        padding-bottom: 1.6rem;
        border-bottom: 0.1536rem solid rgba(100, 80, 57, 0.1);
     }

     .container .text .services ul li p{
        width: 100%;
        max-width: 48.6rem;
        font-size: 1.6rem;
        line-height: 150%;
        color: #7A7786;
        margin-left: 3.9rem;
     }

    .container .image{
        position: relative;
        left: -12rem;
        animation: floating 6s ease-in-out infinite;
    }

    @media(max-width: 1200px) {
 
    }

    @media(max-width: 1050px) {
        .bg-lateral{
            display: none;
        }

        .container .text {
            margin: 0 auto;
            max-width: 100%;
            text-align: center;
        }

        .container .text h2{
            font-size: 48px;
         
        }

        .container .text p{
            font-size: 1.6rem;
            margin: 0 auto;
        }

        .container .text .services p{
            font-size: 1.6rem;
            margin: 0 auto;
    
        }

        .container .text .services ul li{
            flex-direction: column;
            align-items: center;
        }

        .container .text .services ul li p{
            margin-left: 0;
        }
        .container .text .services ul li img{
            margin-bottom: 1.6rem;
        }

        .container .image img{
           display: none;
        }
    }

    @media(max-width: 480px){
        .s-services {
            padding-top: 4rem;
        }
        .container {
            flex-direction: column;
       
        }
    }

     @keyframes floating {
        0% {
            transform: translateX(0);
        }
        66% {
            transform: translateY(-20px);
        }
        100% {
            transform: translateX(0);
        }
    }

</style>