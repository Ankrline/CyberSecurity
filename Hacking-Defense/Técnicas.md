# 🔹 **Técnicas de Ataques e Defesa** 🔥  

A cibersegurança envolve tanto a **identificação e exploração de vulnerabilidades** quanto a **implementação de defesas contra ataques**. Nesta seção, você encontrará conceitos fundamentais sobre **testes de invasão (Pentest), engenharia social, ataques Man-in-the-Middle (MitM), varredura de rede e exploração de vulnerabilidades**.  

O objetivo desses estudos não é apenas aprender a atacar, mas principalmente **entender como proteger sistemas** contra essas ameaças.  

---

## 🏆 **Tópicos abordados**  

### 🛠 **1. Fundamentos de Testes de Invasão (Pentest)**  
📌 **O que é Pentest?**  
Um **teste de invasão** (ou **Penetration Test**) é um processo onde especialistas em segurança tentam encontrar e explorar vulnerabilidades em sistemas, redes ou aplicativos. O objetivo é identificar falhas antes que criminosos cibernéticos possam explorá-las.  

📌 **Fases do Pentest:**  
1️⃣ **Reconhecimento:** Coleta de informações sobre o alvo (ex.: domínios, endereços IP, tecnologia usada).  
2️⃣ **Varredura:** Identificação de portas abertas e serviços rodando no sistema.  
3️⃣ **Enumeração:** Descoberta de usuários, versões de software e outras informações úteis.  
4️⃣ **Exploração:** Tentativa de invadir o sistema explorando vulnerabilidades conhecidas.  
5️⃣ **Pós-Exploração:** O que fazer após obter acesso ao sistema.  
6️⃣ **Relatório:** Documentação das vulnerabilidades encontradas e sugestões de mitigação.  

✅ Ferramentas populares: **Nmap, Metasploit, Burp Suite, Nikto, John the Ripper**.  

---

### 🎭 **2. Tópicos em Engenharia Social**  
📌 **O que é Engenharia Social?**  
A **Engenharia Social** é um tipo de ataque cibernético que explora a **manipulação psicológica** para enganar usuários e fazê-los revelar informações sensíveis, como senhas e dados financeiros.  

📌 **Principais técnicas de Engenharia Social:**  
🔹 **Phishing:** E-mails ou mensagens falsas que tentam roubar credenciais.  
🔹 **Spear Phishing:** Phishing direcionado a uma pessoa ou empresa específica.  
🔹 **Baiting:** Uso de dispositivos infectados (ex.: pendrives) para infectar sistemas.  
🔹 **Pretexting:** Criação de uma identidade falsa para obter informações sigilosas.  
🔹 **Vishing:** Enganação por chamadas telefônicas.  

✅ Defesa contra Engenharia Social:  
✔ Sempre verifique remetentes e links antes de clicar.  
✔ Nunca forneça senhas ou dados sigilosos sem confirmar a identidade do solicitante.  
✔ Desconfie de urgências e ameaças em e-mails.  

---

### 🔗 **3. Man in the Middle: Ataques e Mitigações**  
📌 **O que é um ataque MitM?**  
Um **Man-in-the-Middle (MitM)** ocorre quando um atacante intercepta e possivelmente altera a comunicação entre duas partes sem que elas percebam.  

📌 **Exemplos de ataques MitM:**  
🔹 **Interceptação de Wi-Fi:** Ataques em redes públicas sem criptografia.  
🔹 **ARP Spoofing:** O atacante engana a rede local, fazendo com que os dados passem por ele.  
🔹 **DNS Spoofing:** Redireciona o tráfego para sites falsos sem o conhecimento do usuário.  
🔹 **SSL Stripping:** Remove a criptografia HTTPS, permitindo que o tráfego seja lido em texto plano.  

✅ Como se proteger contra ataques MitM:  
✔ Evite redes Wi-Fi públicas sem VPN.  
✔ Use conexões HTTPS sempre que possível.  
✔ Ative autenticação multifator (MFA).  
✔ Utilize DNS seguros (como 1.1.1.1 da Cloudflare).  

---

### 📡 **4. Conceitos e Técnicas de Varredura de Rede**  
📌 **O que é varredura de rede?**  
A **varredura de rede** é uma técnica usada para mapear ativos de uma rede, identificar portas abertas e descobrir possíveis vulnerabilidades.  

📌 **Ferramentas populares:**  
🔹 **Nmap:** Scanner de rede para descobrir hosts e serviços ativos.  
🔹 **Zenmap:** Interface gráfica do Nmap.  
🔹 **Netcat:** Ferramenta para leitura e escrita de dados em redes.  

✅ Principais tipos de varredura:  
✔ **Varredura de portas (Port Scanning):** Identifica portas abertas em um sistema.  
✔ **Fingerprinting:** Descobre sistemas operacionais e serviços em execução.  
✔ **Varredura de vulnerabilidades:** Usa ferramentas como Nessus ou OpenVAS para detectar falhas.  

---

### 🕵️ **5. Princípios de Enumeração e Exploração de Vulnerabilidades**  
📌 **O que é Enumeração?**  
A enumeração é a fase onde o invasor coleta **informações detalhadas** sobre um sistema, como usuários, grupos, serviços em execução e versões de software.  

📌 **Como as vulnerabilidades são exploradas?**  
🔹 **Ataques de força bruta:** Tentativas de adivinhar senhas usando dicionários.  
🔹 **Exploração de software desatualizado:** Uso de exploits em versões vulneráveis.  
🔹 **Escalada de privilégios:** Obtenção de acesso administrativo em um sistema.  

✅ Ferramentas utilizadas:  
✔ **Metasploit:** Framework para exploração de vulnerabilidades.  
✔ **Hydra:** Ataques de força bruta.  
✔ **Nikto:** Scanner de vulnerabilidades em servidores web.  

---

### 🧩 **6. Técnicas de Exploração de Vulnerabilidades**  
📌 **O que são exploits?**  
Um **exploit** é um código ou técnica usada para tirar vantagem de uma vulnerabilidade em um sistema.  

📌 **Principais categorias de exploits:**  
🔹 **Zero-Day:** Exploração de falhas desconhecidas pelo fabricante.  
🔹 **Buffer Overflow:** Substituição da memória para execução de código malicioso.  
🔹 **Injeção de SQL (SQLi):** Manipulação de bancos de dados através de inputs maliciosos.  

✅ Como se proteger:  
✔ Mantenha softwares e sistemas atualizados.  
✔ Use Firewalls e IDS/IPS para monitorar acessos suspeitos.  
✔ Não utilize credenciais padrão em servidores e aplicações.  

---

### 🔓 **7. Pós-Exploração em Sistemas Comprometidos**  
📌 **O que acontece após uma invasão?**  
Após comprometer um sistema, um atacante pode:  
🔹 **Escalar privilégios** para obter controle total.  
🔹 **Criar backdoors** para acessos futuros.  
🔹 **Exfiltrar dados** sigilosos.  
🔹 **Cobrir rastros** para evitar detecção.  

📌 **Defesa contra pós-exploração:**  
✅ **Monitoramento contínuo:** Uso de SIEMs para detecção de atividades suspeitas.  
✅ **Segmentação de rede:** Limita o impacto de um ataque.  
✅ **Resposta a incidentes:** Ter um plano de ação para detectar, conter e mitigar invasões.  

---
Se tiver dúvidas ou quiser compartilhar experiências, contribua no repositório! 🚀  

---
