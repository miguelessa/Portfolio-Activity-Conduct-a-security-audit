# Portfolio-Activity-Conduct-a-security-audit

# 🔒 Botium Toys - Auditoria de Segurança Interna

## 📋 Visão Geral

**Empresa:** Botium Toys  
**Setor:** Varejo (Brinquedos)  
**Localização:** EUA (com operações online na UE)  
**Data da Auditoria:** 2026

Esta auditoria foi realizada para avaliar a postura de segurança da Botium Toys, uma pequena empresa de brinquedos que está expandindo suas operações online. O objetivo é identificar riscos, vulnerabilidades e lacunas de conformidade para proteger ativos críticos e garantir a continuidade dos negócios.

---

## 🎯 Escopo e Metas

### Escopo
A auditoria abrange **todo o programa de segurança** da Botium Toys, incluindo:
- Ativos físicos e digitais
- Processos internos
- Procedimentos de controle
- Práticas de conformidade

### Metas
- Avaliar ativos existentes
- Preencher a lista de verificação de controles e conformidade
- Identificar controles necessários para melhorar a postura de segurança

---

## 📦 Ativos Gerenciados pelo TI

| Categoria | Ativos |
|-----------|--------|
| **Equipamentos** | Desktops, laptops, smartphones, headsets, cabos, teclados, mouses, docking stations, câmeras de vigilância |
| **Infraestrutura** | Rede interna, acesso à internet, firewall |
| **Sistemas** | Contabilidade, telecomunicações, banco de dados, segurança, e-commerce, gerenciamento de inventário |
| **Dados** | Retenção e armazenamento de dados |
| **Sistemas Legados** | Sistemas em fim de vida que exigem monitoramento humano |
| **Físico** | Produtos na loja/armazém, escritórios |

---

## ⚠️ Avaliação de Risco

### Descrição do Risco
- Gerenciamento inadequado de ativos
- Controles insuficientes
- Conformidade parcial com regulamentações dos EUA e internacionais

### Pontuação de Risco
**8/10** (Alto)

### Principais Achados
- Todos os funcionários têm acesso a dados sensíveis (PII/SPII)
- Ausência de criptografia para dados de cartão de crédito
- Sem princípio de "Least Privilege" ou "Separation of Duties"
- Sem planos de recuperação de desastres
- Sem backups de dados críticos
- Sem sistema de detecção de intrusão (IDS)
- Política de senhas fraca e sem gerenciador centralizado

---

## 🔒 Lista de Verificação de Controles

| Controle | Status |
|----------|--------|
| Least Privilege | ❌ Não |
| Disaster recovery plans | ❌ Não |
| Password policies | ❌ Não |
| Separation of duties | ❌ Não |
| Firewall | ✅ Sim |
| Intrusion detection system (IDS) | ❌ Não |
| Backups | ❌ Não |
| Antivirus software | ✅ Sim |
| Manual monitoring for legacy systems | ✅ Sim |
| Encryption | ❌ Não |
| Password management system | ❌ Não |
| Locks (offices, storefront, warehouse) | ✅ Sim |
| CCTV surveillance | ✅ Sim |
| Fire detection/prevention | ✅ Sim |

**Total:** 6/14 controles implementados (43%)

---

## ✅ Lista de Verificação de Conformidade

### PCI DSS
| Prática | Status |
|---------|--------|
| Apenas usuários autorizados acessam dados de cartão | ❌ Não |
| Dados de cartão armazenados/processados em ambiente seguro | ❌ Não |
| Criptografia para transações de cartão | ❌ Não |
| Políticas seguras de gerenciamento de senhas | ❌ Não |

**PCI DSS:** 0/4 ✅

### GDPR
| Prática | Status |
|---------|--------|
| Dados de clientes da UE mantidos privados/seguros | ❌ Não |
| Plano de notificação em até 72 horas em caso de violação | ✅ Sim |
| Dados classificados e inventariados | ❌ Não |
| Políticas de privacidade aplicadas e documentadas | ✅ Sim |

**GDPR:** 2/4 ✅

### SOC 1 & SOC 2
| Prática | Status |
|---------|--------|
| Políticas de acesso de usuários estabelecidas | ❌ Não |
| Dados sensíveis (PII/SPII) confidenciais/privados | ❌ Não |
| Integridade dos dados garantida | ✅ Sim |
| Dados disponíveis para usuários autorizados | ✅ Sim |

**SOC:** 2/4 ✅

---

## 📈 Resumo dos Resultados

| Área | Status | Pontuação |
|------|--------|-----------|
| Controles de Segurança | 43% implementados | 6/14 |
| PCI DSS | 0% conformidade | 0/4 |
| GDPR | 50% conformidade | 2/4 |
| SOC | 50% conformidade | 2/4 |
| **Risco Geral** | **ALTO** | **8/10** |

---

## 🛠️ Recomendações

### Prioridade Crítica 🔴
1. **Implementar criptografia** para dados de cartão de crédito
2. **Implementar Least Privilege e Separation of Duties**
3. **Estabelecer planos de recuperação de desastres e backups**

### Prioridade Alta 🟠
4. **Implementar IDS (Intrusion Detection System)**
5. **Política de senhas fortes + gerenciador centralizado**
6. **Classificar e inventariar todos os ativos**

### Prioridade Média 🟡
7. **Estabelecer políticas formais de acesso de usuários**
8. **Documentar planos de conformidade e auditoria**

---

## 📄 Conclusão

A Botium Toys apresenta **alto risco de segurança** devido à falta de controles essenciais e conformidade parcial com regulamentações como PCI DSS, GDPR e SOC. Recomenda-se a implementação imediata das ações listadas para proteger dados sensíveis, evitar multas e garantir a continuidade dos negócios.

---

**📅 Próximos Passos:**
1. Implementar controles críticos (criptografia, backups, disaster recovery)
2. Revisar e fortalecer políticas de senha e acesso
3. Realizar auditoria de acompanhamento em 3 meses

---

*Auditoria realizada como parte do portfólio de segurança cibernética.*
