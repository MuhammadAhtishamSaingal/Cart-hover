$(document).ready(function () {
  $('.shop').hover(function () {
    $('.carts').css('visibility', 'visible');
  });

  $('body').click(function(e) {
    if (!$(e.target).is('.carts')) {
      $('.carts').css('visibility', 'hidden');
    }
  });
});
