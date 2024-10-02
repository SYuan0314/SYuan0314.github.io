// 自行加入的JS請寫在這裡
$(function() {
    //tabContent new tag
    $('.text_link ul li a').has('span.new_tag').css('paddingRight', '4.2em');
    //小廣告展開收合
    $('.btn_ad_more').click(function(e) {
        $(this).parents('.ad_banner_accordion').find('.ad_more').stop(true, true).slideToggle(function() {
            if ($(this).is(':visible')) {
                $('.btn_ad_more').html("較少連結 -");
                $('.btn_ad_more').attr('name', '較少連結');
            } else {
                $('.btn_ad_more').html("更多連結 ＋");
                $('.btn_ad_more').attr('name', '更多連結');
            }
        });
        $(this).stop(true, true).toggleClass('close');
    }); 

})
// 輪播col 設定
// 圖文卡片式
$('.col-12 .news_card ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 3,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 3,
            slidesToScroll: 3,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.mpSlider').slick({
        mobileFirst: true,
        dots: false,
        arrow: true,
        infinite: true,
        speed: 500,
        autoplay: true,
        fade: true,
        lazyLoaded: true,
        lazyLoad: 'ondemand',
        ease: 'ease',
        responsive: [{
            breakpoint: 768,
            settings: {
                dots: true
            }
        }]
    });
    // 廣告輪播
    $('.adSlider').slick({
        mobileFirst: true,
        dots: false,
        infinite: true,
        speed: 300,
        slidesToShow: 2,
        slidesToScroll: 1,
        autoplay: true,
        arrow: true,
        lazyLoaded: true,
        lazyLoad: 'ondemand',
        ease: 'ease',
        responsive: [{
            breakpoint: 1200,
            settings: {
                slidesToShow: 6,
                slidesToScroll: 1,
                arrows: true
            }
        }, {
            breakpoint: 768,
            settings: {
                slidesToShow: 4,
                slidesToScroll: 1,
                arrows: true
            }
        }, {
            breakpoint: 575,
            settings: {
                slidesToShow: 3,
                slidesToScroll: 1,
                arrows: true
            }
        }]
    });
    // 跑馬燈
    //上下
    $('.marquee ul').slick({
        dots: false,
        infinite: true,
        vertical: true,
        verticalSwiping: true,
        speed: 1000,
        slidesToShow: 1,
        slidesToScroll: 1,
        autoplay: true,
        pauseOnHover: true, //滑鼠移過後暫停自動撥放
        autoplaySpeed: 1500,
        speed: 1000,
        // centerMode: true,
        focusOnSelect: true,
        //      responsive: [{
        //          breakpoint: 990,
        //          settings: {
        //              slidesToShow: 2,
        //              slidesToScroll: 2
        //          }
        //      }, {
        //          breakpoint: 600,
        //          settings: {
        //              slidesToShow: 2,
        //              slidesToScroll: 2,
        //              vertical: false,
        //              verticalSwiping: false
        //          }
        //      }, {
        //          breakpoint: 480,
        //          settings: {
        //              slidesToShow: 1,
        //              slidesToScroll: 1,
        //              vertical: false,
        //              verticalSwiping: false
        //          }
        //      }]
    });
    //左右捲動文字跑馬燈
    $('.marquee-2 ul').slick({
        dots: false,
        infinite: true,
        vertical: false,
        verticalSwiping: true,
        speed: 1000,
        slidesToShow: 1,
        slidesToScroll: 1,
        autoplay: true,
        pauseOnHover: true, //滑鼠移過後暫停自動撥放
        autoplaySpeed: 1500,
        speed: 1000,
        focusOnSelect: true,
    });
    //燈箱slick+lightBox組合
    $('.cp_slider').slick({
        dots: true,
        infinite: true,
        speed: 500,
        slidesToShow: 4,
        slidesToScroll: 1,
        autoplay: false,
        autoplaySpeed: 1500,
        pauseOnHover: true,
        pauseOnFocus: true,
        focusOnSelect: true,
        accessibility: true,
        lazyLoad: 'ondemand',
        ease: 'ease',
        responsive: [{
            breakpoint: 768,
            settings: {
                slidesToShow: 2,
                slidesToScroll: 2,
                infinite: true,
                dots: true
            }
        }, {
            breakpoint: 545,
            settings: {
                arrows: true,
                slidesToShow: 2,
                slidesToScroll: 2
            }
        }, {
            breakpoint: 480,
            settings: {
                arrows: true,
                slidesToShow: 1,
                slidesToScroll: 1,
                arrows: false
            }
        }]
    });
    $('.cp_slider').slickLightbox({
        caption: 'caption',
        lazyLoad: 'ondemand',
        useHistoryApi: 'true',
        ease: 'ease',
        lazy: true
    });
    // cp_photo
    $('.Slider-for').on('init reInit afterChange', function(event, slick, currentSlide) {
        var i = (currentSlide ? currentSlide : 0) + 1;
        $('.controls').html(i + '/' + slick.slideCount);
    });
    $('.Slider-for').slick({
        slidesToShow: 1,
        slidesToScroll: 1,
        arrows: false,
        fade: true,
        swipe: false,
        swipeToSlide: false,
        lazyLoad: 'ondemand',
        asNavFor: '.Slider-nav',
        infinite: true
    });
    $('.Slider-nav').slick({
        slidesToShow: 3,
        slidesToScroll: 1,
        asNavFor: '.Slider-for',
        dots: true,
        arrows: true,
        lazyLoad: 'ondemand',
        focusOnSelect: true,
        infinite: true
    });
