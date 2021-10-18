<template>
    <section class="s-hero">
        <div class="container">
            <div class="text animate__animated animate__fadeInLeft animate__slow">
                <h1>Tenha seu banco na palma da mão.</h1>
                <p>Todas as operações que você precisa em um só lugar. Simples, completo e feito pra você.</p>
                <div class="cta-download">
                    <img src="../assets/img/btn-google-play.svg" alt="">
                    <img src="../assets/img/btn-apple-store.svg" alt="">
                </div>
                <div class="continue">
                    <img src="../assets/img/arrow-large.svg" alt="">
                    <span>Continue esplorando</span>
                </div>
            </div>
            <div class="image animate__animated animate__fadeInRight animate__slow">
                <img src="../assets/img/model.png" class="model" alt="">
                <img src="../assets/img/lines-phone.svg" class="lines-phone" alt="">
                <img src="../assets/img/card1.png" class="card-1" alt="">
                <img src="../assets/img/card2.png" class="card-2" alt="">
                <img src="../assets/img/feitocomvc.svg" class="feito-vc" alt="">

            </div>
        </div>
    </section>
   
 
</template>


<style scoped>
    .s-hero{
        width: 100%;
        background: url('../assets/img/background.png') no-repeat;
        background-size: cover;
        overflow: hidden;
    }

    .container{
        width: 100%;
        max-width: 1246px;
        margin: 0 auto;
        padding: 0 15px;
        display: flex;
        justify-content: space-between;
    }
    .container .text{
        width: 100%;
        max-width: 49.7rem;
        margin-top: 10.5rem;
       
    }

    .container .text h1{
        font-weight: bold;
        font-size: 72px;
        line-height: 110%;
        color: #FFFFFF;
        margin-bottom: 1.6rem;
    }

    .container .text p{
        width: 100%;
        max-width: 40.9rem;
        font-size: 20px;
        line-height: 150%;
        color: #FFFFFF;
        letter-spacing: 0.02rem;
        margin-bottom: 3.2rem;
    }

    .container .continue{
        margin-top: 10.1rem;
        display: flex;
        align-items: center;
        opacity: .78;
        
    }

    .container .continue img{
        animation: floatingArrow 3s ease-in-out infinite;
    }

    .container .continue span{
        font-weight: bold;
        font-size: 14px;
        line-height: 16px;
        color: #FFFFFF;
        margin-left: 1.7rem;
        letter-spacing: 0.02em;
    }

    .container .image{
        width: 100%;
        max-width: 70.3rem;
        height: 70.3rem;
        position: relative;
        right: -4.2rem;
    }

    .container .image img{
        position: absolute;
    }

    .container .image .model{
        top: 0.664rem;
        left: 3.917rem;
    }

    .container .image .lines-phone{
        top: 6.6rem;
        left: 18.9rem;
    }

    .container .image .card-1{
        left: 1.3rem;
        bottom: 19.5rem;
        animation: floating 9s ease-in-out infinite;
    }

    .container .image .card-2{
        right: 4.2rem;
        top: 28.1rem;
        animation: floating 6s ease-in-out infinite;
    }
    
    .container .feito-vc{
        bottom: 5.8rem;
        right: 6.781rem;
    }

    .container .cta-download img{
        cursor: pointer;
    }

    .container .cta-download img:first-child {
        margin-right: 1.6rem;
    }

    @media(max-width: 1200px) {
        .s-hero .container .text{
            max-width: 37rem;
        
        }
        .container .text h1{
            font-size: 5.5rem ;
         
        }
        .container .text p{
            font-size: 16px;
        }

    }

    @media(max-width: 1050px){
        .s-hero .container{
            flex-direction: column;
          
        }
        .s-hero .container .text{
            text-align: center;
            max-width: 80%;  
            margin: 6rem auto 3rem auto;        
        }
        .s-hero .container .text p {
            max-width: 100%;
        }
        .s-hero .container .continue {
            justify-content: center;
            margin-top: 4rem;
        }

        .s-hero .container .image {
            width: 100%;
            margin: 0 auto;
        }
   
        .container .image .model{
            position: relative;
            left: 0;
        }
        .container .image .card-1{
          
            left: 10rem;
         }

        .container .image .card-2{
            left: 38rem;
            top: 29rem;
           
         }

        .container .image .lines-phone{
            left: 14rem;
            
        }
    
        .container .image .feito-vc{
            display: none;
        }
        

    }

    @media(max-width: 480px){

        .container .cta-download img:first-child {
            margin-right: 0;
            margin-bottom: 1rem;
        }

        .container .image {
            height: auto;
        }

        .container .image img{
            display: block;
            max-width: 100%;
            
        }
        .container .image .model{
            position: relative;
          
        }
        .container .image .card-1{
            display: none;
         }
        .container .image .card-2{
            display: none;
         }
        .container .image .lines-phone{
            left: 14rem;
            display: none;
            
        }
        .container .image .feito-vc{
            display: none;
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

    @keyframes floatingArrow {
        0% {
            transform: translateX(0);
        }
        66% {
            transform: translateY(-10px);
        }
        100% {
            transform: translateX(0);
        }
    }


</style>