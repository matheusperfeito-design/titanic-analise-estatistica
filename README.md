# titanic-analise-estatistica
# 🚢 Titanic — Resumo Estatístico Descritivo

Análise das principais métricas descritivas do **Titanic Dataset**, desenvolvida como parte do desafio **Dados Nível 02** de um programa de formação em análise de dados.

---

## 📋 Sobre o projeto

O script calcula, para as colunas `Age` (idade) e `Fare` (tarifa paga), as seguintes estatísticas:

- Média
- Mediana
- Moda
- Valor mínimo e máximo
- Desvio padrão
- Amplitude e variância

Também responde à pergunta: **por que a mediana às vezes é melhor do que a média?**

---

## 📁 Estrutura do repositório

---

## ▶️ Como executar

**1. Clone o repositório:**
```bash
git clone https://github.com/matheusperfeito-design/titanic-analise-estatistica.git
cd titanic-analise-estatistica
```

**2. Instale as dependências:**
```bash
pip install -r requirements.txt
```

**3. Execute o script:**
```bash
python analise_titanic.py
```

> O dataset já está embutido no script — não é necessário baixar nenhum arquivo externo.

---

## 📊 Resultados

### Age (Idade dos passageiros)

| Métrica        | Valor  |
|----------------|--------|
| Média          | 28,19  |
| Mediana        | 27,00  |
| Moda           | 21,00  |
| Mínimo         | 0,83   |
| Máximo         | 71,00  |
| Desvio padrão  | 15,75  |

### Fare (Tarifa paga)

| Métrica        | Valor   |
|----------------|---------|
| Média          | £30,10  |
| Mediana        | £15,93  |
| Moda           | £8,05   |
| Mínimo         | £7,22   |
| Máximo         | £263,00 |
| Desvio padrão  | £41,12  |

---

## 💡 Insight: média vs. mediana

Na coluna `Fare`, a **média (£30,10)** é quase o dobro da **mediana (£15,93)**.
Isso acontece porque passageiros de 1ª classe pagaram tarifas de até £263, criando uma distribuição assimétrica que puxa a média para cima.

A mediana ignora esses extremos e representa melhor o passageiro típico.

> Regra prática: em dados com outliers (salários, preços, tarifas), prefira a mediana.

---

## 🛠️ Tecnologias

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.24+-013243?logo=numpy&logoColor=white)

---

## 👤 Autor

**Matheus Perfeito**  
[github.com/matheusperfeito-design](https://github.com/matheusperfeito-design)
