# Задание лабораторной работы

Организовать сетевой доступ:
1) из машины А в машину Б,
2) из машины А в машину В,
3) но запретить доступ из машины Б в машину В,

## Ход решения
1) Создаем виртуальные машины и соединяем их в одну сеть:
   
   ![image](https://github.com/user-attachments/assets/0c583a5e-c15b-4266-8a14-7fd6e52eaafe)

   ![image](https://github.com/user-attachments/assets/28f766b9-2072-4b2e-923e-18106e212bba)

   ![image](https://github.com/user-attachments/assets/420a1e06-5c28-4d89-bbce-f58c805afca9)

   ![image](https://github.com/user-attachments/assets/fb815bf6-a02a-4d99-afb4-4803eada5b3f)

2) Разрешаем использование ssh каждой машине:

   ![разрешаем ssh для vm1 ](https://github.com/user-attachments/assets/23ef233f-5477-4987-b609-43934966161a)

   ![разрешаем ssh для vm2](https://github.com/user-attachments/assets/0a4c9af6-8bad-440d-a598-2895e5156625)

   ![Разрешаем ssh дял vm3 ](https://github.com/user-attachments/assets/61cd9fac-4970-4b98-a5cb-a23b39d197ff)

3) Узнаем ip каждой системы:

   ![узнаем ip для vm1 ](https://github.com/user-attachments/assets/43e55124-1523-49d7-984c-2d605726babd)

   ![узнаем ip для vm2 ](https://github.com/user-attachments/assets/94b1fc93-cf77-42ff-ae28-e4d96f665c93)

   ![узнаем ip для vm 3 ](https://github.com/user-attachments/assets/b9edb0bc-cd82-443a-87ce-87503afba4b5)

4) Подключаем 1ю виртуальную машину ко 2й:

   ![1 в 2](https://github.com/user-attachments/assets/8056800e-9627-4010-9770-c0c6511ec9af)

5) Подключаем 1ю и 2ю виртуальные машины к 3й:

   ![Снимок экрана (391)](https://github.com/user-attachments/assets/06c8388e-54e8-48cd-bc78-53bf4fb83efd)

6) Включаем фаервол в 3й виртуальной машине:

   ![Подключаем фаервол в vm3 для всех машин ](https://github.com/user-attachments/assets/8d20f944-ee6b-475f-bc29-80fbc8360d94)

7) Проверяем права на подключение в 3ю систему:

   ![Проверяем права на подключение в vm3 ](https://github.com/user-attachments/assets/f3e17843-206e-4943-bc56-6b6afe4caabc)

8) Настраиваем права на подключение в 3ю виртуальную машину:

   ![Настраиваем права доступа в vm3](https://github.com/user-attachments/assets/4c4c2842-6859-4ad3-9957-62b90aa2f986)

9) Разрешаем доступ из 1й виртуальной машины к 3й:

    ![Разрешаем доступ из vm1 в vm3 ](https://github.com/user-attachments/assets/2df4ee57-1034-490e-8e84-a4f3512f1a22)

10) Задание выполнено!











