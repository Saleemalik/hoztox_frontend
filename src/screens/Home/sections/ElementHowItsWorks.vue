<template>
  <div class="element-how-its-works">
    <img class="line-4" alt="Line" src="@/img/line-3.svg" />
    <div class="step">
      <div class="step-2">
        <div class="title-8">
          <div class="heading-6">REQUEST A QUOTE</div>
          <p class="text-5">
            we believe in providing our clients with personalized and efficient logistics solutions that meet their
            unique needs.
          </p>
        </div>
        <img class="icon-3" alt="Icon" src="@/img/icon-4.svg" />
        <div class="label">
          <div class="text-wrapper-9">Step 1</div>
        </div>
      </div>
      <div class="step-2">
        <div class="title-8">
          <div class="heading-6">PROVIDE DETAILS</div>
          <p class="text-5">
            we believe in providing our clients with personalized and efficient logistics solutions that meet their
            unique needs.
          </p>
        </div>
        <img class="icon-3" alt="Icon" src="@/img/icon-4.svg" />
        <div class="label">
          <div class="text-wrapper-9">Step 2</div>
        </div>
      </div>
      <div class="step-2">
        <div class="title-8">
          <div class="heading-6">SCHEDULE PICK-UP</div>
          <p class="text-5">
            we believe in providing our clients with personalized and efficient logistics solutions that meet their
            unique needs.
          </p>
        </div>
        <img class="icon-3" alt="Icon" src="@/img/icon-4.svg" />
        <div class="label">
          <div class="text-wrapper-9">Step 3</div>
        </div>
      </div>
    </div>
    <p class="text-6">
      we believe in providing our clients with personalized and efficient logistics solutions that meet their unique
      needs. With years of experience and a team of experts, we are dedicated to empowering your business with seamless
      shipping experiences.
    </p>
    <div class="title-9">
      <div class="sub-heading-4">HOW IT WORKS</div>
      <p class="heading-7">SIMPLIFY YOUR SHIPPING EXPERIENCE WITH OUR EASY STEP PROCESS</p>
    </div>
    <div class="overlap-group-wrapper">
      <div class="smiling-female-wrapper">
        <img
          class="smiling-female"
          alt="Smiling female"
          src="@/img/smiling-female-worker-holding-tablet-bar-code-scanner-checking-i.png"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ElementHowItsWorks",
};
</script>

<style>
.element-how-its-works {
  background-color: var(--white);
  height: 1051px;
  position: relative;
  width: 1440px;
}

.element-how-its-works .line-4 {
  height: 2px;
  left: 150px;
  position: absolute;
  top: 524px;
  width: 1140px;
}

.element-how-its-works .step {
  align-items: flex-start;
  display: inline-flex;
  gap: 119px;
  left: 171px;
  position: absolute;
  top: 596px;
}

.element-how-its-works .step-2 {
  height: 345px;
  position: relative;
  width: 287px;
}

.element-how-its-works .title-8 {
  align-items: center;
  display: inline-flex;
  flex-direction: column;
  gap: 16px;
  left: 0;
  position: absolute;
  top: 209px;
}

.element-how-its-works .heading-6 {
  color: #121d50;
  font-family: var(--heading-5-font-family);
  font-size: var(--heading-5-font-size);
  font-style: var(--heading-5-font-style);
  font-weight: var(--heading-5-font-weight);
  letter-spacing: var(--heading-5-letter-spacing);
  line-height: var(--heading-5-line-height);
  margin-top: -1px;
  position: relative;
  text-align: center;
  width: 287px;
}

.element-how-its-works .text-5 {
  color: var(--grey-2);
  font-family: var(--body-2-font-family);
  font-size: var(--body-2-font-size);
  font-style: var(--body-2-font-style);
  font-weight: var(--body-2-font-weight);
  letter-spacing: var(--body-2-letter-spacing);
  line-height: var(--body-2-line-height);
  position: relative;
  text-align: center;
  width: 287px;
}

.element-how-its-works .icon-3 {
  height: 132px;
  left: 78px;
  position: absolute;
  top: 45px;
  width: 132px;
}

.element-how-its-works .label {
  align-items: flex-start;
  background-color: var(--white);
  border: 2px solid;
  border-color: var(--grey-1);
  border-radius: 90px;
  display: inline-flex;
  justify-content: center;
  left: 111px;
  padding: 8px 16px;
  position: absolute;
  top: 0;
}

.element-how-its-works .text-wrapper-9 {
  color: #121d50;
  font-family: var(--caption-font-family);
  font-size: var(--caption-font-size);
  font-style: var(--caption-font-style);
  font-weight: var(--caption-font-weight);
  letter-spacing: var(--caption-letter-spacing);
  line-height: var(--caption-line-height);
  margin-top: -2px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.element-how-its-works .text-6 {
  color: var(--grey-2);
  font-family: var(--body-1-font-family);
  font-size: var(--body-1-font-size);
  font-style: var(--body-1-font-style);
  font-weight: var(--body-1-font-weight);
  left: 710px;
  letter-spacing: var(--body-1-letter-spacing);
  line-height: var(--body-1-line-height);
  position: absolute;
  top: 345px;
  width: 580px;
}

.element-how-its-works .title-9 {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  gap: 16px;
  left: 710px;
  position: absolute;
  top: 110px;
}

.element-how-its-works .sub-heading-4 {
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

.element-how-its-works .heading-7 {
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

.element-how-its-works .overlap-group-wrapper {
  border-radius: 12px;
  height: 336px;
  left: 150px;
  overflow: hidden;
  position: absolute;
  top: 110px;
  width: 506px;
}

.element-how-its-works .smiling-female-wrapper {
  background-color: var(--dark-blue-1);
  height: 372px;
  left: -25px;
  position: relative;
  top: -18px;
  width: 556px;
}

.element-how-its-works .smiling-female {
  height: 336px;
  left: 25px;
  object-fit: cover;
  position: absolute;
  top: 18px;
  width: 506px;
}

</style>
