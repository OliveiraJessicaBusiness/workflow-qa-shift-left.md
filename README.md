# 📋 Plano de Implantação de Qualidade de Software

## 🚀 Fluxo de Qualidade (Shift Left)

### 1. Planejamento
- Refinamento dos requisitos.
- QA levanta riscos e define objetivos de qualidade.

### 2. Desenvolvimento
- QA define critérios de aceitação e cenários de teste.
- Testes automatizados desde o início.
- Desk Check: QA revisa Pull Requests (PRs), auxilia em testes unitários e CI/CD.
- Code Review com foco na qualidade.

### 3. Testes
- QA realiza Desk Check junto ao time de desenvolvimento para validar funcionalidades antes do teste formal.

### 4. Entrega
- QA executa testes exploratórios, regressivos e monitora os resultados.
- Testes de performance e segurança integrados.
- QA valida métricas, acompanha o ambiente de produção e coleta feedback.
- Monitoramento e alertas automáticos em produção.

---

## 🧪 Quando Aplicar Teste Exploratório e Teste Regressivo

### 1. Recebimento da Nova Funcionalidade
- Início do fluxo: time recebe requisito ou nova entrega.

### 2. Teste Exploratório
- Aplicar sempre que a funcionalidade for nova ou sofrer mudança significativa.
- QA explora livremente para identificar falhas ou comportamentos inesperados.
- Feedback e bugs são enviados ao desenvolvimento.

### 3. Desenvolvimento e Correção de Bugs
- Desenvolvedores implementam ou corrigem o que for necessário.

### 4. Teste Regressivo
- Executar para validar que funcionalidades existentes não foram impactadas.
- Inclui execução da suíte de testes automatizados e testes manuais documentados.

### 5. Liberação para Produção
- Após aprovação em todos os testes, realiza-se o deploy.

📸 [Fluxo de QA - Shift Left](./assets/fluxograma_shift_left_completo_com_teste.png)

---

## 📌 Notas Extras
- Suíte de testes automatizados vinculada ao Teste Regressivo.
- Foco em exploração e descoberta vinculado ao Teste Exploratório.

---

✍ **Autor:** Jessica Carina  
📅 **Última atualização:** 2025-08-11
