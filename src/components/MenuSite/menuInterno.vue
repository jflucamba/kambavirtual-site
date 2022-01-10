<template>
    <div id="menu-interno">

        <div id="menu-geral">
            <ul>
                <li>
                    <a href="/"> 
                        <span>
                            <v-icon                                      
                              black
                              small
                            >                            
                                home                            
                            </v-icon>
                        </span> 
                        Página Inicial
                    </a>
                </li>
                <li>
                    <a href="/noticia"> 
                        <span>
                            <v-icon                                      
                              black
                              small
                            >                            
                                import_contacts                            
                            </v-icon>
                        </span> 
                        Notícias
                    </a>
                </li>
                <li>
                    <a href="/musica"> 
                        <span>
                            <v-icon                                      
                              black
                              small
                            >                            
                                library_music                        
                            </v-icon>
                        </span> 
                        Músicas
                    </a>                    
                </li>
                <li>
                    <a href="/video"> 
                        <span>
                            <v-icon                                      
                              black
                              small
                            >                            
                                video_call                            
                            </v-icon>
                        </span> 
                        Vídeos
                    </a>
                </li>
                <li>
                    <a href="/arte"> 
                        <span>
                            <v-icon                                      
                              black
                              small
                            >                            
                                wb_incandescent                            
                            </v-icon>
                        </span> 
                        Arte
                    </a>
                </li>
                <li>
                    <a href="/emprego"> 
                        <span>
                            <v-icon                                      
                              black
                              small
                            >                            
                                home                            
                            </v-icon>
                        </span> 
                        Empregos
                    </a>
                </li>
            </ul>
        </div>
        <div id="search">
            <form action="">
                <input type="text">
                <button> 
                    
                    <v-icon                                      
                      black
                      medium
                      align-center
                      align-content-center
                      class="btn-icon"
                    >                            
                        search                          
                    </v-icon>
                    
                </button>
            </form>
            
        </div>
        
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>

    #menu-interno{
        /*background: var(--color-background-black);*/
        width: 100%;
        margin-top: 15px;
        border: 1px solid red;
        display: flex;
        flex-direction: column;

    }

    #menu-geral{
        margin-bottom: 5px;
        width: 100%;
    }

    #menu-geral ul{
        
        justify-content: center;
        align-items: center;
        /*padding: 10px 0;*/
    }

    #menu-geral ul li{
        margin: 0 15px 0 0;
    }

    #menu-geral ul li a{
        color: #000;
        
    }

    #menu-geral ul li a:hover{
        color: red;
        text-decoration: underline;
    }


    /*#menu-geral ul li a span:hover{
        color: greenyellow;
        text-decoration: underline;
    }*/
    

    #search{
        background: blue;
        display: flex;
        flex-direction: row;
        align-items: center;
        width: 100%;
    }

    #search input{
        height: 35px;
        margin-right: 0;
        padding-right: 0;
        color: #000000;
        
        width: 90%;
        border-top-right-radius: 0;
    }

    #search button{
        height: 35px;
        border: 1px solid orange;
        background-color: greenyellow;
        width: 10%;
        border-top-left-radius: 0;  
        justify-content: center;
        align-content: center;      
    }

    #search button{
        height: 35px;
        border: 3px solid orange;
        background-color: greenyellow;
        width: 10%;
        border-top-left-radius: 0; 
        border-bottom-left-radius: 0;
        /*box-sizing: border-box;*/
    }

    #search button span{
        height: 35px;
        margin-right: 25px;
        border: 3px solid black;
        background-color: red;
        width: 100%;      
    }

    /*#search button span{        
        align-items: center;
        justify-items: center;
        align-self: center;
        align-content: center;
    } */

    

    /* RESPONSIVIDADE */

    @media (min-width: 750px) {

        #menu-interno{
            /*background: var(--color-background-black);*/
            width: 100%;
            margin-top: 15px;
            border: 1px solid red;
            display: flex;
            flex-direction: row;
        }

        /*.container{            
            padding: 0 100px;
        }*/

        #menu-geral{
            margin-bottom: 5px;
            width: 90%;
        }

        #menu-geral ul li{
            margin: 0 15px 0 0;
            display: inline;
            align-items: center;
            align-self: center;
            justify-content: center;
        }

        #menu-geral ul li a{
            color: #000;
            
        }

        /*#search{
            background: blue;
            display: flex;
            flex-direction: row;
            align-items: center;
            width: 20%;
        }

        #search button{
        height: 35px;
        border: 1px solid orange;
        background-color: greenyellow;
        width: 10%;
        border-top-left-radius: 0;  
        justify-content: center;
        align-content: center;      
        }

        #search button{
        height: 35px;
        border: 3px solid orange;
        background-color: greenyellow;
        width: 30%;
        border-top-left-radius: 0; 
        border-bottom-left-radius: 0;
        box-sizing: border-box;
        }

        #search button span{
        height: 35px;
        border: 3px solid black;
        background-color: red;
        width: 100%;      
        }*/

        #search{
            width: 20%;
        }

        form{
            background: pink;
            display: flex;
            flex-direction: row;
        }

        form input{
            width: 90% !important;
            background: black;
        }

        form button{
            width: 10% !important;
            justify-content: center !important;
            align-items: center !important;
            text-align: center !important;
            color: black;
            justify-items: center;
        }

        .btn-icon{
            justify-items: center;
            justify-content: center;
            align-items: center;
            color: red;
        }

        form button span{
            background: cyan !important;
            width: 100% !important;
            justify-items: center;
            padding-right: -55px;
        }

    }  

</style>