<template>
  <header class="header">
    <div class="frame">
      <div class="text-wrapper">massshipping@mail.com</div>
      <img class="line" alt="Line" src="@/img/line-23.svg" />
      <div class="div">+1 (333) 000-0000</div>
    </div>
    <div class="frame-2">
      <div class="navbar">
        <div class="home-2">HOME</div>
        <div class="text-wrapper-2">ABOUT US</div>
        <div class="text-wrapper-2">SERVICES</div>
        <div class="text-wrapper-2">GALLERY</div>
        <div class="text-wrapper-2">CONTACT US</div>
      </div>
      <div class="group">
        <div class="overlap-group">
          <img class="vector" alt="Vector" src="@/img/vector-9.svg" />
          <img class="img" alt="Vector" src="@/img/vector-8.svg" />
          <img class="vector-2" alt="Vector" src="@/img/vector-7.svg" />
          <img class="vector-3" alt="Vector" src="@/img/vector-6.svg" />
          <img class="vector-4" alt="Vector" src="@/img/vector-5.svg" />
        </div>
        <img class="group-2" alt="Group" src="@/img/group-3.png" />
        <div class="group-3" />
        <img class="group-4" alt="Group" src="@/img/group-2.png" />
      </div>
    </div>
    <Button class="button-instance" property1="big" text="GET QUOTE" />
  </header>
</template>

<script>
import Button from "../../../components/Button.vue";

export default {
  name: "Header",
  components: {
    Button,
  },
};
</script>

<style>
.header {
  background-color: var(--white);
  flex: 1;
  flex-grow: 1;
  position: relative;
  width: 1440px;
  margin-bottom: 11rem;
}

.header .frame {
  align-items: center;
  display: inline-flex;
  gap: 16px;
  left: 150px;
  position: absolute;
  top: 27px;
}

.header .text-wrapper {
  color: var(--dark-blue-2);
  font-family: "Space Grotesk", Helvetica;
  font-size: 16px;
  font-weight: 500;
  letter-spacing: 1.04px;
  line-height: 16px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.header .line {
  height: 32px;
  object-fit: cover;
  position: relative;
  width: 1px;
}

.header .div {
  color: var(--dark-blue-2);
  font-family: var(--BUTTON-font-family);
  font-size: var(--BUTTON-font-size);
  font-style: var(--BUTTON-font-style);
  font-weight: var(--BUTTON-font-weight);
  letter-spacing: var(--BUTTON-letter-spacing);
  line-height: var(--BUTTON-line-height);
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.header .frame-2 {
  background-color: var(--dark-blue-1);
  height: 94px;
  left: 0;
  position: absolute;
  top: 86px;
  width: 1440px;
}

.header .navbar {
  align-items: flex-start;
  display: inline-flex;
  gap: 24px;
  left: 844px;
  position: absolute;
  top: 40px;
  transform: rotate(-0.26deg);
}

.header .home-2 {
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

.header .text-wrapper-2 {
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

.header .group {
  height: 64px;
  left: 150px;
  position: absolute;
  top: 15px;
  width: 188px;
}

.header .overlap-group {
  height: 64px;
  left: 0;
  position: absolute;
  top: 0;
  width: 72px;
}

.header .vector {
  height: 64px;
  left: 10px;
  position: absolute;
  top: 0;
  width: 48px;
}

.header .img {
  height: 29px;
  left: 0;
  position: absolute;
  top: 19px;
  width: 72px;
}

.header .vector-2 {
  height: 14px;
  left: 10px;
  position: absolute;
  top: 21px;
  width: 16px;
}

.header .vector-3 {
  height: 8px;
  left: 28px;
  position: absolute;
  top: 13px;
  width: 23px;
}

.header .vector-4 {
  height: 12px;
  left: 1px;
  position: absolute;
  top: 29px;
  width: 8px;
}

.header .group-2 {
  height: 33px;
  left: 80px;
  position: absolute;
  top: 9px;
  width: 106px;
}

.header .group-3 {
  background-image: url(@/img/clip-path-group-1.png);
  background-size: 100% 100%;
  height: 1px;
  left: 80px;
  position: absolute;
  top: 46px;
  width: 108px;
}

.header .group-4 {
  height: 8px;
  left: 80px;
  position: absolute;
  top: 50px;
  width: 104px;
}

.header .button-instance {
  background-color: #1195d6 !important;
  left: 1075px !important;
  position: absolute !important;
  top: 16px !important;
}

</style>