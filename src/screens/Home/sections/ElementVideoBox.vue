<template>
  <div class="element-video-box">
    <div class="overlap-3">
      <div class="div-wrapper">
        <div class="overlap-group-4">
          <img
            class="maksym-kaharlytskyi"
            alt="Maksym kaharlytskyi"
            src="@/img/maksym-kaharlytskyi-kdvafjoqf4m-unsplash-2.png"
          />
          <div class="rectangle" />
        </div>
      </div>
      <div class="play-wrapper">
        <img class="play" alt="Play" src="@/img/play.svg" />
      </div>
      <div class="title-10">
        <div class="heading-8">SEE IT IN ACTION</div>
        <p class="text-7">Watch Our Video to Get a Clear Understanding of How It Works</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ElementVideoBox",
};
</script>

<style>
.element-video-box {
  background-color: var(--white);
  height: 741px;
  overflow: hidden;
  position: relative;
  width: 1440px;
}

.element-video-box .overlap-3 {
  height: 859px;
  left: -44px;
  position: relative;
  top: -108px;
  width: 1528px;
}

.element-video-box .div-wrapper {
  height: 859px;
  left: 0;
  overflow: hidden;
  position: absolute;
  top: 0;
  width: 1528px;
}

.element-video-box .overlap-group-4 {
  background-color: var(--blue-2);
  height: 1110px;
  left: -90px;
  position: relative;
  top: 42px;
  width: 1665px;
}

.element-video-box .maksym-kaharlytskyi {
  height: 741px;
  left: 134px;
  object-fit: cover;
  position: absolute;
  top: 66px;
  width: 1440px;
}

.element-video-box .rectangle {
  background-color: #09123b8f;
  height: 774px;
  left: 99px;
  position: absolute;
  top: 50px;
  width: 1510px;
}

.element-video-box .play-wrapper {
  background-color: var(--white);
  border-radius: 66px;
  height: 132px;
  left: 698px;
  position: absolute;
  top: 413px;
  width: 132px;
}

.element-video-box .play {
  height: 60px;
  left: 41px;
  position: absolute;
  top: 36px;
  width: 60px;
}

.element-video-box .title-10 {
  align-items: center;
  display: inline-flex;
  flex-direction: column;
  gap: 16px;
  left: 474px;
  position: absolute;
  top: 218px;
}

.element-video-box .heading-8 {
  color: var(--white);
  font-family: var(--heading-1-font-family);
  font-size: var(--heading-1-font-size);
  font-style: var(--heading-1-font-style);
  font-weight: var(--heading-1-font-weight);
  letter-spacing: var(--heading-1-letter-spacing);
  line-height: var(--heading-1-line-height);
  margin-top: -1px;
  position: relative;
  text-align: center;
  width: 580px;
}

.element-video-box .text-7 {
  color: var(--white);
  font-family: var(--body-1-font-family);
  font-size: var(--body-1-font-size);
  font-style: var(--body-1-font-style);
  font-weight: var(--body-1-font-weight);
  letter-spacing: var(--body-1-letter-spacing);
  line-height: var(--body-1-line-height);
  position: relative;
  text-align: center;
  width: 510px;
}

</style>
