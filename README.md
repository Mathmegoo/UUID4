# Test-Task
Это тестовое задание для BeBrainee

Полностью, тестовое задание я выполнить не смог, но сделал небольшое приложение для определения моего уровня.В проект реализованы регистрация пользователей, аунтетицикацию пользователей и вывод всех пользователей: для админов - все пользователи, для юзеров - неудаленные пользователи. 

Инструкция по запуску приложения:
  1) создать венв, установить зависимости.
  2) запустить файл server.py - Этот файл запускает локальный сервер, на котором располагается приложение. адресс по дефолту - 127.0.0.1:8000. Можно поменять в самом низу этого же файла.
  3) зайти в браузере на локальный хост, в путь '/' - вас перекинет на страничку входа. 
  4) если вы используете предоставленную мною бд - просто залогиньтесь с логином 'nikita@user.com' и паролем 'password1' - это администратор. Так же вы можете создать своего пользователя, перейдя по адресу '/reg' - откроется форма регистрации пользователей. Это я такой seed базы сделал. Чтобы было веселее.
  5) вам вылезет приветственное сообщение - обновите страницу - вас пустит в корень пути, на основную страницу. На ней вы видите все как видят это пользователи. Там вы увидите всех *видимых* пользователей - что это такое, вам станет ясно, когда посмотрите код. если вы хотите знать сейчас - это, коротко говоря, *не удаленные пользователи*. Изначально  вы будете видеть всех пользователей.
  6) Вы зашли как администратор, помните? это значит, что вы можете управлять состоянием остальных пользователей. Для этого зайдите на страничку "/admin" Если вы зашли с моего пользователя, "nikita@user.com" вас пустит в админку. Если вы зашли с любого другого созданного мной пользователя - не пустит. Если вы создали своего - вас так же пустит, тк. по умолчанию для вашего удобства все новые пользователи - админы. Для того, чтобы это изменить, откройте файл reg.html и прочитайте комментарии к форме.
  7) Из админ панели вы можете изменять состояние других пользователей, даже самого себя (не баг, а фича) - делать админом, делать простым смертным, удалять и восстанавливать. Удаленные пользователи не отображаются другим пользователям. Проверить можно так же зайдя на страничку по адресу '/', или залогиниться под другого созданного мной пользователя - все логины/пароли посмотрите, пожалуйста, в базе данных.
   
  

  
