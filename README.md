# Sistema de Monitorização Térmica para Baterias Recarregáveis
## Certificadora de Competência 2 - UTFPR-CP (2026)

Este projeto consiste em um sistema embarcado inteligente projetado para monitorar a temperatura de baterias de alta densidade energética (Li-Po e Li-Ion) em tempo real. O objetivo principal é prevenir acidentes laboratoriais, como a **Fuga Térmica (Thermal Runaway)**, através de alertas visuais, sonoros e atuação preventiva.

O projeto foi desenvolvido para atender às necessidades do laboratório de engenharia e do projeto de extensão **Overload**, onde o uso constante de protótipos exige protocolos rigorosos de segurança.

---

## 🚀 Problema e Solução

### O Problema
Baterias recarregáveis danificadas ou sob estresse podem superaquecer, liberando gases tóxicos, fumaça corrosiva e, em casos extremos, sofrendo combustão espontânea ou explosão. Em ambientes acadêmicos e hobbistas, o monitoramento manual é muitas vezes falho ou inexistente.

### Solução Proposta
Um dispositivo de hardware não invasivo que utiliza um sensor de precisão para aferição contínua. O sistema processa os dados via microcontrolador e atua antes que a falha crítica ocorra, acionando sistemas de alertas de segurança.

---

## 🛠️ Stack Tecnológica

### Hardware
- **Cérebro:** Microcontrolador Microchip **PIC18F4550**.
- **Sensor:** **LM35** (Sensor de temperatura centígrado de precisão).
- **Interface Visual:** Display **LCD 16x2** (Controlador HD44780).
- **Atuadores/Alertas:**
    - Buzzer Ativo (Alerta sonoro).
    - LCD de Alerta Crítico.

### Software & Ferramentas
- **Linguagem:** C (Compilador XC8).
- **IDE:** MPLAB X IDE.
- **Simulação:** Proteus ISIS.

---

## ⚙️ Funcionalidades Implementadas

O firmware desenvolvido oferece as seguintes capacidades:

1.  **Leitura Analógica (ADC):** Conversão do sinal do LM35 para graus Celsius com ajuste de tempo de aquisição.
2.  **Monitoramento em Tempo Real:** Exibição contínua da temperatura e status do sistema no LCD.
3.  **Alerta** Acionamento de alarme sonoro e LDC com alarme.

---

## 👥 Equipe 4

* **Eduardo Mestre da Gloria** - RA: 2453460
* **Ellian Maciel Moreira Ribeiro** - RA: 2417693
* **Gabriel Augusto Morisaki Rita** - RA: 2268191
* **Louise Paccola Peccin** - RA: 2475502
* **Vithoria Cabreira Monteiro de Souza** - RA: 2410400

---

## 📅 Cronograma de Desenvolvimento

- **01/05 - 15/05:** Elaboração do circuito e lógica inicial.
- **15/05 - 29/05:** Implementação do circuito no Proteus.
- **29/05 - 12/06:** Desenvolvimento avançado do código em C.
- **12/06 - 26/06:** Testes finais, debug e escrita do relatório.
- **29/06:** Entrega Final.

---

## 🎓 Contexto Acadêmico

Projeto desenvolvido para a disciplina **EC46H - Certificadora da Competência 2**, sob orientação da **Professora Monique Emídio de Oliveira**, na Universidade Tecnológica Federal do Paraná (UTFPR), campus Cornélio Procópio.
