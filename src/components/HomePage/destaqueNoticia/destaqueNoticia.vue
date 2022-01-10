<template>
    <div id="destaqueNoticia">        
        <div class="title-category">
            <div class="title-category-type">
                <h4>Notícia</h4>
            </div>
            <div class="title-category-link">
                <a href="#">Ver mais</a>
            </div>            
        </div>
        <div id="detalhe-destaque-noticia">
            <div id="destaque-tipo-news-up">                            
                <div id="destaque-tipo-news-up-capa">                                
                    <div id="capa-title">
                        <div id="capa-title-up">
                            <div id="capa-title-up-title">
                                <span class="autor-destaque"> <i class="far fa-comments"></i> 5 </span>
                            </div>
                            <div id="capa-title-up-comment">                                            
                                <i class="fas fa-house-damage fa-xs"></i>
                            </div>
                        </div>
                        <div id="capa-title-down">
                            <a href="#">Digital</a>
                            <h5>Nova era digital</h5>
                            <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                        </div>
                    </div>
                    <div id="news-description">
                        <p>
                            Lorem Ipsum is simply dummy 
                            text of the printing 
                            and typesetting industry. 
                            Lorem Ipsum has been the industry's 
                            standard dummy text ever since the 1500s,
                        </p>
                        <a href="#">Ler mais</a>
                    </div>
                </div>

                <div id="destaque-tipo-news-up-beside">                                
                    <div id="destaque-tipo-news-up-beside-up">
                        <div id="beside-up-capa-title-up">
                            <div id="beside-up-capa-title-up-title">
                                <span class="autor-destaque"> <i class="far fa-comments"></i> 5 </span>
                            </div>
                            <div id="beside-up-capa-title-up-comment">                                            
                                <i class="fas fa-house-damage fa-xs"></i>
                            </div>
                        </div>
                        <div id="beside-up-capa-title-down">
                            <h4>Nova era digital com a Kamba Virtual</h4>
                            <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                        </div>
                    </div>
                    <div id="destaque-tipo-news-up-beside-down">
                                    
                                    <div id="beside-down-capa-title-up">
                                        <div id="beside-down-capa-title-up-title">
                                            <span class="autor-destaque"> <i class="far fa-comments"></i> 5 </span>
                                        </div>
                                        <div id="beside-down-capa-title-up-comment">                                            
                                            <i class="fas fa-house-damage fa-xs"></i>
                                        </div>
                                    </div>

                                    <div id="beside-down-capa-title-down">
                                        
                                        <h4>Nova era digital com a Kamba Virtual</h4>
                                        <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                                    </div>

                    </div>
                </div>
            </div>

            <div id="destaque-tipo-news-down">

                <div id="destaque-tipo-news-down-left">
                                
                                <div id="down-left-capa-title-up">
                                    <div id="down-left-capa-title-up-title">
                                        <span class="autor-destaque"> <i class="far fa-comments"></i> 5 </span>
                                    </div>
                                    <div id="down-left-capa-title-up-comment">                                            
                                        <i class="fas fa-house-damage fa-xs"></i>
                                    </div>
                                </div>
                                <div id="down-left-capa-title-down">
                                    
                                    <h4>Nova era digital com a Kamba Virtual</h4>
                                    <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                                </div>

                </div>

                <div id="destaque-tipo-news-down-right">
                                
                                <div id="down-right-capa-title-up">
                                    <div id="down-right-capa-title-up-title">
                                        <span class="autor-destaque"> <i class="far fa-comments"></i> 5 </span>
                                    </div>
                                    <div id="down-right-capa-title-up-comment">                                            
                                        <i class="fas fa-house-damage fa-xs"></i>
                                    </div>
                                </div>
                                <div id="down-right-capa-title-down">
                                    
                                    <h4>Nova era digital com a Kamba Virtual</h4>
                                    <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                                </div>

                </div>

            </div>

        </div>        
    </div>
</template>

<script>
export default {

}
</script>

<style>

#destaqueNoticia{  
    width: 100%;
}

#destaqueNoticiaTitulo{
    display: flex;
    flex-direction: column;
}

.title-category{
    background: orange;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 100%;  
    /*border: 2px solid black; */
    
}

.title-category-type{
    width: 8%;
}

.title-category-link{
    background: blue;
    width: 92%;
    margin-bottom: 5px;
}

.title-category-link a{
    text-align: left;
    float: right;
    background: orange;
    margin: 5px 5px 5px 0;
}

#detalhe-destaque-noticia{
    width: 100%;
    display: flex;
    flex-direction: column;
}

#destaque-tipo-news-up{
    display: flex;
    flex-direction: row;
    width: 100%;
}

