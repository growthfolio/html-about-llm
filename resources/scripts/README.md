# Scripts de Teste de Segurança LLM

## Scripts Disponíveis

### jailbreak-tester.py
Testa vulnerabilidades de jailbreak em LLMs usando técnicas conhecidas (DAN, roleplay, etc.)

```python
# Uso básico
python jailbreak-tester.py --model gpt-3.5-turbo --api-key YOUR_KEY
```

### rate-limit-tester.py
Testa limites de taxa e detecta possíveis bypass de rate limiting

```python
# Teste de stress
python rate-limit-tester.py --url https://api.example.com --concurrent 100
```

### data-extraction-tester.py
Tenta extrair dados de treinamento e system prompts

```python
# Teste de extração
python data-extraction-tester.py --target chatbot.example.com
```

## Requisitos

- Python 3.8+
- requests
- openai (para testes com APIs OpenAI)
- aiohttp (para testes assíncronos)

## Aviso Legal

Estes scripts são para uso educacional e testes autorizados apenas. Não use contra sistemas sem permissão explícita.
