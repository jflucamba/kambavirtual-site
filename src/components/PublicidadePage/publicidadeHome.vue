<template>
    <div id="publicidadeHome">
        <a target="_blank" v-bind:href="linkPublicidadeHome">
            <img :src="imagemPublicidade" alt="">
        </a>
    </div>
</template>

<script>
export default {
    data(){
        return{
            imagemPublicidade:require('../../static/homePublicidade.jpg'),
            linkPublicidadeHome: 'http://google.com.br'
        }
    }
}
</script>

<style scoped>

#publicidadeHome{
    width: 100%;
    height: 100px;
    margin-top: 15px;
}

#publicidadeHome img{
    object-fit:fi;
    width: 100%;
    height: 100%;
    background-size: 100 100;
    
}


</style>