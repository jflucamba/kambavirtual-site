<template>
    <div id="destaque">

        <div id="news">
                    
            <div id="news-up">
                <div id="news-up-title">
                    <h5>Notícia</h5>
                </div>
                <div id="news-up-comment">
                    <span class="autor-destaque comentario-destaque"> 
                        <v-icon
                          large
                          dark
                          small
                        >                            
                            question_answer                            
                        </v-icon> 
                        {{noticiaComentario}} 
                    </span>
                    
                </div>
            </div>

            <div id="news-down">
                <h4>Nova era digital com kamba Virtual</h4>
                <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                <p>
                    Lorem Ipsum is simply dummy text of the printing and typesetting 
                    industry. Lorem Ipsum has been the industry's 
                    standard dummy text ever since the 1500s
                </p>
            </div>

        </div>

        <div id="multimidia">

            <div id="music">
                        
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
                    <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                    <p>
                        Lorem Ipsum is simply ...
                    </p>
                </div>

            </div>

            <div id="video">
                        
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

            </div>

        </div>

        <div id="arte">
                    
            <div id="arte-up">
                <div id="arte-up-title">
                    <h5>Arte</h5>
                </div>
                <div id="arte-up-comment">
                    <span class="autor-destaque comentario-destaque"> 
                        <v-icon
                          large
                          dark
                          small
                        >                            
                            question_answer                            
                        </v-icon>  
                        {{arteComentario}} 
                    </span>
                </div>
            </div>
            <div id="arte-down">
                <h4>Nova era digital com kamba Virtual</h4>
                <span class="autor-destaque"> <i class="fas fa-user"></i> {{autor}} </span> <span class="autor-destaque"> <i class="far fa-calendar"></i> 17/03/2021</span>
                <p>
                    Lorem Ipsum is simply dummy text of the printing and typesetting 
                    industry.
                </p>
            </div>

        </div>

    </div>
</template>

<script>
export default {
    data() {
        return{
            noticiaComentario:35,
            musicaComentario:45,
            videoComentario:13,
            arteComentario:8,


            autor:'Tony Rodrigues',
            visivel: true
        }
    }
}
</script>

<style scoped>

#destaque{
            display: flex;
            flex-direction: row;
            margin-top: 15px;
            
        }

        /*#destaque #news,#multimidia,#arte{
            
        }*/

        #destaque #news{
            
            width: 50%;
            margin-right: 10px;
            background: url('../../../static/destaque-news-capa.jpg');
            background-size: 100% 100%;
            display: flex;
            flex-direction: column;
        }

        #news-up{
            display: flex;
            flex-direction: row;
            justify-content: space-between;
        }

        #news-up-title{
            float: left;
            background: orange;
            padding: 5px;
        }

        #news-up-comment{
            float: right;
            background: orange;
            padding: 5px;
        }

        #news-down{
            margin-top: 100px;
            
            margin-left: 10px;
            margin-right: 30px;
        }

        #news-down h4{
            margin-bottom: 10px;
        }

        .autor-destaque{
            font-size: small;
        }

        #news-down p{
            margin-top: 10px;
            text-align: justify;
        }
        
        #destaque #multimidia{
            border: none;          
            width: 25%;
            margin-right: 10px;
            display: flex;
            flex-direction: column;
            margin-top: 0;            
        }       

        #music{
            background: url('../../../static/capa-musica2021.jpeg');
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
            background: url('../../../static/destaque-video-capa.jpg') !important;
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

        #arte{
            background: url('../../../static/arte-capa-destaque2021.jpg') !important;
            width: 25% !important;
            background-size: 100% 100% !important;
            margin: 0 !important;
        }

        #arte-up{
            display: flex;
            flex-direction: row;
            justify-content: space-between;
        }

        #arte-up-title{
            float: left;
            background: orange;
            padding: 5px;
        }

        #arte-up-comment{
            float: right;
            background: orange;
            padding: 5px;
        }

        #arte-down{
            margin-top: 80px;            
            margin-left: 10px;
            margin-right: 30px;
        }

        #arte-down h4{
            margin-bottom: 10px;
        }
        
        #arte-down p{
            margin-top: 10px;
            text-align: justify;
            font-size: medium;
        }

        .comentario-destaque{
            font-size: medium;
            font-weight: 400;
            
        }

</style>