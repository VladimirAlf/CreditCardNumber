# Отчёт о тестировании Прием платежей с банковских карт организациями


## Краткое описание

12.07.21. - 12.07.21. было проведено функциональное тестирование приложения Прием платежей с банковских карт организациями.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Не проходит валидацию номер карты Visa не равный 16 цифрам](https://github.com/VladimirAlf/CreditCardNumber/issues/1)
* [Не проходят валидацию номера карт American Express (AMEX)](https://github.com/VladimirAlf/CreditCardNumber/issues/2)
* [Не проходят валидацию номера карт Diners Club - Carte Blanche](https://github.com/VladimirAlf/CreditCardNumber/issues/3)
* [Не проходит валидацию номер карты Discover не равный 16 цифрам](https://github.com/VladimirAlf/CreditCardNumber/issues/4)
* [Не проходит валидацию номер карты JCB не равный 16 цифрам](https://github.com/VladimirAlf/CreditCardNumber/issues/5)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Код](https://github.com/VladimirAlf/CreditCardNumber/commit/7b9ce2995fa0a11b00bad053f4c1a7c377379017#diff-1597d2955516e4d404c9395c883d26475c58b27032926237f062392226c69fe9)



В качестве тестовых данных использовались данные:
* [Сайт](https://www.freeformatter.com/credit-card-number-generator-validator.html) генерации валидных номеров карт.


Тестирование производилось в следующем окружении:
* Windows 10 Home, 64-разрядная ОС
* OpenJDK11U-jdk_x64_windows_hotspot_11.0.11_9
* Intellij IDEA Community Edition 2021.1.3