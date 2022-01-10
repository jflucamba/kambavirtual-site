<template>
    <div id="destaqueArt">        
        <div class="title-category">
            <div class="title-category-type">
                <h4>Notícia</h4>
            </div>
            <div class="title-category-link">
                <a href="#">Ver mais</a>
            </div>            
        </div>
        
        <div id="destaque-tipo-arte">
            <div id="destaque-tipo-arte-capa">
                            
                <div id="arte-capa-up">
                    <div id="arte-capa-up-title">
                        <span class="autor-destaque"> <i class="far fa-comments"></i> 10 </span>
                    </div>
                    <div id="arte-capa-up-comment">
                        <i class="fas fa-house-damage fa-xs"></i>
                    </div>
                </div>
                <div id="arte-capa-down">
                    <h4>Nova era digital com kamba Virtual</h4>
                    <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                    <p>
                        Lorem Ipsum is simply dummy text of the printing and typesetting 
                        industry. Lorem Ipsum has been the.
                    </p>
                </div>

            </div>
            <div id="destaque-tipo-arte-beside">
                            
                <div id="tipo-arte-beside-1">
                                
                                <div class="tipo-arte-beside1-img">
                                    <span class="arte-beside-img"> <i class="fas fa-bolt"></i> </span>
                                </div>

                                <div class="tipo-arte-beside-info">
                                    <h5> Nova era digital em Angola </h5>
                                    <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                                </div>

                </div>

                <hr>

                <div id="tipo-arte-beside-2">
                                
                                <div class="tipo-arte-beside2-img">
                                    <span class="arte-beside-img"> <i class="fas fa-bolt"></i> </span>
                                </div>

                                <div class="tipo-arte-beside-info">
                                    <h5> Nova fase digital em Angola </h5>
                                    <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                                </div>

                </div>

                <hr>                            

                <div id="tipo-arte-beside-3">
                                
                                <div class="tipo-arte-beside3-img">
                                    <span class="arte-beside-img"> <i class="fas fa-bolt"></i> </span>
                                </div>

                                <div class="tipo-arte-beside-info">
                                    <h5> Nova energia em Angola </h5>
                                    <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                                </div>

                </div>

                <hr>

                <div id="tipo-arte-beside-4">
                                
                                <div class="tipo-arte-beside4-img">
                                    <span class="arte-beside-img"> <i class="fas fa-bolt"></i> </span>
                                </div>

                                <div class="tipo-arte-beside-info">
                                    <h5> Nova era digital em África </h5>
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

#destaqueArt{
    margin-top: 15px;
}

#destaque-tipo-arte{
    width: 100%;
    display: flex;
    flex-direction: row;
}

#destaque-tipo-arte-capa{
    width: 50%;
    background: url('../../../static/destaque-arte-capa1.jpg');
    background-size: 100% 100%;
    margin-top: 5px;
}

#arte-capa-up{
            display: flex;
            flex-direction: row;
            justify-content: space-between;
        }

    #arte-capa-up-title{
        float: left;
        background: red;
        padding: 3px;
        margin: 0 0 0 10px;
    }

    #arte-capa-up-comment{
        float: right;
        background: red;
        
        margin: 5px 10px 0 0;
    }

    #arte-capa-down{
        margin: 100px 30px 0 10px;            
        padding-bottom: 5px;
    }

    #arte-capa-down h4{
        margin-bottom: 10px;
    }

    .autor-destaque{
        font-size: small;
    }

#arte-capa-down p{
    margin-top: 10px;
    text-align: justify;
}

#destaque-tipo-arte-beside{
    width: 50%;
    margin-left: 10px;
}


#tipo-arte-beside-1{
            display: flex;
            flex-direction: row;
            width: 100%;
            justify-content: space-between;           
            margin: 5px 0;
        }

        #tipo-arte-beside-2{
            display: flex;
            flex-direction: row;
            width: 100%;
            justify-content: space-between;           
            margin: 5px 0;
        }

        #tipo-arte-beside-3{
            display: flex;
            flex-direction: row;
            width: 100%;
            justify-content: space-between;                        
            margin: 5px 0;
        }

        #tipo-arte-beside-4{
            display: flex;
            flex-direction: row;
            width: 100%;
            justify-content: space-between;
            margin-top: 5px;        
        }

        .tipo-arte-beside1-img{
            background: url('../../../static/arte-beside-1.jpg');
            background-size: 100% 100%;
            width: 25%;
            margin-right: 5px;
        }

        .tipo-arte-beside2-img{
            background: url('../../../static/arte-beside-2.png');
            background-size: 100% 100%;
            width: 25%;
            margin-right: 5px;
        }

        .tipo-arte-beside3-img{
            background: url('../../../static/arte-beside-3.png');
            background-size: 100% 100%;
            width: 25%;
            margin-right: 5px;
        }

        .tipo-arte-beside4-img{
            background: url('../../../static/arte-beside-4.jpg');
            background-size: 100% 100%;
            width: 25%;
            margin-right: 5px;
        }

        .arte-beside-img{
            background: red;
            float: right;
            margin: 10px 10px 0 0;
            padding: 1px;
        }

        .tipo-arte-beside-info{
            
            width: 75%;
            margin-left: 5px;
            padding-bottom: 5px;
            font-size: medium;
        }

        .tipo-arte-beside-info h5{
            margin-bottom: 25px;
            color: #1C1C1C;
        }

        .tipo-arte-beside-info .autor-destaque{
            color: #1C1C1C;
            margin-bottom: 15px;
            
        }

</style>