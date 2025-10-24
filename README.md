<p align="center">
  <img src="assets/banner.png" alt="BIA PC Builder Banner" width="100%">
</p>

<h1 align="center">💻 BIA PC Builder — Montador de PC Gamer Inteligente</h1>

<p align="center">
  🚀 <em>Versão MVP v3.0 — Desenvolvido por <a href="https://github.com/lsilveiralg13">Lucas Barros</a></em>
</p>

---

## 🧠 O que é o BIA PC Builder?

O **BIA PC Builder** é uma plataforma inteligente desenvolvida em **Python + Streamlit** que ajuda o usuário a **montar um PC Gamer personalizado**, comparando **preços reais** em lojas como a **Amazon**, sugerindo **peças compatíveis** com base no **perfil de uso**.

---

## ⚙️ Funcionalidades Principais

✅ Recomendação automática de componentes (CPU, GPU, RAM, SSD, etc.)  
✅ Comparação de preços em tempo real  
✅ Identificação do melhor custo-benefício  
✅ Exportação dos resultados para Excel  
✅ Interface intuitiva e visual com Streamlit  
✅ Possibilidade de integração futura com tags de afiliado (Amazon API)  

---

## 🧩 Estrutura do Projeto

```
bia-pc-builder/
│
├── app.py                 # Código principal da aplicação Streamlit
├── requirements.txt       # Dependências do projeto
├── README.md              # Documentação do projeto
├── .streamlit/
│   └── secrets.toml       # (Opcional) Suas credenciais ou tag de afiliado
└── assets/
    ├── banner.png         # Banner visual do projeto
    └── logo.png           # Logotipo da BIA
```

---

## 🚀 Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/lsilveiralg13/bia-pc-builder.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd bia-pc-builder
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute o app:
   ```bash
   streamlit run app.py
   ```

---

## 🧱 Tecnologias Utilizadas

- **Python 3.11+**
- **Streamlit**
- **BeautifulSoup / Requests**
- **Pandas**
- **OpenPyXL**
- **Amazon Web Scraper**
- **TensorFlow Lite (futuro para otimização preditiva)**

---

## 🧭 Roadmap Futuro

🔹 Integração direta com APIs de lojas (Amazon, Kabum, TerabyteShop)  
🔹 Sistema de recomendação baseado em IA  
🔹 Modo Dark customizável  
🔹 Criação automática de builds salvos (com login de usuário)  
🔹 Versão web hospedada no Streamlit Cloud  

---

## 👨‍💻 Autor

**Lucas Barros**  
Desenvolvedor e criador da assistente **BIA** 🧠  
📫 Contato: [linkedin.com/in/lucasbarros](https://linkedin.com/in/lucasbarros)

---

<p align="center">
  <img src="assets/logo.png" alt="BIA Logo" width="120">
</p>

<p align="center">
  <em>“Montar o PC ideal ficou inteligente.”</em>
</p>
