# 🏠⚡ Checkpoint 01 – Data Science e Machine Learning

Este projeto contém a resolução completa do **Checkpoint 01** da disciplina de *Data Science e Machine Learning*, utilizando:

- **Python (Google Colab)** → para análise e modelagem (Questões 1–35).  
- **Orange Data Mining (GUI)** → para análise visual (Questões 36–40).  

---

## 📂 Estrutura do Projeto

- `household_power_consumption.txt` → base principal (Individual Household Electric Power Consumption – UCI).  
- `appliances_energy_prediction.csv` → segunda base (Appliances Energy Prediction – UCI).  
- `Checkpoint_IHEPC_Appliances_Notebook.ipynb` → notebook com todas as resoluções (Python).  
- `README.md` → este arquivo, com instruções de uso.  

---

## 🚀 Como executar no Google Colab

1. Acesse [Google Colab](https://colab.research.google.com/).  
2. Crie um novo notebook e copie o código disponível neste repositório.  
3. Faça **upload dos datasets** quando solicitado:  
   - `household_power_consumption.txt`  
   - `appliances_energy_prediction.csv` (para a Parte 3).  

### 🔹 Setup inicial
O notebook já está preparado para:
- Ler o `.txt` diretamente (sem precisar do `.zip`).  
- Tratar datas, valores ausentes e variáveis numéricas.  

### 🔹 Execução das Partes
- **Parte 1 (Q1–Q20):** análises exploratórias, séries temporais, clustering e regressão simples.  
- **Parte 2 (Q21–Q25):** séries horárias, autocorrelação, PCA, regressão linear vs polinomial.  
- **Parte 3 (Q26–Q35):** análises e modelos de predição usando *Appliances Energy Prediction*.  
- **Parte 4 (Q36–Q40):** tarefas realizadas no Orange Data Mining.

---

## 🟠 Parte 4 – Orange Data Mining (Q36–Q40)

Estas questões são realizadas **na interface gráfica do Orange**, sem código.  
Fluxo sugerido:

1. **File** → importar `household_power_consumption.txt` (`;` como separador, `?` como missing).  
2. **Data Table** → visualizar os primeiros registros.  
3. **Sample Data (1%)** → comparar distribuições.  
4. **Distribution** → analisar `Global_active_power`.  
5. **Scatter Plot** → `Voltage` × `Global_intensity`.  
6. **k-Means (3 clusters)** → `Sub_metering_1,2,3` → visualizar no Scatter Plot.  

---

## 📊 Informações detalhadas do dataset

### 🔹 Individual Household Electric Power Consumption
- Origem: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)  
- Registros: **2.075.259** (um a cada minuto, entre 2006 e 2010).  
- Variáveis:  
  - `Date` → Data (dd/mm/yyyy)  
  - `Time` → Hora (hh:mm:ss)  
  - `Global_active_power` → Potência ativa global (kW).  
  - `Global_reactive_power` → Potência reativa global (kVAR).  
  - `Voltage` → Tensão média (V).  
  - `Global_intensity` → Corrente média (A).  
  - `Sub_metering_1` → Consumo na cozinha (Wh).  
  - `Sub_metering_2` → Consumo na lavanderia (Wh).  
  - `Sub_metering_3` → Consumo de aquecimento/AC (Wh).  

### 🔹 Appliances Energy Prediction
- Origem: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction)  
- Registros: **19.735** (10 minutos de intervalo, 2016).  
- Variáveis principais:  
  - `date` → Data/hora.  
  - `Appliances` → Consumo de energia dos aparelhos (Wh).  
  - Sensores de temperatura (`T1`–`T9`).  
  - Sensores de umidade relativa (`RH_1`–`RH_9`).  
  - Temperatura e umidade externa (`T_out`, `RH_out`).  
  - Condições meteorológicas externas (`Windspeed`, `Visibility`, `Tdewpoint`).  

---

## 📑 Instruções de entrega

- Entregar o notebook `.ipynb` com todas as resoluções (Partes 1–3).  
- Adicionar prints/telas do workflow do Orange para as questões 36–40.  
- Incluir este `README.md` no repositório/documentação.  
- Entregar em formato PDF ou compactado, conforme solicitado na disciplina.

---

## 👨‍💻 Autor

Projeto desenvolvido para fins acadêmicos na disciplina  
**Advanced Business Development with .NET – Data Science & ML**.  
