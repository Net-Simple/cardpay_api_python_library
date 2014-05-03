cardpay_api_python_library
==========================

CARDPAY API Python library

http://www.cardpay.com/ru/
http://www.cardpay.com/

Библиотека содержит функции выполнения операций:

1. Зds авторизация
2. Платеж
3. Авторизация (холд)
4. Отмена авторизации (снятие холда)
5. Отмена платежа
6. Рефанд
7. Получение статуса платежа

PyCardPay quick methods list:

1. Process payment PyCardPay.api.pay()
2. Capture transaction PyCardPay.api.capture()
3. Refund transaction PyCardPay.api.refund()
4. Void transaction PyCardPay.api.void()
5. Check payment status PyCardPay.api.status()
6. Change transaction status PyCardPay.api.status_change()
7. Finish 3Ds authorization PyCardPay.api.finish_3ds()
8. Create order xml PyCardPay.utils.order_to_xml()
9. XML to base64 PyCardPay.utils.xml_to_string()
10. Calculate sha512 PyCardPay.utils.xml_get_sha512()
11. Validate XML checksum PyCardPay.utils.xml_check_sha512()
