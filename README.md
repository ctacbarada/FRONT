# How to learn

This landing page has been written by `HTML5` and `CSS3`. The project was created on the basis of [BEM](https://en.bem.info/) methodology.

<a href="https://sirstanislav.github.io/how-to-learn/"><img src="https://github.com/sirstanislav/HowToLearn/blob/main/images/Gif.gif?raw=true"></a>
<br>

Of the features it is the application of `animations`

```CSS
@keyframes rotation {
  from {
    transform: rotate(0deg);
    -webkit-transform: rotate(0deg);
    -moz-transform: rotate(0deg);
    -ms-transform: rotate(0deg);
    -o-transform: rotate(0deg);
}
  to {
    transform: rotate(360deg);
    -webkit-transform: rotate(360deg);
    -moz-transform: rotate(360deg);
    -ms-transform: rotate(360deg);
    -o-transform: rotate(360deg);
}
}

.rotation {
  animation: rotation 20s linear infinite;
  -webkit-animation: rotation 20s linear infinite;
}
```
