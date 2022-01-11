<template>
    <div id="destaque">

        <div id="noticias">                    
            <index-news/>
        </div>

        <div id="midia">            
            <index-multimidia/>
        </div>

        <div id="cultura">                    
            <index-arte/>
        </div>

    </div>
</template>

<script>

import indexNews from './destaqueHomeNoticia/indexNews.vue'
import indexMultimidia from './destaqueHomeMultimidia/indexMultimidia.vue'
import indexArte from './destaqueHomeArte/indexArte.vue'

export default {
    components:{
        indexNews,
        indexMultimidia,
        indexArte
    },
    data() {
        // return{
        //     noticiaComentario:35,
        //     musicaComentario:45,
        //     videoComentario:13,
        //     arteComentario:8,


        //     autor:'Tony Rodrigues',
        //     visivel: true
        // }
    }
}
</script>

<style scoped>

    #destaque{
        display: flex;
        flex-direction: column;
        margin-top: 15px;
        /* border: 2px solid lightgreen;   */
        /* height: 49%;     */
        width: 100%;
        /* background: blueviolet; */
    }

    #noticias{
        width: 100%;
        /* margin-right: 10px; */
    }

    #midia{
        width: 100%;
        /* margin-right: 10px; */
        margin-top: 10px;
    }

    #cultura{
        width: 100%;
        margin-top: 10px;
    }
       
    /* Extra small devices (phones, 600px and down) */
    @media only screen and (max-width: 600px) {
        #destaque{
            display: flex;
            flex-direction: column;
            margin-top: 15px;
            /* border: 2px solid lightgreen;   */
            height: 49%;    
        }

        #noticias{
            width: 100%;
            
        }
    
        #midia{
            width: 100%;
            margin-top: 10px;
        }

        #cultura{
            width: 100%;
            margin-top: 10px;
        }
    }

    /* Small devices (portrait tablets and large phones, 600px and up) */
    @media only screen and (min-width: 600px) {
        #destaque{
            display: flex;
            flex-direction: column;
            margin-top: 15px;
            /* border: 2px solid lightgreen;   */
            height: 49%;    
        }

        #noticias{
            width: 50%;
            
        }
    
        #midia{
            width: 25%;
            margin-top: 10px;
        }

        #cultura{
            width: 25%;
            margin-top: 10px;
        }
    }

    /* Medium devices (landscape tablets, 768px and up) */
    @media only screen and (min-width: 768px) {
        #destaque{
            display: flex;
            flex-direction: column;
            margin-top: 15px;
            /* border: 2px solid lightgreen;   */
            height: 49%;    
            background: none;
        }

        #noticias{
            width: 50%;
            margin-right: 10px;
        }
    
        #midia{
            width: 25%;
            margin-right: 10px;
            margin-top: 0 !important;
        }

        #cultura{
            width: 25%;
            margin-top: 0 !important;
        }
    }

    /* Large devices (laptops/desktops, 992px and up) */
    @media only screen and (min-width: 992px) {
        #destaque{
            display: flex;
            flex-direction: row;
            margin-top: 15px;
            /* border: 2px solid lightgreen;   */
            height: 49%;    
        }

        #noticias{
            width: 50%;
            margin-right: 10px;
        }
    
        #midia{
            width: 25%;
            margin-right: 10px;
        }

        #cultura{
            width: 25%;
        }
    }

    /* Extra large devices (large laptops and desktops, 1200px and up) 
    @media only screen and (min-width: 1200px) {...}*/

</style>