<script setup>
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
    <template #heading>Biodata</template>

    Vue’s
     Hi, im Rysky Faras Student & Programming,I come from Airtiris and I am currently studying at the Islamic University of Riau. 
    provides you with all information you need to get started.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobi</template>

    I have several hobbies including playing futsal, playing MOBA games, and playing Growtopia.

    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skill</template>

    - Flutter <br>
    - Dart <br>
    - Html & Css <br>
    - Node js <br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Soft Skill</template>

    - Discipline<br>
    - Work with passion <br>
    - Cas work in team<br>
 
  </WelcomeItem>

  
</template>
