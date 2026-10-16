# Não Trava Mas Anda 💻

> **Slogan:** O orçamento tu decides, a performance nós garantimos.

**Projeto Escolar / Avaliação**
- **Colaboradores:** 
  - Domingos Macedo (nº 13698)
  - David Gonçalves (nº 13695)
  - Diogo Ferreira (nº 13697)

---

## 🚀 Como Executar Localmente

1. Clonar o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/nao-trava-mas-anda.git
   cd nao-trava-mas-anda
   ```

2. Instalar dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Executar a aplicação:
   ```bash
   python app.py
   ```

4. Aceder em: `http://127.0.0.1:5000`

---

## 🌐 Alojameto no Render

1. Crie uma conta no [Render](https://render.com/).
2. Ligue a sua conta do GitHub ao Render.
3. Crie um novo **Web Service** selecionando o repositório deste projeto.
4. O Render detetará o ficheiro `render.yaml` ou configure manualmente:
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `gunicorn app:app`
