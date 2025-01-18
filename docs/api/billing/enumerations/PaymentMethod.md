# PaymentMethod

Enum representing different types of payment methods.
These are used to specify the payment mechanism chosen by a customer.

## Enumeration Members

| Enumeration Member | Value | Description |
| ------ | ------ | ------ |
| <a id="banktransfer"></a> `BankTransfer` | `"Bank Transfer"` | Payment via direct bank transfer. Used typically for larger transactions or where credit cards and PayPal are not viable. |
| <a id="creditcard"></a> `CreditCard` | `"Credit Card"` | Payment through credit card. |
| <a id="paypal"></a> `PayPal` | `"PayPal"` | Payment through PayPal. Ideal for users who prefer not to directly use their credit card details. |
