# 💬 Analisador de Sentimento com Django e TextBlob

Este é um projeto web simples para análise de sentimento de textos em inglês.  
Ele permite que usuários se cadastrem, façam login e submetam textos para análise com retorno imediato da polaridade e sentimento.

## 📌 Funcionalidades

- Cadastro e login de usuários  
- Análise de sentimento usando **TextBlob**  
- Interface web com **Bootstrap**  
- Sistema de logout  
- Resultados claros e instantâneos para o texto submetido  

---

## 🚀 Como rodar o projeto localmente

### 1. Faça o download do projeto

📥 Clique [aqui para baixar o arquivo `.zip`](https://github.com/enzodias1/sentimento4/raw/main/sentimento4.zip)  
💡 Após o download, extraia o conteúdo para uma pasta local.

---

### 2. Acesse a pasta do projeto no terminal

```bash
cd caminho/para/pasta-extraída
```

### 3. Crie e ative um ambiente virtual *(opcional, mas recomendado)*

**Windows:**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux/Mac:**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Instale as dependências

```bash
pip install django textblob
```

### 5. Execute o servidor

```bash
python manage.py runserver
```

### 6. Acesse no navegador

Abra o navegador e vá até:  
[http://127.0.0.1:8000/cadastro/](http://127.0.0.1:8000/cadastro/)

---

## 🧪 Exemplos para testar a análise de sentimento

**Texto positivo:**

> I love this product! It works perfectly and makes my life easier.

**Texto neutro:**

> The package arrived today. It was in a box.

**Texto negativo:**

> I'm really disappointed. It broke after one day of use.

---

## 🛠 Tecnologias utilizadas

- Python 3  
- Django  
- TextBlob  
- HTML + CSS (Bootstrap)  

---

## 👤 Autor

Desenvolvido por [@enzodias1](https://github.com/enzodias1)  
Sinta-se à vontade para sugerir melhorias!
