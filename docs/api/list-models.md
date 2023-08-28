# Chat API

## Request

```json
{
  "input": {
    "api": {
      "method": "POST",
      "endpoint": "/model"
    },
    "payload": {
      "action": "list"
    }
  }
}
```

## Response

### RUN

```json
{
    "id": "83bbc301-5dcd-4236-9293-a65cdd681858",
    "status": "IN_QUEUE"
}
```

### RUNSYNC

```json
{
    "delayTime": 27982,
    "executionTime": 307,
    "id": "sync-4b4a8565-0018-4802-a453-b336f9d332d7",
    "output": {
        "result": [
            "TheBloke_Nous-Hermes-13B-SuperHOT-8K-GPTQ"
        ]
    },
    "status": "COMPLETED"
}
```