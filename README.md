# Отчёт о тестировании 1.1 Credit Card Number Validator

## Краткое описание

19.07.2021 было проведено функциональное тестирование валидации номера банковской карты 
На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* https://github.com/lizadegt/JAVA-1.1-Credit-Card-Number-Validator/issues/1#issue-947765712
* https://github.com/lizadegt/JAVA-1.1-Credit-Card-Number-Validator/issues/2#issue-947767569
* https://github.com/lizadegt/JAVA-1.1-Credit-Card-Number-Validator/issues/3#issue-947769354

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Сервис по генерированию валидных номеров карт - freeformatter.com


### В качестве тестовых данных использовались данные с сервиса по генерированию валидных номеров карт - freeformatter.com:

VISA:
4929078242640775
4485050621938460038 

Discover:
6011534170157830
6011664406513309390 

Diners Club - Carte Blanche:
30570244622904 

Visa Electron:
4844204408105351

MasterCard:
5370019311790365

JCB:
3536012058712045
3536841152031642269 

Diners Club - International:
36200355660840 

InstaPayment:
6373997381750366

American Express (AMEX):
371181748031084 

Diners Club - North America:
5570555524773704

Maestro:
5020711913862527

### Тестирование производилось в следующем окружении:
* Windows 10 x64
* Версия Java - version "11.0.11" 2021-04-20
