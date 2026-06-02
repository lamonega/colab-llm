# colab-llm

Ejecutá modelos LLM locales en Google Colab y exponelos via API pública usando Ollama y Cloudflare Tunnel.

## Uso

1. Abrí el notebook en Colab, ya sea subiéndolo o [directamente desde acá.](https://colab.research.google.com/github/lamonega/colab-llm/blob/main/colab_llm.ipynb)
2. Seleccioná runtime: T4 GPU.
3. Ejecutá todas las celdas.
4. Esperá a que termine. Vas a ver una URL publica como `https://...trycloudflare.com`.
5. Usá esa URL desde cualquier cliente (curl, VS Code, etc.) apuntando al endpoint `/api/generate`.

Podés probar que tu modelo anda en mi chat web [jermaine](https://lamonega.github.io/jermaine/) con la URL y el nombre de modelo.

## Notas

- La sesión de Colab dura hasta ~4 horas.
- No requiere cuenta de Cloudflare.
- Recomiendo Qwen3 14B y DeepSeek R1 14B con 16MB de contexto para 10-12t/s.
