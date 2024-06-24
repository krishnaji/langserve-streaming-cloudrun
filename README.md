![](streamed.gif)

```bash
sh deloy.sh
```
```
curl -X 'POST' \
  'https://streaming-piaidmycda-uc.a.run.app/vertexai/stream' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{"input": {
  "text": "What are some fun facts about cats?",
  "type": "StringPromptValue"
}}
```
![](Curl-Stream.gif)

```
https://streaming-piaidmycda-uc.a.run.app/vertexai/playground
```
![](Playground-Stream.gif)
