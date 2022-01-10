<template>    
    <div id="capaKambaVirtual" >
        <div class="imagem-Capa">
            <img :src="imagemCapa" alt="">
        </div>
        <div class="imagem-CapaPublicite">
            <img :src="imagemCapaPublicite" alt="">
        </div>
    </div>      
</template>

<script>
export default {
    data(){        
        return{
            imagemCapa:require('../../../static/KAMBA-VIRTUAL-LOGO.png'),
            imagemCapaPublicite:require('../../../static/PUBLICITE-AQUI.jpg'),
            
            //src\static\KAMBA-VIRTUAL-LOGO.png
            
            //publish-beside-1
            autor:'Tony Rodrigues',
            visivel: true
        }
    }
}
</script>

<style scoped>


.container{
    padding: 0 5px;
}

#capaKambaVirtual{
    width: 100%;
    display: flex;
    flex-direction: row;    
    margin-top: 25px;
    
}


.imagem-Capa{
    width: 50%;
    
}

.imagem-Capa img{
    width: 100%;
    height: 80px;
    background-size: 100% 100%;
}

.imagem-CapaPublicite{
    width: 50%;
    
}

.imagem-CapaPublicite img{
    width: 100%;
    height: 80px;
    background-size: 100% 100%;
}

</style>