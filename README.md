# 🎭 Social Engineering Toolkit (SET) - Demonstração Educacional

<div align="center">

![Kali Linux](https://img.shields.io/badge/Platform-Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![SET](https://img.shields.io/badge/Tool-SET%20Toolkit-FF6B6B?style=for-the-badge&logo=security&logoColor=white)
![Education](https://img.shields.io/badge/Purpose-Educational-4ECDC4?style=for-the-badge&logo=graduation-cap&logoColor=white)

</div>

## ⚠️ **AVISO IMPORTANTE DE SEGURANÇA**

> 🚨 **Este tutorial é destinado EXCLUSIVAMENTE para fins educacionais e testes em ambientes controlados com autorização prévia. O uso não autorizado dessas técnicas é ILEGAL e pode resultar em sérias consequências legais.**

---

## 🎯 **Objetivo do Projeto**

Demonstrar como funciona um ataque de **Credential Harvesting** utilizando o Social Engineering Toolkit, uma ferramenta amplamente usada por analistas de segurança para:
- 🔍 **Testes de penetração autorizados**
- 🛡️ **Avaliação de vulnerabilidades humanas**
- 📚 **Treinamento de conscientização em segurança**

---

## 🛠️ **Pré-requisitos**

### Ambiente de Laboratório Necessário:
- 🐉 **Kali Linux** (distribuição de segurança)
- 🌐 **Rede controlada/isolada** (VMware, VirtualBox)
- 📝 **Autorização explícita** para testes
- 🎯 **Máquina alvo** (própria ou autorizada)

---

## 🚀 **Execução Passo a Passo**

### **Fase 1: Preparação do Ambiente** 🔧

```bash
# 1️⃣ Inicializar o Kali Linux
# Boot do sistema operacional de segurança

# 2️⃣ Elevar privilégios administrativos
sudo su
```

### **Fase 2: Ativação da Ferramenta** ⚡

```bash
# 3️⃣ Lançar o Social Engineering Toolkit
setoolkit
```

<div align="center">
<img src="https://img.shields.io/badge/Status-Tool%20Initialized-success?style=flat-square&logo=check&logoColor=white"/>
</div>

### **Fase 3: Configuração do Ataque** 🎯

```
┌─────────────────────────────────────┐
│  4️⃣ MENU PRINCIPAL                 │
│  [1] Social-Engineering Attacks    │
│     ↳ Seleção: 1                   │
└─────────────────────────────────────┘

┌─────────────────────────────────────┐
│  5️⃣ VETORES DE ATAQUE             │
│  [2] Website Attack Vectors        │
│     ↳ Seleção: 2                   │
└─────────────────────────────────────┘

┌─────────────────────────────────────┐
│  6️⃣ MÉTODO DE CAPTURA             │
│  [3] Credential Harvester Attack   │
│     ↳ Seleção: 3                   │
└─────────────────────────────────────┘

┌─────────────────────────────────────┐
│  7️⃣ TÉCNICA DE CLONAGEM           │
│  [2] Site Cloner                   │
│     ↳ Seleção: 2                   │
└─────────────────────────────────────┘
```

### **Fase 4: Implementação** 🌐

```bash
# 8️⃣ Inserir URL do site alvo para clonagem
# Exemplo: https://exemplo-login.com
# ⚠️ APENAS sites de teste ou próprios!
```

### **Fase 5: Ativação do Servidor Malicioso** 🕸️

```bash
# 9️⃣ O SET criará um servidor local
# Acesso via: http://[IP_DA_MAQUINA_ATACANTE]
# A vítima será redirecionada para o clone
```

---

## 📊 **Resultado da Demonstração**

### **Captura de Credenciais Simulada:**

<div align="center">

```
🎯 CREDENTIAL HARVESTER - RESULTADO
═══════════════════════════════════════
👤 Username: usuario_teste@exemplo.com
🔐 Password: ************
🌐 IP Origem: 192.168.1.100
⏰ Timestamp: 2024-08-28 15:30:22
═══════════════════════════════════════
```

</div>

### **Exemplo Visual:**
![Captura de Credenciais](https://github.com/user-attachments/assets/5f9c6a89-1ee7-48c2-80b8-8963962ed505)

---

## 🛡️ **Medidas de Proteção Demonstradas**

### **Como Detectar Este Ataque:**
1. 🔍 **Verificação de URL** - Sempre confirmar domínio legítimo
2. 🔒 **Certificados SSL** - Verificar HTTPS válido
3. 📧 **Origem do link** - Desconfiar de emails suspeitos
4. 🛡️ **2FA** - Autenticação de dois fatores como proteção

### **Contramedidas Organizacionais:**
- 📚 **Treinamento de conscientização**
- 🚫 **Filtros de email avançados**
- 🔍 **Monitoramento de rede (SOC)**
- 📊 **Simulações regulares de phishing**

---

## 📖 **Contexto Educacional**

### **Por que Estudar Social Engineering?**
- 🎯 **85% dos ataques** exploram falhas humanas
- 🛡️ **Analistas SOC** precisam entender técnicas
- 📈 **Testes de penetração** exigem conhecimento completo
- 🔬 **Pesquisa em segurança** demanda expertise técnica

---

## ⚖️ **Aspectos Legais e Éticos**

<div align="center">

### 🚨 **LEMBRETE CRÍTICO** 🚨

</div>

```
┌────────────────────────────────────────────────┐
│  ❌ NUNCA utilize sem autorização explícita    │
│  ✅ SEMPRE documente testes autorizados        │
│  📋 SEMPRE obtenha consentimento por escrito   │
│  🛡️ SEMPRE use ambiente controlado            │
└────────────────────────────────────────────────┘
```

---

## 📚 **Recursos para Aprofundamento**

- 🎓 **OWASP Testing Guide**
- 📖 **NIST Cybersecurity Framework**
- 🔍 **MITRE ATT&CK - Social Engineering**
- 🛡️ **SANS SEC504 - Hacker Tools and Techniques**

---

<div align="center">

### 💡 **"Conhecer as técnicas de ataque é fundamental para construir defesas eficazes"**

![Made with](https://img.shields.io/badge/Made%20with-Kali%20Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![For](https://img.shields.io/badge/For-Security%20Education-4ECDC4?style=flat-square&logo=graduation-cap&logoColor=white)
![By](https://img.shields.io/badge/By-SOC%20Analyst-FF6B6B?style=flat-square&logo=security&logoColor=white)

</div>
