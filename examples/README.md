# Примеры XML-сообщений ISO 20022 и UML-диаграммы

Каталог содержит наборы XML-сообщений ISO 20022 и UML-диаграммы по ключевым сценариям, которые описывают процесс взаимодействия Участников с TKEY7 для клиринга и расчётов по международным платежам.

## Сценарии приминения

* Каталог [`/examples/settlement-method-TDSO/`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/settlement-method-TDSO) — Примеры XML-сообщений ISO 20022 и UML-диаграммы, связанные с операциями по расчётным инструментам группы [ЦРО](https://developer.tkey7.com/ru/docs-glossary/digital-settlement-obligation-dso).

* Каталог [`/examples/settlement-method-TDSA/`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/settlement-method-TDSA) — Примеры XML-сообщений ISO 20022 и UML-диаграммы, связанные с операциями по расчётным инструментам группы [ЦРА](https://developer.tkey7.com/ru/docs-glossary/digital-settlement-asset-dsa).

## Примеры XML-сообщений ISO 20022 — ЦРО

### payment-dso
Подкаталог [`/payment-dso`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/settlement-method-TDSO/payment-dso) содержит набор сообщений, применяемый в процессе платёжа с помощью ЦРО.

> [Подробнее об использовании сообщений в этом сценарии.](https://developer.tkey7.com/ru/docs-scenarios/payment-dso)

### return-dso-after-payment-dso-after-payment-dso
Подкаталог [`/return-dso-after-payment-dso-after-payment-dso`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/settlement-method-TDSO/return-dso-after-payment-dso-after-payment-dso) содержит набор сообщений, применяемый в процессе возврата ЦРО.

> [Подробнее об использовании сообщений в этом сценарии.](https://developer.tkey7.com/ru/docs-scenarios/return-dso/)

### debtor-cancel-payment-dso-agree
Подкаталог [`/debtor-cancel-payment-dso-agree`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/settlement-method-TDSO/debtor-cancel-payment-dso-agree) содержит набор сообщений, применяемый в процессе отмены платежа с помощью ЦРО — сценарий № 1.

> [Подробнее об использовании сообщений в этом сценарии.](https://developer.tkey7.com/ru/docs-scenarios/cancel-dso-1)

### debtor-cancel-payment-dso-reject
Подкаталог [`/debtor-cancel-payment-dso-reject`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/settlement-method-TDSO/debtor-cancel-payment-dso-reject) содержит набор сообщений, применяемый в процессе отмены платежа с помощью ЦРО — сценарий № 2.

> [Подробнее об использовании сообщений в этом сценарии.](https://developer.tkey7.com/ru/docs-scenarios/cancel-dso-2)

### creditor-cancel-payment-dso
Подкаталог [`/creditor-cancel-payment-dso`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/settlement-method-TDSO/creditor-cancel-payment-dso) содержит набор сообщений, применяемый в процессе отмены платежа с помощью ЦРО — сценарий № 3.

> [Подробнее об использовании сообщений в этом сценарии.](https://developer.tkey7.com/ru/docs-scenarios/cancel-dso-3)

### modify-payment-dso
Подкаталог [`/modify-payment-dso`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/settlement-method-TDSO/modify-payment-dso) содержит набор сообщений, применяемый в процессе изменения платежа с помощью ЦРО.

> [Подробнее об использовании сообщений в этом сценарии.](https://developer.tkey7.com/ru/docs-scenarios/modify-payment-dso)

## Примеры XML-сообщений ISO 20022 ЦРА

### payment-dsa
Подкаталог [`/payment-dsa`](https://developer.tkey7.com/ru/docs-glossary/digital-settlement-asset-dsa/payment-dsa) содержит набор сообщений, применяемый в процессе платёжа с помощью ЦРА.

> [Подробнее об использовании сообщений в этом сценарии.](https://developer.tkey7.com/ru/docs-scenarios/payment-dsa)

### redeem-dsa
Подкаталог [`/redeem-dsa`](https://developer.tkey7.com/ru/docs-glossary/digital-settlement-asset-dsa/redeem-dsa) содержит набор сообщений, применяемый в процессе выкупа ЦРА.

> [Подробнее об использовании сообщений в этом сценарии.](https://developer.tkey7.com/ru/docs-scenarios/redeem-dsa)

### debtor-cancel-payment-dsa-agree
Подкаталог [`/debtor-cancel-payment-dsa-agree`](https://developer.tkey7.com/ru/docs-glossary/digital-settlement-asset-dsa/debtor-cancel-payment-dsa-agree) содержит набор сообщений, применяемый в процессе отмены платежа ЦРА — сценарий № 1

> [Подробнее об использовании сообщений в этом сценарии.](https://developer.tkey7.com/ru/docs-scenarios/cancel-dsa-1)

### debtor-cancel-payment-dsa-reject
Подкаталог [`/debtor-cancel-payment-dsa-reject`](https://developer.tkey7.com/ru/docs-glossary/digital-settlement-asset-dsa/debtor-cancel-payment-dsa-reject) содержит набор сообщений, применяемый в процессе отмены платежа с помощью ЦРА — сценарий № 2

> [Подробнее об использовании сообщений в этом сценарии.](https://developer.tkey7.com/ru/docs-scenarios/cancel-dsa-2)

### creditor-cancel-payment-dsa
Подкаталог [`/creditor-cancel-payment-dsa`](https://developer.tkey7.com/ru/docs-glossary/digital-settlement-asset-dsa/creditor-cancel-payment-dsa) содержит набор сообщений, применяемый в процессе отмены платежа с помощью ЦРА — сценарий № 3.

> [Подробнее об использовании сообщений в этом сценарии.](https://developer.tkey7.com/ru/docs-scenarios/cancel-dsa-3)

### modify-payment-dsa
Подкаталог [`/modify-payment-dsa`](https://developer.tkey7.com/ru/docs-glossary/digital-settlement-asset-dsa/modify-payment-dsa) содержит набор сообщений, применяемый в процессе изменения платежа с помощью ЦРА.

> [Подробнее об использовании сообщений в этом сценарии.](https://developer.tkey7.com/ru/docs-scenarios/modify-payment-dsa)

## UML-диаграммы

Каталог содержит UML-диаграммы, представленные в формате `.jpg`, которые являются дополнением к примерам XML-сообщений ISO 20022.

### Платёж с помощью ЦРО — payment-dso

* Диаграмма [`payment-dso.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/settlement-method-TDSO/payment-dso/payment-dso.jpg) демонстрирует ситуацию создания платежа Финансовым учреждением-отправителем от имени Плательщика Финансовому учреждению-получателю от имени конечного Бенефициара с помощью расчётного метода ЦРО, в рамках которого два Участника принимают условия сделки и обязательство по последующему расчёту, и проводят идентификацию Плательщика и конечного Бенефициара в соответствии с действующими комплаенс-требованиями.

### Возврат ЦРО — return-dso-after-payment-dso

* Диаграмма [`return-dso-after-payment-dso.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/settlement-method-TDSO/return-dso-after-payment-dso/return-dso-after-payment-dso.jpg) демонстрирует ситуацию возврата ЦРО по ранее совершённому платежу.

### Отмена платежа ЦРО (сценарий № 1) — debtor-cancel-payment-dso-agree

* Диаграмма [`debtor-cancel-payment-dso-agree.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/settlement-method-TDSO/debtor-cancel-payment-dso-agree/debtor-cancel-payment-dso-agree.jpg) демонстрирует ситуацию отмены платежа по инициативе Финансового учреждения-отправителя.

### Отмена платежа ЦРО (сценарий № 2) — debtor-cancel-payment-dso-reject

* Диаграмма [`debtor-cancel-payment-dso-reject.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/settlement-method-TDSO/debtor-cancel-payment-dso-reject/debtor-cancel-payment-dso-reject.jpg) демонстрирует ситуацию, в которой Финансовое учреждение-отправитель запрашивает отмену платежа у Финансового учреждения-получателя. 

### Отмена платежа ЦРО (сценарий № 3) — creditor-cancel-payment-dso

* Диаграмма [`creditor-cancel-payment-dso.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/settlement-method-TDSO/creditor-cancel-payment-dso/creditor-cancel-payment-dso.jpg) демонстрирует ситуацию отмены платежа по инициативе Финансового учреждения-получателя.

### Изменение платежа ЦРО — modify-payment-dso

* Диаграмма [`modify-payment-dso.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/settlement-method-TDSO/modify-payment-dso/modify-payment-dso.jpg) демонстрирует ситуацию изменения местоположения платежа и последующую доставку до конечного Бенефициара.

### Платёж с помощью ЦРА — payment-dsa

* Диаграмма [`payment-dsa.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/settlement-method-TDSA/payment-dsa/payment-dsa.jpg) демонстрирует ситуацию создания платежа с одновременным клирингом и расчётом в реальном времени. Финансовое учреждение-отправитель инструктирует платёж от имени Плательщика Финансовому учреждению-получателю от имени конечного Бенефициара, в рамках которого Участники принимают условия сделки, проводят идентификацию Плательщика и конечного Бенефициара в соответствии с действующими комплаенс-требованиями.

### Выкуп ЦРА — redeem-dsa

* Диаграмма [`redeem-dsa.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/settlement-method-TDSA/redeem-dsa/redeem-dsa.jpg) демонстрирует ситуацию, в которой Финансовое учреждение запрашивает выкуп ЦРА у Токенизатора, после чего Токенизатор инструктирует перевод безналичных средств на банковский счёт Участника вне TKEY7.

### Отмена платежа ЦРА (сценарий № 1) — debtor-cancel-payment-dsa-agree

* Диаграмма [`debtor-cancel-payment-dsa-agree.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/settlement-method-TDSA/debtor-cancel-payment-dsa-agree/debtor-cancel-payment-dsa-agree.jpg) демонстрирует ситуацию отмены платежа по инициативе Финансового учреждения-отправителя.

### Отмена платежа ЦРА (сценарий № 2) — debtor-cancel-payment-dsa-reject

* Диаграмма [`debtor-cancel-payment-dsa-reject.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/settlement-method-TDSA/debtor-cancel-payment-dsa-reject/debtor-cancel-payment-dsa-reject.jpg) демонстрирует ситуацию, в которой Финансовое учреждение-отправитель запрашивает отмену платежа у Финансового учреждения-получателя.

### Отмена платежа ЦРА (сценарий № 3) — creditor-cancel-payment-dsa

* Диаграмма [`creditor-cancel-payment-dsa.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/settlement-method-TDSA/creditor-cancel-payment-dsa/creditor-cancel-payment-dsa.jpg) демонстрирует ситуацию отмены платежа по инициативе Финансового учреждения-получателя.

### Изменение платежа ЦРА — modify-payment-dsa

* Диаграмма [`modify-payment-dsa.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/settlement-method-TDSA/modify-payment-dsa/modify-payment-dsa.jpg) демонстрирует ситуацию отмены платежа по инициативе Финансового учреждения-получателя.

# Документация

Подробная информация о ключевых сценариях, которые описывают процесс взаимодействия Участников с TKEY7 для клиринга и расчётов по международным платежам — доступна в [официальной документации](https://developer.tkey7.com/ru/docs-scenarios-introduction). Сценарии содержат шаги с подробными инструкциями, UML-диаграммы и примеры финансовых сообщений ISO 20022.