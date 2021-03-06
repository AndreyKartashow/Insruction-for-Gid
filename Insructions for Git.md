# Инструкция по работе с Git в VS Code
  ![Это логотип Git](git.jpg)
## Проверка работы git в VS Code 
Перед началом  работы с git в VS Code, необходимо выполнить следующие действия: 
1. Активировать _Terminal_ (Terminale-New Terminale);
2. ввести в _Terminal_ команду "git version" (в _Terminale_ отобразиться рабочая версия);
3. ввести в _Terminal_ команду "git status" (в _Terminale_ отобразиться текущее состояние).

## Активация учетной записи, создание файла и репозитория в git 
1. Активировать учетную запись командами в консоли "git config --global user.name_Ваше имя англ. буквами" и "git config --global user.email_Ваша почта";
2. создать папку нашего репозитория (File-Open folder-Created folder);
3. в меню "Explorer" появиться наш репозиторий по имени, которым мы его назвали. Далее, создаем новый файл в нашем репозитории (New file), задаем ему название и разрешение.

## Сохранение файла и создание первого коммита 
После создания файла необходимо совершить фиксацию версии (создать первый коммит), для этого необходимо выполнить следующие действия:
1. Сохраняем наш файл командой горячих клавиш "Ctrl+s";
2. Далее, в _Terminale_ вводим команду "git add_название файла" (для ввода имени файла достаточно ввести первые буквы название файла и произвести табуляцию клавишей "Tab") и поддтверждаем ее нажатием клавиши "Enter";
3. Вводим в _Terminale_ команду "git commit --m "Ваш комментарий"", подтвержаем команду нажатием клавиши "Enter".

 ## Работа с коммитами
 При необходимости перехода из одного коммита в другой (переход между версиями) нужно использовать следующие команды:
* "git log" - отображение всех коммитов за жизненый период файла;
* "git diff" - разница между текущим и крайним коммитом; 
* "git checkout "имя коммита"" - переход к необходимому коммиту.

## Работа с ветками
Ветки позволяют делить файл на разные подфайлы (подуровни), в которых можно решать отдельные задачи, а затем их переносить в отдельный  файл. 
![Это представление ветки](git_branch.png)
Для того чтобы работать с ветками, необходимо знать такие команды, как:
* "git branch "Название_ветки"" - сздание новой ветки;
* "git merge "Название_ветки"" - слияние веток;
* "git branch --d "Название_ветки"" - удаление ветки;
* "git checkout "Название_ветки""- переход на другую ветку;
* "git log --graph" - отображение коммитов на разных ветвлениях.

version 1.1.1
