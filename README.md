# slider-owl

  $(".product-promotion").owlCarousel({
            items:5,
            nav:false,
            dot:true,
            loop:true,
            navText: ['<i class="fa fa-angle-left"></i>', '<i class="fa fa-angle-right"></i>'],
            margin:30,
            autoplay:false,
            autoplayTimeout:3000,
            smartSpeed:1000,
            responsiveClass:true,
            responsive:{
                0:{
                    items:1,
                   
                },
                768:{
                    items:1,
                   
                },
                1000:{
                    items:1,
                   
                }
            }
            
          
        });
