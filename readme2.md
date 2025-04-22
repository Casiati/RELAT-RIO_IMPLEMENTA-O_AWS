# 🛡️ Relatório de Implementação de Medidas de Segurança na AWS

**Data:** 15/04/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Lucas Batista Robiati

---

## 📌 Introdução

Este relatório apresenta o processo de implementação de medidas de segurança na empresa **Abstergo Industries**, conduzido por **Lucas Batista Robiati**.  
O objetivo foi reforçar a **segurança na nuvem AWS**, utilizando três soluções práticas que aumentam a proteção de dados, o controle de acesso e a visibilidade de eventos.

---

## 🛠️ Descrição do Projeto

A implementação foi dividida em **3 medidas principais de segurança**, descritas a seguir:

---

### 🔐 Medida 1: AWS Identity and Access Management (IAM)
- **Foco:** Gerenciamento de acesso baseado em permissões mínimas
- **Caso de uso:**  
  Foi realizada a reestruturação das permissões com base no princípio do menor privilégio. Perfis de usuários e políticas foram revisados para garantir acesso apenas ao necessário, com autenticação multifator (MFA) habilitada para contas privilegiadas.

---

### 🔎 Medida 2: AWS CloudTrail
- **Foco:** Auditoria e monitoramento de atividades
- **Caso de uso:**  
  O AWS CloudTrail foi ativado em todas as regiões para registrar chamadas de API, permitindo o rastreamento detalhado de ações realizadas nos recursos da AWS. Isso aumenta a visibilidade e facilita a identificação de comportamentos suspeitos ou não autorizados.

---

### 🧱 Medida 3: AWS Trusted Advisor
- **Foco:** Análise de segurança e boas práticas operacionais
- **Caso de uso:**  
  O AWS Trusted Advisor foi utilizado para escanear a infraestrutura da empresa e gerar recomendações automáticas de segurança, como uso de autenticação multifator, exposição de portas públicas e uso de grupos de segurança abertos.  
  A ferramenta também identificou pontos de otimização de custos e performance, fortalecendo a postura de segurança geral da empresa.

---

## ✅ Conclusão

A implementação das ferramentas de segurança proporcionou à **Abstergo Industries** maior controle, rastreabilidade e conformidade na infraestrutura em nuvem.  
Essas ações reforçam a proteção contra acessos indevidos e garantem a integridade dos dados e operações da empresa.  
Recomenda-se a manutenção dessas práticas e a adoção contínua de novas soluções de segurança.

---

## 📎 Anexos e Documentações

- 📘 [AWS IAM – Documentação Oficial](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/introduction.html)  
- 📘 [AWS CloudTrail – Documentação Oficial](https://docs.aws.amazon.com/pt_br/awscloudtrail/latest/userguide/cloudtrail-user-guide.html)  
- 📘 [AWS Trusted Advisor – Documentação Oficial](https://docs.aws.amazon.com/pt_br/awssupport/latest/user/trusted-advisor.html)  
- 📊 Plano interno de conformidade e checklist de segurança *(anexo interno)*

---

### ✍️ Assinatura do Responsável  
**Lucas Batista Robiati**
