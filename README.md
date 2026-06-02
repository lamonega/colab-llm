# colab-llm

Ejecutá modelos LLM locales en Google Colab y exponelos via API pública usando Ollama y Cloudflare Tunnel.

## Uso

1. Subí el notebook a Google Colab (podés usar GitHub directamente)
2. Seleccioná runtime: T4 GPU.
3. Ejecutá todas las celdas.
4. Esperá a que termine. Vas a ver una URL publica como `https://...trycloudflare.com`.
5. Usá esa URL desde cualquier cliente (curl, VS Code, etc.) apuntando al endpoint `/api/generate`.

## Notas

- La sesión de Colab dura hasta ~4 horas.
- No requiere cuenta de Cloudflare.
- Recomiendo Qwen3 14B y DeepSeek R1 14B con 16MB de contexto para 10-12t/s.
