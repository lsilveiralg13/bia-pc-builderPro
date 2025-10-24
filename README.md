# 💻 BIA PC Builder — Montador de PC Gamer Inteligente

🚀 *Versão MVP v3.0 — Desenvolvido por [Lucas Barros](https://github.com/seuusuario)*

![banner](assets/banner.png)

---
## 🧠 O que é o BIA PC Builder?

A **BIA PC Builder** é uma plataforma inteligente desenvolvida em **Python + Streamlit** que ajuda o usuário a **montar um PC Gamer personalizado**, comparando **preços reais** em lojas como a **Amazon** e sugerindo **peças compatíveis** com base no perfil de uso.

### ⚙️ Funcionalidades

- 💡 Sugestão automática de peças conforme a usabilidade do PC  
  (`Fraco`, `Médio`, `Forte`, `Multitarefas`, `Entusiasta`)
- 🛒 Busca de preços em tempo real (via Selenium headless)
- 🧩 Edição manual das peças antes da busca
- 💰 Comparativo de custo-benefício por componente
- 📊 Exportação dos resultados para Excel (`comparativo_pc.xlsx`)
- 🔗 Links com **tag de afiliado** da Amazon integrados (para monetização)

---

## 🧩 Tecnologias utilizadas

| Categoria | Tecnologias |
|------------|-------------|
| Backend | Python 3.13 |
| Web App | Streamlit |
| Automação Web | Selenium + WebDriver Manager |
| Dados | Pandas, OpenPyXL |
| Visual | Streamlit UI Components |

---

## ⚙️ Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/seuusuario/bia-pc-builder.git
cd bia-pc-builder

# Instale as dependências
pip install -r requirements.txt

# Execute o app
streamlit run app.py
