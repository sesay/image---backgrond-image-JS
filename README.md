# image[img] to backgrond-image-JS
Covert img  to Background image  JS

# $('selector-name').each(function () {
#  var $container = $(this),
                imgUrl = $container.find('img').prop('src');
            if (imgUrl) {
              $container
                .css('backgroundImage', 'url(' + imgUrl + ')')
                .addClass('compat-object-fit');
            }  
 });
