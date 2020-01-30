@charset "UTF-8";

/*!
Animate.css - http://daneden.me/animate
Licensed under the MIT license

Copyright (c) 2013 Daniel Eden

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
*/

.animated {
    -webkit-animation-duration: 1s;
    animation-duration: 1s;
    -webkit-animation-fill-mode: both;
    animation-fill-mode: both;
    z-index: 100;
}

.animated.infinite {
    -webkit-animation-iteration-count: infinite;
    animation-iteration-count: infinite;
}

.animated.hinge {
    -webkit-animation-duration: 2s;
    animation-duration: 2s;
}

@-webkit-keyframes bounce {
    0%, 20%, 50%, 80%, 100% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }

    40% {
        -webkit-transform: translateY(-30px);
        transform: translateY(-30px);
    }

    60% {
        -webkit-transform: translateY(-15px);
        transform: translateY(-15px);
    }
}

@keyframes bounce {
    0%, 20%, 50%, 80%, 100% {
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }

    40% {
        -webkit-transform: translateY(-30px);
        -ms-transform: translateY(-30px);
        transform: translateY(-30px);
    }

    60% {
        -webkit-transform: translateY(-15px);
        -ms-transform: translateY(-15px);
        transform: translateY(-15px);
    }
}

.bounce {
    -webkit-animation-name: bounce;
    animation-name: bounce;
}

@-webkit-keyframes flash {
    0%, 50%, 100% {
        opacity: 1;
    }

    25%, 75% {
        opacity: 0;
    }
}

@keyframes flash {
    0%, 50%, 100% {
        opacity: 1;
    }

    25%, 75% {
        opacity: 0;
    }
}

.flash {
    -webkit-animation-name: flash;
    animation-name: flash;
}

/* originally authored by Nick Pettit - https://github.com/nickpettit/glide */

@-webkit-keyframes pulse {
    0% {
        -webkit-transform: scale(1);
        transform: scale(1);
    }

    50% {
        -webkit-transform: scale(1.1);
        transform: scale(1.1);
    }

    100% {
        -webkit-transform: scale(1);
        transform: scale(1);
    }
}

@keyframes pulse {
    0% {
        -webkit-transform: scale(1);
        -ms-transform: scale(1);
        transform: scale(1);
    }

    50% {
        -webkit-transform: scale(1.1);
        -ms-transform: scale(1.1);
        transform: scale(1.1);
    }

    100% {
        -webkit-transform: scale(1);
        -ms-transform: scale(1);
        transform: scale(1);
    }
}

.pulse {
    -webkit-animation-name: pulse;
    animation-name: pulse;
}

@-webkit-keyframes rubberBand {
    0% {
        -webkit-transform: scale(1);
        transform: scale(1);
    }

    30% {
        -webkit-transform: scaleX(1.25) scaleY(0.75);
        transform: scaleX(1.25) scaleY(0.75);
    }

    40% {
        -webkit-transform: scaleX(0.75) scaleY(1.25);
        transform: scaleX(0.75) scaleY(1.25);
    }

    60% {
        -webkit-transform: scaleX(1.15) scaleY(0.85);
        transform: scaleX(1.15) scaleY(0.85);
    }

    100% {
        -webkit-transform: scale(1);
        transform: scale(1);
    }
}

@keyframes rubberBand {
    0% {
        -webkit-transform: scale(1);
        -ms-transform: scale(1);
        transform: scale(1);
    }

    30% {
        -webkit-transform: scaleX(1.25) scaleY(0.75);
        -ms-transform: scaleX(1.25) scaleY(0.75);
        transform: scaleX(1.25) scaleY(0.75);
    }

    40% {
        -webkit-transform: scaleX(0.75) scaleY(1.25);
        -ms-transform: scaleX(0.75) scaleY(1.25);
        transform: scaleX(0.75) scaleY(1.25);
    }

    60% {
        -webkit-transform: scaleX(1.15) scaleY(0.85);
        -ms-transform: scaleX(1.15) scaleY(0.85);
        transform: scaleX(1.15) scaleY(0.85);
    }

    100% {
        -webkit-transform: scale(1);
        -ms-transform: scale(1);
        transform: scale(1);
    }
}

.rubberBand {
    -webkit-animation-name: rubberBand;
    animation-name: rubberBand;
}

@-webkit-keyframes shake {
    0%, 100% {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }

    10%, 30%, 50%, 70%, 90% {
        -webkit-transform: translateX(-10px);
        transform: translateX(-10px);
    }

    20%, 40%, 60%, 80% {
        -webkit-transform: translateX(10px);
        transform: translateX(10px);
    }
}

@keyframes shake {
    0%, 100% {
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }

    10%, 30%, 50%, 70%, 90% {
        -webkit-transform: translateX(-10px);
        -ms-transform: translateX(-10px);
        transform: translateX(-10px);
    }

    20%, 40%, 60%, 80% {
        -webkit-transform: translateX(10px);
        -ms-transform: translateX(10px);
        transform: translateX(10px);
    }
}

.shake {
    -webkit-animation-name: shake;
    animation-name: shake;
}

@-webkit-keyframes swing {
    20% {
        -webkit-transform: rotate(15deg);
        transform: rotate(15deg);
    }

    40% {
        -webkit-transform: rotate(-10deg);
        transform: rotate(-10deg);
    }

    60% {
        -webkit-transform: rotate(5deg);
        transform: rotate(5deg);
    }

    80% {
        -webkit-transform: rotate(-5deg);
        transform: rotate(-5deg);
    }

    100% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg);
    }
}

@keyframes swing {
    20% {
        -webkit-transform: rotate(15deg);
        -ms-transform: rotate(15deg);
        transform: rotate(15deg);
    }

    40% {
        -webkit-transform: rotate(-10deg);
        -ms-transform: rotate(-10deg);
        transform: rotate(-10deg);
    }

    60% {
        -webkit-transform: rotate(5deg);
        -ms-transform: rotate(5deg);
        transform: rotate(5deg);
    }

    80% {
        -webkit-transform: rotate(-5deg);
        -ms-transform: rotate(-5deg);
        transform: rotate(-5deg);
    }

    100% {
        -webkit-transform: rotate(0deg);
        -ms-transform: rotate(0deg);
        transform: rotate(0deg);
    }
}

.swing {
    -webkit-transform-origin: top center;
    -ms-transform-origin: top center;
    transform-origin: top center;
    -webkit-animation-name: swing;
    animation-name: swing;
}

@-webkit-keyframes tada {
    0% {
        -webkit-transform: scale(1);
        transform: scale(1);
    }

    10%, 20% {
        -webkit-transform: scale(0.9) rotate(-3deg);
        transform: scale(0.9) rotate(-3deg);
    }

    30%, 50%, 70%, 90% {
        -webkit-transform: scale(1.1) rotate(3deg);
        transform: scale(1.1) rotate(3deg);
    }

    40%, 60%, 80% {
        -webkit-transform: scale(1.1) rotate(-3deg);
        transform: scale(1.1) rotate(-3deg);
    }

    100% {
        -webkit-transform: scale(1) rotate(0);
        transform: scale(1) rotate(0);
    }
}

