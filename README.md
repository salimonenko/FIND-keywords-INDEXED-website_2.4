# FIND-keywords-INDEXED-website_2.4
Fast FUZZY search for keywords across website files. Indexing. Improved version of FIND-keywords-INDEXED-website

In previous versions, indexing was performed by refreshing the search page and waiting for it to finish loading. During this time, the server reported the names of indexed files.
In this version, I used server-side events (SSE). A SINGLE indexing request is made to the server, after which, having indexed each website file, it returns the name of that file and a message indicating its successful indexing.

Быстрый НЕЧЕТКИЙ поиск искомых (ключевых) слов по файлам сайта. Индексирование. Улучшенная версия FIND-keywords-INDEXED-website
В предыдущих версиях индексация осуществлялась путем обновления страницы поиска и ожидания окончания ее загрузки. В это время сервер сообщал имена проиндексированных файлов. 
В этой версии я использовал события сервера (SSE). На сервер делается ОДИН запрос на индексирование, после чего он, проиндексировав очередной файл сайта, возвращает имя этого файла и сообщение об успешности его индексирования. 
