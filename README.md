# langchain_email
To get a working enviornment up follow the commands
```
git clone https://github.com/albrmar/langchain_email.git
cd langchain_email
python3.11 -m venv venv
source venv/bin/activate
pip install -U pip
pip install -r requirements.txt
```

place a .env file in the root directory and get your
open AI key.  You will need to place your secrets file
for the gmail connector in the root directory
following the lanchain instructions [langchain](https://python.langchain.com/v0.2/docs/integrations/tools/gmail/)
 
```
echo "OPEN_AI_KEY=<key>" >> .env

```