@keyframes tada {
    0% {
        -webkit-transform: scale(1);
        -ms-transform: scale(1);
        transform: scale(1);
    }

    10%, 20% {
        -webkit-transform: scale(0.9) rotate(-3deg);
        -ms-transform: scale(0.9) rotate(-3deg);
        transform: scale(0.9) rotate(-3deg);
    }

    30%, 50%, 70%, 90% {
        -webkit-transform: scale(1.1) rotate(3deg);
        -ms-transform: scale(1.1) rotate(3deg);
        transform: scale(1.1) rotate(3deg);
    }

    40%, 60%, 80% {
        -webkit-transform: scale(1.1) rotate(-3deg);
        -ms-transform: scale(1.1) rotate(-3deg);
        transform: scale(1.1) rotate(-3deg);
    }

    100% {
        -webkit-transform: scale(1) rotate(0);
        -ms-transform: scale(1) rotate(0);
        transform: scale(1) rotate(0);
    }
}

.tada {
    -webkit-animation-name: tada;
    animation-name: tada;
}

/* originally authored by Nick Pettit - https://github.com/nickpettit/glide */

@-webkit-keyframes wobble {
    0% {
        -webkit-transform: translateX(0%);
        transform: translateX(0%);
    }

    15% {
        -webkit-transform: translateX(-25%) rotate(-5deg);
        transform: translateX(-25%) rotate(-5deg);
    }

    30% {
        -webkit-transform: translateX(20%) rotate(3deg);
        transform: translateX(20%) rotate(3deg);
    }

    45% {
        -webkit-transform: translateX(-15%) rotate(-3deg);
        transform: translateX(-15%) rotate(-3deg);
    }

    60% {
        -webkit-transform: translateX(10%) rotate(2deg);
        transform: translateX(10%) rotate(2deg);
    }

    75% {
        -webkit-transform: translateX(-5%) rotate(-1deg);
        transform: translateX(-5%) rotate(-1deg);
    }

    100% {
        -webkit-transform: translateX(0%);
        transform: translateX(0%);
    }
}

@keyframes wobble {
    0% {
        -webkit-transform: translateX(0%);
        -ms-transform: translateX(0%);
        transform: translateX(0%);
    }

    15% {
        -webkit-transform: translateX(-25%) rotate(-5deg);
        -ms-transform: translateX(-25%) rotate(-5deg);
        transform: translateX(-25%) rotate(-5deg);
    }

    30% {
        -webkit-transform: translateX(20%) rotate(3deg);
        -ms-transform: translateX(20%) rotate(3deg);
        transform: translateX(20%) rotate(3deg);
    }

    45% {
        -webkit-transform: translateX(-15%) rotate(-3deg);
        -ms-transform: translateX(-15%) rotate(-3deg);
        transform: translateX(-15%) rotate(-3deg);
    }

    60% {
        -webkit-transform: translateX(10%) rotate(2deg);
        -ms-transform: translateX(10%) rotate(2deg);
        transform: translateX(10%) rotate(2deg);
    }

    75% {
        -webkit-transform: translateX(-5%) rotate(-1deg);
        -ms-transform: translateX(-5%) rotate(-1deg);
        transform: translateX(-5%) rotate(-1deg);
    }

    100% {
        -webkit-transform: translateX(0%);
        -ms-transform: translateX(0%);
        transform: translateX(0%);
    }
}

.wobble {
    -webkit-animation-name: wobble;
    animation-name: wobble;
}

@-webkit-keyframes bounceIn {
    0% {
        opacity: 0;
        -webkit-transform: scale(.3);
        transform: scale(.3);
    }

    50% {
        opacity: 1;
        -webkit-transform: scale(1.05);
        transform: scale(1.05);
    }

    70% {
        -webkit-transform: scale(.9);
        transform: scale(.9);
    }

    100% {
        opacity: 1;
        -webkit-transform: scale(1);
        transform: scale(1);
    }
}

@keyframes bounceIn {
    0% {
        opacity: 0;
        -webkit-transform: scale(.3);
        -ms-transform: scale(.3);
        transform: scale(.3);
    }

    50% {
        opacity: 1;
        -webkit-transform: scale(1.05);
        -ms-transform: scale(1.05);
        transform: scale(1.05);
    }

    70% {
        -webkit-transform: scale(.9);
        -ms-transform: scale(.9);
        transform: scale(.9);
    }

    100% {
        opacity: 1;
        -webkit-transform: scale(1);
        -ms-transform: scale(1);
        transform: scale(1);
    }
}

.bounceIn {
    -webkit-animation-name: bounceIn;
    animation-name: bounceIn;
}

@-webkit-keyframes bounceInDown {
    0% {
        opacity: 0;
        -webkit-transform: translateY(-2000px);
        transform: translateY(-2000px);
    }

    60% {
        opacity: 1;
        -webkit-transform: translateY(30px);
        transform: translateY(30px);
    }

    80% {
        -webkit-transform: translateY(-10px);
        transform: translateY(-10px);
    }

    100% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }
}

@keyframes bounceInDown {
    0% {
        opacity: 0;
        -webkit-transform: translateY(-2000px);
        -ms-transform: translateY(-2000px);
        transform: translateY(-2000px);
    }

    60% {
        opacity: 1;
        -webkit-transform: translateY(30px);
        -ms-transform: translateY(30px);
        transform: translateY(30px);
    }

    80% {
        -webkit-transform: translateY(-10px);
        -ms-transform: translateY(-10px);
        transform: translateY(-10px);
    }

    100% {
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }
}

.bounceInDown {
    -webkit-animation-name: bounceInDown;
    animation-name: bounceInDown;
}

