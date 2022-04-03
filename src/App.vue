<template>
  <HeaderAndBanner></HeaderAndBanner>
  <MainBody></MainBody>
  <SkillsArea></SkillsArea>
  <ContactArea></ContactArea>
  <FooterArea></FooterArea>
</template>

<script>
import HeaderAndBanner from "./components/HeaderAndBanner.vue"
import MainBody from "./components/MainBody.vue"
import SkillsArea from "./components/SkillsArea.vue"
import ContactArea from "./components/ContactArea.vue"
import FooterArea from "./components/FooterArea.vue"

export default {
  name: 'App',
  components: {
    HeaderAndBanner,
    MainBody,
    SkillsArea,
    ContactArea,
    FooterArea
  }
}
</script>


