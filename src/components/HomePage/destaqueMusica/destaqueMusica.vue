<template>
    <div id="destaqueMusica">
        <v-row class="destaqueMusica">
            <v-col cols="12" class="title-category">
                <v-row>
                    <div class="title-category-type">
                    <h4>Música</h4>
                </div>
                <div class="title-category-link">
                    <a href="#">Ver mais</a>
                </div>
                </v-row>
            </v-col>

            <v-col cols="12" id="detalhe-destaque-musica">
                <div 
                    class="destaque-music" 
                    v-for="destaque in destaqueMusicaDetalhes" 
                    :key="destaque.id"
                    v-bind:style='{backgroundImage: `url(${destaque.imagemFundo})`}'
                >

                    <h3>{{destaque.titulo}}</h3>

                    <span class="destaque-span">Data: {{destaque.dataPulicacao}}</span>
                    
                    <p>
                        {{destaque.descricao}}
                    </p>

                    <a v-bind:href='destaque.linkMusica' target="_blank" >Ler mais</a>

                </div>
            </v-col>
        </v-row>
    </div>
</template>

<script>
export default {
    data:()=>({
        destaqueMusicaDetalhes:[
            {
                id:1, titulo: 'Drena', dataPulicacao: '17/03/2020',
                descricao: 'It is a long established fact that a reader will be distracted by the readable content.',
                linkMusica: 'https://www.google.com/',
                imagemFundo:require('../../../static/destaque-musica/destaque-musica-1.jpg')
            },
            {
                id:2, titulo: 'Drena', dataPulicacao: '17/03/2020',
                descricao: 'It is a long established fact that a reader will be distracted by the readable content.',
                linkMusica: 'https://www.google.com/',
                imagemFundo:require('../../../static/destaque-musica/destaque-musica-2.jpg')
            },
            {
                id:3, titulo: 'Drena', dataPulicacao: '17/03/2020',
                descricao: 'It is a long established fact that a reader will be distracted by the readable content.',
                linkMusica: 'https://www.google.com/',
                imagemFundo:require('../../../static/destaque-musica/destaque-musica-3.jpg')
            },
            {
                id:4, titulo: 'Drena', dataPulicacao: '17/03/2020',
                descricao: 'It is a long established fact that a reader will be distracted by the readable content.',
                linkMusica: 'https://www.google.com/',
                imagemFundo:require('../../../static/destaque-musica/destaque-musica-4.jpg')
            },
        ]
    })
}
</script>

<style scoped>

#destaqueMusica{
    
    margin-top: 20px;
    width: 100%;
}

.destaqueMusica{
    width: 100%;
}

.title-category{
    background: orange;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 100%;  
    /*border: 2px solid black; */
    margin-left: 12px;  
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

#detalhe-destaque-musica{
    
    width: 100%;
    margin-left: 12px;
    margin-top: 5px;
    margin-bottom: 50px;
    display: flex;
    flex-direction: row;
    padding: 0;
}

.destaque-music{
    width: 25%;
    justify-content: space-between;
    /*background: darkblue;*/
    margin: 0%;
    margin-right: 10px;
    padding-top: 10px;
    padding-right: 25px;
    padding-bottom: 10px;
    padding-left: 25px;
    text-align: center;
    background-size: 100 100;
}



.destaque-music:last-child{
    margin: 0;
}

.destaque-music h3{
    /*background: greenyellow;*/
    margin-bottom: 25px;
}

.destaque-music p{
    margin-top: 15px;
    margin-bottom: 20px;
    text-align: justify;
}

.destaque-music a{
    background: orange;
    padding: 5px 3px;
}

.destaque-music a:hover{
    text-decoration: underline;
    background: orangered;
}

.destaque-music:hover h3{
    background: orange;
}







</style>