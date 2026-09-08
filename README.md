# Sprint 3 — Matemática Linear

Projeto desenvolvido para a **Sprint 3**, utilizando conceitos de estatística, probabilidade e regressão linear com Python.

## Sobre o projeto

Neste projeto, utilizamos uma base de dados de seguros de saúde (`insurance.csv`) para realizar algumas análises estatísticas e aplicar um modelo simples de **Regressão Linear**.

O objetivo principal é analisar a relação entre a **idade dos clientes** e os **custos médicos**.

## O que foi feito

### 1. Probabilidade acima da mediana

Utilizamos a variável `age` para calcular a probabilidade de uma pessoa possuir uma idade acima da mediana da base.

### 2. Probabilidade dentro de um intervalo

Também é calculada a probabilidade de um valor de idade estar dentro do intervalo:

**Média ± 2 desvios-padrão**

### 3. Regressão Linear

Aplicamos **Regressão Linear** para analisar a relação entre:

* **Variável independente:** idade (`age`)
* **Variável dependente:** custo médico (`charges`)

Ao final, é gerado um gráfico com os dados e a reta de regressão.

## Tecnologias utilizadas

* Python
* Pandas
* Matplotlib
* SciPy
* Scikit-learn

## Estrutura do projeto

```text
Sprint_3_Matematica-linear/
│
├── analise
├── insurance.csv
└── README.md
```

## Como executar

Instale as bibliotecas necessárias:

```bash
pip install pandas matplotlib scipy scikit-learn
```

Depois, mantenha o arquivo `insurance.csv` na mesma pasta do código e execute:

```bash
python analise
```

## Integrantes

Gustavo Zagato Bottechia - RM: 569420

Davi Q. Zuolo - RM: 571669

Daniel Vilela Mana - RM: 571632

Kayo Henderson - RM: 570706

## Vídeo do projeto

🎥 **Apresentação do projeto:**
[Assista ao vídeo no YouTube](COLE_AQUI_O_LINK_DO_YOUTUBE)

---

**Sprint 3 — Matemática Linear**
Projeto acadêmico desenvolvido em Python.