$('.col-4-8 .col:nth-child(2) .news_card ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 2,
    slidesToScroll: 2,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-4-8 .col:nth-child(1) .news_card ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-8-4 .col:nth-child(2) .news_card ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-8-4 .col:nth-child(1) .news_card ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 2,
    slidesToScroll: 2,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-4-4-4 .col .news_card ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-6-6 .col .news_card ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-3-3-3-3 .col .news_card ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
// 影音專區
$('.col-12 .multi_video ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 3,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 3,
            slidesToScroll: 3,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-4-8 .col:nth-child(2) .multi_video ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 3,
    slidesToScroll: 3,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 3,
            slidesToScroll: 3,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-4-8 .col:nth-child(1) .multi_video ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-8-4 .col:nth-child(2) .multi_video ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-8-4 .col:nth-child(1) .multi_video ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 3,
    slidesToScroll: 3,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 3,
            slidesToScroll: 3,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-4-4-4 .col .multi_video ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-6-6 .col .multi_video ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-3-3-3-3 .col .multi_video ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
// 照片花絮
$('.col-12 .multi_photo ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 3,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 3,
            slidesToScroll: 3,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-4-8 .col:nth-child(2) .multi_photo ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 3,
    slidesToScroll: 3,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 3,
            slidesToScroll: 3,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-4-8 .col:nth-child(1) .multi_photo ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-8-4 .col:nth-child(2) .multi_photo ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-8-4 .col:nth-child(1) .multi_photo ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 3,
    slidesToScroll: 3,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 3,
            slidesToScroll: 3,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-4-4-4 .col .multi_photo ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-6-6 .col .multi_photo ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-3-3-3-3 .col .multi_photo ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    pauseOnHover: true,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
// 便民專區
$('.col-12 .service ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 6,
    pauseOnHover: true,
    slidesToScroll: 1,
    autoplay: false,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 4,
            slidesToScroll: 4,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 3,
            slidesToScroll: 3,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            arrows: true
        }
    }]
});
$('.col-8-4 .col:nth-child(1) .service ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 4,
    pauseOnHover: true,
    slidesToScroll: 1,
    autoplay: false,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 3,
            slidesToScroll: 3,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-8-4 .col:nth-child(2) .service ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 2,
    pauseOnHover: true,
    slidesToScroll: 1,
    autoplay: false,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-4-8 .col:nth-child(1) .service ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 2,
    pauseOnHover: true,
    slidesToScroll: 1,
    autoplay: false,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-4-8 .col:nth-child(2) .service ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 4,
    pauseOnHover: true,
    slidesToScroll: 1,
    autoplay: false,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 3,
            slidesToScroll: 3,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 2,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-4-4-4 .col .service ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 2,
    pauseOnHover: true,
    slidesToScroll: 1,
    autoplay: false,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-3-3-3-3 .col .service ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    pauseOnHover: true,
    slidesToScroll: 1,
    autoplay: false,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});
$('.col-6-6 .col .service ul').slick({
    dots: false,
    infinite: true,
    speed: 300,
    slidesToShow: 3,
    pauseOnHover: true,
    slidesToScroll: 1,
    autoplay: false,
    arrow: true,
    responsive: [{
        breakpoint: 1024,
        settings: {
            slidesToShow: 3,
            slidesToScroll: 1,
            infinite: true,
            dots: false,
            arrows: true
        }
    }, {
        breakpoint: 992,
        settings: {
            slidesToShow: 2,
            slidesToScroll: 1,
            arrows: true
        }
    }, {
        breakpoint: 575,
        settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
            arrows: true
        }
    }]
});