#destaque-tipo-news-up-capa{        
    /*display: flex;
    flex-direction: column;*/
    width: 50%;
    margin-right: 5px;
    background: red;
    padding: 10px;
}

#capa-title{
        /*background: url('../static/destaque-news-capa-title.jpg');*/
        background: url('../../../static/destaque-musica/destaque-musica-1.jpg');
        background-size: 100% 100%;
        /*padding: 10px;*/

        /*imagemFundo:require('../../../static/destaque-musica/destaque-musica-1.jpg')*/
    }

    #capa-title-up{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }

    #capa-title-up-title{
        top: 0;
        background: red;
        margin: 0 0 0 10px;
        padding: 2px 5px;
    }

    #capa-title-up-comment{
        margin: 5px 10px 0 0;
    }

    #capa-title-down{
        margin-top: 60px;
        padding: 10px;
    }

    #capa-title-down a{
        background: red;        
        padding: 3px 5px;        
    }

    #capa-title-down h5{
        margin: 3px 0;        
    }

    #news-description p{
        margin: 5px 0 10px 0;
        text-align: justify;
    }

    #news-description a{
        background: black;
        padding: 5px;
        border-radius: 5px;
    }

#destaque-tipo-news-up-beside{        
    /*display: flex;
    flex-direction: column;*/
    width: 50%;
    margin-left: 5px;
    margin-top: 0;
    display: flex;
    flex-direction: column;
}

#destaque-tipo-news-up-beside-up{
        display: flex;
        flex-direction: column;
        background: url('../../../static/destaque-news-beside-up.jpg');
        background-size: 100% 100%;
    }
    
    #beside-up-capa-title-up{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin-bottom: 5px;
        
    }

    #beside-up-capa-title-up-title{
        top: 0;
        background: red;
        margin: 0 0 0 10px;
        padding: 2px 5px;
    }

    #beside-up-capa-title-up-comment{
        margin: 5px 10px 0 0;
        background: red;
    }

    #beside-up-capa-title-down{
        margin-top: 60px;
        padding: 10px;
    }

    #beside-up-capa-title-down a{
        background: red;        
        padding: 3px 5px;        
    }

    #beside-up-capa-title-down h5{
        margin: 3px 0;        
    }

    #destaque-tipo-news-up-beside-down{
        background: url('../../../static/destaque-news-beside-down.jpg');
        background-size: 100% 100%;
        margin-top: 5px;
        display: flex;
        flex-direction: column;
    }

    #beside-down-capa-title-up{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin-bottom: 5px;
        
    }

    #beside-down-capa-title-up-title{
        top: 0;
        background: red;
        margin: 0 0 0 10px;
        padding: 2px 5px;
    }

    #beside-down-capa-title-up-comment{
        margin: 5px 10px 0 0;
    }

    #beside-down-capa-title-down{
        margin-top: 60px;
        padding: 10px;
    }


#beside-down-capa-title-down a{
        background: red;        
        padding: 3px 5px;        
    }

    #beside-down-capa-title-down h5{
        margin: 3px 0;        
    }

    #destaque-tipo-news-down{       
        display: flex;
        flex-direction: row;
    }

    #destaque-tipo-news-down-left{
        background: url('../../../static/destaque-news-down-left.jpg');
        background-size: 100% 100%;
        display: flex;
        flex-direction: column;
        margin-top: 5px;
        width: 50%;
        margin-right: 10px;
    }

    #down-left-capa-title-up{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin-bottom: 5px;
        
    }

    #down-left-capa-title-up-title{
        top: 0;
        background: red;
        margin: 0 0 0 10px;
        padding: 2px 5px;
    }

    #down-left-capa-title-up-comment{
        margin: 5px 10px 0 0;
        background: red;
    }

    #down-left-capa-title-down{
        margin-top: 60px;
        padding: 10px;
    }

    #down-left-capa-title-down a{
        background: red;        
        padding: 3px 5px;        
    }

    #down-left-capa-title-down h5{
        margin: 3px 0;        
    }

    #destaque-tipo-news-down-right{
        background: url('../../../static/destaque-news-down-right.jpg');
        background-size: 100% 100%;
        margin-top: 5px;
        display: flex;
        flex-direction: column;
        width: 50%;
    }

    #down-right-capa-title-up{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin-bottom: 5px;
        
    }

    #down-right-capa-title-up-title{
        top: 0;
        background: red;
        margin: 0 0 0 10px;
        padding: 2px 5px;
    }

    #down-right-capa-title-up-comment{
        margin: 5px 10px 0 0;
        background: red;
    }

    #down-right-capa-title-down{
        margin-top: 60px;
        padding: 10px;
    }

    #down-right-capa-title-down a{
        background: red;        
        padding: 3px 5px;        
    }

    #down-right-capa-title-down h5{
        margin: 3px 0;        
    }



</style>