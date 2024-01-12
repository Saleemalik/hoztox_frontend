
<template>
  <div class="home">
    <Header />
    <ElementHeroSection />
    <ElementAboutUs />
    <ElementSevice />
    <img class="element-social-proof" alt="Element social proof" src="@/img/4-social-proof.svg" />
    <ElementHowItsWorks />
    <ElementVideoBox />
    <ElementTestimonials />
    <ElementCallToAction />
    <Footer />
  </div>
</template>

<script>
import Header from "./Home/sections/Header.vue";
import ElementHeroSection from "./Home/sections/ElementHeroSection.vue";
import ElementAboutUs from "./Home/sections/ElementAboutUs.vue";
import ElementSevice from "./Home/sections/ElementSevice.vue";
import ElementHowItsWorks from "./Home/sections/ElementHowItsWorks.vue";
import ElementVideoBox from "./Home/sections/ElementVideoBox.vue";
import ElementTestimonials from "./Home/sections/ElementTestimonials.vue";
import ElementCallToAction from "./Home/sections/ElementCallToAction.vue";
import Footer from "./Home/sections/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    ElementHeroSection,
    ElementAboutUs,
    ElementSevice,
    ElementHowItsWorks,
    ElementVideoBox,
    ElementTestimonials,
    ElementCallToAction,
    Footer,
  },
};
</script>


<style>
 .home {
  align-items: flex-end;
  background-color: var(--white);
  display: inline-flex;
  flex-direction: column;
  min-height: 100vh;
  position: relative;
}

.home .element-social-proof {
  height: 246px;
  position: relative;
  width: 1440px;
}

</style>