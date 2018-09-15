# CFC F18 RCOS-Tweets 

Overview 
---

Components:

- Twitter Feed Ingest Layer
- Keyword Analysis Layer
- NLP Layer 
- Disaster Databases
  - 2x staging databases
  - Main datawarehouse
- Logistics Analysis Layer


To Do:
---

1. Use Node-Red to pipe twtiiter data into MongoDB
2. Pipe MDB to Watson to extract keywords
3. On keywordl, filter by topics, emotions ,ettc
4. Take clean data, using Node-PS, to send back to 2nd datastore
