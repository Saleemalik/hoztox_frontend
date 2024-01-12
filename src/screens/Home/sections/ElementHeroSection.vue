<template>
  <div class="element-hero-section">
    <div class="overlap">
      <div class="image-background">
        <div class="overlap-group-2">
          <img
            class="logistics"
            alt="Logistics"
            src="@/img/logistics-transportation-container-cargo-ship-cargo-plane-with-w.png"
          />
          <div class="replace-this" />
        </div>
      </div>
      <div class="tracking-form-box">
        <div class="tab">
          <div class="tracking-wrapper">
            <div class="tracking">TRACKING</div>
          </div>
          <div class="rate-ship-wrapper">
            <div class="text-wrapper-3">RATE &amp; SHIP</div>
          </div>
        </div>
        <div class="form-box">
          <p class="see-the-tracking-id">
            <span class="span">See the tracking id on shipping document. </span>
            <span class="text-wrapper-4">Help</span>
          </p>
          <div class="tracking-form">
            <div class="field">
              <div class="text-wrapper-3">TRACKING ID</div>
            </div>
            <button class="track-wrapper">
              <div class="track-2">TRACK</div>
            </button>
          </div>
        </div>
      </div>
      <div class="fun-fact">
        <div class="image-box">
          <div class="image" />
          <div class="title">
            <div class="text-wrapper-5">26 K</div>
            <div class="text-wrapper-6">Satisfied Clients</div>
          </div>
        </div>
        <img class="line-2" alt="Line" src="@/img/line-1.svg" />
        <div class="title">
          <div class="text-wrapper-5">12 +</div>
          <div class="text-wrapper-6">Years of Experience</div>
        </div>
      </div>
      <div class="content">
        <div class="title-2">
          <p class="sub-heading">WE ARE BEST LOGISTIC COMPANY</p>
          <p class="heading">STREAMLINE YOUR SHIPPING WITH OUR CARGO SERVICES</p>
        </div>
        <p class="text">
          Simplify your shipping process and make it more efficient with our cargo services. From start to finish,
          we'll handle everything to ensure your cargo arrives safely.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ElementHeroSection",
};
</script>

<style>
.element-hero-section {
  background-color: var(--white);
  height: 741px;
  position: relative;
  width: 1440px;
}

.element-hero-section .overlap {
  height: 741px;
  position: relative;
}

.element-hero-section .image-background {
  background-color: var(--white);
  height: 741px;
  left: 0;
  overflow: hidden;
  position: absolute;
  top: 0;
  width: 1440px;
}

.element-hero-section .overlap-group-2 {
  height: 846px;
  left: -39px;
  position: relative;
  top: -22px;
  width: 1503px;
}

.element-hero-section .logistics {
  height: 741px;
  left: 39px;
  object-fit: cover;
  position: absolute;
  top: 22px;
  width: 1440px;
}

.element-hero-section .replace-this {
  background-color: #00000099;
  height: 846px;
  left: 0;
  position: absolute;
  top: 0;
  width: 1503px;
}

.element-hero-section .tracking-form-box {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  left: 730px;
  position: absolute;
  top: 453px;
}

.element-hero-section .tab {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  position: relative;
}

.element-hero-section .tracking-wrapper {
  align-items: flex-start;
  background-color: var(--dark-blue-2);
  border-radius: 8px 0px 0px 0px;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 10px;
  padding: 16px 24px;
  position: relative;
}

