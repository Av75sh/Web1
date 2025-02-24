
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

`stagger` :- refers to the delay applied to animations of multiple elements, making them appear one after another instead of all at once