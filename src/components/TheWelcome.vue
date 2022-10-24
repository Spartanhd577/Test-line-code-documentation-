z<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Documentacion odoo</template>

    Odoo
    <a target="_blank" href="https://www.odoo.com/documentation/16.0/">offici al documentacion</a>
    empezar.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>ERP</template>

    ERP informacion sobre modulos y de mas:
    <a target="_blank" href="https://www.odoo.com/es_ES/page/all-apps">Modulos</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Odoo Forum</template>

    ¿Está atascado? Haga su pregunta en
    <a target="_blank" href="https://www.odoo.com/es_ES/forum/ayuda-1">Odoo forum</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
        <template #heading>Odoo Enterprise vs Odoo Community</template>
        Diferencias entre Odoo enterprise y Odoo Comminity revise
        <a target="_blank" href="https://www.odoo.com/es_ES/page/editions">Odoo page</a>       
  </WelcomeItem>

</template>
