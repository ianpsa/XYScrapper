# **XYScraper**  
**Gotta Catch 'Em All!**  
por **Ian - ECHOSEC**  

---
  
### 🔥 **Scraper + Testador + Atualizador Automático de Proxies** 🔥  

1. **Coleta proxies SOCKS4/SOCKS5** de múltiplas fontes públicas:
   - `socks-proxy.net`
   - `free-proxy-list.net`
   - `spys.one`
   - E mais...

2. **Testa proxies em 2 etapas**:
   - **Handshake TCP/UDP** (verificação técnica)
   - **Requisição HTTP** (teste de funcionalidade real)

3. **Atualiza automaticamente** o arquivo `proxychains.conf`:
   - Mantém apenas proxies funcionais
   - Remove proxies mortos
   - Limita a 50 proxies (configurável)

4. **Testa proxies existentes** no seu `proxychains.conf` antes de adicionar novos.

---

## **Passo-a-Passo para Executar**  

### **⚠️ Requisitos**  
- Python 3.x  
- `sudo` access (para atualizar proxychains.conf)  
- Pacotes:  
  ```bash
  python -m venv venv
  source venv/bin/activate
  pip install -r requirements.txt
  deactivate

- Inicialização:
    ``` bash
    sudo venv/bin/python XYScrapper.py

        # E PRONTO!