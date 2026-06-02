# colab-llm

Ejecutá modelos LLM locales en Google Colab y exponelos via API pública usando Ollama y Cloudflare Tunnel.

## Uso

1. Subí el notebook a Google Colab.
2. Seleccioná runtime: T4 GPU.
3. Ejecutá todas las celdas.
4. Esperá a que termine. Aparecera una URL publica como `https://...trycloudflare.com`.
5. Usa esa URL desde cualquier cliente (curl, VS Code, etc.) apuntando a `/api/generate`.

## Notas

- La sesion de Colab dura hasta ~3 horas.
- No requiere cuenta de Cloudflare.
