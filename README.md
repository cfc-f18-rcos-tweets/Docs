# CFC F18 RCOS-Tweets 

Overview:
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

1. Ingest Twitter data into a MongoDB staging area.
2. Pipe staging data into the NLP layer and extract keywords,topics.
3. On keyword analysis, filter by topics, emotions ,ettc
4. Take clean data, using NLP model to then back to 2nd datastore
5. Send data from 2nd datastore to main Disaster Database


Repos:
---

`/twitter-ingest` - Streams tweets from twitter into MongoDB, analyze with Jupyter Notebook
