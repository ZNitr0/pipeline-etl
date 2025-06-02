# pipeline-etl
# 🛠️ Pipeline ETL com Python

Este projeto consiste em uma **Pipeline ETL (Extract, Transform, Load)** desenvolvida em Python, executada e documentada em um notebook do Google Colab.

A pipeline realiza a extração de dados, transformação para limpeza e padronização, e por fim a carga dos dados prontos para análise ou armazenamento.

> 🔗 [Acesse o notebook no Google Colab](https://colab.research.google.com/drive/1wdqKvR3COMw5j3QSslOrQ8ZYYV65MIHs)

---

## 📌 Objetivos do Projeto

- Automatizar o fluxo de dados desde a origem até o destino final.
- Garantir consistência, qualidade e reprodutibilidade dos dados.
- Fornecer uma base tratada para análises ou integração com sistemas externos.

---

## ⚙️ Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy
- Google Colab
- Requests / APIs (se aplicável)
- SQL ou integração com bancos (opcional)

---

## 🧩 Estrutura da Pipeline

A pipeline está dividida nas seguintes etapas:

1. **Extração (Extract)**  
   - Coleta de dados a partir de [API / CSV / Excel / Banco de Dados].
   - Exemplo: `pd.read_csv()`, `requests.get()`, etc.

2. **Transformação (Transform)**  
   - Limpeza de dados (valores nulos, duplicados).
   - Conversão de formatos e tipos.
   - Normalização ou agregações.

3. **Carga (Load)**  
   - Exportação dos dados tratados para [CSV / Banco de Dados / Google Sheets / outra API].

---

## 📁 Como Usar

Você pode clonar este repositório e abrir o notebook no Colab:

```bash
git clone https://github.com/ZNitr0/pipeline-etl.git
