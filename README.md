# LR6
Лабораторная работа №6 Miagkov Roman V1441
> Первое задание Создать аккаунт на сайте GitHub.
>  Далее переходим ко второму заданию делае копию из 'https://github.com/Kurtyanik/LR6/ (Fork)'
Далее устанавливаем Git локально.
# Добавить пользователя
Далее добавляем пользователя GIT c помощью команды  `git config -- global user.name "Roman Miagkov" `
![This is an image](https://raw.githubusercontent.com/RoMiag/LAB-6/master/%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0.png)\
Давайте теперь добавим почту с помощью команды  `git config -- global user. email m_roman93@mail.ru- `
![This is an image](https://raw.githubusercontent.com/RoMiag/LAB-6/master/email.png)
# Клонировать свой личный удалённый репозиторий на компьютер. 
Данное задание мы можешь сделать с помощью команды `git clone https://github.com/RoMiag/LAB-6`
![This is an image](https://raw.githubusercontent.com/RoMiag/LAB-6/master/%D0%9A%D0%BB%D0%BE%D0%BD.png)
# Добавить файл через интерфейс GitHub. Подтянуть изменения в локальный репозиторий. 
Добавли файл Test_file и подтянул его в локальный репрозитеорий
![This is an image](https://raw.githubusercontent.com/RoMiag/LAB-6/master/%D1%84%D0%B0%D0%B9%D0%BB%D1%8B.png)
# Получить историю операций для каждой из веток. 
 Для этого задания вызовим команаду `git status` \
![This is an image](https://raw.githubusercontent.com/RoMiag/LAB-6/master/git_status.png)\
Далее передаем файл под контроль Git. Для этого используется команда `git add`\
Проверьте git status снова\
![This is an image](https://raw.githubusercontent.com/RoMiag/LAB-6/master/%D1%84%D0%B0%D0%B9%D0%BB_%D1%80%D0%B5%D0%B4%D0%BC%D0%B8.png)\
Следующий шаг, который мы должны сделать, передав файл под контроль Git и закончив все изменения в нём – закоммитить их (фиксироватьизменения)\
С помощью команды `gitcommit m` \
![This is an image](https://raw.githubusercontent.com/RoMiag/LAB-6/master/commit.png)\
Для того, чтобы просмотреть историю коммитов, нужно использовать команду `git log` – это лог всех изменений.
![This is an image](https://raw.githubusercontent.com/RoMiag/LAB-6/master/log.png)\
# Сделать откат коммита
`gitresetHEAD` – откат к последнему коммиту (здесь HEAD–указатель натекущий коммит). \
То есть, если что-то пошло не так, то можно отменить все изменения и откатиться к состоянию после последнего коммита.\
`gitreset --hard<commit>` - самая мощная и самая опасная команда – откат к указанному коммиту с потерей всех изменений!
Для примера что-нибудь изменим, а затем откатимся к состояниюпосле коммита. Откройте файл README, замените !!! на ???. Файл test.txt удалим\
![This is an image](https://raw.githubusercontent.com/RoMiag/LAB-6/master/%D0%9E%D1%82%D0%BA%D0%B0%D1%82.png)\
# Создать ветку\
Создать ветку можно с помщью команды `git branch Report`
![This is an image](https://raw.githubusercontent.com/RoMiag/LAB-6/master/report.png)
