# wavify-js live https://jibon87.github.io/wavify-js/

```
wavify 

1.  js--link ---> jquery.min.js

2.  js--link ---> js/wavify.TweenMax.min.js

3.  js--link ---> js/wavify.min.js

4.  css--link ---> css/style.css [

            svg {
                /* position: absolute; */
                height: 50vh;
                width: 100%;
                top: 0;
                left: 0;
                /* bottom: 0; */
                right: 0;
            }
]

5.  html 
    {
    
    <div style="position: relative;">
        <svg version="1.1" xmlns="http://www.w3.org/2000/svg"><path id="wave" d="" /></svg>
    </div>

    }
    
6.  active js {

     $("#wave").wavify({
        height: 100,
        bones: 4,
        amplitude: 60,
        color: "#80ff80",
        speed: 0.25,
    });

}

7.  note [ 
          
         ]
