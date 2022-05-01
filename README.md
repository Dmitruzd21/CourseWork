**ТЕСТИРОВАНИЕ САЙТА КРУПНОЙ КОМПАНИИ**

**Требования/документация:**
https://github.com/netology-code/iqa-diplom/blob/main/README.md

**Чек - лист:**

Чек-лист для функциональной проверки личного кабинета зарегистированного авторизованного пользователя (включая функционал разделов) на сайте https://henderson.ru/.

https://docs.google.com/spreadsheets/d/1B2ciMi7FvBX1zQIpWhAw92t60Gvjkihaf9QgBuN0LBQ/edit?usp=sharing

**Тест - кейсы**

Набор тест-кейсов на проверку функционала восстановления пароля:

https://docs.google.com/spreadsheets/d/1sa1DskVUmJDRs1G8hnmCQeuYHoYIG1YAu6Rv664tREg/edit?usp=sharing

**Тестирование требований:**

https://docs.google.com/document/d/1dpw2LH1HNVMBDnk_W7nNGaTnbkceBNuO0Ey2qKA2rdc/edit?usp=sharing

**Баг - репорты:**

https://docs.google.com/spreadsheets/d/19HkS5JdXdkQqt3eT46zTsilUn1_-yH-mE8tCr750Mt0/edit?usp=sharing

https://docs.google.com/spreadsheets/d/1mHA7SRxsr0OCV7r9p_gFMZGJ0J2sFdsFFgQy4E5l5Ng/edit?usp=sharing

**Тестирование верстки**

Тестирование верстки страницы карточки товара с максимальной и минимальной ценой:

1. Один рубль (карточка товара):
   https://drive.google.com/file/d/1f35FS-S3HT8aj1SzpLe5CKrlrj55DlKv/view?usp=sharing

2. Десять млн рублей (карточка товара):
   https://drive.google.com/file/d/19xza8q4Fs1_Z1mMqMQYtVhYJsKnW-C-G/view?usp=sharing

3. Основная страница (1 рубль):
   https://drive.google.com/file/d/1OYEK89rV66MMFsGkJ_8YLKE3d03_dow3/view?usp=sharing

4. Десять млн рублей (основная тсраница):
   https://drive.google.com/file/d/1RYx_iYbFLgzfh9Gd9T-jaU1LfSlyQOJg/view?usp=sharing

**Клиент - сервер**

Проблема: Бекенд разработчик говорит, что мы отправляем данные с сайта в неправильном формате и просит помочь найти нужный запрос.
Известно, что проблема в данных, которые уходят в post запросе по адресу api.mindbox.ru/v3/js/operations/, и происходит это скорее всего при работе с личными данными пользователя (например авторизация, личный кабинет, просмотр корзины).

Решение: изучение ответов и запросов при работе с сайтом. Параметры deviceUUID, requestId и status.

1. Авторизация через почту:
   https://drive.google.com/file/d/11eWaBeDskh6X0lQ2Ngzkd_eD-HMo24sL/view?usp=sharing

2. Авторизация по номеру телефона:
   https://drive.google.com/file/d/1PmmIUFVesfVKZIsLbcZ8OWg179vNpkol/view?usp=sharing

3. Параметры deviceUUID, requestId и status:
   https://drive.google.com/file/d/1nIprm-BZL2qkgpyGyFzx7G5B_E6yDFRR/view?usp=sharing
