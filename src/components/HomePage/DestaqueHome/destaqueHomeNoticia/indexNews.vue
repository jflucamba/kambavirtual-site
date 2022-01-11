<template>
    <div id="news">
        <a href="#">                   
                    
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
        </a>
    </div>
</template>

<script>
export default {
    data() {
        return{
            noticiaComentario:35,
            autor:'Euclides Matias',
            visivel: true
        }
    }
}
</script>

<style>

    #news{
        width: 100%;
        margin-right: 10px;
        background: url('../../../../static/destaque-news-capa.jpg');
        background-size: 100% 100%;
        display: flex;
        flex-direction: column;
        height: 100%;
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

    #news-up-title:hover{
        background: red;        
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
                               
    .comentario-destaque{
        font-size: medium;
        font-weight: 400;
        
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