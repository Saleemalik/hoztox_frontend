<template>
  <div class="element-about-us">
    <div class="card">
      <div class="title-wrapper">
        <div class="title-3">
          <div class="text-wrapper-7">01</div>
          <img class="line-3" alt="Line" src="@/img/line-2.svg" />
          <div class="heading-2">EXPERTISE AND EXPERIENCE</div>
        </div>
      </div>
      <div class="title-wrapper">
        <div class="title-4">
          <div class="text-wrapper-7">02</div>
          <img class="line-3" alt="Line" src="@/img/line-2.svg" />
          <div class="heading-2">COMMITTED TO QUALITY</div>
        </div>
      </div>
      <div class="title-wrapper">
        <div class="title-4">
          <div class="text-wrapper-7">03</div>
          <img class="line-3" alt="Line" src="@/img/line-2.svg" />
          <div class="heading-2">COMPREHENSIVE SERVICES</div>
        </div>
      </div>
    </div>
    <div class="content-2">
      <div class="title-5">
        <div class="sub-heading-2">ABOUT US</div>
        <p class="p">EMPOWERING YOUR BUSINESS WITH TAILORED LOGISTICS SOLUTIONS</p>
      </div>
      <p class="text-2">
        we believe in providing our clients with personalized and efficient logistics solutions that meet their unique
        needs. With years of experience and a team of experts, we are dedicated to empowering your business with
        seamless shipping experiences.
      </p>
      <Button class="design-component-instance-node" property1="big" text="LEARN MORE" />
    </div>
    <div class="overlap-wrapper">
      <div class="overlap-2">
        <img
          class="two-warehouse"
          alt="Two warehouse"
          src="@/img/two-warehouse-workers-walking-distribution-storage-area-discussi.png"
        />
        <div class="ornament-box">
          <div class="overlap-group-3">
            <div class="fun-fact-2">
              <div class="text-box">
                <div class="awwards-winning">AWWARDS WINNING</div>
              </div>
              <div class="text-wrapper-8">647 +</div>
            </div>
            <div class="icon">
              <img class="anchor" alt="Anchor" src="@/img/anchor.svg" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Button from "../../../components/Button.vue";

export default {
  name: "ElementAboutUs",
  components: {
    Button,
  },
};
</script>

<style>
.element-about-us {
  background-color: var(--white);
  height: 890px;
  position: relative;
  width: 1440px;
}

.element-about-us .card {
  align-items: flex-start;
  display: inline-flex;
  gap: 20px;
  left: 150px;
  position: absolute;
  top: 620px;
}

.element-about-us .title-wrapper {
  background-color: var(--dark-blue-2);
  border-radius: 12px;
  height: 160px;
  overflow: hidden;
  position: relative;
  width: 367px;
}

.element-about-us .title-3 {
  align-items: center;
  display: inline-flex;
  gap: 16px;
  left: 40px;
  position: relative;
  top: 48px;
}

.element-about-us .text-wrapper-7 {
  color: var(--white);
  font-family: var(--heading-2-font-family);
  font-size: var(--heading-2-font-size);
  font-style: var(--heading-2-font-style);
  font-weight: var(--heading-2-font-weight);
  letter-spacing: var(--heading-2-letter-spacing);
  line-height: var(--heading-2-line-height);
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.element-about-us .line-3 {
  height: 50px;
  position: relative;
  width: 2px;
}

.element-about-us .heading-2 {
  color: var(--white);
  font-family: var(--heading-5-font-family);
  font-size: var(--heading-5-font-size);
  font-style: var(--heading-5-font-style);
  font-weight: var(--heading-5-font-weight);
  letter-spacing: var(--heading-5-letter-spacing);
  line-height: var(--heading-5-line-height);
  margin-top: -1px;
  position: relative;
  width: 203px;
}

.element-about-us .title-4 {
  align-items: center;
  display: inline-flex;
  gap: 16px;
  left: 36px;
  position: relative;
  top: 48px;
}

.element-about-us .content-2 {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  gap: 20px;
  left: 150px;
  position: absolute;
  top: 110px;
}

.element-about-us .title-5 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 16px;
  position: relative;
}

