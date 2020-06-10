# n8n-daily-quotes
![https://f000.backblazeb2.com/file/n8n-website-images/cbcb64ecb1c344e49f84a9f787ca53f6.png](Workflow Image)

A workflow that allows you to receive Daily Random Quotes via Telegram by querying a REST API triggered by a Cron node.

I made use of the [quotable.io](https://quotable.io) API

## Nodes used in workflow:
 1x Cron
 1x Start
 1x Telegram
 1x HTTP Request
 
## Workflow Code:
To open this workflow in n8n do the following:
Copy the workflow-code saved as `dailyquotes.json`
Go into n8n
Click anywhere in the n8n-window
Paste the code (Ctrl + c)
It will then automatically create all the nodes and connections
