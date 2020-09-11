## Float & Decimal

- Float are not safe for accurately handling decimal places but it is json serializable using `json.dumps(float(1.9))`.
- Decimal are safe but more complicated to use and not serializable by default using something like `json.dumps(Decimal.decimal(1.9))`

## Currencies

- Dealing with currencies in python (and in many other languages) better be done as integers using the smallest unit of currency and working your way up (ala bitcoin being integers from satoshis -the smallest unit)
