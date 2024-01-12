<template>
  <footer class="footer">
    <div class="group-5">
      <div class="overlap-group-5">
        <img class="vector-5" alt="Vector" src="@/img/vector-4.svg" />
        <img class="vector-6" alt="Vector" src="@/img/vector-3.svg" />
        <img class="vector-7" alt="Vector" src="@/img/vector-2.svg" />
        <img class="vector-8" alt="Vector" src="@/img/vector-1.svg" />
        <img class="vector-9" alt="Vector" src="@/img/vector.svg" />
      </div>
      <img class="group-6" alt="Group" src="@/img/group-1.png" />
      <div class="group-7"></div>
      <img class="group-8" alt="Group" src="@/img/group.png" />
    </div>
    <p class="text-8">
      we believe in providing our clients with personalized and efficient logistics solutions that meet their unique
      needs.
    </p>
    <div class="navigation">
      <div class="heading-12">NAVIGATION</div>
      <div class="list">
        <div class="text-wrapper-13">Home</div>
        <div class="text-wrapper-14">About Us</div>
        <div class="text-wrapper-14">Services</div>
        <div class="text-wrapper-14">Contact Us</div>
      </div>
    </div>
    <div class="recent-project">
      <div class="heading-12">RECENT PROJECT</div>
      <div class="image-3">
        <div class="man-with-helmet-wrapper">
          <img class="man-with-helmet" alt="Man with helmet" src="@/img/man-with-helmet-warehouse-1.png" />
        </div>
      </div>
    </div>
    <div class="subscribe">
      <div class="heading-12">SUBSCRIBE US</div>
      <div class="form-subscribe">
        <input class="input" placeholder="Enter Your Email" type="email" />
        <Button class="button-3" property1="big" text="SUBSCRIBE NOW" />
      </div>
    </div>
    <img class="line-6" alt="Line" src="@/img/line-7.svg" />
    <div class="copyright">
      COPYRIGHT © 2023 MASSSHIPPING
    </div>
  </footer>
</template>

<script>
import Button from "../../../components/Button.vue";

export default {
  name: "Footer",
  components: {
    Button,
  },
};
</script>

<style>
.footer {
  background-color: var(--dark-blue-2);
  height: 470px;
  position: relative;
  width: 1440px;
}

.footer .group-5 {
  height: 84px;
  left: 150px;
  position: absolute;
  top: 100px;
  width: 248px;
}

.footer .overlap-group-5 {
  height: 84px;
  left: 0;
  position: absolute;
  top: 0;
  width: 95px;
}

.footer .vector-5 {
  height: 84px;
  left: 13px;
  position: absolute;
  top: 0;
  width: 63px;
}

.footer .vector-6 {
  height: 39px;
  left: 0;
  position: absolute;
  top: 25px;
  width: 95px;
}

.footer .vector-7 {
  height: 19px;
  left: 13px;
  position: absolute;
  top: 28px;
  width: 21px;
}

.footer .vector-8 {
  height: 10px;
  left: 37px;
  position: absolute;
  top: 18px;
  width: 30px;
}

.footer .vector-9 {
  height: 15px;
  left: 1px;
  position: absolute;
  top: 38px;
  width: 11px;
}

.footer .group-6 {
  height: 43px;
  left: 105px;
  position: absolute;
  top: 12px;
  width: 139px;
}

.footer .group-7 {
  background-image: url(@/img/clip-path-group.png);
  background-size: 100% 100%;
  height: 1px;
  left: 105px;
  position: absolute;
  top: 61px;
  width: 142px;
}

.footer .group-8 {
  height: 10px;
  left: 105px;
  position: absolute;
  top: 65px;
  width: 137px;
}

.footer .text-8 {
  color: var(--white);
  font-family: var(--body-1-font-family);
  font-size: var(--body-1-font-size);
  font-style: var(--body-1-font-style);
  font-weight: var(--body-1-font-weight);
  left: 150px;
  letter-spacing: var(--body-1-letter-spacing);
  line-height: var(--body-1-line-height);
  position: absolute;
  top: 201px;
  width: 311px;
}

.footer .navigation {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  gap: 20px;
  left: 521px;
  position: absolute;
  top: 100px;
}

.footer .heading-12 {
  color: var(--white);
  font-family: var(--heading-5-font-family);
  font-size: var(--heading-5-font-size);
  font-style: var(--heading-5-font-style);
  font-weight: var(--heading-5-font-weight);
  letter-spacing: var(--heading-5-letter-spacing);
  line-height: var(--heading-5-line-height);
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.footer .list {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 8px;
  position: relative;
}

.footer .text-wrapper-13 {
  color: var(--white);
  font-family: var(--body-1-font-family);
  font-size: var(--body-1-font-size);
  font-style: var(--body-1-font-style);
  font-weight: var(--body-1-font-weight);
  letter-spacing: var(--body-1-letter-spacing);
  line-height: var(--body-1-line-height);
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.footer .text-wrapper-14 {
  color: var(--white);
  font-family: var(--body-1-font-family);
  font-size: var(--body-1-font-size);
  font-style: var(--body-1-font-style);
  font-weight: var(--body-1-font-weight);
  letter-spacing: var(--body-1-letter-spacing);
  line-height: var(--body-1-line-height);
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.footer .recent-project {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  gap: 20px;
  left: 721px;
  position: absolute;
  top: 100px;
}

.footer .image-3 {
  background-color: var(--grey-1);
  border-radius: 4px;
  height: 124px;
  overflow: hidden;
  position: relative;
  width: 213px;
}

.footer .man-with-helmet-wrapper {
  background-color: var(--dark-blue-1);
  height: 212px;
  left: -82px;
  position: relative;
  top: -36px;
  width: 378px;
}

.footer .man-with-helmet {
  height: 124px;
  left: 82px;
  object-fit: cover;
  position: absolute;
  top: 36px;
  width: 213px;
}

.footer .subscribe {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  gap: 20px;
  left: 994px;
  position: absolute;
  top: 100px;
}

.footer .form-subscribe {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 14px;
  position: relative;
}

.footer .input {
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
  width: 296px;
}

.footer .button-3 {
  background-color: #1195d6 !important;
  display: flex !important;
  flex: 0 0 auto !important;
  justify-content: center !important;
  width: 296px !important;
}

.footer .line-6 {
  height: 1px;
  left: 150px;
  object-fit: cover;
  position: absolute;
  top: 355px;
  width: 1140px;
}

.footer .copyright {
  color: var(--white);
  font-family: "Space Grotesk", Helvetica;
  font-size: 14px;
  font-weight: 400;
  left: 588px;
  letter-spacing: 1.33px;
  line-height: 14px;
  position: absolute;
  top: 402px;
  white-space: nowrap;
}
</style>