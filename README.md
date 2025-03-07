# 📡 Sensor Ultrassônico com Arduino

Este projeto utiliza um **sensor ultrassônico** para medir distâncias e exibir os valores no **monitor serial do Arduino**. O sensor calcula a distância com base no tempo que um sinal sonoro leva para ir até um objeto e voltar.

## ⚙️ Como Funciona?
1. O **pino TRIGGER** envia um pulso ultrassônico.
2. O **pino ECHO** recebe o retorno desse pulso.
3. O tempo que o som demora para voltar é convertido em distância.
4. O valor é mostrado no **monitor serial** do Arduino

![image](https://github.com/user-attachments/assets/64e97eca-ef82-49cd-ab13-11918f084062)

## 🔌 Esquema de Ligações  

| Componente               | Pino no Arduino |
|-------------------------|----------------|
| **Sensor Ultrassônico (Trigger)** | 11 |
| **Sensor Ultrassônico (Echo)** | 12 |
| **Alimentação do Sensor (VCC)** | 5V |
| **GND do Sensor** | GND |


## 📂 Docs   
O código-fonte pode ser acessado aqui:  
</> [Código](docs/Código)  


## 🔗 Simulação no Tinkercad
[Acesse aqui a simulação do semáforo](https://www.tinkercad.com/things/9vQ1JMXBe7l-sensor-ultrassonico?sharecode=4dW8RHvU8C7ZafbCxqkpLUHNCDzWWhmmKWGl_FAmt24)





