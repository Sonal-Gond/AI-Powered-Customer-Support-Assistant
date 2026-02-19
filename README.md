# AI-Powered-Customer-Support-Assistant

**Import File:**
1. Download .vf file
2. Go to Voiceflow Dashboard
3. Click New Project
4. Select Import Project
5. Upload the provided .vf file


**Reconnect Knowledge Base (RAG)**
1. Go to Knowledge Base
2. Upload your:
 - FAQs
 - Policy Documents
 - Product and service question Information

**API :**
1. Zendesk API:
    - get the API token from zendesk then convert the **your_loginemail.com/token:your_api_token** into bs64 encoder then use these converted key in zendesk API Authorization header.
2. Google sheet API:
   - for logging data inside google sheet first get the web url of google sheet for creating record and lookup record and use it in voiceflow project 


**Integrate Messaging Platform (Optional)**

-> Telegram (use flowbridge or other thirsd party)
-> WhatsApp (using twillio sandbox or other third party )
-> Web Chat :
  - goto voiceflow project -> interfaces -> copy the code -> paste the code inside website html code before </body> tag
  - If using html file of these github repo replace "YOUR_PROJECT_ID" with your actual project file  
