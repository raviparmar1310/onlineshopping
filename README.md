# onlineshopping
This Project is online product to purchaes easily...
<!DOCTYPE html>
<html dir="ltr" lang="en-US"><head><!-- Created by Artisteer v4.1.0.59861 -->
    <meta charset="utf-8">
    <title>Main</title>
    <meta name="viewport" content="initial-scale = 1.0, maximum-scale = 1.0, user-scalable = no, width = device-width">

    <!--[if lt IE 9]><script src="https://html5shiv.googlecode.com/svn/trunk/html5.js"></script><![endif]-->
    <link rel="stylesheet" href="style.css" media="screen">
    <!--[if lte IE 7]><link rel="stylesheet" href="style.ie7.css" media="screen" /><![endif]-->
    <link rel="stylesheet" href="style.responsive.css" media="all">
<link rel="stylesheet" type="text/css" href="http://fonts.googleapis.com/css?family=Gentium+Basic&amp;subset=latin">
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <script src="jquery.js"></script>
    <script src="script.js"></script>
    <script src="script.responsive.js"></script>
<meta name="description" content="veejaygarments is wholeseller in mumbai">
<meta name="keywords" content="veejaygarments, veejay garments, mumbai garments">



<script>jQuery(function($) {
    'use strict';
    if ($.fn.slider) {
        $(".htl-slidecontainerimages2").each(function () {
            var slideContainer = $(this), tmp;
            var inner = $(".htl-slider-inner", slideContainer);
            var helper = null;

            if ($.support.transition) {
                helper = new BackgroundHelper();
                helper.init("vertical", "next", $(".htl-slide-item", inner).first().css($.support.transition.prefix + "transition-duration"));
                inner.children().each(function () {
                    helper.processSlide($(this), true);
                });

                var items = helper.items(helper.current(0), helper.next(0));
                helper.setBackground(inner, items);
                helper.setPosition(inner, items);

                slideContainer.on("beforeSlide", function () {
                    var activeItem = $(".active", this),
                        nextItem = $(".next, .prev", this),
                        activePos = $(".htl-slide-item", this).index(activeItem),
                        nextPos = $(".htl-slide-item", this).index(nextItem);

                    var currentItems = helper.items(helper.current(activePos), helper.current(nextPos));

                    helper.transition(inner, false);
                    helper.setBackground(inner, currentItems);
                    helper.setPosition(inner, currentItems);
                    if (inner.length) {
                        tmp = inner.get(0).offsetHeight;
                    }

                    var movedCurrentItems = helper.items(helper.current(activePos), helper.current(nextPos), true);
                    helper.transition(inner, true);
                    helper.setPosition(inner, movedCurrentItems);
                });
            }


            inner.children().eq(0).addClass("active");
            slideContainer.slider({
                pause: 2600,
                speed: 600,
                repeat: true,
                animation: "vertical",
                direction: "next",
                navigator: slideContainer.siblings(".htl-slidenavigatorimages2"),
                helper: helper                
            });
        });
    }
});
</script><style>.htl-content .htl-postcontent-0 .layout-item-0 { margin-top: 10px;margin-bottom: 10px;  }
.htl-content .htl-postcontent-0 .layout-item-1 { padding-right: 15px;padding-left: 15px;  }
.htl-content .htl-postcontent-0 .layout-item-2 { padding-top: 0px;padding-right: 20px;padding-bottom: 0px;padding-left: 15px;  }
.htl-content .htl-postcontent-0 .layout-item-3 { color: #281510; background: #F7F7F7; padding-right: 20px;padding-left: 15px;  }
.ie7 .htl-post .htl-layout-cell {border:none !important; padding:0 !important; }
.ie6 .htl-post .htl-layout-cell {border:none !important; padding:0 !important; }

.htl-slidecontainerimages2 {
    position: relative;
        width: 183px;
    height: 275px;
        }

.htl-slidecontainerimages2 .htl-slide-item
{

}


.htl-slidecontainerimages2 .htl-slide-item {
    -webkit-transition: 600ms ease-in-out top;
    -moz-transition: 600ms ease-in-out top;
    -ms-transition: 600ms ease-in-out top;
    -o-transition: 600ms ease-in-out top;
    transition: 600ms ease-in-out top;
    position: relative;
    display: none;
    width:  100%;
    height: 100%;
}

.htl-slidecontainerimages2 .active, .htl-slidecontainerimages2 .next, .htl-slidecontainerimages2 .prev {
    display: block;
}

.htl-slidecontainerimages2 .active {
    top: 0;
}

.htl-slidecontainerimages2 .next, .htl-slidecontainerimages2 .prev {
    position: absolute;
    top: 0;
    width: 100%;
}

.htl-slidecontainerimages2 .next {
    top: 100%;
}

.htl-slidecontainerimages2 .prev {
    top: -100%;
}

.htl-slidecontainerimages2 .next.forward, .htl-slidecontainerimages2 .prev.back {
    top: 0;
}

.htl-slidecontainerimages2 .active.forward {
    top: -100%;
}

.htl-slidecontainerimages2 .active.back {
    top: 100%;
}



.htl-slideimages20 {
    background-image:  url('images/slideimages20.jpg');
        background-size:  100%;
        background-position:  0 0;
    background-repeat: no-repeat;
}
.htl-slideimages21 {
    background-image:  url('images/slideimages21.jpg');
        background-size:  100%;
        background-position:  0 0;
    background-repeat: no-repeat;
}
.htl-slideimages22 {
    background-image:  url('images/slideimages22.jpg');
        background-size:  100%;
        background-position:  0 0;
    background-repeat: no-repeat;
}
.htl-slideimages23 {
    background-image:  url('images/slideimages23.jpg');
        background-size:  100%;
        background-position:  0 0;
    background-repeat: no-repeat;
}
.htl-slideimages24 {
    background-image:  url('images/slideimages24.jpg');
        background-size:  100%;
        background-position:  0 0;
    background-repeat: no-repeat;
}
.htl-slideimages25 {
    background-image:  url('images/slideimages25.jpg');
        background-size:  100%;
        background-position:  0 0;
    background-repeat: no-repeat;
}


.htl-slidenavigatorimages2 {
  display: inline-block;
  position: absolute;
  direction: ltr !important;
  top: 256px;
  left: 24.32%;
  z-index: 101;
  line-height: 0 !important;
  -webkit-background-origin: border !important;
  -moz-background-origin: border !important;
  background-origin: border-box !important;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  text-align: center;
    white-space: nowrap;
    }
.htl-slidenavigatorimages2
{
background: #BDBDBD;background: transparent;background: transparent;background: transparent;background: transparent;background: transparent;background: transparent;-svg-background: transparent;
-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px;


padding:7px;





}
.htl-slidenavigatorimages2 > a
{
background: #787878;background: #787878;background: #787878;background: #787878;background: #787878;background: #787878;background: #787878;-svg-background: #787878;
-webkit-border-radius:20%;-moz-border-radius:20%;border-radius:20%;



margin:0 10px 0 0;

width: 5px;

height: 5px;
}
.htl-slidenavigatorimages2 > a.active
{
background: #FF7824;background: #FF7824;background: #FF7824;background: #FF7824;background: #FF7824;background: #FF7824;background: #FF7824;-svg-background: #FF7824;
-webkit-border-radius:20%;-moz-border-radius:20%;border-radius:20%;



margin:0 10px 0 0;

width: 5px;

height: 5px;
}
.htl-slidenavigatorimages2 > a:hover
{
background: #A84100;background: #A84100;background: #A84100;background: #A84100;background: #A84100;background: #A84100;background: #A84100;-svg-background: #A84100;
-webkit-border-radius:20%;-moz-border-radius:20%;border-radius:20%;



margin:0 10px 0 0;

width: 5px;

height: 5px;
}

</style></head>
<body>
<div id="htl-main">
<header class="htl-header">
<div class="htl-slider htl-slidecontainerheader" data-width="900" data-height="250">
    <div class="htl-slider-inner">
<div class="htl-slide-item htl-slideheader0">

</div>
<div class="htl-slide-item htl-slideheader1">

</div>
<div class="htl-slide-item htl-slideheader2">

</div>
<div class="htl-slide-item htl-slideheader3">

</div>
<div class="htl-slide-item htl-slideheader4">

</div>

    </div>
</div>
<div class="htl-slidenavigator htl-slidenavigatorheader" data-left="45.61">
<a href="#" class="htl-slidenavigatoritem"></a><a href="#" class="htl-slidenavigatoritem"></a><a href="#" class="htl-slidenavigatoritem"></a><a href="#" class="htl-slidenavigatoritem"></a><a href="#" class="htl-slidenavigatoritem"></a>
</div>



    <div class="htl-shapes">

            </div>




                
                    
</header>
<div class="htl-sheet clearfix">
            <div class="htl-layout-wrapper">
                <div class="htl-content-layout">
                    <div class="htl-content-layout-row">
                        <div class="htl-layout-cell htl-sidebar1"><div class="htl-vmenublock clearfix">
        <div class="htl-vmenublockcontent">
<ul class="htl-vmenu"><li><a href="main.html" class="active">Main</a></li><li><a href="about-us.html">About Us</a></li><li><a href="catalog.html">Catalog</a><ul><li><a href="catalog/mens-wear.html">Men's Wear</a></li><li><a href="catalog/mens-denim-jeans.html">Men's Denim Jeans</a></li><li><a href="catalog/mens-cotton.html">Men's Cotton</a></li><li><a href="catalog/mens-formal.html">Men's Formal</a></li><li><a href="catalog/payment-options.html">Payment Options</a></li></ul></li><li><a href="home.html">News</a></li><li><a href="pricing.html">Pricing</a></li><li><a href="testimonials.html">Testimonials</a></li><li><a href="contacts.html">Contact Us</a></li></ul>
                
        </div>
</div><div class="htl-block clearfix">
        <div class="htl-blockcontent"><div style="padding: 10px; border: 1px solid #B7BCBD">
<p><a href="/catalog/mens-jeans"><span style="font-size: 16px; font-weight: bold;">50% OFF JEANS!</span></a></p><br>

<p>Yppee offer valid for short period only......</p><br>

<p><a href="catalog/mens-denim-jeans.html">Click Here</a><br>
 to check out our special deal!</p>
</div></div>
</div></div>
                        <div class="htl-layout-cell htl-content"><article class="htl-post htl-article">
                                
                                                
                <div class="htl-postcontent htl-postcontent-0 clearfix"><div class="htl-content-layout-wrapper layout-item-0">
<div class="htl-content-layout">
    <div class="htl-content-layout-row">
    <div class="htl-layout-cell layout-item-1" style="width: 55%" >
        <img width="350" height="233" style="margin-top: 5px; margin-right: 5px; margin-bottom: 5px; margin-left: 5px; border-top-width: 0px; border-right-width: 0px; border-bottom-width: 0px; border-left-width: 0px; " alt="" class="htl-lightbox" src="images/943c8bee-afce-4b9e-8012-65a67afd20f2.png">
    </div><div class="htl-layout-cell layout-item-2" style="width: 45%" >
        <blockquote style="text-align: left;"><span style="font-size: 15px;">We delight our customers with our products and service, and always make them feel that they are getting great value for their money.To design, make and sell products with intrinsic worth that comes from the original designs, knowledge, care and skill with which these are made.</span><span style="font-weight: bold;"></span></blockquote>
    </div>
    </div>
</div>
</div>
<div class="htl-content-layout">
    <div class="htl-content-layout-row">
    <div class="htl-layout-cell layout-item-1" style="width: 55%" >
        <h3>Website Updates</h3><ul style="margin-top: 1em; margin-bottom: 1em; margin-left: 2em;"><li><a href="catalog/mens-wear.html">"Vain Glory"</a><span style="font-size: 14px; font-weight: bold;"></span></li><li><a href="catalog/mens-denim-jeans.html">&nbsp;Men's Denim</a><span style="font-size: 14px;"><span style="font-weight: bold;"></span></span></li><li><a href="catalog/mens-cotton.html">Men's Cotton</a><span style="font-size: 14px; font-weight: bold;"></span></li><li><a href="catalog/mens-cotton.html">Men's Formals</a><span style="font-size: 14px; font-weight: bold;"></span></li><li><span style="font-size: 14px; font-weight: bold;">New Arrivals!!</span><br><span style="font-size: 13px;">To be true to our commitment and history as an ethical and trust-worthy brand promoting a stake-holder based community model of inclusive capitalism.To constantly share our Vision with our employees, suppliers, business associates and customers, so that we collectively ensure that all our actions are in service of our Vision, Mission and Guiding Principles.</span><span style="color: rgb(105, 48, 35);"><br></span>
        </li>
        </ul>
    </div><div class="htl-layout-cell layout-item-3" style="width: 45%" >
        <h3>Collection Updates</h3><p></p><div id="images2" style="position: relative; display: inline-block; z-index: 0; margin: 5px;  border-width: 0px;  " class="htl-collage">
<div class="htl-slider htl-slidecontainerimages2" data-width="183" data-height="275">
    <div class="htl-slider-inner">
<div class="htl-slide-item htl-slideimages20">

</div>
<div class="htl-slide-item htl-slideimages21">

</div>
<div class="htl-slide-item htl-slideimages22">

</div>
<div class="htl-slide-item htl-slideimages23">

</div>
<div class="htl-slide-item htl-slideimages24">

</div>
<div class="htl-slide-item htl-slideimages25">

</div>

    </div>
</div>
<div class="htl-slidenavigator htl-slidenavigatorimages2" data-left="24.32">
<a href="#" class="htl-slidenavigatoritem"></a><a href="#" class="htl-slidenavigatoritem"></a><a href="#" class="htl-slidenavigatoritem"></a><a href="#" class="htl-slidenavigatoritem"></a><a href="#" class="htl-slidenavigatoritem"></a><a href="#" class="htl-slidenavigatoritem"></a>
</div>



    </div>

        
         
         
        <p><br></p>
    </div>
    </div>
</div>
</div>
                                
                

</article></div>
                    </div>
                </div>
            </div><footer class="htl-footer">
<div style="position:relative;padding-left:10px;padding-right:10px"><p>Copyright © 2014.<br>
veejaygarments. All Rights Reserved.</p></div>
</footer>

    </div>
    <p class="htl-page-footer">
        <span id="htl-footnote-links">Designed by <a href="http://www.htlwebs.com" target="_blank">Ravi Parmar</a>.</span>
    </p>
</div>


</body></html>