.element-hero-section .tracking {
  color: #1195d6;
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

.element-hero-section .rate-ship-wrapper {
  align-items: flex-start;
  background-color: var(--dark-blue-3);
  border-radius: 0px 8px 0px 0px;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 10px;
  padding: 16px 24px;
  position: relative;
}

.element-hero-section .text-wrapper-3 {
  color: var(--grey-2);
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

.element-hero-section .form-box {
  background-color: var(--dark-blue-2);
  border-radius: 0px 8px 8px 8px;
  height: 132px;
  overflow: hidden;
  position: relative;
  width: 560px;
}

.element-hero-section .see-the-tracking-id {
  color: transparent;
  font-family: var(--caption-font-family);
  font-size: var(--caption-font-size);
  font-style: var(--caption-font-style);
  font-weight: var(--caption-font-weight);
  left: 24px;
  letter-spacing: var(--caption-letter-spacing);
  line-height: var(--caption-line-height);
  position: absolute;
  top: 89px;
  white-space: nowrap;
}

.element-hero-section .span {
  color: #ffffff;
  font-family: var(--caption-font-family);
  font-size: var(--caption-font-size);
  font-style: var(--caption-font-style);
  font-weight: var(--caption-font-weight);
  letter-spacing: var(--caption-letter-spacing);
  line-height: var(--caption-line-height);
}

.element-hero-section .text-wrapper-4 {
  color: #1195d6;
  font-family: var(--caption-font-family);
  font-size: var(--caption-font-size);
  font-style: var(--caption-font-style);
  font-weight: var(--caption-font-weight);
  letter-spacing: var(--caption-letter-spacing);
  line-height: var(--caption-line-height);
}

.element-hero-section .tracking-form {
  align-items: flex-start;
  display: inline-flex;
  gap: 16px;
  left: 24px;
  position: absolute;
  top: 24px;
}

.element-hero-section .field {
  align-items: flex-start;
  border: 1px solid;
  border-color: var(--grey-2);
  border-radius: 8px;
  display: flex;
  gap: 10px;
  padding: 18px 16px;
  position: relative;
  width: 285px;
}

.element-hero-section .track-wrapper {
  all: unset;
  align-items: center;
  background-color: #1195d6;
  border-radius: 8px;
  box-sizing: border-box;
  display: flex;
  gap: 10px;
  justify-content: center;
  padding: 18px 54px;
  position: relative;
  width: 211px;
}

.element-hero-section .track-2 {
  color: var(--white);
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

.element-hero-section .fun-fact {
  align-items: center;
  display: inline-flex;
  gap: 32px;
  left: 150px;
  position: absolute;
  top: 453px;
}

.element-hero-section .image-box {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 20px;
  position: relative;
}

.element-hero-section .image {
  background-image: url(@/img/replace-this.png);
  background-position: 50% 50%;
  background-size: cover;
  border-radius: 6px;
  height: 100px;
  position: relative;
  width: 100px;
}

.element-hero-section .title {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.element-hero-section .text-wrapper-5 {
  color: var(--white);
  font-family: var(--heading-2-font-family);
  font-size: var(--heading-2-font-size);
  font-style: var(--heading-2-font-style);
  font-weight: var(--heading-2-font-weight);
  letter-spacing: var(--heading-2-letter-spacing);
  line-height: var(--heading-2-line-height);
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.element-hero-section .text-wrapper-6 {
  color: var(--white);
  font-family: var(--body-2-font-family);
  font-size: var(--body-2-font-size);
  font-style: var(--body-2-font-style);
  font-weight: var(--body-2-font-weight);
  letter-spacing: var(--body-2-letter-spacing);
  line-height: var(--body-2-line-height);
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.element-hero-section .line-2 {
  height: 72px;
  position: relative;
  width: 2px;
}

.element-hero-section .content {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  gap: 24px;
  left: 150px;
  position: absolute;
  top: 110px;
}

.element-hero-section .title-2 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 16px;
  position: relative;
}

.element-hero-section .sub-heading {
  color: var(--white);
  font-family: var(--SUB-HEADING-1-font-family);
  font-size: var(--SUB-HEADING-1-font-size);
  font-style: var(--SUB-HEADING-1-font-style);
  font-weight: var(--SUB-HEADING-1-font-weight);
  letter-spacing: var(--SUB-HEADING-1-letter-spacing);
  line-height: var(--SUB-HEADING-1-line-height);
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.element-hero-section .heading {
  color: var(--white);
  font-family: var(--heading-1-font-family);
  font-size: var(--heading-1-font-size);
  font-style: var(--heading-1-font-style);
  font-weight: var(--heading-1-font-weight);
  letter-spacing: var(--heading-1-letter-spacing);
  line-height: var(--heading-1-line-height);
  position: relative;
  width: 1040px;
}

.element-hero-section .text {
  color: var(--white);
  font-family: var(--body-1-font-family);
  font-size: var(--body-1-font-size);
  font-style: var(--body-1-font-style);
  font-weight: var(--body-1-font-weight);
  letter-spacing: var(--body-1-letter-spacing);
  line-height: var(--body-1-line-height);
  position: relative;
  width: 560px;
}

</style>
