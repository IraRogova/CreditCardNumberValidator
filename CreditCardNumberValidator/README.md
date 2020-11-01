# Отчёт о тестировании Credit Card Number Validator
## Краткое описание
29/10/2020 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

+ [Проверка карт American Express (AMEX)](https://github.com/IraRogova/CreditCardNumberValidator/issues/1)
+ [Проверка 19-ти значных карт VISA](https://github.com/IraRogova/CreditCardNumberValidator/issues/2)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:

Руководство по установке IntelliJ IDEA

В качестве тестовых данных использовались данные [credit-card-number-generator-validator](https://www.freeformatter.com/credit-card-number-generator-validator.html):

VISA:
+ 4755964528449750
+ 4485092414205693
+ 4539613228475547716

MasterCard:
+ 5257131315627663
+ 2720996994156309
+ 5593805123018958

American Express (AMEX):
+ 371257129640675
+ 370006586847245
+ 346420975035521

Maestro:
+ 5020123385515031
+ 6762617531327183
+ 6762094143719878

Visa Electron:
+ 4917153970899614
+ 4917777650318048
+ 4175000746887521

Тестирование производилось в следующем окружении:

+ Windows10 Домашняя x64
+ Openjdk version "11.0.9" 2020-10-20
+ IntelliJ IDEA Community 2020.2.3 (Community Edition)
