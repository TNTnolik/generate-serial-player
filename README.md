# generate-serial-player
Осуществляет создания кнопок для серий из ссылок на странице.

# Install
1)Для установки скрипта, установите в месте где вы бы хотели установить плеер html код:

'''html
<div id="vid" >
<iframe src="" allow="autoplay; fullscreen" webkitallowfullscreen="true" mozallowfullscreen="true" allowfullscreen="true" frameborder="0" width="100%" height="100%"></iframe>
</div>
<div id="sb" ></div>
'''

2)В конце страници добавьте код подключения скрипта:

<script src="js/HDGOP.js"></script>

3)Для добавления видео в тексте страници добавьте ссылку на видео, типа => https://vio.to/video/t/***/

4)id адреса для редактирования:
 Блок видео: #vid
 Блок серий: #sb
 Кнопки серий: #sbutton