@-webkit-keyframes bounceInLeft {
    0% {
        opacity: 0;
        -webkit-transform: translateX(-2000px);
        transform: translateX(-2000px);
    }

    60% {
        opacity: 1;
        -webkit-transform: translateX(30px);
        transform: translateX(30px);
    }

    80% {
        -webkit-transform: translateX(-10px);
        transform: translateX(-10px);
    }

    100% {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}

@keyframes bounceInLeft {
    0% {
        opacity: 0;
        -webkit-transform: translateX(-2000px);
        -ms-transform: translateX(-2000px);
        transform: translateX(-2000px);
    }

    60% {
        opacity: 1;
        -webkit-transform: translateX(30px);
        -ms-transform: translateX(30px);
        transform: translateX(30px);
    }

    80% {
        -webkit-transform: translateX(-10px);
        -ms-transform: translateX(-10px);
        transform: translateX(-10px);
    }

    100% {
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }
}

.bounceInLeft {
    -webkit-animation-name: bounceInLeft;
    animation-name: bounceInLeft;
}

@-webkit-keyframes bounceInRight {
    0% {
        opacity: 0;
        -webkit-transform: translateX(2000px);
        transform: translateX(2000px);
    }

    60% {
        opacity: 1;
        -webkit-transform: translateX(-30px);
        transform: translateX(-30px);
    }

    80% {
        -webkit-transform: translateX(10px);
        transform: translateX(10px);
    }

    100% {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}

@keyframes bounceInRight {
    0% {
        opacity: 0;
        -webkit-transform: translateX(2000px);
        -ms-transform: translateX(2000px);
        transform: translateX(2000px);
    }

    60% {
        opacity: 1;
        -webkit-transform: translateX(-30px);
        -ms-transform: translateX(-30px);
        transform: translateX(-30px);
    }

    80% {
        -webkit-transform: translateX(10px);
        -ms-transform: translateX(10px);
        transform: translateX(10px);
    }

    100% {
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }
}

.bounceInRight {
    -webkit-animation-name: bounceInRight;
    animation-name: bounceInRight;
}

@-webkit-keyframes bounceInUp {
    0% {
        opacity: 0;
        -webkit-transform: translateY(2000px);
        transform: translateY(2000px);
    }

    60% {
        opacity: 1;
        -webkit-transform: translateY(-30px);
        transform: translateY(-30px);
    }

    80% {
        -webkit-transform: translateY(10px);
        transform: translateY(10px);
    }

    100% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }
}

@keyframes bounceInUp {
    0% {
        opacity: 0;
        -webkit-transform: translateY(2000px);
        -ms-transform: translateY(2000px);
        transform: translateY(2000px);
    }

    60% {
        opacity: 1;
        -webkit-transform: translateY(-30px);
        -ms-transform: translateY(-30px);
        transform: translateY(-30px);
    }

    80% {
        -webkit-transform: translateY(10px);
        -ms-transform: translateY(10px);
        transform: translateY(10px);
    }

    100% {
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }
}

.bounceInUp {
    -webkit-animation-name: bounceInUp;
    animation-name: bounceInUp;
}

@-webkit-keyframes bounceOut {
    0% {
        -webkit-transform: scale(1);
        transform: scale(1);
    }

    25% {
        -webkit-transform: scale(.95);
        transform: scale(.95);
    }

    50% {
        opacity: 1;
        -webkit-transform: scale(1.1);
        transform: scale(1.1);
    }

    100% {
        opacity: 0;
        -webkit-transform: scale(.3);
        transform: scale(.3);
    }
}

@keyframes bounceOut {
    0% {
        -webkit-transform: scale(1);
        -ms-transform: scale(1);
        transform: scale(1);
    }

    25% {
        -webkit-transform: scale(.95);
        -ms-transform: scale(.95);
        transform: scale(.95);
    }

    50% {
        opacity: 1;
        -webkit-transform: scale(1.1);
        -ms-transform: scale(1.1);
        transform: scale(1.1);
    }

    100% {
        opacity: 0;
        -webkit-transform: scale(.3);
        -ms-transform: scale(.3);
        transform: scale(.3);
    }
}

.bounceOut {
    -webkit-animation-name: bounceOut;
    animation-name: bounceOut;
}

@-webkit-keyframes bounceOutDown {
    0% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }

    20% {
        opacity: 1;
        -webkit-transform: translateY(-20px);
        transform: translateY(-20px);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(2000px);
        transform: translateY(2000px);
    }
}

@keyframes bounceOutDown {
    0% {
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }

    20% {
        opacity: 1;
        -webkit-transform: translateY(-20px);
        -ms-transform: translateY(-20px);
        transform: translateY(-20px);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(2000px);
        -ms-transform: translateY(2000px);
        transform: translateY(2000px);
    }
}

.bounceOutDown {
    -webkit-animation-name: bounceOutDown;
    animation-name: bounceOutDown;
}

@-webkit-keyframes bounceOutLeft {
    0% {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }

    20% {
        opacity: 1;
        -webkit-transform: translateX(20px);
        transform: translateX(20px);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(-2000px);
        transform: translateX(-2000px);
    }
}

@keyframes bounceOutLeft {
    0% {
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }

    20% {
        opacity: 1;
        -webkit-transform: translateX(20px);
        -ms-transform: translateX(20px);
        transform: translateX(20px);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(-2000px);
        -ms-transform: translateX(-2000px);
        transform: translateX(-2000px);
    }
}

.bounceOutLeft {
    -webkit-animation-name: bounceOutLeft;
    animation-name: bounceOutLeft;
}

@-webkit-keyframes bounceOutRight {
    0% {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }

    20% {
        opacity: 1;
        -webkit-transform: translateX(-20px);
        transform: translateX(-20px);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(2000px);
        transform: translateX(2000px);
    }
}

@keyframes bounceOutRight {
    0% {
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }

    20% {
        opacity: 1;
        -webkit-transform: translateX(-20px);
        -ms-transform: translateX(-20px);
        transform: translateX(-20px);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(2000px);
        -ms-transform: translateX(2000px);
        transform: translateX(2000px);
    }
}

.bounceOutRight {
    -webkit-animation-name: bounceOutRight;
    animation-name: bounceOutRight;
}

@-webkit-keyframes bounceOutUp {
    0% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }

    20% {
        opacity: 1;
        -webkit-transform: translateY(20px);
        transform: translateY(20px);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(-2000px);
        transform: translateY(-2000px);
    }
}

@keyframes bounceOutUp {
    0% {
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }

    20% {
        opacity: 1;
        -webkit-transform: translateY(20px);
        -ms-transform: translateY(20px);
        transform: translateY(20px);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(-2000px);
        -ms-transform: translateY(-2000px);
        transform: translateY(-2000px);
    }
}

.bounceOutUp {
    -webkit-animation-name: bounceOutUp;
    animation-name: bounceOutUp;
}

@-webkit-keyframes fadeIn {
    0% {
        opacity: 0;
    }

    100% {
        opacity: 1;
    }
}

@keyframes fadeIn {
    0% {
        opacity: 0;
    }

    100% {
        opacity: 1;
    }
}

.fadeIn {
    -webkit-animation-name: fadeIn;
    animation-name: fadeIn;
}

