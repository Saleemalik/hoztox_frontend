<template>
  <div class="element-call-to-action">
    <div class="form-box-2">
      <Button class="button-2" property1="big" text="SUBMIT" />
      <div class="form">
        <div class="field-2">
          <div class="label-2">YOUR NAME</div>
          <div class="filed">
            <div class="text-field">Ex: Jhon Dee</div>
          </div>
        </div>
        <div class="field-2">
          <div class="label-2">EMAIL ADDRESS</div>
          <div class="filed">
            <div class="text-field">Ex: jhondee@gmail.com</div>
          </div>
        </div>
        <div class="field-2">
          <div class="label-2">PHONE</div>
          <div class="filed">
            <div class="text-field">Ex: +1 (333) 000-0000</div>
          </div>
        </div>
        <div class="field-2">
          <div class="label-2">MESSAGE</div>
          <input class="text-field-wrapper" placeholder="Writing your message here..." type="number" />
        </div>
      </div>
      <div class="request-a-quote">REQUEST A QUOTE TODAY</div>
    </div>
    <div class="title-12">
      <div class="sub-heading-6">CONTACT US</div>
      <p class="heading-10">TAKE THE FIRST STEP TO STREAMLINED SHIPPING</p>
    </div>
    <div class="icon-box">
      <div class="icon-box-2">
        <img class="icon-5" alt="Icon" src="@/img/icon.svg" />
        <div class="title-13">
          <div class="heading-11">Call Us</div>
          <div class="text-wrapper-12">+2 333 000-0000</div>
        </div>
      </div>
      <img class="line-5" alt="Line" src="@/img/line-5.svg" />
      <div class="icon-box-2">
        <img class="icon-5" alt="Icon" src="@/img/icon.svg" />
        <div class="title-13">
          <div class="heading-11">Email</div>
          <div class="text-wrapper-12">MASSSHIPPING@MAIL.COM</div>
        </div>
      </div>
      <img class="line-5" alt="Line" src="@/img/line-5.svg" />
      <div class="icon-box-2">
        <img class="icon-5" alt="Icon" src="@/img/icon.svg" />
        <div class="title-13">
          <div class="heading-11">Office</div>
          <div class="text-wrapper-12">ANYWHERE STREET, NY</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Button from "../../../components/Button.vue";

export default {
  name: "ElementCallToAction",
  components: {
    Button,
  },
};
</script>

<style>
.element-call-to-action {
  background-color: var(--white);
  height: 910px;
  position: relative;
  width: 1440px;
}

.element-call-to-action .form-box-2 {
  background-color: var(--grey-1);
  border-radius: 12px;
  height: 690px;
  left: 730px;
  overflow: hidden;
  position: absolute;
  top: 110px;
  width: 560px;
}

.element-call-to-action .button-2 {
  background-color: #1195d6 !important;
  left: 68px !important;
  position: absolute !important;
  top: 568px !important;
}

.element-call-to-action .form {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  gap: 20px;
  left: 68px;
  position: absolute;
  top: 160px;
}

.element-call-to-action .field-2 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 10px;
  position: relative;
}

.element-call-to-action .label-2 {
  color: var(--dark-blue-2);
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

.element-call-to-action .filed {
  align-items: center;
  background-color: var(--white);
  border-radius: 8px;
  display: flex;
  flex: 0 0 auto;
  gap: 10px;
  padding: 20px 58px 20px 20px;
  position: relative;
  width: 424px;
}

.element-call-to-action .text-field {
  color: var(--grey-2);
  font-family: var(--caption-font-family);
  font-size: var(--caption-font-size);
  font-style: var(--caption-font-style);
  font-weight: var(--caption-font-weight);
  letter-spacing: var(--caption-letter-spacing);
  line-height: var(--caption-line-height);
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.element-call-to-action .text-field-wrapper {
  background-color: var(--white);
  border: none;
  border-radius: 8px;
  color: var(--grey-2);
  font-family: var(--caption-font-family);
  font-size: var(--caption-font-size);
  font-style: var(--caption-font-style);
  font-weight: var(--caption-font-weight);
  letter-spacing: var(--caption-letter-spacing);
  line-height: var(--caption-line-height);
  margin-top: -1px;
  padding: 20px 58px 20px 20px;
  position: relative;
  white-space: nowrap;
  width: 424px;
}

.element-call-to-action .request-a-quote {
  color: var(--dark-blue-1);
  font-family: var(--heading-5-font-family);
  font-size: var(--heading-5-font-size);
  font-style: var(--heading-5-font-style);
  font-weight: var(--heading-5-font-weight);
  left: 68px;
  letter-spacing: var(--heading-5-letter-spacing);
  line-height: var(--heading-5-line-height);
  position: absolute;
  top: 67px;
  white-space: nowrap;
}

.element-call-to-action .title-12 {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  gap: 16px;
  left: 150px;
  position: absolute;
  top: 110px;
}

.element-call-to-action .sub-heading-6 {
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

.element-call-to-action .heading-10 {
  color: var(--dark-blue-1);
  font-family: var(--heading-2-font-family);
  font-size: var(--heading-2-font-size);
  font-style: var(--heading-2-font-style);
  font-weight: var(--heading-2-font-weight);
  letter-spacing: var(--heading-2-letter-spacing);
  line-height: var(--heading-2-line-height);
  position: relative;
  width: 481px;
}

.element-call-to-action .icon-box {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  gap: 24px;
  left: 150px;
  position: absolute;
  top: 366px;
}

.element-call-to-action .icon-box-2 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 44px;
  position: relative;
}

.element-call-to-action .icon-5 {
  height: 106px;
  position: relative;
  width: 106px;
}

.element-call-to-action .title-13 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 8px;
  position: relative;
}

.element-call-to-action .heading-11 {
  color: var(--dark-blue-1);
  font-family: var(--body-1-font-family);
  font-size: var(--body-1-font-size);
  font-style: var(--body-1-font-style);
  font-weight: var(--body-1-font-weight);
  letter-spacing: var(--body-1-letter-spacing);
  line-height: var(--body-1-line-height);
  margin-top: -1px;
  position: relative;
  width: 287px;
}

.element-call-to-action .text-wrapper-12 {
  color: var(--dark-blue-2);
  font-family: "Space Grotesk", Helvetica;
  font-size: 20px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 26px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.element-call-to-action .line-5 {
  height: 1px;
  object-fit: cover;
  position: relative;
  width: 437px;
}

</style>