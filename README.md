# Altered TCG tools
serie of tools for Altered TCG

## Tips
- in case of SSL error:<br>
Modify .venv\Lib\site-packages\requests\adapters.py function send() at the very begining add:<br>
```verify = False``` (~line 631)

