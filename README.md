# AnderPlay1.github.io

## Добавление нового фотографа

Чтобы добавить нового фотографа и его работы:

1. **Добавить фото фотографа**: Поместите изображение в `images/People/` с именем `NewPhotographer.jpg` (замените на реальное имя).

2. **Обновить секцию "Наша команда"**: В `index.html` в секции `#services` добавьте новый блок:
   ```html
   <div class="col-md-4">
       <div class="services-inner-box">
           <img src="images/People/NewPhotographer.jpg" class="peoplePhoto">
           <h2>Имя Фотографа</h2>
           <p>Описание</p>
       </div>
   </div>
   ```

3. **Добавить папку с работами**: Создайте папку `images/photos/NewPhotographer/` и поместите туда фото (убедитесь в правильном регистре расширений, .jpg или .JPG).

4. **Добавить фильтр**: В секции `#portfolio` в `.button-group` добавьте:
   ```html
   <a data-filter=".newphotographer" href="ссылка_на_альбом" type="button" target="_blank">Имя Фотографа</a>
   ```

5. **Добавить галерею**: После существующих `<!-- Photographer: ... -->` добавьте:
   ```html
   <!-- Photographer: newphotographer -->
   <div class="gallery-list row">
       <!-- Копируйте структуру из других секций, замените класс на newphotographer и пути на images/photos/NewPhotographer/ -->
   </div>
   ```

6. **Проверьте регистр**: Убедитесь, что пути к изображениям соответствуют реальным файлам (учитывайте регистр на GitHub Pages).
 
