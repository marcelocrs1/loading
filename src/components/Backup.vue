<template>
  <main class="main-wrapper">
    <div class="svg-box">
      <div class="animate-svg">
        <svg x="0px" y="0px" viewBox="0 0 664 566">
          <path
            fill="none"
            d="M428.621 478.617L271.589 60.2939C258.929 26.5687 211.224 26.5687 198.564 60.2938L41.5322 478.617C31.9605 504.116 50.8088 531.323 78.0444 531.323H392.109C419.344 531.323 438.193 504.116 428.621 478.617ZM280.951 56.7795C265.045 14.4069 205.108 14.4068 189.202 56.7794L32.1701 475.103C20.1441 507.139 43.8253 541.323 78.0444 541.323H392.109C426.328 541.323 450.009 507.139 437.983 475.103L280.951 56.7795Z"
          />
          <path
            fill="none"
            d="M622.621 478.617L465.589 60.2939C452.929 26.5687 405.224 26.5687 392.564 60.2938L235.532 478.617C225.961 504.116 244.809 531.323 272.044 531.323H586.109C613.344 531.323 632.193 504.116 622.621 478.617ZM474.951 56.7795C459.045 14.4069 399.108 14.4068 383.202 56.7794L226.17 475.103C214.144 507.139 237.825 541.323 272.044 541.323H586.109C620.328 541.323 644.009 507.139 631.983 475.103L474.951 56.7795Z"
          />
        </svg>
      </div>
      <div class="animate-svg2">
        <svg x="0px" y="0px" viewBox="0 0 664 566">
          <path
            fill="none"
            d="M351.767 234.767L514.139 91.1587C514.124 91.1422 514.109 91.1257 514.095 91.1091C512.16 88.9228 510.183 86.7784 508.167 84.6769C485.186 60.7304 456.984 42.3507 425.712 31.0022C391.674 18.6503 355.085 15.0217 319.285 20.4476C283.484 25.8735 249.613 40.1811 220.765 62.064C191.916 83.9469 169.009 112.708 154.134 145.721C139.26 178.734 132.892 214.947 135.613 251.054C138.333 287.161 150.056 322.011 169.709 352.422C189.363 382.834 216.321 407.837 248.123 425.15C277.342 441.057 309.793 450.006 342.955 451.355C345.887 451.474 348.825 451.534 351.767 451.534L351.767 234.767ZM342.955 442.535L342.955 230.797L501.56 90.5197C479.56 67.6728 452.594 50.1316 422.706 39.2854C390.052 27.4356 354.95 23.9544 320.605 29.1597C286.26 34.3651 253.766 48.0911 226.09 69.0844C198.414 90.0778 176.438 117.67 162.168 149.341C147.898 181.012 141.79 215.753 144.4 250.392C147.01 285.031 158.255 318.465 177.11 347.64C195.964 376.815 221.827 400.802 252.336 417.411C280.262 432.614 311.266 441.191 342.955 442.535Z"
          />
          <path
            fill="none"
            d="M311.233 330.814L148.861 474.422C148.876 474.439 148.891 474.455 148.905 474.472C150.84 476.658 152.817 478.802 154.833 480.904C177.814 504.85 206.016 523.23 237.288 534.579C271.326 546.93 307.915 550.559 343.715 545.133C379.516 539.707 413.387 525.4 442.235 503.517C471.084 481.634 493.991 452.873 508.866 419.86C523.74 386.847 530.108 350.634 527.387 314.527C524.667 278.42 512.944 243.57 493.291 213.158C473.637 182.747 446.679 157.743 414.877 140.43C385.658 124.524 353.207 115.575 320.045 114.226C317.113 114.107 314.175 114.047 311.233 114.047L311.233 330.814ZM320.045 123.045L320.045 334.784L161.44 475.061C183.44 497.908 210.406 515.449 240.294 526.295C272.948 538.145 308.05 541.626 342.395 536.421C376.74 531.216 409.234 517.49 436.91 496.496C464.586 475.503 486.562 447.911 500.832 416.24C515.102 384.569 521.21 349.828 518.6 315.189C515.99 280.55 504.745 247.116 485.89 217.941C467.036 188.766 441.173 164.779 410.664 148.17C382.738 132.967 351.734 124.389 320.045 123.045Z"
          />
        </svg>
      </div>
    </div>

    <!-- <div class="load">
      <div class="loader">
        <div class="bar"></div>
      </div>
      <div class="loader">
        <div class="bar2"></div>
      </div>
    </div> -->

    <div class="loader23">
      <span></span>
      <span></span>
      <span></span>
      <span></span>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style scoped>
