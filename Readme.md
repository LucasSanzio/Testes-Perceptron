# README - Modelos de Perceptron

## Sobre os Códigos
Este repositório contém três implementações de modelos de Perceptron utilizando a biblioteca `sklearn`. Cada modelo é treinado para tomar decisões binárias com base em diferentes conjuntos de dados. Abaixo estão os detalhes de cada implementação:

---

## 1. Modelo: Levar Guarda-chuva?

### **Descrição:**
Este modelo de Perceptron é treinado para prever se uma pessoa deve levar um guarda-chuva, com base na presença de nuvens e na previsão de chuva.

### **Entradas (X):**
- `0,0` - Sem nuvens, sem previsão de chuva
- `0,1` - Sem nuvens, previsão de chuva
- `1,0` - Nuvens, sem previsão de chuva
- `1,1` - Nuvens, previsão de chuva

### **Saída (Y):**
- `0` - Não levar guarda-chuva
- `1` - Levar guarda-chuva

---

## 2. Modelo: Ir ao Parque?

### **Descrição:**
Este modelo prevê se uma pessoa deve ir ao parque, considerando as condições climáticas e se é final de semana.

### **Entradas (X):**
- `Tempo ensolarado`
- `Final de semana`
- `Dia chuvoso`

### **Saída (Y):**
- `0` - Não ir ao parque
- `1` - Ir ao parque


---

## 3. Modelo: Comer Fora?

### **Descrição:**
Este modelo prevê se uma pessoa deve comer fora, levando em conta quatro fatores: cansaço, disponibilidade de ingredientes, se o restaurante está aberto e se um pagamento recente foi recebido.

### **Entradas (X):**
- `Estou cansado`
- `Possuo os Ingredientes`
- `Restaurante aberto`
- `Pix vai cair`

### **Saída (Y):**
- `0` - Não comer fora
- `1` - Comer fora
