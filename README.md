# IBM-project
# step by step dissection of peoject

# importing data

url = 'url of the webpage' #to caputre url#
response.status_code #it will check the if it is imported successfully (will give 200 as output if done so)#
data = requests.json(url) #decoding the encoded and imported data#
df = pd.json_normalize(data) #to put that into pandas format#
