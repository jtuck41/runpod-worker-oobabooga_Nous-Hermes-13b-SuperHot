# Chat API

## Request

```json
{
  "input": {
    "api": {
      "method": "GET",
      "endpoint": "/model"
    },
    "payload": {
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
    "delayTime": 19234,
    "executionTime": 329,
    "id": "sync-b2e9990f-5542-457f-a1ec-47cea56186b1",
    "output": {
        "result": "TheBloke_Nous-Hermes-13B-SuperHOT-8K-GPTQ"
    },
    "status": "COMPLETED"
}
```