.main-wrapper {
  width: 100%;
  height: 100%;
  display: flex;
  flex-flow: column;
  align-items: center;
  justify-content: center;
  gap: 50px;
}
.svg-box {
  display: flex;
}
.animate-svg {
  display: flex;
  width: 130px;
  height: max-content;
  /* margin: 200px auto; */
}
.animate-svg2 {
  display: flex;
  width: 130px;
  height: max-content;
  /* margin: 200px auto; */
}
.animate-svg svg {
  stroke-width: 8px;
  stroke: #0e63d2;
  width: 100%;
  height: 100%;
  stroke-dashoffset: 1000;
  stroke-dasharray: 1000;
  animation: svganimation 3s forwards infinite;
}
.animate-svg2 svg {
  stroke-width: 8px;
  stroke: #ddd;
  width: 100%;
  height: 100%;
  stroke-dashoffset: 1000;
  stroke-dasharray: 1000;
  animation: svganimation 3s forwards infinite;
}

.animate-svg svg path:nth-of-type(2) {
  animation: svganimation 3s forwards infinite !important;
  animation-delay: 320ms !important;
}
.animate-svg2 svg path:nth-of-type(2) {
  animation: svganimation 3s forwards infinite !important;
  animation-delay: 320ms !important;
}

@keyframes svganimation {
  0% {
    stroke-dashoffset: 1000;
    /* stroke-dasharray: 1000; */
  }

  50% {
    stroke-dashoffset: 0;
  }

  100% {
    stroke-dashoffset: 1000;
  }
}

/* ------- loading bar -------- */
.load {
  display: flex;
  flex-flow: column;
  gap: 2px;
}
.loader {
  --uib-size: 600px;
  --uib-speed: 3s;
  --uib-color: linear-gradient(to right, #ddd, #0e63d2);
  /* --uib-color: #0e63d2; */
  --uib-line-weight: 2px;
  background-image: linear-gradient(to left, #dddddd67, #0e63d267);
  background-clip: content-box;
  position: relative;
  overflow: hidden;
  height: var(--uib-line-weight);
  width: var(--uib-size);
  border-radius: calc(var(--uib-line-weight) / 2);
  overflow: hidden;
}

.bar {
  width: 300px;
  height: 20px;
  background-color: transparent;
  position: absolute;
  left: -50px;
  top: 0;
  animation: move 3s infinite ease-out;
  box-shadow: 0 0 0 1000px #181818e7;
  mix-blend-mode: normal;
}

@keyframes move {
  0% {
    transform: translateX(220%);
  }
  50% {
    transform: translateX(-90%);
  }
  100% {
    transform: translateX(220%);
  }
}
.bar2 {
  width: 300px;
  height: 20px;
  background-color: transparent;
  position: absolute;
  left: -50px;
  top: 0;
  animation: move2 3s infinite ease-out;
  box-shadow: 0 0 0 1000px #181818e7;
  mix-blend-mode: normal;
}

@keyframes move2 {
  0% {
    transform: translateX(-90%);
  }
  50% {
    transform: translateX(220%);
  }
  100% {
    transform: translateX(-90%);
  }
}

/* --------------------------------- */

/* From cssbuttons.io by @satyamchaudharydev */
.loader23 {
  --loader: #0a6ff2;
  --loader-size: 6px;
  position: absolute;
  width: 300px;
  height: 300px;
  overflow: hidden;
  transition: 0.5s;
  letter-spacing: 2px;
  border-radius: 8px;
  background-color: #303030;
  z-index: -1;
  box-shadow: rgba(50, 50, 93, 0.25) 0px 6px 12px -2px,
    rgba(0, 0, 0, 0.3) 0px 3px 7px -3px;
}

.loader23 span {
  position: absolute;
}

.loader23 span:nth-child(1) {
  top: 0;
  left: -100%;
  width: 100%;
  height: var(--loader-size);
  background: linear-gradient(90deg, transparent, #0a6ff2);
  animation: loader-anim1 1s linear infinite;
}

@keyframes loader-anim1 {
  0% {
    left: -100%;
  }

  50%,
  100% {
    left: 100%;
  }
}

.loader23 span:nth-child(2) {
  top: -100%;
  right: 0;
  width: var(--loader-size);
  height: 100%;
  background: linear-gradient(180deg, transparent, var(--loader));
  animation: loader-anim2 1s linear infinite;
  animation-delay: 0.25s;
}

@keyframes loader-anim2 {
  0% {
    top: -100%;
  }

  50%,
  100% {
    top: 100%;
  }
}

.loader23 span:nth-child(3) {
  bottom: 0;
  right: -100%;
  width: 100%;
  height: var(--loader-size);
  background: linear-gradient(270deg, transparent, var(--loader));
  animation: loader-anim3 1s linear infinite;
  animation-delay: 0.5s;
}

@keyframes loader-anim3 {
  0% {
    right: -100%;
  }

  50%,
  100% {
    right: 100%;
  }
}

.loader23 span:nth-child(4) {
  bottom: -100%;
  left: 0;
  width: var(--loader-size);
  height: 100%;
  background: linear-gradient(360deg, transparent, #0a6ff2);
  animation: loader-anim4 1s linear infinite;
  animation-delay: 0.75s;
}

@keyframes loader-anim4 {
  0% {
    bottom: -100%;
  }

  50%,
  100% {
    bottom: 100%;
  }
}
</style>
