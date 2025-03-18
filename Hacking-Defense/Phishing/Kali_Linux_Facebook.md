# 🛑 Criação de um Phishing com o Kali Linux

## 📌 Introdução
Este repositório documenta um projeto prático de **Phishing** utilizando o **Kali Linux** e a ferramenta **SET (Social-Engineer Toolkit)**. 
Iremos utilizar os conceitos aprendidos até aqui para **reproduzir** (ou até mesmo melhorar) este projeto prático. O objetivo é demonstrar como funciona a captura de credenciais de login do Facebook para fins educativos e de conscientização sobre segurança digital.

> **⚠️ Aviso:** Este projeto tem propósitos estritamente educacionais. A utilização indevida dessas técnicas para fins maliciosos é ilegal e antiética. Use com responsabilidade.

---

## 🛠 Ferramentas Utilizadas
Para a execução deste projeto, utilizamos:
- **Kali Linux**
- **SET (Social-Engineer Toolkit)**
- **Terminal com acesso root**

---

## 🔧 Configurando o Phishing no Kali Linux
1. **Acesse o terminal como root:**
   ```bash
   sudo su
   ```
2. **Inicie o SET:**
   ```bash
   setoolkit
   ```
3. **Escolha o tipo de ataque:**
   - `1` Social-Engineering Attacks
4. **Selecione o vetor de ataque:**
   - `2` Web Site Attack Vectors
5. **Escolha o método de ataque:**
   - `3` Credential Harvester Attack Method
6. **Utilize a opção de clonar site:**
   - `2` Site Cloner
7. **Obtenha o endereço da sua máquina:**
   ```bash
   ifconfig
   ```
8. **Digite a URL do site que deseja clonar:**
   ```
   http://www.facebook.com
   ```

---

## 📊 Resultados
Se configurado corretamente, ao acessar o link gerado, a vítima visualizará uma cópia idêntica do Facebook. Ao inserir as credenciais, elas serão capturadas e armazenadas no Kali Linux.

![image](https://github.com/user-attachments/assets/a82b7055-3e3a-4ef0-9582-7306d21f89e7)

OBS: Os navegadores atuais detectam o site clonado, então eles impedem que os dados sejam transferido, por conta disso ao testar pode não se opter o resultado.

---

