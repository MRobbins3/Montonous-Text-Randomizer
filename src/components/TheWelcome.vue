<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
</script>

<template>
    <WelcomeItem>
        <template #icon>
            <DocumentationIcon/>
        </template>
        <template #heading>Documentation</template>

        Vue’s
        <a target="_blank" href="https://vuejs.org/">official documentation</a>
        provides you with all information you need to get started.
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <ToolingIcon/>
        </template>
        <template #heading>Tooling</template>
        This project is served and bundled with Vite. The recommended IDE setup is VSCode + Volar.
        If you need to test your components and web pages, check out Cypress.
        <br/>

        More instructions are available in <code>README.md</code>.
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <EcosystemIcon/>
        </template>
        <template #heading>Ecosystem</template>
        Get official tools and libraries for your project: Pinia, Vue Router, Vue Test Utils, and Vue Dev Tools.
        If you need more resources, we suggest paying Awesome Vue a visit.
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <CommunityIcon/>
        </template>
        <template #heading>Community</template>

        Got stuck? Ask your question on Vue Land, our official Discord server, or StackOverflow.
        You should also subscribe to our mailing list and follow the official @vuejs twitter account for latest news in the Vue world.
    </WelcomeItem>

</template>
