# mlx

pip install mlx-lm

MPDEL=mlx-community/Qwen-3.5-4B-8bit

mlx_lm.server --model ${MODEL}

# agent
U="http://127.0.0.1:8080/v1/chat/completions"
curl -X POST ${U} -H "Content-type: application/json" \
  -d '{"model": "default_model", "messages": [{"role": "user", "content", "hello there"}]}'

a<z
  
