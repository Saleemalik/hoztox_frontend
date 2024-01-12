<template>
  <div class="element-testimonials">
    <div class="testimonial-card">
      <div class="testimonial">
        <div class="star">
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
        </div>
        <p class="text-wrapper-10">
          I was very impressed with FastGo handling of my recent shipment. They went above and beyond to ensure my
          cargo arrived safely and on time. I will definitely be using their services again in the future.
        </p>
        <div class="text-wrapper-11">JANE SMITH, FREELANCE CONSULTANT</div>
      </div>
      <div class="testimonial">
        <div class="star">
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
        </div>
        <p class="text-wrapper-10">
          I was very impressed with FastGo handling of my recent shipment. They went above and beyond to ensure my
          cargo arrived safely and on time. I will definitely be using their services again in the future.
        </p>
        <div class="text-wrapper-11">MICHAEL JOHNSON, CEO</div>
      </div>
      <div class="testimonial">
        <div class="star">
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
        </div>
        <p class="text-wrapper-10">
          I was very impressed with FastGo handling of my recent shipment. They went above and beyond to ensure my
          cargo arrived safely and on time. I will definitely be using their services again in the future.
        </p>
        <div class="text-wrapper-11">SARAH LEE, ONLINE RETAILER</div>
      </div>
    </div>
    <div class="testimonial-hero">
      <div class="testimonial-box">
        <div class="star">
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
          <img class="star-2" alt="Star" src="/img/star-5.svg" />
        </div>
        <p class="i-have-been-using">
          I have been using FastGo cargo logistic &amp; transportation services for over a year now and I am extremely
          satisfied with their service. They are efficient, reliable, and always deliver on time. I highly recommend
          them to anyone in need of logistics services.
        </p>
        <div class="john-doe-business">JOHN DOE, BUSINESS OWNER</div>
      </div>
      <div class="overlap-4">
        <div class="image-2">
          <div class="young-handsome-wrapper">
            <img
              class="young-handsome"
              alt="Young handsome"
              src="/img/young-handsome-business-man-choosing-car-car-showroom-1.png"
            />
          </div>
        </div>
        <img class="icon-4" alt="Icon" src="/img/icon-3.svg" />
      </div>
    </div>
    <div class="title-11">
      <div class="sub-heading-5">TESTIMONIALS</div>
      <p class="heading-9">OUR CLIENTS SPEAK FOR US</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "ElementTestimonials",
};
</script>

<style>
.element-testimonials {
  background-color: var(--grey-1);
  height: 1064px;
  position: relative;
  width: 1440px;
}

.element-testimonials .testimonial-card {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  gap: 24px;
  left: 770px;
  position: absolute;
  top: 126px;
}

.element-testimonials .testimonial {
  background-color: var(--white);
  border-radius: 12px;
  height: 260px;
  overflow: hidden;
  position: relative;
  width: 520px;
}

.element-testimonials .star {
  align-items: flex-start;
  display: inline-flex;
  left: 38px;
  position: absolute;
  top: 34px;
}

.element-testimonials .star-2 {
  height: 30.52px;
  position: relative;
  width: 31.99px;
}

.element-testimonials .text-wrapper-10 {
  color: var(--dark-blue-1);
  font-family: var(--body-2-font-family);
  font-size: var(--body-2-font-size);
  font-style: var(--body-2-font-style);
  font-weight: var(--body-2-font-weight);
  left: 38px;
  letter-spacing: var(--body-2-letter-spacing);
  line-height: var(--body-2-line-height);
  position: absolute;
  top: 95px;
  width: 444px;
}

.element-testimonials .text-wrapper-11 {
  color: var(--dark-blue-1);
  font-family: var(--SUB-HEADING-1-font-family);
  font-size: var(--SUB-HEADING-1-font-size);
  font-style: var(--SUB-HEADING-1-font-style);
  font-weight: var(--SUB-HEADING-1-font-weight);
  left: 38px;
  letter-spacing: var(--SUB-HEADING-1-letter-spacing);
  line-height: var(--SUB-HEADING-1-line-height);
  position: absolute;
  top: 207px;
  white-space: nowrap;
}

.element-testimonials .testimonial-hero {
  height: 690px;
  left: 150px;
  position: absolute;
  top: 264px;
  width: 560px;
}

.element-testimonials .testimonial-box {
  background-color: var(--dark-blue-2);
  border-radius: 12px;
  height: 282px;
  left: 0;
  overflow: hidden;
  position: absolute;
  top: 408px;
  width: 506px;
}

.element-testimonials .i-have-been-using {
  color: var(--white);
  font-family: var(--body-2-font-family);
  font-size: var(--body-2-font-size);
  font-style: var(--body-2-font-style);
  font-weight: var(--body-2-font-weight);
  left: 38px;
  letter-spacing: var(--body-2-letter-spacing);
  line-height: var(--body-2-line-height);
  position: absolute;
  top: 95px;
  width: 422px;
}

.element-testimonials .john-doe-business {
  color: var(--white);
  font-family: var(--SUB-HEADING-1-font-family);
  font-size: var(--SUB-HEADING-1-font-size);
  font-style: var(--SUB-HEADING-1-font-style);
  font-weight: var(--SUB-HEADING-1-font-weight);
  left: 38px;
  letter-spacing: var(--SUB-HEADING-1-letter-spacing);
  line-height: var(--SUB-HEADING-1-line-height);
  position: absolute;
  top: 229px;
  white-space: nowrap;
}

.element-testimonials .overlap-4 {
  height: 384px;
  left: 0;
  position: absolute;
  top: 0;
  width: 560px;
}

.element-testimonials .image-2 {
  border-radius: 12px;
  height: 336px;
  left: 0;
  overflow: hidden;
  position: absolute;
  top: 48px;
  width: 506px;
}

.element-testimonials .young-handsome-wrapper {
  background-color: var(--dark-blue-1);
  height: 488px;
  left: -87px;
  position: relative;
  top: -6px;
  width: 733px;
}

.element-testimonials .young-handsome {
  height: 336px;
  left: 87px;
  object-fit: cover;
  position: absolute;
  top: 6px;
  width: 506px;
}

.element-testimonials .icon-4 {
  height: 132px;
  left: 428px;
  position: absolute;
  top: 0;
  width: 132px;
}

.element-testimonials .title-11 {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  gap: 16px;
  left: 150px;
  position: absolute;
  top: 110px;
}

.element-testimonials .sub-heading-5 {
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

.element-testimonials .heading-9 {
  color: var(--dark-blue-1);
  font-family: var(--heading-2-font-family);
  font-size: var(--heading-2-font-size);
  font-style: var(--heading-2-font-style);
  font-weight: var(--heading-2-font-weight);
  letter-spacing: var(--heading-2-letter-spacing);
  line-height: var(--heading-2-line-height);
  position: relative;
  width: 506px;
}

</style>
