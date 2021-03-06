1. **Создать README.md**;
    * У каждого проекта размещенного на github должно быть readme.md;
    * Readme должно содержать название проекта;
    * Readme должно содержать всю необходимую информацию для развертывания(установки) проекта и запуска/тестирования, обязательно самим протестировать с нуля разворачивание в новой папке;
    * В проекте должно быть использовано по минимуму глобальных библиотек, все они должны быть перечислены в Readme (webpack, karma и все, что может быть поставлено через npm точно не должно быть глобальным);
    * Если из названия проекта не ясно его предназначение, то стоит внести его краткое описание;
    * Если в проекте используются нестандартные библиотеки или архитектурные подходы, то их тоже нужно указывать. Причем желательно указывать ссылки на их репозитории, чтобы человеку поставленному на этот проект, но не работавшему с используемыми технологиями, не нужно было искать их в гугле;
    * Если проект из репозитория уже где-то развернут (например, на github pages), то следует указать на него ссылку; 

2. **Спросить на входе под какие браузеры верстаем (Обязательно)**;

3. **Спросить есть ли адаптив, если нет, то под какие разрешения верстать и что делать для других экранов**;

4. **Запускать сайт через http://localhost, а не через file:///c:\test.html**;
  > Иначе могут быть проблемы с элементами, вставляемыми через iframe, например лайки от фб, вк и тд и при работе скриптов, которые отправляют HTTP-запросы, плюс еще могут быть вообще неожиданные и неизвестные нам проблемы
5. **Заранее четко узнать, что является фиксированным результатом проекта - развернутое на нашем сервере production-окружение или только git-репозиторий, а то и zip-архив, отправленный по почте, это всегда надо узнавать на входе**;

6. **Всегда помните: если вы можете решить проблемы каким-то способом, это не значит, что способ действительно стоит применять**;
  > И в верстке, и в программировании часто возникают ситуации, когда можно написать вполне рабочий код - но сделать это ненадежным способом, либо используя откровенные хаки, неочевидные другим разработчикам, либо просто оформив все некрасивым способом. Если перед вами появилась проблема, то нужно не только решить ее, но и сделать решение читабельным, масштабируемым и надежным. Во всех случаях, когда появляются сомнения, лучше спросить более опытных товарищей - это и вам позволит быстрее вырасти, и проекту получить более качественный код.
