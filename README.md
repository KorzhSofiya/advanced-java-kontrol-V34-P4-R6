Індивідуальні умови вашого варіанта:

Профіль оплати P4: CardPayment: дозволяє суму до 35_000; PayPalPayment: приймає суму від 400; BankTransferPayment: комісія 2.5%.
Пакет правил R6: валідація - заборонити дублікати productId у масиві OrderItem[].
Знижки/комісії: знижка 15% для промокоду SPRING15.
Переходи станів: дозволити PAID -> REFUNDED.
Додатковий крок Template Method: реалізувати крок validatePromoCode.
Обов'язковий негативний сценарій: передбачити і протестувати виняток InvalidPromoCodeException.
