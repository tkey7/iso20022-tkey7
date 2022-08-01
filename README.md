[![TKEY7 Instant Payment System](https://github.com/tkey7/.github/blob/main/images/iso20022-tkey7-repo.jpg)](https://tkey7.com/ru)

<p align="center">
  ·
  <a href="https://developer.tkey7.com/ru/docs-introduction">Документация TKEY7</a>
  ·
  <a href="https://developer.tkey7.com/ru/api-introduction">API документация</a>
  ·
  <br>
  <br>
</p>

# Финансовые сообщения ISO 20022

Финансовые сообщения для Участников, применяемые в автоматизированной системе мгновенных платежей — TKEY7.

TKEY7 поддерживает общепринятые финансовые сообщения `head.001`, `pacs.002`, `pacs.004`, `pacs.008`, `pacs.009`, `camt.026`, `camt.029`, `camt.030`, `camt.056`, `camt.087`, и также собственные сообщения `tkey.001`, `tkey.002`, разработанные на основании методологии международного стандарта ISO 20022 и с учётом внутренней практики для использования в рамках системы.

# Навигация по репозиторию

Репозиторий содержит шаблоны финансовых XML-сообщений, XML-схемы (XSD), примеры сообщений ISO 20022, которые используются Участниками TKEY7, и также UML-диаграммы по ключевым бизнес-процессам.

## XML-схемы сообщений ISO 20022 — XSD

Каталог [`/xsd`](https://github.com/tkey7/iso20022-tkey7/tree/main/xsd) — Определение XML-схемы для сообщений, используемых в TKEY7.

>Для Участников TKEY7 подготовлен конфигурационный XSD-файл `tkeysettlement.xsd` для чтения, проверки и создания XML-сообщений. Необходимо изменить значение `/path/to` в атрибуте `schemaLocation` в соответствии с каталогом серверной системы Участника, где расположены XSD-файлы.

* [head.001.001.03](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/head.001.001.03.xsd)
* [tkey.001.001.01](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/tkey.001.001.01.xsd)
* [tkey.002.001.01](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/tkey.002.001.01.xsd)
* [pacs.002.001.11](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/pacs.002.001.11.xsd)
* [pacs.004.001.10](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/pacs.004.001.10.xsd)
* [pacs.008.001.09](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/pacs.008.001.09.xsd)
* [pacs.009.001.09](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/pacs.009.001.09.xsd)
* [camt.026.001.09](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/camt.026.001.09.xsd)
* [camt.029.001.11](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/camt.029.001.11.xsd)
* [camt.030.001.05](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/camt.030.001.05.xsd)
* [camt.056.001.10](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/camt.056.001.10.xsd)
* [camt.087.001.08](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/camt.087.001.08.xsd)
* [tkeysettlement](https://github.com/tkey7/iso20022-tkey7/blob/main/xsd/tkeysettlement.xsd)

## Шаблоны XML-сообщений ISO 20022

Каталог [`/templates/ru/`](https://github.com/tkey7/iso20022-tkey7/tree/main/templates/ru) — Шаблоны XML-сообщений ISO 20022, используемые в системе TKEY7.

> Шаблоны включает в себя комментарии на русском языке.

* [tkey.001.001.01](https://github.com/tkey7/iso20022-tkey7/blob/main/templates/ru/tkey.001.001.01.xml)
* [tkey.002.001.01](https://github.com/tkey7/iso20022-tkey7/blob/main/templates/ru/tkey.002.001.01.xml)
* [pacs.002.001.11](https://github.com/tkey7/iso20022-tkey7/blob/main/templates/ru/pacs.002.001.11_02.xml)
* [pacs.004.001.10](https://github.com/tkey7/iso20022-tkey7/blob/main/templates/ru/pacs.004.001.10.xml)
* [pacs.008.001.09](https://github.com/tkey7/iso20022-tkey7/blob/main/templates/ru/pacs.008.001.09.xml)
* [pacs.009.001.09](https://github.com/tkey7/iso20022-tkey7/blob/main/templates/ru/pacs.009.001.09.xml)
* [camt.026.001.09](https://github.com/tkey7/iso20022-tkey7/blob/main/templates/ru/camt.026.001.09.xml)
* [camt.029.001.11](https://github.com/tkey7/iso20022-tkey7/blob/main/templates/ru/camt.029.001.11.xml)
* [camt.056.001.10](https://github.com/tkey7/iso20022-tkey7/blob/main/templates/ru/camt.056.001.10.xml)
* [camt.087.001.08](https://github.com/tkey7/iso20022-tkey7/blob/main/templates/ru/camt.087.001.08.xml)

## Примеры XML-сообщений ISO 20022 и UML-диаграммы

Примеры XML-сообщений ISO 20022 и UML-диаграммы по ключевым сценариям, которые описывают процесс взаимодействия Участников с TKEY7 для клиринга и расчётов по международным платежам.

Каталог [`/examples/settlement-method-TDSO/`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/settlement-method-TDSO) — Примеры XML-сообщений ISO 20022 и UML-диаграммы, связанные с операциями по расчётным инструментам группы [ЦРО](https://developer.tkey7.com/ru/docs-glossary/digital-settlement-obligation-dso).

Каталог [`/examples/settlement-method-TDSA/`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/settlement-method-TDSA) — Примеры XML-сообщений ISO 20022 и UML-диаграммы, связанные с операциями по расчётным инструментам группы [ЦРА](https://developer.tkey7.com/ru/docs-glossary/digital-settlement-asset-dsa).

# Дерево каталогов

```
└── iso20022-tkey7
    ├── README.md
    ├── examples
    │   ├── README.md
    │   ├── settlement-method-TDSA
    │   │   ├── creditor-cancel-payment-dsa
    │   │   │   ├── camt.026.001.09.xml
    │   │   │   ├── camt.056.001.10.xml
    │   │   │   ├── creditor-cancel-payment-dsa.jpg
    │   │   │   └── pacs.004.001.10.xml
    │   │   ├── debtor-cancel-payment-dsa-agree
    │   │   │   ├── camt.056.001.10.xml
    │   │   │   ├── debtor-cancel-payment-dsa-agree.jpg
    │   │   │   └── pacs.004.001.10.xml
    │   │   ├── debtor-cancel-payment-dsa-reject
    │   │   │   ├── camt.029.001.11.xml
    │   │   │   ├── camt.056.001.10.xml
    │   │   │   └── debtor-cancel-payment-dsa-reject.jpg
    │   │   ├── modify-payment-dsa
    │   │   │   ├── camt.026.001.09.xml
    │   │   │   ├── camt.087.001.08.xml
    │   │   │   └── modify-payment-dsa.jpg
    │   │   ├── payment-dsa
    │   │   │   ├── pacs.002.001.11.xml
    │   │   │   ├── pacs.008.001.09.xml
    │   │   │   ├── payment-dsa.jpg
    │   │   │   └── tkey.001.001.01.xml
    │   │   └── redeem-dsa
    │   │       ├── pacs.002.001.11.xml
    │   │       ├── pacs.009.001.09.xml
    │   │       └── redeem-dsa.jpg
    │   └── settlement-method-TDSO
    │       ├── creditor-cancel-payment-dso
    │       │   ├── camt.026.001.09.xml
    │       │   ├── camt.056.001.10.xml
    │       │   ├── creditor-cancel-payment-dso.jpg
    │       │   └── pacs.004.001.10.xml
    │       ├── debtor-cancel-payment-dso-agree
    │       │   ├── camt.056.001.10.xml
    │       │   ├── debtor-cancel-payment-dso-agree.jpg
    │       │   └── pacs.004.001.10.xml
    │       ├── debtor-cancel-payment-dso-reject
    │       │   ├── camt.029.001.11.xml
    │       │   ├── camt.056.001.10.xml
    │       │   └── debtor-cancel-payment-dso-reject.jpg
    │       ├── modify-payment-dso
    │       │   ├── camt.026.001.09.xml
    │       │   ├── camt.087.001.08.xml
    │       │   └── modify-payment-dso.jpg
    │       ├── payment-dso
    │       │   ├── pacs.002.001.11.xml
    │       │   ├── pacs.008.001.09.xml
    │       │   ├── payment-dso.jpg
    │       │   └── tkey.001.001.01.xml
    │       └── return-dso-after-payment-dso
    │           ├── pacs.004.001.10.xml
    │           ├── return-dso-after-payment-dso.jpg
    │           └── tkey.002.001.01.xml
    ├── templates
    │   └── ru
    │       ├── README.md
    │       ├── camt.026.001.09.xml
    │       ├── camt.029.001.11.xml
    │       ├── camt.056.001.10.xml
    │       ├── camt.087.001.08.xml
    │       ├── pacs.002.001.11_02.xml
    │       ├── pacs.004.001.10.xml
    │       ├── pacs.008.001.09.xml
    │       ├── pacs.009.001.09.xml
    │       ├── tkey.001.001.01.xml
    │       └── tkey.002.001.01.xml
    └── xsd
        ├── camt.026.001.09.xsd
        ├── camt.029.001.11.xsd
        ├── camt.030.001.05.xsd
        ├── camt.056.001.10.xsd
        ├── camt.087.001.08.xsd
        ├── head.001.001.03.xsd
        ├── pacs.002.001.11.xsd
        ├── pacs.004.001.10.xsd
        ├── pacs.008.001.09.xsd
        ├── pacs.009.001.09.xsd
        ├── tkey.001.001.01.xsd
        ├── tkey.002.001.01.xsd
        └── tkeysettlement.xsd
```
# Документация

Подробная информация о системе TKEY7 доступна на [портале разработчика](https://developer.tkey7.com/ru/).

# Лицензия

Лицензия Apache License 2.0 — [подробнее о лицензии](https://github.com/tkey7/iso20022-tkey7/blob/main/LICENSE).