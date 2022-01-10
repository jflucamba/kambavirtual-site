<template>
    <div class="container">
        <div id="homepage">
            <div>
                <capa-kamba-virtual/>
            </div>

            <div>
                <menu-interno/>
            </div>
            
            <div>
                <destaque-home/>
            </div>

            <div>
                <publicidade-home/>
            </div>

            <div>
                <destaque-musica/>
            </div>

            <div>
                <divisao-final/>
            </div>
            
        </div>
    </div>
    
</template>

<script>
import capaKambaVirtual from '@/components/HomePage/imagensCapaPrincipal/capaKambaVirtual.vue'
import menuInterno from '@/components/MenuSite/menuInterno.vue'
import destaqueHome from '@/components/HomePage/DestaqueHome/destaqueHome.vue'
import publicidadeHome from '@/components/PublicidadePage/publicidadeHome.vue'
import destaqueMusica from '@/components/HomePage/destaqueMusica/destaqueMusica.vue'
import divisaoFinal from '@/components/HomePage/divisaoFinalDaPagina/divisaoFinal.vue'


export default {
    components:{
        capaKambaVirtual,
        menuInterno,
        destaqueHome,
        publicidadeHome,
        destaqueMusica,
        divisaoFinal,
        
    }
}
</script>

<style scoped>



#homepage{
    display: flex;
    flex-direction: column;
    width: 100%;
}



</style>