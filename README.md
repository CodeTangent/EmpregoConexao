# 🚀 Conexão Empregos – Automação de Envio de Currículos

**Conexão Empregos** é uma solução desenvolvida em Python para automatizar o envio de currículos, organizando contatos e otimizando o processo de candidatura.

O sistema foi projetado para aumentar produtividade, reduzir esforço manual e organizar o fluxo de envio de forma controlada e eficiente.

---

## 🎯 Proposta

Automatizar um processo repetitivo (envio de currículos) transformando em um fluxo organizado, rastreável e escalável.

O foco é produtividade com controle — não disparo descontrolado.

---

## ✨ Funcionalidades

- 📄 Leitura de contatos via planilha Excel (`contatox.xls`)  
- 📧 Envio automatizado de e-mails com currículos  
- 🔐 Autenticação segura via senha de aplicativo (`senha_app.txt`)  
- 🖥 Interface gráfica com Tkinter  
- 🎯 Controle manual por envio (enviar ou pular empresa)  
- 📊 Acompanhamento de progresso em tempo real  
- 📁 Organização de currículos por área profissional  

---

## 🧠 Estrutura do Projeto

A arquitetura foi organizada para separar responsabilidades e manter segurança:

```text
curriculos/
  ├── administrativo/
  ├── analista_ti/
  ├── logistica/
  └── desenvolvedor/

contatox.xls   → Base de dados com empresas e contatos  
main.py        → Interface + lógica de envio  
senha_app.txt  → Credenciais seguras (não versionadas)  
```

✔ Separação de dados e lógica  
✔ Estrutura escalável  
✔ Fácil manutenção  

---

## ⚙️ Tecnologias Utilizadas

- Python  
- Tkinter (interface gráfica)  
- SMTP (envio de e-mails)  
- Manipulação de Excel  
- Automação de processos  

---

## 📊 Diferenciais

- 🎯 Controle granular (não é envio em massa cego)  
- 🔐 Boas práticas de segurança (dados sensíveis isolados)  
- 📁 Organização por área profissional  
- ⚡ Redução significativa de tempo no processo de candidatura  

---

## 💼 Uso Real

Este sistema é utilizado na prática para:

- Envio organizado de currículos  
- Prospecção de oportunidades  
- Testes de abordagem (A/B com flyers e mensagens)  

---

## 🖼 Demonstração

### Estrutura geral do projeto
<img width="710" height="397" alt="estrutura" src="https://github.com/user-attachments/assets/3b327873-6377-4204-b9d2-41030f74b899" />

### Organização de candidatos por área
<img width="710" height="397" alt="candidatos" src="https://github.com/user-attachments/assets/d4f75c45-babd-4ca5-9691-526ca61b8ba6" />

---

## ⚙️ Como Usar

1. Execute o arquivo `main.py` com Python 3 instalado  
2. Configure o e-mail no arquivo `senha_app.txt`  
3. Preencha a planilha `contatox.xls` com os contatos  
4. Organize os currículos nas pastas por área  
5. Utilize a interface para controlar os envios  

---

## 🚀 Próximos Passos

- 🤖 Automação de respostas para candidatos  
- 📢 Automação de prospecção de clientes  
- 💼 Modelo de assinatura para empresas  
- 📊 Relatórios de envio e performance  

---

## 📜 Segurança

Todos os dados sensíveis foram removidos ou substituídos por placeholders.

Este repositório não expõe:
- E-mails reais  
- Credenciais  
- Informações de candidatos  

---

## 📌 Status do Projeto

- ✔ Sistema funcional  
- ✔ Interface implementada  
- ✔ Uso real validado  
- 🔄 Em evolução para novas automações  

---

## 👨‍💻 Autor

Desenvolvido por **Renan Lima**  

📍 Porto Alegre - RS  
📧 developerchsharp14@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/renan-gabriel-lima  
