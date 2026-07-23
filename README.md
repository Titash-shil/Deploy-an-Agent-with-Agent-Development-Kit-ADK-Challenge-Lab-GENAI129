# [Deploy-an-Agent-with-Agent-Development-Kit-ADK-Challenge-Lab-GENAI129](https://www.skills.google/catalog_lab/32530)
GCP solution, Educational Purspose only!

- ### Add the Code to `agent.py` Under `paint_agent` :
```
AgentTool(agent=search_agent, skip_summarization=False),
```
- ### Add Your `Bucket Name` & Run this code in `Cloud Shell Terminal` :
```
adk deploy agent_engine paint_agent
--display_name "Paint Agent"
--staging_bucket gs://
```

- ### Watch the next process from the video carefully!
