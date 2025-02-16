
## Gsap `GreenSock Animation`
First install it in by gsap cdn
For moving button use the following commands

```js
        var videocon = document.querySelector("#video-container")
        var playbtn = document.querySelector("#play");

        videocon.addEventListener("mousemove", function(dets){
            gsap.to(playbtn,{
                left:dets.x,
                top:dets.y
            })
        })
```

stagger :- delay the animation from the previous one