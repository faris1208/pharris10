$(document).ready(function () {
  $('.top').click(function () {
    $('.header_1').slideToggle(600);
  });

  $('.menu').click(function(){
    $('.toggle_nav').toggle();
  });

  $('.main_top').click(function(){
    let geturl = window.location.href ;
    let getlocation = geturl.substring(geturl.lastIndexOf('#')+1);
    if(getlocation == 'home'){
      $('html, body').animate({
        scrollTop: $('#'+ getlocation).offset().top
      },1000);
    }
  });

});


window.addEventListener('scroll', function(){
  let top = document.querySelector('.main_top');

  let scrolling = document.documentElement.scrollTop;

  if(scrolling < 160){
    top.style.display = 'none';
  }else {
    top.style.display = 'block';
  }
})



