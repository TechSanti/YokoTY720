<div align="center">

<h1>📟 YokoTY720</h1>

<h3>Monitor serial profissional para o multímetro Yokogawa TY720</h3>

<p>
  Aplicativo desktop desenvolvido em Python e PyQt6 para leitura,
  monitoramento e análise de dados seriais do Yokogawa TY720.
</p>

<p>
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/PyQt6-Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white">
  <img src="https://img.shields.io/badge/pyserial-Serial-4B8BBE?style=for-the-badge">
  <img src="https://img.shields.io/badge/Windows-Suportado-0078D6?style=for-the-badge&logo=windows&logoColor=white">
  <img src="https://img.shields.io/badge/Versão-1.0.0.0-555555?style=for-the-badge">
</p>
</div>

---
<img width="802" height="632" alt="Capturar" src="https://github.com/user-attachments/assets/1a621615-cb45-4259-8506-6fa7fe973507" />

</div>

---
<img width="800" height="440" alt="Capturar2" src="https://github.com/user-attachments/assets/4c3422ac-c4a1-48e6-a5d1-ab535b02f7bf" />

</div>

---

## 📌 Sobre o projeto

O **YokoTY720** é uma aplicação desktop criada para realizar a comunicação serial com o multímetro **Yokogawa TY720**, exibindo as leituras em uma interface moderna, proporcional e responsiva.

O projeto possui visor vetorial, redimensionamento proporcional, modo de visualização ampliado com `F11`, suporte a vários idiomas e ferramentas de diagnóstico e análise local.

## ✨ Principais recursos

- 🔌 Comunicação serial com o Yokogawa TY720.
- 📊 Leitura e monitoramento em tempo real.
- 🖥️ Visor vetorial com proporção preservada.
- 🔄 Redimensionamento proporcional da interface.
- ⛶ Modo ampliado com `F11`.
- ↩️ Restauração da interface com `F11` ou `Esc`.
- 🌍 Suporte para 12 idiomas.
- 🧪 Modo demonstração com valores simulados.
- 💡 Teste completo do visor LCD.
- 🔍 Diagnóstico e captura da comunicação serial.
- 📈 Análise local das leituras no computador.
- 💾 Importação de memória do equipamento.
- 📄 Exportação de registros para CSV.
- ⚙️ Configuração portátil salva em `YokoTY720.ini`.
- 📝 Registro de erros junto ao arquivo `.py` ou `.exe`.
- 📦 Compatibilidade com compilação para Windows usando Nuitka.

## 🔧 Comunicação serial

| Configuração | Valor |
|---|---:|
| Baud rate | 9600 |
| Bits de dados | 8 |
| Paridade | Nenhuma |
| Bits de parada | 2 |

## 🛠️ Tecnologias utilizadas

- 🐍 Python
- 🎨 PyQt6
- 🔗 pyserial
- 🪟 Windows
- ⚙️ Nuitka

## 📦 Instalação

```bash
pip install PyQt6 pyserial