@-webkit-keyframes fadeInDown {
    0% {
        opacity: 0;
        -webkit-transform: translateY(-20px);
        transform: translateY(-20px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }
}

@keyframes fadeInDown {
    0% {
        opacity: 0;
        -webkit-transform: translateY(-20px);
        -ms-transform: translateY(-20px);
        transform: translateY(-20px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }
}

.fadeInDown {
    -webkit-animation-name: fadeInDown;
    animation-name: fadeInDown;
}

@-webkit-keyframes fadeInDownBig {
    0% {
        opacity: 0;
        -webkit-transform: translateY(-2000px);
        transform: translateY(-2000px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }
}

@keyframes fadeInDownBig {
    0% {
        opacity: 0;
        -webkit-transform: translateY(-2000px);
        -ms-transform: translateY(-2000px);
        transform: translateY(-2000px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }
}

.fadeInDownBig {
    -webkit-animation-name: fadeInDownBig;
    animation-name: fadeInDownBig;
}

@-webkit-keyframes fadeInLeft {
    0% {
        opacity: 0;
        -webkit-transform: translateX(-20px);
        transform: translateX(-20px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}

@keyframes fadeInLeft {
    0% {
        opacity: 0;
        -webkit-transform: translateX(-20px);
        -ms-transform: translateX(-20px);
        transform: translateX(-20px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }
}

.fadeInLeft {
    -webkit-animation-name: fadeInLeft;
    animation-name: fadeInLeft;
}

@-webkit-keyframes fadeInLeftBig {
    0% {
        opacity: 0;
        -webkit-transform: translateX(-2000px);
        transform: translateX(-2000px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}

@keyframes fadeInLeftBig {
    0% {
        opacity: 0;
        -webkit-transform: translateX(-2000px);
        -ms-transform: translateX(-2000px);
        transform: translateX(-2000px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }
}

.fadeInLeftBig {
    -webkit-animation-name: fadeInLeftBig;
    animation-name: fadeInLeftBig;
}

@-webkit-keyframes fadeInRight {
    0% {
        opacity: 0;
        -webkit-transform: translateX(20px);
        transform: translateX(20px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}

@keyframes fadeInRight {
    0% {
        opacity: 0;
        -webkit-transform: translateX(40px);
        -ms-transform: translateX(40px);
        transform: translateX(40px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }
}

.fadeInRight {
    -webkit-animation-name: fadeInRight;
    animation-name: fadeInRight;
}

@-webkit-keyframes fadeInRightBig {
    0% {
        opacity: 0;
        -webkit-transform: translateX(2000px);
        transform: translateX(2000px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}

@keyframes fadeInRightBig {
    0% {
        opacity: 0;
        -webkit-transform: translateX(2000px);
        -ms-transform: translateX(2000px);
        transform: translateX(2000px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }
}

.fadeInRightBig {
    -webkit-animation-name: fadeInRightBig;
    animation-name: fadeInRightBig;
}

@-webkit-keyframes fadeInUp {
    0% {
        opacity: 0;
        -webkit-transform: translateY(20px);
        transform: translateY(20px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }
}

@keyframes fadeInUp {
    0% {
        opacity: 0;
        -webkit-transform: translateY(20px);
        -ms-transform: translateY(20px);
        transform: translateY(20px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }
}

.fadeInUp {
    -webkit-animation-name: fadeInUp;
    animation-name: fadeInUp;
}

@-webkit-keyframes fadeInUpBig {
    0% {
        opacity: 0;
        -webkit-transform: translateY(2000px);
        transform: translateY(2000px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }
}

@keyframes fadeInUpBig {
    0% {
        opacity: 0;
        -webkit-transform: translateY(2000px);
        -ms-transform: translateY(2000px);
        transform: translateY(2000px);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }
}

.fadeInUpBig {
    -webkit-animation-name: fadeInUpBig;
    animation-name: fadeInUpBig;
}

@-webkit-keyframes fadeOut {
    0% {
        opacity: 1;
    }

    100% {
        opacity: 0;
    }
}

@keyframes fadeOut {
    0% {
        opacity: 1;
    }

    100% {
        opacity: 0;
    }
}

.fadeOut {
    -webkit-animation-name: fadeOut;
    animation-name: fadeOut;
}

@-webkit-keyframes fadeOutDown {
    0% {
        opacity: 1;
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(20px);
        transform: translateY(20px);
    }
}

@keyframes fadeOutDown {
    0% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(20px);
        -ms-transform: translateY(20px);
        transform: translateY(20px);
    }
}

.fadeOutDown {
    -webkit-animation-name: fadeOutDown;
    animation-name: fadeOutDown;
}

@-webkit-keyframes fadeOutDownBig {
    0% {
        opacity: 1;
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(2000px);
        transform: translateY(2000px);
    }
}

@keyframes fadeOutDownBig {
    0% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(2000px);
        -ms-transform: translateY(2000px);
        transform: translateY(2000px);
    }
}

.fadeOutDownBig {
    -webkit-animation-name: fadeOutDownBig;
    animation-name: fadeOutDownBig;
}

@-webkit-keyframes fadeOutLeft {
    0% {
        opacity: 1;
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(-20px);
        transform: translateX(-20px);
    }
}

@keyframes fadeOutLeft {
    0% {
        opacity: 1;
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(-20px);
        -ms-transform: translateX(-20px);
        transform: translateX(-20px);
    }
}

.fadeOutLeft {
    -webkit-animation-name: fadeOutLeft;
    animation-name: fadeOutLeft;
}

@-webkit-keyframes fadeOutLeftBig {
    0% {
        opacity: 1;
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(-2000px);
        transform: translateX(-2000px);
    }
}

@keyframes fadeOutLeftBig {
    0% {
        opacity: 1;
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(-2000px);
        -ms-transform: translateX(-2000px);
        transform: translateX(-2000px);
    }
}

.fadeOutLeftBig {
    -webkit-animation-name: fadeOutLeftBig;
    animation-name: fadeOutLeftBig;
}

@-webkit-keyframes fadeOutRight {
    0% {
        opacity: 1;
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(20px);
        transform: translateX(20px);
    }
}

@keyframes fadeOutRight {
    0% {
        opacity: 1;
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(20px);
        -ms-transform: translateX(20px);
        transform: translateX(20px);
    }
}

.fadeOutRight {
    -webkit-animation-name: fadeOutRight;
    animation-name: fadeOutRight;
}

@-webkit-keyframes fadeOutRightBig {
    0% {
        opacity: 1;
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(2000px);
        transform: translateX(2000px);
    }
}

@keyframes fadeOutRightBig {
    0% {
        opacity: 1;
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(2000px);
        -ms-transform: translateX(2000px);
        transform: translateX(2000px);
    }
}

.fadeOutRightBig {
    -webkit-animation-name: fadeOutRightBig;
    animation-name: fadeOutRightBig;
}

@-webkit-keyframes fadeOutUp {
    0% {
        opacity: 1;
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(-20px);
        transform: translateY(-20px);
    }
}

@keyframes fadeOutUp {
    0% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(-20px);
        -ms-transform: translateY(-20px);
        transform: translateY(-20px);
    }
}

.fadeOutUp {
    -webkit-animation-name: fadeOutUp;
    animation-name: fadeOutUp;
}

@-webkit-keyframes fadeOutUpBig {
    0% {
        opacity: 1;
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(-2000px);
        transform: translateY(-2000px);
    }
}

@keyframes fadeOutUpBig {
    0% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(-2000px);
        -ms-transform: translateY(-2000px);
        transform: translateY(-2000px);
    }
}

.fadeOutUpBig {
    -webkit-animation-name: fadeOutUpBig;
    animation-name: fadeOutUpBig;
}

@-webkit-keyframes flip {
    0% {
        -webkit-transform: perspective(400px) translateZ(0) rotateY(0) scale(1);
        transform: perspective(400px) translateZ(0) rotateY(0) scale(1);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out;
    }

    40% {
        -webkit-transform: perspective(400px) translateZ(150px) rotateY(170deg) scale(1);
        transform: perspective(400px) translateZ(150px) rotateY(170deg) scale(1);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out;
    }

    50% {
        -webkit-transform: perspective(400px) translateZ(150px) rotateY(190deg) scale(1);
        transform: perspective(400px) translateZ(150px) rotateY(190deg) scale(1);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in;
    }

    80% {
        -webkit-transform: perspective(400px) translateZ(0) rotateY(360deg) scale(.95);
        transform: perspective(400px) translateZ(0) rotateY(360deg) scale(.95);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in;
    }

    100% {
        -webkit-transform: perspective(400px) translateZ(0) rotateY(360deg) scale(1);
        transform: perspective(400px) translateZ(0) rotateY(360deg) scale(1);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in;
    }
}

@keyframes flip {
    0% {
        -webkit-transform: perspective(400px) translateZ(0) rotateY(0) scale(1);
        -ms-transform: perspective(400px) translateZ(0) rotateY(0) scale(1);
        transform: perspective(400px) translateZ(0) rotateY(0) scale(1);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out;
    }

    40% {
        -webkit-transform: perspective(400px) translateZ(150px) rotateY(170deg) scale(1);
        -ms-transform: perspective(400px) translateZ(150px) rotateY(170deg) scale(1);
        transform: perspective(400px) translateZ(150px) rotateY(170deg) scale(1);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out;
    }

    50% {
        -webkit-transform: perspective(400px) translateZ(150px) rotateY(190deg) scale(1);
        -ms-transform: perspective(400px) translateZ(150px) rotateY(190deg) scale(1);
        transform: perspective(400px) translateZ(150px) rotateY(190deg) scale(1);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in;
    }

    80% {
        -webkit-transform: perspective(400px) translateZ(0) rotateY(360deg) scale(.95);
        -ms-transform: perspective(400px) translateZ(0) rotateY(360deg) scale(.95);
        transform: perspective(400px) translateZ(0) rotateY(360deg) scale(.95);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in;
    }

    100% {
        -webkit-transform: perspective(400px) translateZ(0) rotateY(360deg) scale(1);
        -ms-transform: perspective(400px) translateZ(0) rotateY(360deg) scale(1);
        transform: perspective(400px) translateZ(0) rotateY(360deg) scale(1);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in;
    }
}

.animated.flip {
    -webkit-backface-visibility: visible;
    -ms-backface-visibility: visible;
    backface-visibility: visible;
    -webkit-animation-name: flip;
    animation-name: flip;
}

@-webkit-keyframes flipInX {
    0% {
        -webkit-transform: perspective(400px) rotateX(90deg);
        transform: perspective(400px) rotateX(90deg);
        opacity: 0;
    }

    40% {
        -webkit-transform: perspective(400px) rotateX(-10deg);
        transform: perspective(400px) rotateX(-10deg);
    }

    70% {
        -webkit-transform: perspective(400px) rotateX(10deg);
        transform: perspective(400px) rotateX(10deg);
    }

    100% {
        -webkit-transform: perspective(400px) rotateX(0deg);
        transform: perspective(400px) rotateX(0deg);
        opacity: 1;
    }
}

@keyframes flipInX {
    0% {
        -webkit-transform: perspective(400px) rotateX(90deg);
        -ms-transform: perspective(400px) rotateX(90deg);
        transform: perspective(400px) rotateX(90deg);
        opacity: 0;
    }

    40% {
        -webkit-transform: perspective(400px) rotateX(-10deg);
        -ms-transform: perspective(400px) rotateX(-10deg);
        transform: perspective(400px) rotateX(-10deg);
    }

    70% {
        -webkit-transform: perspective(400px) rotateX(10deg);
        -ms-transform: perspective(400px) rotateX(10deg);
        transform: perspective(400px) rotateX(10deg);
    }

    100% {
        -webkit-transform: perspective(400px) rotateX(0deg);
        -ms-transform: perspective(400px) rotateX(0deg);
        transform: perspective(400px) rotateX(0deg);
        opacity: 1;
    }
}

.flipInX {
    -webkit-backface-visibility: visible !important;
    -ms-backface-visibility: visible !important;
    backface-visibility: visible !important;
    -webkit-animation-name: flipInX;
    animation-name: flipInX;
}

@-webkit-keyframes flipInY {
    0% {
        -webkit-transform: perspective(400px) rotateY(90deg);
        transform: perspective(400px) rotateY(90deg);
        opacity: 0;
    }

    40% {
        -webkit-transform: perspective(400px) rotateY(-10deg);
        transform: perspective(400px) rotateY(-10deg);
    }

    70% {
        -webkit-transform: perspective(400px) rotateY(10deg);
        transform: perspective(400px) rotateY(10deg);
    }

    100% {
        -webkit-transform: perspective(400px) rotateY(0deg);
        transform: perspective(400px) rotateY(0deg);
        opacity: 1;
    }
}

@keyframes flipInY {
    0% {
        -webkit-transform: perspective(400px) rotateY(90deg);
        -ms-transform: perspective(400px) rotateY(90deg);
        transform: perspective(400px) rotateY(90deg);
        opacity: 0;
    }

    40% {
        -webkit-transform: perspective(400px) rotateY(-10deg);
        -ms-transform: perspective(400px) rotateY(-10deg);
        transform: perspective(400px) rotateY(-10deg);
    }

    70% {
        -webkit-transform: perspective(400px) rotateY(10deg);
        -ms-transform: perspective(400px) rotateY(10deg);
        transform: perspective(400px) rotateY(10deg);
    }

    100% {
        -webkit-transform: perspective(400px) rotateY(0deg);
        -ms-transform: perspective(400px) rotateY(0deg);
        transform: perspective(400px) rotateY(0deg);
        opacity: 1;
    }
}

.flipInY {
    -webkit-backface-visibility: visible !important;
    -ms-backface-visibility: visible !important;
    backface-visibility: visible !important;
    -webkit-animation-name: flipInY;
    animation-name: flipInY;
}

@-webkit-keyframes flipOutX {
    0% {
        -webkit-transform: perspective(400px) rotateX(0deg);
        transform: perspective(400px) rotateX(0deg);
        opacity: 1;
    }

    100% {
        -webkit-transform: perspective(400px) rotateX(90deg);
        transform: perspective(400px) rotateX(90deg);
        opacity: 0;
    }
}

@keyframes flipOutX {
    0% {
        -webkit-transform: perspective(400px) rotateX(0deg);
        -ms-transform: perspective(400px) rotateX(0deg);
        transform: perspective(400px) rotateX(0deg);
        opacity: 1;
    }

    100% {
        -webkit-transform: perspective(400px) rotateX(90deg);
        -ms-transform: perspective(400px) rotateX(90deg);
        transform: perspective(400px) rotateX(90deg);
        opacity: 0;
    }
}

.flipOutX {
    -webkit-animation-name: flipOutX;
    animation-name: flipOutX;
    -webkit-backface-visibility: visible !important;
    -ms-backface-visibility: visible !important;
    backface-visibility: visible !important;
}

@-webkit-keyframes flipOutY {
    0% {
        -webkit-transform: perspective(400px) rotateY(0deg);
        transform: perspective(400px) rotateY(0deg);
        opacity: 1;
    }

    100% {
        -webkit-transform: perspective(400px) rotateY(90deg);
        transform: perspective(400px) rotateY(90deg);
        opacity: 0;
    }
}

@keyframes flipOutY {
    0% {
        -webkit-transform: perspective(400px) rotateY(0deg);
        -ms-transform: perspective(400px) rotateY(0deg);
        transform: perspective(400px) rotateY(0deg);
        opacity: 1;
    }

    100% {
        -webkit-transform: perspective(400px) rotateY(90deg);
        -ms-transform: perspective(400px) rotateY(90deg);
        transform: perspective(400px) rotateY(90deg);
        opacity: 0;
    }
}

.flipOutY {
    -webkit-backface-visibility: visible !important;
    -ms-backface-visibility: visible !important;
    backface-visibility: visible !important;
    -webkit-animation-name: flipOutY;
    animation-name: flipOutY;
}

@-webkit-keyframes lightSpeedIn {
    0% {
        -webkit-transform: translateX(100%) skewX(-30deg);
        transform: translateX(100%) skewX(-30deg);
        opacity: 0;
    }

    60% {
        -webkit-transform: translateX(-20%) skewX(30deg);
        transform: translateX(-20%) skewX(30deg);
        opacity: 1;
    }

    80% {
        -webkit-transform: translateX(0%) skewX(-15deg);
        transform: translateX(0%) skewX(-15deg);
        opacity: 1;
    }

    100% {
        -webkit-transform: translateX(0%) skewX(0deg);
        transform: translateX(0%) skewX(0deg);
        opacity: 1;
    }
}

@keyframes lightSpeedIn {
    0% {
        -webkit-transform: translateX(100%) skewX(-30deg);
        -ms-transform: translateX(100%) skewX(-30deg);
        transform: translateX(100%) skewX(-30deg);
        opacity: 0;
    }

    60% {
        -webkit-transform: translateX(-20%) skewX(30deg);
        -ms-transform: translateX(-20%) skewX(30deg);
        transform: translateX(-20%) skewX(30deg);
        opacity: 1;
    }

    80% {
        -webkit-transform: translateX(0%) skewX(-15deg);
        -ms-transform: translateX(0%) skewX(-15deg);
        transform: translateX(0%) skewX(-15deg);
        opacity: 1;
    }

    100% {
        -webkit-transform: translateX(0%) skewX(0deg);
        -ms-transform: translateX(0%) skewX(0deg);
        transform: translateX(0%) skewX(0deg);
        opacity: 1;
    }
}

.lightSpeedIn {
    -webkit-animation-name: lightSpeedIn;
    animation-name: lightSpeedIn;
    -webkit-animation-timing-function: ease-out;
    animation-timing-function: ease-out;
}

@-webkit-keyframes lightSpeedOut {
    0% {
        -webkit-transform: translateX(0%) skewX(0deg);
        transform: translateX(0%) skewX(0deg);
        opacity: 1;
    }

    100% {
        -webkit-transform: translateX(100%) skewX(-30deg);
        transform: translateX(100%) skewX(-30deg);
        opacity: 0;
    }
}

@keyframes lightSpeedOut {
    0% {
        -webkit-transform: translateX(0%) skewX(0deg);
        -ms-transform: translateX(0%) skewX(0deg);
        transform: translateX(0%) skewX(0deg);
        opacity: 1;
    }

    100% {
        -webkit-transform: translateX(100%) skewX(-30deg);
        -ms-transform: translateX(100%) skewX(-30deg);
        transform: translateX(100%) skewX(-30deg);
        opacity: 0;
    }
}

.lightSpeedOut {
    -webkit-animation-name: lightSpeedOut;
    animation-name: lightSpeedOut;
    -webkit-animation-timing-function: ease-in;
    animation-timing-function: ease-in;
}

@-webkit-keyframes rotateIn {
    0% {
        -webkit-transform-origin: center center;
        transform-origin: center center;
        -webkit-transform: rotate(-200deg);
        transform: rotate(-200deg);
        opacity: 0;
    }

    100% {
        -webkit-transform-origin: center center;
        transform-origin: center center;
        -webkit-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }
}

@keyframes rotateIn {
    0% {
        -webkit-transform-origin: center center;
        -ms-transform-origin: center center;
        transform-origin: center center;
        -webkit-transform: rotate(-200deg);
        -ms-transform: rotate(-200deg);
        transform: rotate(-200deg);
        opacity: 0;
    }

    100% {
        -webkit-transform-origin: center center;
        -ms-transform-origin: center center;
        transform-origin: center center;
        -webkit-transform: rotate(0);
        -ms-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }
}

.rotateIn {
    -webkit-animation-name: rotateIn;
    animation-name: rotateIn;
}

@-webkit-keyframes rotateInDownLeft {
    0% {
        -webkit-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(-90deg);
        transform: rotate(-90deg);
        opacity: 0;
    }

    100% {
        -webkit-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }
}

@keyframes rotateInDownLeft {
    0% {
        -webkit-transform-origin: left bottom;
        -ms-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(-90deg);
        -ms-transform: rotate(-90deg);
        transform: rotate(-90deg);
        opacity: 0;
    }

    100% {
        -webkit-transform-origin: left bottom;
        -ms-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(0);
        -ms-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }
}

.rotateInDownLeft {
    -webkit-animation-name: rotateInDownLeft;
    animation-name: rotateInDownLeft;
}

@-webkit-keyframes rotateInDownRight {
    0% {
        -webkit-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(90deg);
        transform: rotate(90deg);
        opacity: 0;
    }

    100% {
        -webkit-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }
}

@keyframes rotateInDownRight {
    0% {
        -webkit-transform-origin: right bottom;
        -ms-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(90deg);
        -ms-transform: rotate(90deg);
        transform: rotate(90deg);
        opacity: 0;
    }

    100% {
        -webkit-transform-origin: right bottom;
        -ms-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(0);
        -ms-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }
}

.rotateInDownRight {
    -webkit-animation-name: rotateInDownRight;
    animation-name: rotateInDownRight;
}

@-webkit-keyframes rotateInUpLeft {
    0% {
        -webkit-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(90deg);
        transform: rotate(90deg);
        opacity: 0;
    }

    100% {
        -webkit-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }
}

@keyframes rotateInUpLeft {
    0% {
        -webkit-transform-origin: left bottom;
        -ms-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(90deg);
        -ms-transform: rotate(90deg);
        transform: rotate(90deg);
        opacity: 0;
    }

    100% {
        -webkit-transform-origin: left bottom;
        -ms-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(0);
        -ms-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }
}

.rotateInUpLeft {
    -webkit-animation-name: rotateInUpLeft;
    animation-name: rotateInUpLeft;
}

@-webkit-keyframes rotateInUpRight {
    0% {
        -webkit-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(-90deg);
        transform: rotate(-90deg);
        opacity: 0;
    }

    100% {
        -webkit-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }
}

@keyframes rotateInUpRight {
    0% {
        -webkit-transform-origin: right bottom;
        -ms-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(-90deg);
        -ms-transform: rotate(-90deg);
        transform: rotate(-90deg);
        opacity: 0;
    }

    100% {
        -webkit-transform-origin: right bottom;
        -ms-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(0);
        -ms-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }
}

.rotateInUpRight {
    -webkit-animation-name: rotateInUpRight;
    animation-name: rotateInUpRight;
}

@-webkit-keyframes rotateOut {
    0% {
        -webkit-transform-origin: center center;
        transform-origin: center center;
        -webkit-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }

    100% {
        -webkit-transform-origin: center center;
        transform-origin: center center;
        -webkit-transform: rotate(200deg);
        transform: rotate(200deg);
        opacity: 0;
    }
}

@keyframes rotateOut {
    0% {
        -webkit-transform-origin: center center;
        -ms-transform-origin: center center;
        transform-origin: center center;
        -webkit-transform: rotate(0);
        -ms-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }

    100% {
        -webkit-transform-origin: center center;
        -ms-transform-origin: center center;
        transform-origin: center center;
        -webkit-transform: rotate(200deg);
        -ms-transform: rotate(200deg);
        transform: rotate(200deg);
        opacity: 0;
    }
}

.rotateOut {
    -webkit-animation-name: rotateOut;
    animation-name: rotateOut;
}

@-webkit-keyframes rotateOutDownLeft {
    0% {
        -webkit-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }

    100% {
        -webkit-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(90deg);
        transform: rotate(90deg);
        opacity: 0;
    }
}

@keyframes rotateOutDownLeft {
    0% {
        -webkit-transform-origin: left bottom;
        -ms-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(0);
        -ms-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }

    100% {
        -webkit-transform-origin: left bottom;
        -ms-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(90deg);
        -ms-transform: rotate(90deg);
        transform: rotate(90deg);
        opacity: 0;
    }
}

.rotateOutDownLeft {
    -webkit-animation-name: rotateOutDownLeft;
    animation-name: rotateOutDownLeft;
}

@-webkit-keyframes rotateOutDownRight {
    0% {
        -webkit-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }

    100% {
        -webkit-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(-90deg);
        transform: rotate(-90deg);
        opacity: 0;
    }
}

@keyframes rotateOutDownRight {
    0% {
        -webkit-transform-origin: right bottom;
        -ms-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(0);
        -ms-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }

    100% {
        -webkit-transform-origin: right bottom;
        -ms-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(-90deg);
        -ms-transform: rotate(-90deg);
        transform: rotate(-90deg);
        opacity: 0;
    }
}

.rotateOutDownRight {
    -webkit-animation-name: rotateOutDownRight;
    animation-name: rotateOutDownRight;
}

@-webkit-keyframes rotateOutUpLeft {
    0% {
        -webkit-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }

    100% {
        -webkit-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(-90deg);
        transform: rotate(-90deg);
        opacity: 0;
    }
}

@keyframes rotateOutUpLeft {
    0% {
        -webkit-transform-origin: left bottom;
        -ms-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(0);
        -ms-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }

    100% {
        -webkit-transform-origin: left bottom;
        -ms-transform-origin: left bottom;
        transform-origin: left bottom;
        -webkit-transform: rotate(-90deg);
        -ms-transform: rotate(-90deg);
        transform: rotate(-90deg);
        opacity: 0;
    }
}

.rotateOutUpLeft {
    -webkit-animation-name: rotateOutUpLeft;
    animation-name: rotateOutUpLeft;
}

@-webkit-keyframes rotateOutUpRight {
    0% {
        -webkit-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }

    100% {
        -webkit-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(90deg);
        transform: rotate(90deg);
        opacity: 0;
    }
}

@keyframes rotateOutUpRight {
    0% {
        -webkit-transform-origin: right bottom;
        -ms-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(0);
        -ms-transform: rotate(0);
        transform: rotate(0);
        opacity: 1;
    }

    100% {
        -webkit-transform-origin: right bottom;
        -ms-transform-origin: right bottom;
        transform-origin: right bottom;
        -webkit-transform: rotate(90deg);
        -ms-transform: rotate(90deg);
        transform: rotate(90deg);
        opacity: 0;
    }
}

.rotateOutUpRight {
    -webkit-animation-name: rotateOutUpRight;
    animation-name: rotateOutUpRight;
}

@-webkit-keyframes slideInDown {
    0% {
        opacity: 0;
        -webkit-transform: translateY(-2000px);
        transform: translateY(-2000px);
    }

    100% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }
}

@keyframes slideInDown {
    0% {
        opacity: 0;
        -webkit-transform: translateY(-2000px);
        -ms-transform: translateY(-2000px);
        transform: translateY(-2000px);
    }

    100% {
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }
}

.slideInDown {
    -webkit-animation-name: slideInDown;
    animation-name: slideInDown;
}

@-webkit-keyframes slideInLeft {
    0% {
        opacity: 0;
        -webkit-transform: translateX(-2000px);
        transform: translateX(-2000px);
    }

    100% {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}

@keyframes slideInLeft {
    0% {
        opacity: 0;
        -webkit-transform: translateX(-2000px);
        -ms-transform: translateX(-2000px);
        transform: translateX(-2000px);
    }

    100% {
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }
}

.slideInLeft {
    -webkit-animation-name: slideInLeft;
    animation-name: slideInLeft;
}

@-webkit-keyframes slideInRight {
    0% {
        opacity: 0;
        -webkit-transform: translateX(2000px);
        transform: translateX(2000px);
    }

    100% {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}

@keyframes slideInRight {
    0% {
        opacity: 0;
        -webkit-transform: translateX(2000px);
        -ms-transform: translateX(2000px);
        transform: translateX(2000px);
    }

    100% {
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }
}

.slideInRight {
    -webkit-animation-name: slideInRight;
    animation-name: slideInRight;
}

@-webkit-keyframes slideOutLeft {
    0% {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(-2000px);
        transform: translateX(-2000px);
    }
}

@keyframes slideOutLeft {
    0% {
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(-2000px);
        -ms-transform: translateX(-2000px);
        transform: translateX(-2000px);
    }
}

.slideOutLeft {
    -webkit-animation-name: slideOutLeft;
    animation-name: slideOutLeft;
}

@-webkit-keyframes slideOutRight {
    0% {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(2000px);
        transform: translateX(2000px);
    }
}

@keyframes slideOutRight {
    0% {
        -webkit-transform: translateX(0);
        -ms-transform: translateX(0);
        transform: translateX(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(2000px);
        -ms-transform: translateX(2000px);
        transform: translateX(2000px);
    }
}

.slideOutRight {
    -webkit-animation-name: slideOutRight;
    animation-name: slideOutRight;
}

@-webkit-keyframes slideOutUp {
    0% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(-2000px);
        transform: translateY(-2000px);
    }
}

@keyframes slideOutUp {
    0% {
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(-2000px);
        -ms-transform: translateY(-2000px);
        transform: translateY(-2000px);
    }
}

.slideOutUp {
    -webkit-animation-name: slideOutUp;
    animation-name: slideOutUp;
}

@-webkit-keyframes slideOutDown {
    0% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(2000px);
        transform: translateY(2000px);
    }
}

@keyframes slideOutDown {
    0% {
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateY(2000px);
        -ms-transform: translateY(2000px);
        transform: translateY(2000px);
    }
}

.slideOutDown {
    -webkit-animation-name: slideOutDown;
    animation-name: slideOutDown;
}

@-webkit-keyframes hinge {
    0% {
        -webkit-transform: rotate(0);
        transform: rotate(0);
        -webkit-transform-origin: top left;
        transform-origin: top left;
        -webkit-animation-timing-function: ease-in-out;
        animation-timing-function: ease-in-out;
    }

    20%, 60% {
        -webkit-transform: rotate(80deg);
        transform: rotate(80deg);
        -webkit-transform-origin: top left;
        transform-origin: top left;
        -webkit-animation-timing-function: ease-in-out;
        animation-timing-function: ease-in-out;
    }

    40% {
        -webkit-transform: rotate(60deg);
        transform: rotate(60deg);
        -webkit-transform-origin: top left;
        transform-origin: top left;
        -webkit-animation-timing-function: ease-in-out;
        animation-timing-function: ease-in-out;
    }

    80% {
        -webkit-transform: rotate(60deg) translateY(0);
        transform: rotate(60deg) translateY(0);
        -webkit-transform-origin: top left;
        transform-origin: top left;
        -webkit-animation-timing-function: ease-in-out;
        animation-timing-function: ease-in-out;
        opacity: 1;
    }

    100% {
        -webkit-transform: translateY(700px);
        transform: translateY(700px);
        opacity: 0;
    }
}

@keyframes hinge {
    0% {
        -webkit-transform: rotate(0);
        -ms-transform: rotate(0);
        transform: rotate(0);
        -webkit-transform-origin: top left;
        -ms-transform-origin: top left;
        transform-origin: top left;
        -webkit-animation-timing-function: ease-in-out;
        animation-timing-function: ease-in-out;
    }

    20%, 60% {
        -webkit-transform: rotate(80deg);
        -ms-transform: rotate(80deg);
        transform: rotate(80deg);
        -webkit-transform-origin: top left;
        -ms-transform-origin: top left;
        transform-origin: top left;
        -webkit-animation-timing-function: ease-in-out;
        animation-timing-function: ease-in-out;
    }

    40% {
        -webkit-transform: rotate(60deg);
        -ms-transform: rotate(60deg);
        transform: rotate(60deg);
        -webkit-transform-origin: top left;
        -ms-transform-origin: top left;
        transform-origin: top left;
        -webkit-animation-timing-function: ease-in-out;
        animation-timing-function: ease-in-out;
    }

    80% {
        -webkit-transform: rotate(60deg) translateY(0);
        -ms-transform: rotate(60deg) translateY(0);
        transform: rotate(60deg) translateY(0);
        -webkit-transform-origin: top left;
        -ms-transform-origin: top left;
        transform-origin: top left;
        -webkit-animation-timing-function: ease-in-out;
        animation-timing-function: ease-in-out;
        opacity: 1;
    }

    100% {
        -webkit-transform: translateY(700px);
        -ms-transform: translateY(700px);
        transform: translateY(700px);
        opacity: 0;
    }
}

.hinge {
    -webkit-animation-name: hinge;
    animation-name: hinge;
}

/* originally authored by Nick Pettit - https://github.com/nickpettit/glide */

@-webkit-keyframes rollIn {
    0% {
        opacity: 0;
        -webkit-transform: translateX(-100%) rotate(-120deg);
        transform: translateX(-100%) rotate(-120deg);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateX(0px) rotate(0deg);
        transform: translateX(0px) rotate(0deg);
    }
}

@keyframes rollIn {
    0% {
        opacity: 0;
        -webkit-transform: translateX(-100%) rotate(-120deg);
        -ms-transform: translateX(-100%) rotate(-120deg);
        transform: translateX(-100%) rotate(-120deg);
    }

    100% {
        opacity: 1;
        -webkit-transform: translateX(0px) rotate(0deg);
        -ms-transform: translateX(0px) rotate(0deg);
        transform: translateX(0px) rotate(0deg);
    }
}

.rollIn {
    -webkit-animation-name: rollIn;
    animation-name: rollIn;
}

/* originally authored by Nick Pettit - https://github.com/nickpettit/glide */

@-webkit-keyframes rollOut {
    0% {
        opacity: 1;
        -webkit-transform: translateX(0px) rotate(0deg);
        transform: translateX(0px) rotate(0deg);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(100%) rotate(120deg);
        transform: translateX(100%) rotate(120deg);
    }
}

@keyframes rollOut {
    0% {
        opacity: 1;
        -webkit-transform: translateX(0px) rotate(0deg);
        -ms-transform: translateX(0px) rotate(0deg);
        transform: translateX(0px) rotate(0deg);
    }

    100% {
        opacity: 0;
        -webkit-transform: translateX(100%) rotate(120deg);
        -ms-transform: translateX(100%) rotate(120deg);
        transform: translateX(100%) rotate(120deg);
    }
}

.rollOut {
    -webkit-animation-name: rollOut;
    animation-name: rollOut;
}
