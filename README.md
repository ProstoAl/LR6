# LR6
Лабораторная работа №6
1. Клонируем репозиторий на компьютер. 
![image](https://user-images.githubusercontent.com/94538589/142269402-d5dd6fac-4983-470e-9961-14c6f6ccbf4a.png)
2. На сайте GitHub создаем файл file_1 и подтягиваем изменения на локальное устройство.
![image](https://user-images.githubusercontent.com/94538589/142412629-7b1b8940-5e96-4d26-ac53-eda72229f985.png)
3. Получем историю операций для каждой ветки.
![image](https://user-images.githubusercontent.com/94538589/142413165-3a76e8bf-f549-43b7-b330-05e666b28898.png)
4. Смотрим последние изменения. 
![image](https://user-images.githubusercontent.com/94538589/142414011-a626d70f-dadb-4565-95fa-52863b4a9993.png)
5. Смотрим доступные ветки, переходим в одну из них.
![image](https://user-images.githubusercontent.com/94538589/142439771-98fd9d03-4788-4a46-a1ff-4e714135d53e.png)
6. Возвращаемся обратно в ветку master, сливаем ее с выбранной веткой(решая конфликт) и удаляем уже ненужную ветку.
![image](https://user-images.githubusercontent.com/94538589/142440031-31fedaf3-2bcf-4d23-992b-9191bab795e0.png)
![image](https://user-images.githubusercontent.com/94538589/142440081-869ffc66-8bf1-4dc9-9c24-b6483a5c57e2.png)
7. Делаем изменения в файле и коммитим их.
![image](https://user-images.githubusercontent.com/94538589/142452116-8336bb83-fc11-4127-8882-48f63e768b88.png)
8. Делаем "хард" коммит.
![image](https://user-images.githubusercontent.com/94538589/142440617-d8220895-b520-4a09-afae-2705658b938b.png)
9. Создаём ветку для отчёта.
![image](https://user-images.githubusercontent.com/94538589/142440720-5387734c-1ce6-4603-bebf-12ca1e69d669.png)
10. Загружаем ветку в удалённый репозиторий.
![image](https://user-images.githubusercontent.com/94538589/142440887-6a105243-98c6-4a65-9679-a9a3f6dc9969.png)
11. Лог команд
git clone
cd LR6
git pull
git reflog --all
git log -p
git branch -r
git checkout report
git checkout master
git merge report
git branch -d report
git diff
git add file_1
git commit -m "new information"
git reset --hard HEAD
git checkout -b report
git add --all
git commit -m "new information 2"
git push --set-upstream origin report
12. История коммитов
commit 61fc16f2452e5934684d232a5ef54f3bc671d848 (HEAD -> report, origin/report)
Merge: 3c8f3d5 98501fd
Author: Anastaseva V.N. 4016 <anval-22@mail.ru>
Date:   Thu Nov 18 18:28:04 2021 +0300

    Merge branch 'report' of https://github.com/ProstoAl/LR6 into report

commit 3c8f3d5f1302528f3d791319640bb5758c42718a
Author: Anastaseva V.N. 4016 <anval-22@mail.ru>
Date:   Thu Nov 18 18:25:23 2021 +0300

    new information 2

commit 98501fd0ba246df4e53a8535b5feed42656c9535
Author: ProstoAl <94538589+ProstoAl@users.noreply.github.com>
Date:   Thu Nov 18 18:11:36 2021 +0300

    Update README.md

commit 98938ad80625e3e98e0f5b2cb6e6a3fa0d1d2bc9 (master)
Author: Anastaseva V.N. 4016 <anval-22@mail.ru>
Date:   Thu Nov 18 17:38:25 2021 +0300

    new information

commit e74b1fbb5b0c2d479f6d19aab6e42f10f1d8a5ce
Merge: 382c1ef 3e7458d
Author: Anastaseva V.N. 4016 <anval-22@mail.ru>
Date:   Thu Nov 18 16:41:41 2021 +0300

    new informatoin

commit 382c1ef8e93e99182fe6add8a0592ddfc2f9cbed
Author: ProstoAl <94538589+ProstoAl@users.noreply.github.com>
Date:   Thu Nov 18 15:05:44 2021 +0300

    Create file_1

commit e0d8ef1328257dde5bb3f665a484db63e749db96
Author: ProstoAl <94538589+ProstoAl@users.noreply.github.com>
Date:   Wed Nov 17 22:29:34 2021 +0300

    Update README.md




