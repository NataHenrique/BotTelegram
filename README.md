---

# 📖 Bot Telegram – Devocionais & Plano Bíblico (usando Groq)

Um bot para Telegram que gera **devocionais cristãos personalizados** e **planos bíblicos organizados** usando modelos compatíveis com a API da OpenAI através da plataforma **Groq**.

Este projeto permite que qualquer pessoa receba textos inspiradores, versículos e planos de leitura diretamente no chat do Telegram.

---

## 🚀 Funcionalidades

### ✨ **1. Devocionais Cristãos**

* Gera devocionais curtos baseados em temas.
* Inclui:

  * 1 versículo bíblico
  * Reflexão
  * Aplicação prática
* ~130 a 220 palavras

Comando:

```
/devocional <tema>
```

---

### 📘 **2. Planos Bíblicos Estruturados**

Cria automaticamente planos bíblicos completos e equilibrados entre Antigo e Novo Testamento.

Exemplos:

```
/plano 30 dias
/plano 3 meses
```

---

### 📚 **3. Lista de Temas Disponíveis**

```
/temas
```

---

### 👋 **4. Início**

```
/start
```

---

## 🧠 Modelos Usados (Groq)

* `llama-3.3-70b-versatile`
* `llama-3.1-8b-instant`
* `openai/gpt-oss-20b`

O bot tenta os modelos em sequência caso algum falhe.

---

# ⚙️ Instalação e Execução

## 1️⃣ Criar e Ativar o Ambiente Virtual Python

Recomendado para manter as dependências isoladas.

### **Windows (PowerShell)**

Criar ambiente:

```powershell
python -m venv venv
```

Ativar:

```powershell
.\venv\Scripts\activate
```

Desativar:

```powershell
deactivate
```

---

### **Linux / macOS**

Criar ambiente:

```bash
python3 -m venv venv
```

Ativar:

```bash
source venv/bin/activate
```

Desativar:

```bash
deactivate
```

---

## 2️⃣ Instalar dependências

Com o ambiente virtual ativado:

```bash
pip install python-telegram-bot openai
```

---

## 3️⃣ Configurar Variáveis de Ambiente

### **Windows (PowerShell)**:

```powershell
setx GROQ_API_KEY "SUA_CHAVE_AQUI"
setx TELEGRAM_TOKEN "SEU_TOKEN_AQUI"
```

### **Linux/macOS**:

```bash
export GROQ_API_KEY="SUA_CHAVE_AQUI"
export TELEGRAM_TOKEN="SEU_TOKEN_AQUI"
```

---

## 4️⃣ Executar o Bot

```bash
python bot.py
```

Ao iniciar, aparecerá:

```
BOT RODANDO...
```


---

# 📝 Temas Suportados

fé, esperança, gratidão, perdão, amor, coragem, sabedoria, paciência, confiança,
obediência, adoração, humildade, justiça, salvação, família, oração, libertação, propósito.

---

# 🔒 Segurança

🔐 **Nunca exponha as chaves `GROQ_API_KEY` e `TELEGRAM_TOKEN`.**

O projeto já exige que elas venham por variáveis de ambiente.

---

# 🤝 Contribuições

Pull requests e sugestões são bem-vindas!

---


