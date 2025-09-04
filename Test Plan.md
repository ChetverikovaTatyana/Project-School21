### <u>Баг-репорт</u> ###

**Краткое описание:** Товар из каталога не добавляется в корзину.

**Подробное описание:** На странице каталога (inventory) не добавляются в корзину 3 товара из 6 представленных. Кнопка "Add to cart" не активна для клика для следующих товаров:

-Sause Labs Bolt T-Shirt

-Sause Labs Fleeece Jacket

-Test.allTheThings() T-Shirt (Red).

**Фактический результат:** Не добавляется товар в корзину.

**Ожидаемый результат:** Кнопка "Add to cart" активна для клика и товар добавляется в корзину.

**Шаги по воспроизведению:**

- Открыть сайт по ссылке [saucedemo](https://www.saucedemo.com/)

- Ввести в поле Username логин (error_user)

- Ввести в поле Password пароль (secret_sauce)

- Нажать кнопку Login.

- На отображаемой странице [inventory](https://www.saucedemo.com/inventory.html) добавить товары (Sause Labs Bolt T-Shirt, Sause Labs Fleeece Jacket, Test.allTheThings() T-Shirt (Red)) в корзину


**Окружение:** Linux 6.8.0-48-generic, Google Chrome 127.0.6533.99

**Важность:** Major

**Срочность:** High

![Скрин](<..misc/image/Не добавляется товар в корзину.png>)