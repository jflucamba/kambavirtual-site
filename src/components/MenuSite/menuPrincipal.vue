<template>
    <div id="menu">

        <div class="container">
            
            <section id="menu-principal">

                <div id="menu-geral">
                <ul>
                    <li>
                        <a href="#">Sobre Nós</a>
                    </li>
                    <li>
                        <a href="#">Publicite Aqui</a>
                    </li>
                    <li>
                        <a href="#">Remoção de Conteúdo</a>                    
                    </li>
                    <li>
                        <a href="#">Politica de Privacidade</a>
                    </li>
                    <li>
                        <a href="#">F.A.Q</a>
                    </li>
                </ul>
                </div>

                <div id="redes">
                    <ul>
                    <li class="facebook">
                        <a>
                            <span> <i class="fab fa-facebook-f fa-xs"></i> </span>
                        </a>
                    </li>
                    <li class="instagram">
                        <a>
                            <span> <i class="fab fa-instagram fa-xs"></i> </span>
                        </a>
                    </li>
                    <li class="twitter">
                        <a>
                            <span> <i class="fab fa-twitter fa-xs"></i> </span>
                        </a>
                    </li>
                    <li class="youtube">
                        <a>
                            <span> <i class="fab fa-youtube fa-xs"></i> </span>
                        </a>
                    </li>
                    <li class="pinterest">
                        <a>
                            <span> <i class="fab fa-pinterest fa-xs"></i> </span>
                        </a>
                    </li>
                    <li class="facebook-alter">
                        <a>
                            <span> <i class="fab fa-facebook-f fa-xs"></i> </span>
                        </a>
                    </li>
                    </ul>
                </div>

            </section>            

        </div>        
        
    </div>
</template>

<script>
export default {
    name:'MenuComponent'
    
}
</script>

<style scoped>

    #menu{
        background: var(--color-background-black);
        width: 100%;
    }

    .container{            
            padding: 0 10px;
    }
    
    #menu-principal{
        padding: 5px 0;
        display: flex;
        flex-direction: row;
        width: 100%;
        justify-content: space-between;
    }

    #menu-geral{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-self: center;
        align-items: center;
    }

    #redes ul{
        background: black;
    }

    #redes ul li{
        display: inline-block;
        
    }
    
    .facebook,
    .instagram,
    .twitter,
    .youtube,
    .pinterest{
        margin-right: 3px;
    }

    .facebook,
    .instagram,
    .twitter,
    .youtube,
    .pinterest,
    .facebook-alter{
        background: blue;
        padding: 3px 7px;
    }

    .facebook{
        background: blue;
    }

    .instagram{
        background: #FF69B4;
    }

    .twitter{
        background: #00BFFF;
    }

    .pinterest,
    .youtube{
        background: #F80623;
    }

    .facebook-alter{
        background: #0000CD;
    }

    /* RESPONSIVIDADE */

    @media (min-width: 900px) {

        #menu-principal{
            display: flex;
            flex-direction: row;
            padding: 5px 0;
            width: 100%;
            justify-content: space-between;
        }

        .container{
            padding: 0 100px;
        }

        #menu-geral{
            float: left;
                     
            
        }

        #menu-geral ul li{
            margin: 0 10px 0 0;
        }

        #redes{
            float: right;            
            background: blue;
            
        }

        ul li{
            display: inline-block;
        }

    }


</style>
