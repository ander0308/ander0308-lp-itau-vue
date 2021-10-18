<template>
    <header>
        <div class="container">
            <div class="menu">
                <a href=""><img src="../assets/img/logo.svg" class="logo" alt=""></a>
                <nav>
                    <ul>
                        <li>
                            <a href="">Para você</a>
                            <img src="../assets/img/arrow.svg" alt="">
                        </li>
                        <li>
                            <a href="">Para empresas</a>
                            <img src="../assets/img/arrow.svg" alt="">
                        </li>
                        <li>
                            <a href="">Serviços</a>
                            <img src="../assets/img/arrow.svg" alt="">
                        </li>
                        <li>
                            <a href="">Ajuda</a>
                            <img src="../assets/img/arrow.svg" alt="">
                        </li>
                    </ul>
                </nav>
            </div>
      
            <div class="btns">
                <div class="busca">
                    <img src="../assets/img/icon-search.svg" alt="">
                    <a href="">Buscar</a>
                </div>
                  <div class="acesso">
                    <img src="../assets/img/icon-user.svg" alt="">
                    <a href="">Acessar conta</a>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

    <style scoped>

    header{
        background-color: #EC7000;
        height: 8rem;
        display: flex;
        /* position: relative; */
    }

    .container{
        width: 100%;
        max-width: 1246px;
        margin: 0 auto;
        padding: 0 15px;
        display: flex;
        justify-content: space-between;
           transition: all .3s;
    }

    .container .menu {
        display: flex;
        align-items: center;
    }
    .container .menu nav {
        margin-left: 5.754rem;
    }

    .container .menu nav ul{
        display: flex;
        align-items: center;
    }

    .container .menu nav ul li{
        margin-right: 4.8rem;
        display: flex;
        align-items: center;

    }

    .container .menu nav ul li a {
        font-weight: bold;
        font-size: 16px;
        line-height: 113.2%;
        color: #FFFFFF;
        margin-right: 1.2rem;
        letter-spacing: 0.02em;
        transition: all .3s;
    }

    .container .menu nav ul li a:hover{
        color: #f3d193;
    }

    .container .btns {
        display: flex;
        align-items: center;
        /* position: absolute;
        top: 0;
        right: 0; */
    }
    .container .btns .busca, 
    .container .btns .acesso{
        display: flex;
        align-items: center;
    }
    .container .btns .acesso {
        margin-left: 4.8rem;
        background-color: #106EB0;
        height: 100%;
        padding: 0 4.2rem;
        padding-right: 4.8rem;
        transition:  all .3s;
        cursor: pointer;
    }

    .container .btns .acesso:hover{
        background-color: #2087d1;
    }


    .container .btns a {
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 113.2%;
        letter-spacing: 0.02em;
        color: #FFFFFF;
    }

    .container .btns img {
        margin-right: 1.6rem;
    }

    @media(max-width: 1200px) {
        header .container {
            padding-right: 0;
         
        }

        header .container .menu nav{
            display: none;
        }

    }

    @media(max-width: 480px) {
        header .container {
            padding-right: 0;
         
        }

        header .container .menu nav{
            display: none;
        }

        .logo{
            width: 3.6rem;
        }

        .container .btns .acesso {
            margin-left: 2.2rem;
            padding: 0 2.2rem;
    }

        .container .btns a {
            font-style: normal;
            font-weight: bold;
            font-size: 1.4rem;
            line-height: 113.2%;
            letter-spacing: 0.02em;
            color: #FFFFFF;
    }

    .container .btns img {
        margin-right: 1.6rem;
    }

    }

</style>