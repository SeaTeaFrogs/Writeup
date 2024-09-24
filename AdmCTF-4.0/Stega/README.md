![image](https://github.com/user-attachments/assets/6ad6cb98-3bc4-4f7a-af9d-437cb534d363)

1. Fabric

достаём thumbnail и читаем флаг. Достать можно через exiftool или онлайн сервисами

2. Best Fantasy

Один пробел - 0, два пробела - 1. from binary to text

3. Абстракция

Получаем rgb значения всех пикселей по главной диагонали, переводим в ascii, декодим base64

4. Хаха

Чётные байты записываем в один PNG файл, нечётные - во второй, открываем и видим две половинки флага

5. Mirror

steghide с паролем, брутится по rockyou (например, утилитой stegseek)
