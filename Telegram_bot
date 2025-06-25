import requests
from datetime import datetime

BOT_TOKEN="zzxzxzxxz4:AAEUxxxxxxxxxxxxxx_DX8"
CHAT_ID="19xxxxxxx4"
MESSAGE="HEY!,\n Billionarie"
url = f"https://api.telegram.org/bot{BOT_TOKEN}/sendMessage"
pay_load={
    "chat_id":CHAT_ID,
    "text":MESSAGE,
}
start_time=datetime.now()
response=requests.post(url,data=pay_load)
end_time=datetime.now()
#time=(end_time - start_time).total_seconds()
#response=requests.post(url,data={"chat_id":CHAT_ID,"text":time})
print("Message Sent At:", start_time.strftime('%H:%M:%S.%f'))
print("STATUS : ",response.status_code)
print("RESPONSE : ",response.json())
print(" HTTP total round trip time : ",(end_time - start_time).total_seconds(),"seconds")
