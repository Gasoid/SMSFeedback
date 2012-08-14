SMSFeedback
===========

Python API for smsfeedback.ru

##Пример

    from api_smsfeedback import SmsFeedBack
    client = SmsFeedBack("jika","pass123")
    #проверяем состояние счета
    balance = client.credits()
    print balance
    #отправка смс
    client.send_sms("7987654321",'i love you!')
