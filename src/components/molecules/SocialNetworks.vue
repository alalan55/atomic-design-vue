<template>
 <div class="social-networks">
     <SocialLink name="Gitihub" to="https://githu.com" icon="github.svg" />
      <SocialLink name="Twitter" to="https://githu.com" icon="twitter.svg" />
       <SocialLink name="Facebook" to="https://githu.com" icon="facebook.svg" />
 </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink} from '@/components/atoms'

export default defineComponent({

    components:{
        SocialLink
    }
})
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>