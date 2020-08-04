# JS-Slug

JavaScript için uygun olan utf-8 ve Türkçe karakterler dahil yazıları, urlyi slug haline getirmenize yardımcı olacak slug dosyası ektedir.

The slug file is included to help you convert the url to text, including utf-8 and Turkish characters, suitable for javascript.

<h1>Kullanımı</h1> 
url_slug("general settings") 
Şeklinde kullanılır.
<h3>JavaScript için örnek</h3>
$(document).on('keyup','#title',function(){ <br>
    $('#Slug_url').val(url_slug($('#title').val()));<br>
});<br>
