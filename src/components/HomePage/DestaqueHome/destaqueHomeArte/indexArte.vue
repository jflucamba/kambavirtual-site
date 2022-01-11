<template>                    
    <div id="arte">
        <a href="#">
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
        </a>
    </div>
</template>

<script>
export default {
    data() {
        return{            
            arteComentario:8,
            autor:'Tony Rodrigues',
            visivel: true
        }
    }
}
</script>

<style>

    #arte{
            background: url('../../../../static/arte-capa-destaque2021.jpg') !important;
            width: 100% !important;
            background-size: 100% 100% !important;
            margin: 0 !important;
            /* height: 49%; */
            height: 100%;
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