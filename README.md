# orml-token pallet : Enable Multicurrency support.

##DOT Token

<img src="https://github.com/rafat/ormltoken/blob/main/img/dot.jpg"/>

##Custom RTK Token

<img src="https://github.com/rafat/ormltoken/blob/main/img/rtk.jpg"/>

types.json File used
```
{
    "CurrencyId": {
        "_enum": [
            "RTK",
            "DOT",
            "KSM",
            "BTC"
        ]
    },
    "CurrencyIdOf": "CurrencyId",
    "Amount": "i128",
    "AmountOf": "Amount",
    "Order": {
        "base_currency_id": "CurrencyId",
        "base_amount": "Compact<Balance>",
        "target_currency_id": "CurrencyId",
        "target_amount": "Compact<Balance>",
        "owner": "AccountId"
    },
    "OrderOf": "Order",
    "OrderId": "u32"
}
```


