# jquery-fixed-height-carousel

[View a simple demo here](https://cdn.rawgit.com/ninapavlich/jquery-fixed-height-carousel/master/example.html)

[View the carousel in the wild here](https://tess-vigil.squarespace.com/about/collections/bridesmaids)



![alt text](https://raw.githubusercontent.com/ninapavlich/jquery-fixed-height-carousel/master/docs/bridesmaids.png "Very Simple Screenshot")

## Initialization

**Example Markup**

    <div class="fixed-height-carousel unloaded fixed-height-carousel-theme-default">    
            <ul>
                <li>                
                    <a href="http://www.example.com">
                        <figure>
                            
                            <img src="http://placehold.it/800x450" alt="Image alt" />
                        </figure>
                    </a>
                    <figcaption>
                        Image Caption that contains <a href="http://www.google.com">a link</a>.
                    </figcaption>
                </li>
                <li>
                    <figure>
                        <img src="http://placehold.it/800x450" alt="Image alt" />
                    </figure>
                </li>
                <li>                
                    <a href="http://www.example.com">
                        <figure>
                            <img src="http://placehold.it/800x450" alt="Image alt" />
                        </figure>
                    </a>
                </li>
            </ul>            
        </div>


**Required Libraries**

    <script src="js/vendor/jquery-1.11.2.min.js"></script>

    <!-- Required for draggability -->
    <script src="js/vendor/jquery-ui.min.js"></script>
    <script src="js/vendor/jquery.ui.touch-punch.min.js"></script>

**Javascript**

    <script>
         $('.fixed-height-carousel').fixedHeightCarousel();
    </script>
    


## Options

**margin:1**
margin between each slide

**autoPlay:false**
Auto-play carousel

**autoPlayInterval:5000**
Seconds between slides if auto-play is turned on

**maxAutoPlayIntervals:0**
Number of times that auto-play runs before pausing. Auto-play will play indefinitely if set to 0.

**useAnchors:false**
Update window hash so that specific slides can be bookmarkable.

**pageAnchorPrefix:'slide'**
Window hash prefix used if useAnchors is true. For example, if the second slide is selected, the window url would be: http://www.example.com/#slide2

**animationDuration:600**
Duration in ms of sliding animation

**animationEase:'easeInOutQuart'**
Easing function used in sliding animation

**themeClass:'ribbon-carousel-theme-default'**
The css class to add to the container

**initialUnloadedClass:'unloaded'**
Class that gets removed from container once widget is loaded

**minimumLoad:true**
Class that gets removed from container once widget is loaded

**initKeyboardEvents:true**
Initialize keyboard arrow capabilities

**initDraggingEvents:true**
Initialize dragging capabilities

**initUI:true**
Initialize UI elements