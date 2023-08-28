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
      "action": "info"
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
    "delayTime": 1215,
    "executionTime": 316,
    "id": "sync-69964d6c-39ad-4c43-8bce-9cea62c27ef4",
    "output": {
        "result": {
            "lora_names": [],
            "model_name": "TheBloke_Nous-Hermes-13B-SuperHOT-8K-GPTQ",
            "shared.args": {
                "alpha_value": 1,
                "api": true,
                "api_blocking_port": 5000,
                "api_streaming_port": 5005,
                "auto_devices": false,
                "auto_launch": false,
                "autogptq": false,
                "bf16": false,
                "cache_capacity": null,
                "character": null,
                "chat": false,
                "checkpoint": null,
                "compress_pos_emb": 1,
                "compress_weight": false,
                "compute_dtype": "float16",
                "cpu": false,
                "cpu_memory": null,
                "deepspeed": false,
                "desc_act": false,
                "disk": false,
                "disk_cache_dir": "cache",
                "extensions": [
                    "api"
                ],
                "flexgen": false,
                "fused_mlp": false,
                "gptq_for_llama": false,
                "gpu_memory": null,
                "gpu_split": null,
                "gradio_auth": null,
                "gradio_auth_path": null,
                "groupsize": -1,
                "listen": true,
                "listen_host": null,
                "listen_port": 3000,
                "llama_cpp_seed": 0,
                "load_in_4bit": false,
                "load_in_8bit": false,
                "loader": "AutoGPTQ",
                "local_rank": 0,
                "lora": null,
                "lora_dir": "loras/",
                "low_vram": false,
                "max_seq_len": 2048,
                "mlock": false,
                "model": "TheBloke_Nous-Hermes-13B-SuperHOT-8K-GPTQ",
                "model_dir": "models/",
                "model_menu": false,
                "model_type": null,
                "monkey_patch": false,
                "multi_user": false,
                "multimodal_pipeline": null,
                "n_batch": 512,
                "n_ctx": 2048,
                "n_gpu_layers": 0,
                "no_cache": false,
                "no_inject_fused_attention": false,
                "no_inject_fused_mlp": false,
                "no_mmap": false,
                "no_stream": false,
                "no_use_cuda_fp16": false,
                "notebook": false,
                "nvme_offload_dir": null,
                "percent": [
                    0,
                    100,
                    100,
                    0,
                    100,
                    0
                ],
                "pin_weight": true,
                "pre_layer": null,
                "public_api": false,
                "quant_attn": false,
                "quant_type": "nf4",
                "rwkv_cuda_on": false,
                "rwkv_strategy": null,
                "sdp_attention": false,
                "settings": null,
                "share": false,
                "threads": 0,
                "triton": false,
                "trust_remote_code": false,
                "use_double_quant": false,
                "verbose": false,
                "warmup_autotune": false,
                "wbits": 0,
                "xformers": false
            },
            "shared.settings": {
                "add_bos_token": true,
                "autoload_model": true,
                "ban_eos_token": false,
                "character": "None",
                "chat-instruct_command": "Continue the chat dialogue below. Write a single reply for the character \"<|character|>\".\n\n<|prompt|>",
                "chat_default_extensions": [
                    "gallery"
                ],
                "chat_generation_attempts": 1,
                "chat_generation_attempts_max": 10,
                "chat_generation_attempts_min": 1,
                "chat_style": "cai-chat",
                "context": "This is a conversation with your Assistant. It is a computer program designed to help you with various tasks such as answering questions, providing recommendations, and helping with decision making. You can ask it anything you want and it will do its best to give you accurate and relevant information.",
                "custom_stopping_strings": "",
                "dark_theme": false,
                "default_extensions": [],
                "greeting": "",
                "groupsize": "None",
                "instruction_template": "None",
                "max_new_tokens": 200,
                "max_new_tokens_max": 2000,
                "max_new_tokens_min": 1,
                "mode": "chat",
                "model_type": "None",
                "name1": "You",
                "name2": "Assistant",
                "pre_layer": 0,
                "preset": "simple-1",
                "prompt": "QA",
                "seed": -1,
                "skip_special_tokens": true,
                "start_with": "",
                "stop_at_newline": false,
                "truncation_length": 8192,
                "truncation_length_max": 16384,
                "truncation_length_min": 0,
                "turn_template": "",
                "wbits": "None"
            }
        }
    },
    "status": "COMPLETED"
}
```