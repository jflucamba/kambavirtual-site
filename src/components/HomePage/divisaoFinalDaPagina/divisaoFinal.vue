<template>
    <div id="divisao-final" >
        <div id="lateral-esquerda">
            <destaque-noticia/>
            <destaque-art/>
        </div>
        <div id="lateral-direita">
            j,nkfghfkghklfghklfklhklfklhjfknhjflnhjmnmcv,.bnm,bvn,.vmn 
            jkdghjkdfhjkgdfjkgh jkhjgfjk jkdfsjkh
            fgjhdfgs
        </div>
    </div>
</template>

<script>
import destaqueNoticia from '@/components/HomePage/destaqueNoticia/destaqueNoticia.vue'
import destaqueArt from '@/components/HomePage/destaqueArt/destaqueArt.vue'
export default {
    components:{
        destaqueNoticia,
        destaqueArt
        
    }
}
</script>

<style>

#divisao-final{
    border: 2px solid red;
    width: 100%;
    /*margin-left: 5px;*/
    margin-top: -25px;
    /*justify-content: space-between;*/
    display: flex;
    flex-direction: row;
    
}

#lateral-esquerda{
    
    margin-right: 0px;
    width: 70%;
    margin-right: 10px;
    display: flex;
    flex-direction: column;
}

#lateral-direita{
    background: coral;
    width: 30%;
    
}

</style>