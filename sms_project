# Send texts on phone (python mini project)
import requests
import json


def send_sms(number , msg):
    url = 'https://www.fast2sms.com/dev/bulkV2'
    params = {
        'authorization': '9ogPdYtyZ1kIHfaTCpnRFiwD5cxe6lQLOGXhW0qr8S23ubMAUNDpIc40nSTLCosfXPe85dzi7EZ2V1ag',
        'sender_id': 'FSTSMS',
        'message': msg ,
        'language': "english",
        'route': 'p',
        'numbers': number,
    }
    response = requests.get(url , params = params)
    dic = response.json()
    print(dic)
send_sms('8527898991' , "Hello chuchi")
