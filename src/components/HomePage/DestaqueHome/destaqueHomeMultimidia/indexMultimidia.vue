<template>                    
    <div id="multimidia">

        <div id="music">  
            <a href="#">   
                <div id="music-up">                
                        <div id="music-up-title">
                            <h5>Música</h5>
                        </div>
                        <div id="music-up-comment">
                            <span class="autor-destaque comentario-destaque"> 
                                <v-icon
                                large
                                dark
                                small
                                >                            
                                    question_answer                            
                                </v-icon> 
                                {{musicaComentario}} 
                            </span>
                        </div>
                </div>
                <div id="music-down">
                        <h5>Nova era digital com kamba Virtual</h5>
                        <span class="autor-destaque"> 
                            <i class="fas fa-user"></i> {{autor}} 
                        </span> 
                        <span class="autor-destaque"> 
                            <i class="far fa-calendar"></i> 17/03/2021
                        </span>
                        <p>
                            Lorem Ipsum is simply ...
                        </p>
                </div>
            </a>
        </div>

        <div id="video">
            <a href="#">                        
                <div id="video-up">
                    <div id="video-up-title">
                        <h5>Vídeo</h5>
                    </div>
                    <div id="video-up-comment">
                        <span class="autor-destaque comentario-destaque"> 
                            <v-icon
                              large
                              dark
                              small
                            >                            
                                question_answer                            
                            </v-icon> 
                            {{videoComentario}} 
                        </span>
                    </div>
                </div>
                <div id="video-down">
                    <h5>Nova era digital com kamba Virtual</h5>
                    <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                    <p>
                        Lorem Ipsum is simply ...
                    </p>
                </div>
            </a>
        </div>

    </div>    
</template>

<script>
export default {
    data() {
        return{
            musicaComentario:45,
            videoComentario:13,
            autor:'Tony Rodrigues',
            visivel: true
        }
    }
}
</script>

<style>

    #multimidia{
        border: none;          
        width: 100%;
        margin-right: 10px;
        display: flex;
        flex-direction: column;
        margin-top: 0; 
        /* height: 49%; */
        height: 100%;
    }       

    #music{
        background: url('../../../../static/capa-musica2021.jpeg');
        background-size: 100% 100%;
        height: 50%;
        margin-bottom: 5px;
    }

    #music-up{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }

    #music-up-title{
        float: left;
        background: orange;
        padding: 5px;
    }

    #music-up-comment{
        float: right;
        background: orange;
        padding: 5px;
    }

    #music-down{
        margin-top: 30px;
        
        margin-left: 10px;
        margin-right: 30px;
        margin-bottom: 5px;
    }

    #music-down h6{
        margin-bottom: 10px;
    }

    .autor-destaque{
        font-size: x-small;
    }

    #music-down p{
        margin-top: 10px;
        text-align: justify;
        font-size: medium;
    }
        
    #video{
        background: url('../../../../static/destaque-video-capa.jpg') !important;
        background-size: 100% 100% !important;
        height: 50%;
        margin-top: 6px !important;
        margin-bottom: 0 !important;
    }

        #video-up{
            display: flex;
            flex-direction: row;
            justify-content: space-between;
        }

        #video-up-title{
            float: left;
            background: orange;
            padding: 5px;
        }

        #video-up-comment{
            float: right;
            background: orange;
            padding: 5px;
        }

        #video-down{
            margin-top: 30px;            
            margin-left: 10px;
            margin-right: 30px;
            margin-bottom: 5px;
        }

        #video-down h6{
            margin-bottom: 10px;
        }

        
        #video-down p{
            margin-top: 10px;
            text-align: justify;
            font-size: medium;
        }

    /* Extra small devices (phones, 600px and down) */
    @media only screen and (max-width: 600px) {
        
    }

    /* Small devices (portrait tablets and large phones, 600px and up) 
    @media only screen and (min-width: 600px) {...}*/

    /* Medium devices (landscape tablets, 768px and up) 
    @media only screen and (min-width: 768px) {...}*/

    /* Large devices (laptops/desktops, 992px and up) 
    @media only screen and (min-width: 992px) {...}*/

    /* Extra large devices (large laptops and desktops, 1200px and up) 
    @media only screen and (min-width: 1200px) {...}*/


</style>