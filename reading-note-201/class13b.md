## Transforms

ways to position and alter element

Transform Syntax:

div {

  -webkit-transform: scale(1.5);

     -moz-transform: scale(1.5);

       -o-transform: scale(1.5);

          transform: scale(1.5);
}

we can rotate element by   transform: rotate(20deg);

transform: skew(5deg, -20deg); used to distort elements on the horizontal axis, vertical axis, or both.

there is many position in transform such as 3d on combain and so on..

## Transitions & Animations

transitions you have the potential to alter the appearance and behavior of an element 
Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes

transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay.
 
 }

 transition-property: background;

  transition-duration: 1s;

  transition-timing-function: linear;

 transition-delay: 0s, 1s;
}

**Animations Keyframes**

To set multiple points at which an element should undergo a transition for example

@keyframes slide {

  0% {

    left: 0;

    top: 0;
  }

then we put animation name :

.stage:hover .ball {

  animation-name: slide;

}

to start animation we should add duration like this :

stage:hover .ball {

  animation-name: slide;

  animation-duration: 2s;

}

and we can add delly and fill mode or play state

.stage:hover .ball {

  animation-name: slide;

  animation-duration: 2s;

  animation-timing-function: ease-in-out;

  animation-delay: .5s;

  animation-fill-mode: forwards;

}

## SIMPLE CSS3 TRANSITIONS

+ Fade in which is change opacity when we hover it
 
.fade

{

        opacity:0.5;

}

.fade:hover

{

        opacity:1;
}

+ Change color

.color:hover

{

        background:#53a7ea;

}

+ Grow & Shrink by using hieght and width

.grow:hover
{

        -webkit-transform: scale(1.3);
        -ms-transform: scale(1.3);
        transform: scale(1.3);

}

+ Rotate elements

.rotate:hover

{
       
        -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);
        transform: rotateZ(-30deg);

}

+  Square to circle

.circle:hover

{

        border-radius:50%;

}

+  Inset border

.border:hover

{

        box-shadow: inset 0 0 0 25px #53a7ea;
}

+  3D shadow

.threed:hover

{

        box-shadow:

                1px 1px #53a7ea,
                2px 2px #53a7ea,
                3px 3px #53a7ea;

        -webkit-transform: translateX(-3px);

        transform: translateX(-3px);
        
}

 


 



 
