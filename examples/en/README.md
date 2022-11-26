# Examples of ISO 20022 XML Messages and UML Diagrams

The directory contains ISO 20022 XML message sets and UML diagrams for key scenarios of Members’ interaction with TKEY7 for clearing and settling international payments.

## Application Scenarios

Directory [`/examples/en/settlement-method-TDSO/`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSO) are examples of ISO 20022 XML messages and UML diagrams related to operations on settlement instruments of the [DSO](https://developer.tkey7.com/docs-glossary/digital-settlement-obligation-dso) asset group.

Directory [`/examples/en/settlement-method-TDSA/`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSA) are examples of ISO 20022 XML messages and UML diagrams related to operations on settlement instruments of the [DSA](https://developer.tkey7.com/docs-glossary/digital-settlement-obligation-dsa) asset group.

## ISO 20022 XML Message Examples—DSO

### payment-dso

The [`/payment-dso`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSO/payment-dso) subdirectory contains the messages applied in the Payments using the DSO.

> [Learn more about using messages in this scenario](https://developer.tkey7.com/docs-scenarios/payment-dso).

### return-dso-after-payment-dso

The [`/return-dso-after-payment-dso`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSO/return-dso-after-payment-dso) subdirectory contains the messages applied in the DSO Return.

> [Learn more about using messages in this scenario](https://developer.tkey7.com/docs-scenarios/return-dso/).

### debtor-cancel-payment-dso-agree

The [`/debtor-cancel-payment-dso-agree`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSO/debtor-cancel-payment-dso-agree) subdirectory contains the messages applied in the DSO Payment Cancelation: Scenario No. 1.

> [Learn more about using messages in this scenario](https://developer.tkey7.com/docs-scenarios/dso-payment-cancelation-1).

### debtor-cancel-payment-dso-reject

The [`/debtor-cancel-payment-dso-reject`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSO/debtor-cancel-payment-dso-reject) subdirectory contains the messages applied in the DSO Payment Cancelation: Scenario No. 2.

> [Learn more about using messages in this scenario](https://developer.tkey7.com/docs-scenarios/dso-payment-cancelation-2).

### creditor-cancel-payment-dso

The [`/creditor-cancel-payment-dso`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSO/creditor-cancel-payment-dso) subdirectory contains the messages applied in the DSO Payment Cancelation: Scenario No. 3.

> [Learn more about using messages in this scenario](https://developer.tkey7.com/docs-scenarios/dso-payment-cancelation-3).

### payment-dso-modify

The [`/payment-dso-modify`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSO/payment-dso-modify) subdirectory contains the messages applied in the DSO Payment Modification.

> [Learn more about using messages in this scenario](https://developer.tkey7.com/docs-scenarios/dso-payment-modify).

## ISO 20022 XML Message Examples—DSA

### payment-dsa

The [`/payment-dsa`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSA/en/payment-dsa) subdirectory contains the messages applied in the Payments using the DSA.

> [Learn more about using messages in this scenario](https://developer.tkey7.com/docs-scenarios/payment-dsa).

### redeem-dsa

The [`/redeem-dsa`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSA/redeem-dsa) subdirectory contains the messages applied in the DSA Redeem.

> [Learn more about using messages in this scenario](https://developer.tkey7.com/docs-scenarios/redeem-dsa).

### debtor-cancel-payment-dsa-agree

The [`/debtor-cancel-payment-dsa-agree`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSA/debtor-cancel-payment-dsa-agree) subdirectory contains the messages applied in the DSA Payment Cancelation: Scenario No. 1.

> [Learn more about using messages in this scenario](https://developer.tkey7.com/docs-scenarios/dsa-payment-cancelation-1).

### debtor-cancel-payment-dsa-reject

The [`/debtor-cancel-payment-dsa-reject`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSA/debtor-cancel-payment-dsa-reject) subdirectory contains the messages applied in the DSA Payment Cancelation: Scenario No. 2.

> [Learn more about using messages in this scenario](https://developer.tkey7.com/docs-scenarios/dsa-payment-cancelation-2).

### creditor-cancel-payment-dsa

The [`/creditor-cancel-payment-dsa`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSA/creditor-cancel-payment-dsa) subdirectory contains the messages applied in the DSA Payment Cancelation: Scenario No. 3.

> [Learn more about using messages in this scenario](https://developer.tkey7.com/docs-scenarios/dsa-payment-cancellation-3).

### payment-dsa-modify

The [`/payment-dsa-modify`](https://github.com/tkey7/iso20022-tkey7/tree/main/examples/en/settlement-method-TDSA/payment-dsa-modify) subdirectory contains the messages applied in the DSA Payment Modification.

> [Learn more about using messages in this scenario](https://developer.tkey7.com/docs-scenarios/dsa-payment-modify).

## UML Diagrams

The directory contains UML diagrams, presented in `.jpg` format, which supplement the ISO 20022 XML example messages.

### Payment using the DSO—`/payment-dso`

* The diagram [`payment-dso.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/en/settlement-method-TDSO/payment-dso/payment-dso.jpg) demonstrates the creation of a Payment using the Settlement Method of DSO when the Sender Financial Institution, acting on behalf of the Payer, instructs the Beneficiary Financial Institution, acting on behalf of the ultimate Beneficiary, to make the Payment. As part of the Payment, the Members accept the terms of the transaction and identify the Payer and the ultimate Beneficiary per applicable compliance requirements.

### DSO Return—`/return-dso-after-payment-dso`

* The diagram [`return-dso-after-payment-dso.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/en/settlement-method-TDSO/return-dso-after-payment-dso/return-dso-after-payment-dso.jpg) demonstrates the DSO Return on a previously made Payment.

### DSO Payment Cancelation: Scenario No. 1—`/debtor-cancel-payment-dso-agree`

* The diagram [`debtor-cancel-payment-dso-agree.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/en/settlement-method-TDSO/debtor-cancel-payment-dso-agree/debtor-cancel-payment-dso-agree.jpg) demonstrates the Payment Cancelcation initiated by the Sender Financial Institution.

### DSO Payment Cancelation: Scenario No. 2—`/debtor-cancel-payment-dso-reject`

* The diagram [`debtor-cancel-payment-dso-reject.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/en/settlement-method-TDSO/debtor-cancel-payment-dso-reject/debtor-cancel-payment-dso-reject.jpg) demonstrates a situation where the Sender Financial Institution requests Payment Cancelation from the Beneficiary Financial Institution. 

### DSO Payment Cancelation: Scenario No. 3—`/creditor-cancel-payment-dso`

* The diagram [`creditor-cancel-payment-dso.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/en/settlement-method-TDSO/creditor-cancel-payment-dso/creditor-cancel-payment-dso.jpg) demonstrates the Payment Cancelation initiated by the Beneficiary Financial Institution.

### DSO Payment Modification—`/payment-dso-modify`

* The diagram [`payment-dso-modify.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/en/settlement-method-TDSO/payment-dso-modify/payment-dso-modify.jpg) demonstrates the modification of Payment location and subsequent delivery to the ultimate Beneficiary.

### Payment using the DSA—`/payment-dsa`

* The diagram [`payment-dsa.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/en/settlement-method-TDSA/payment-dsa/payment-dsa.jpg) demonstrates creating a Payment with simultaneous clearing and settlement in real time.

### DSA Redeem—`/redeem-dsa`

* The diagram [`redeem-dsa.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/en/settlement-method-TDSA/redeem-dsa/redeem-dsa.jpg) demonstrates a situation in which a Financial Institution requests redemption of a DSA from the Tokenizer, after which the Tokenizer instructs to transfer non-cash funds to the Member’s bank account outside TKEY7.

### DSA Payment Cancelation: Scenario No. 1—`/debtor-cancel-payment-dsa-agree`

* The diagram [`debtor-cancel-payment-dsa-agree.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/en/settlement-method-TDSA/debtor-cancel-payment-dsa-agree/debtor-cancel-payment-dsa-agree.jpg) demonstrates the Payment Cancelation initiated by the Sender Financial Institution.

### DSA Payment Cancelation: Scenario No. 2—`/debtor-cancel-payment-dsa-reject`

* The diagram [`debtor-cancel-payment-dsa-reject.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/en/settlement-method-TDSA/debtor-cancel-payment-dsa-reject/debtor-cancel-payment-dsa-reject.jpg) demonstrates a situation where the Sender Financial Institution requests Payment Cancelation from the Beneficiary Financial Institution.

### DSA Payment Cancelation: Scenario No. 3—`/creditor-cancel-payment-dsa`

* The diagram [`creditor-cancel-payment-dsa.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/en/settlement-method-TDSA/creditor-cancel-payment-dsa/creditor-cancel-payment-dsa.jpg) demonstrates the Payment Cancelation initiated by the Beneficiary Financial Institution.

### DSA Payment Modification—`/payment-dsa-modify`

* The diagram [`payment-dsa-modify.jpg`](https://github.com/tkey7/iso20022-tkey7/blob/main/examples/en/settlement-method-TDSA/modify-payment-dsa/payment-dsa-modify.jpg) demonstrates the modification of Payment location and subsequent delivery to the ultimate Beneficiary.

# TKEY7 Documentation

Detailed information about the key scenarios that describe how the Members interact with TKEY7 for clearing and settlement of international payments is available on the [developer’s portal](https://developer.tkey7.com/docs-scenarios-introduction). The scenarios contain steps with detailed instructions, UML diagrams, and examples of ISO 20022 financial messages.