.element-about-us .sub-heading-2 {
  color: var(--blue-1);
  font-family: var(--SUB-HEADING-2-font-family);
  font-size: var(--SUB-HEADING-2-font-size);
  font-style: var(--SUB-HEADING-2-font-style);
  font-weight: var(--SUB-HEADING-2-font-weight);
  letter-spacing: var(--SUB-HEADING-2-letter-spacing);
  line-height: var(--SUB-HEADING-2-line-height);
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.element-about-us .p {
  color: var(--dark-blue-1);
  font-family: var(--heading-2-font-family);
  font-size: var(--heading-2-font-size);
  font-style: var(--heading-2-font-style);
  font-weight: var(--heading-2-font-weight);
  letter-spacing: var(--heading-2-letter-spacing);
  line-height: var(--heading-2-line-height);
  position: relative;
  width: 580px;
}

.element-about-us .text-2 {
  color: var(--grey-2);
  font-family: var(--body-1-font-family);
  font-size: var(--body-1-font-size);
  font-style: var(--body-1-font-style);
  font-weight: var(--body-1-font-weight);
  letter-spacing: var(--body-1-letter-spacing);
  line-height: var(--body-1-line-height);
  position: relative;
  width: 580px;
}

.element-about-us .design-component-instance-node {
  background-color: #1195d6 !important;
  flex: 0 0 auto !important;
}

.element-about-us .overlap-wrapper {
  border-radius: 12px;
  height: 410px;
  left: 784px;
  overflow: hidden;
  position: absolute;
  top: 110px;
  width: 506px;
}

.element-about-us .overlap-2 {
  background-color: var(--dark-blue-1);
  height: 438px;
  left: -116px;
  position: relative;
  top: -14px;
  width: 656px;
}

.element-about-us .two-warehouse {
  height: 410px;
  left: 116px;
  object-fit: cover;
  position: absolute;
  top: 14px;
  width: 506px;
}

.element-about-us .ornament-box {
  height: 217px;
  left: 176px;
  position: absolute;
  top: 147px;
  width: 172px;
}

.element-about-us .overlap-group-3 {
  height: 217px;
  position: relative;
}

.element-about-us .fun-fact-2 {
  background-color: var(--white);
  border-radius: 8px;
  height: 187px;
  left: 0;
  overflow: hidden;
  position: absolute;
  top: 30px;
  width: 172px;
}

.element-about-us .text-box {
  background-color: var(--blue-1);
  border-radius: 4px;
  height: 73px;
  left: 10px;
  overflow: hidden;
  position: absolute;
  top: 104px;
  width: 152px;
}

.element-about-us .awwards-winning {
  color: var(--white);
  font-family: var(--SUB-HEADING-1-font-family);
  font-size: var(--SUB-HEADING-1-font-size);
  font-style: var(--SUB-HEADING-1-font-style);
  font-weight: var(--SUB-HEADING-1-font-weight);
  left: 22px;
  letter-spacing: var(--SUB-HEADING-1-letter-spacing);
  line-height: var(--SUB-HEADING-1-line-height);
  position: absolute;
  text-align: center;
  top: 18px;
  width: 108px;
}

.element-about-us .text-wrapper-8 {
  color: var(--dark-blue-1);
  font-family: var(--heading-2-font-family);
  font-size: var(--heading-2-font-size);
  font-style: var(--heading-2-font-style);
  font-weight: var(--heading-2-font-weight);
  left: 22px;
  letter-spacing: var(--heading-2-letter-spacing);
  line-height: var(--heading-2-line-height);
  position: absolute;
  text-align: center;
  top: 34px;
  white-space: nowrap;
}

.element-about-us .icon {
  background-color: #1195d6;
  border-radius: 29.5px;
  height: 59px;
  left: 10px;
  position: absolute;
  top: 0;
  width: 59px;
}

.element-about-us .anchor {
  height: 24px;
  left: 18px;
  position: absolute;
  top: 18px;
  width: 24px;
}

</style>