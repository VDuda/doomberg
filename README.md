# DoomBerg

DoomBerg pulls in S&P500 data, recent news, and runs a negative analysis on the stock. Based on the EBIDTA and recent news, a Senior Doom Research Analyst orchestrates a team of agents such as an Analyst, Financial Model Builder, and Dash Programmer to build a dash app for measuring “Gloom” and it’s reasoning, for how the ticker/company will be guided negatively based on current events.

## Inspiraion 

Inspired by Claude's implementation of "make me a pretty graph based on 10k" 
https://x.com/alliekmiller/status/1808252365130104878

## N8n Setup
For news and vector embeddings of 10k reports. 
<img width="1287" alt="image" src="https://github.com/VDuda/doomberg/assets/6300279/bb5b07ad-2ad5-439b-8d61-0a9a8a49bb75">



## Setup

```
pip install -r requirements.txt
```

```env
DATABRICKS_TOKEN=a88... #set to DBRX API
DATABRICKS_BASE_URL=https://dbrx-base-url.com #set to dbrx url
```

## Run

```
python main.py
```
