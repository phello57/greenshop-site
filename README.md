Ссылка: https://phello57.github.io/greenshop2.github.io/
<br> Макет: https://www.figma.com/file/GDInt7mjgpSp3YUE2cgxN0/GreenShop?node-id=0%3A1
<br>
Мой макет, логику которого, все кнопки и фильтрации я сделал сам, основываясь на шаблоне классов, который я взял в интернете. 
<br>
## Что работает и код
### 1. Меню
![Диаграмма без названия drawio (2)](https://user-images.githubusercontent.com/103268341/199113426-c27da146-6af4-4f83-be79-8dfc015be6ce.png)
### 2. Слайдер
![Диаграмма без названия drawio (3)](https://user-images.githubusercontent.com/103268341/199113440-1a970795-3c04-40d3-a37b-8308e77c79ac.png)
### 3. Блок с товарами
![Диаграмма без названия drawio (4)](https://user-images.githubusercontent.com/103268341/199114952-07df80a8-32c3-49fc-899c-b8de9799e769.png)
### 3.1 Нажатие на кнопку ![Screenshot_1](https://user-images.githubusercontent.com/103268341/199177840-6ecd776a-a12a-4124-a3db-1c373e7b6723.png)
формирует новую страницу с этим объектом. Каждый товар имеет свою страницу
![Screenshot_2](https://user-images.githubusercontent.com/103268341/199116097-75602fc4-6fa8-460c-ad43-87dda12d5410.png)

### 4.
При нажатии на иконку корзины на товаре
<br>
![image](https://user-images.githubusercontent.com/103268341/214679771-d0f73092-4dfb-409d-87c6-90e6d0d06a69.png)
<br>
Товар добавляется в корзину
*Лайк с анимацией 

Пока отображается только число в корзине, сама корзина не работает

## Код 
Все товары лежат в 1 файле в таком виде:<br>
![image](https://user-images.githubusercontent.com/103268341/214681898-b4cc8d82-90c4-4c96-b3f4-13beeaeda3fa.png)<br>
<br>
Я все написал в процедурном стиле

Класс HTMLService занимается только отрисовкой.
![image](https://user-images.githubusercontent.com/103268341/214683045-58370a88-66be-4e5a-b761-d9978f8edc28.png)


Класс ProductService занимается поиском товаров, смотря что нужно сделать и как
![image](https://user-images.githubusercontent.com/103268341/214682865-254134d6-b92a-45df-92c6-432927e70099.png)

