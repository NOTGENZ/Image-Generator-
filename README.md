![Untitled design](https://github.com/user-attachments/assets/11a001b2-f31e-403a-9706-d0617d2c9cb5)
<h3>NOTE</h3>
.btn-16,
.btn-16 *,
.btn-16 :after,
.btn-16 :before,
.btn-16:after,
.btn-16:before {
  border: 0 solid;
  box-sizing: border-box;
}
.btn-16 {
  -webkit-tap-highlight-color: transparent;
  -webkit-appearance: button;
  background-color: #000;
  background-image: none;
  color: #fff;
  cursor: pointer;
  font-family: ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont,
    Segoe UI, Roboto, Helvetica Neue, Arial, Noto Sans, sans-serif,
    Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji;
  font-size: 100%;
  font-weight: 900;
  line-height: 1.5;
  margin: 0;
  -webkit-mask-image: -webkit-radial-gradient(#000, #fff);
  padding: 0;
  text-transform: uppercase;
}
.btn-16:disabled {
  cursor: default;
}
.btn-16:-moz-focusring {
  outline: auto;
}
.btn-16 svg {
  display: block;
  vertical-align: middle;
}
.btn-16 [hidden] {
  display: none;
}
.btn-16 {
  border-radius: 99rem;
  border-width: 2px;
  overflow: hidden;
  padding: 0.8rem 3rem;
  position: relative;
  z-index: 0;
}
.btn-16 span {
  mix-blend-mode: difference;
}
.btn-16:after,
.btn-16:before {
  --tilt: 40px;
  background: #fff;
  -webkit-clip-path: polygon(
    0 0,
    100% 0,
    calc(100% - var(--tilt)) 50%,
    100% 100%,
    0 100%
  );
  clip-path: polygon(
    0 0,
    100% 0,
    calc(100% - var(--tilt)) 50%,
    100% 100%,
    0 100%
  );
  content: "";
  display: block;
  height: 100%;
  left: -100%;
  position: absolute;
  top: 0;
  transition: transform 0.2s ease;
  width: 100%;
}
.btn-16:after {
  -webkit-clip-path: polygon(0 0, var(--tilt) 50%, 0 100%, 100% 100%, 100% 0);
  clip-path: polygon(0 0, var(--tilt) 50%, 0 100%, 100% 100%, 100% 0);
  left: 100%;
  z-index: -1;
}
.btn-16:hover:before {
  transform: translateX(calc(50% + var(--tilt)));
}
.btn-16:hover:after {
  transform: translateX(calc(-50% - var(--tilt)));
}

<a href="https://pixabay.com/">Original website of images </a> 
 FOR INAGES WE ARE NO LICENCE : https://pixabay.com/api/?key=${apiKey}&q=${encodeURIComponent(prompt)}&image_type=photo
