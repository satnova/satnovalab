# Projeto: Monitoramento de Eixos com MMA7361 e Arduino/ESP32

Este projeto configura um sensor acelerômetro **MMA7361** conectado a um **Arduino Uno** ou **ESP32** para monitorar os eixos X, Y e Z, convertendo os dados analógicos em tensões e exibindo-os no monitor serial.

---

## 📝 **Descrição do Projeto**

O objetivo deste projeto é:
- Ler os valores dos eixos X, Y e Z do sensor MMA7361.
- Converter os valores analógicos em tensões reais (em Volts).
- Exibir os dados no monitor serial.
- (Opcional) Usar ESP32 para comunicação sem fio.

Este projeto pode ser usado em aplicações como monitoramento de aceleração, detecção de movimento, e integração com CubeSats.

---

## 📋 **Requisitos**

### **Hardware**
- Arduino Uno ou ESP32-WROOM-32D
- Sensor Acelerômetro MMA7361
- Protoboard
- Cabos jumper
- Fonte de alimentação (se necessário)

### **Software**
- [Arduino IDE](https://www.arduino.cc/en/software) ou VS Code com extensão PlatformIO
- Biblioteca para ESP32 (caso o use)
  
---

## ⚙️ **Montagem do Circuito**

1. **Conexão do MMA7361**:
   - **VCC** → 3.3V ou 5V do Arduino/ESP32
   - **GND** → GND do Arduino/ESP32
   - **X** → Pino analógico A0
   - **Y** → Pino analógico A1
   - **Z** → Pino analógico A2

2. Caso esteja usando um **ESP32**, conecte os pinos X, Y e Z aos pinos analógicos (GPIO36, GPIO39, etc.).

---

## 🚀 **Como Usar**

1. **Baixe o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio

## 📚 Referências**
* Arduino IDE Documentação
* ESP32 com Arduino IDE
* Datasheet do MMA7361

✨ Autor
* Luis Cláudio
* E-mail: contato.satnova@gmail.com
* LinkedIn: www.linkedin.com/in/lcdvita
