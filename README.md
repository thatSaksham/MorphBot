# MorphBot

![Image 1](./public/logo_dark.png)

### Installation

#### Step 1: Clone the repository
```bash 
git clone https://github.com/thatSaksham/MorphBot
cd MorphBot
```
#### Step 3: Create Python Environment
```bash 
python3 -m venv aienv
.\aienv\Scripts\activate
```
#### Step 4: Add API Key
##### Create Groq API Key from [here](https://console.groq.com/keys) and edit the .env file
```bash 
GROQ_API_KEY=####
```
#### Step 5: Install the dependencies
```bash
pip install -r requirements.txt
```
#### Step 6: Run the bot
```bash
chainlit run app.py
```
