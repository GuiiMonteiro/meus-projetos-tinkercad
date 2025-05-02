# 🎵 Mini Piano com Arduino

Este projeto é um mini teclado musical feito com Arduino. Ele utiliza botões para tocar diferentes notas sonoras e acende um LED para indicar a atividade.

---

## ⚙️ Componentes Utilizados

- Arduino UNO R3
- Placa de Ensaio Pequena (Breadboard)
- Resistor de 120 Ohms
- LED Verde
- Buzzer Piezo
- 7 Botões push-button
- Jumpers (fios de conexão)

![Mini piano circuito](./img/circuito.png)


---

## 🧠 Lógica do Código

- Cada botão está ligado a uma nota musical (Dó a Si).
- Ao pressionar um botão:
  - A nota correspondente é tocada no buzzer.
  - O LED verde acende enquanto a nota é emitida.
- O buzzer e o LED desligam quando nenhum botão está pressionado.

---

## 📄 Código

O código está comentado em **português e inglês**, facilitando o aprendizado e a compreensão técnica para falantes de diferentes idiomas.

```cpp
int buzzer = 2; // Pino do buzzer / Buzzer pin
int led = 4; // Pino do LED de funcionamento / Status LED pin
// ...
