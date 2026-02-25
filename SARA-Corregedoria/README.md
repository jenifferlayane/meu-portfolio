# ⚖️ Sistema de Análise e Registro de Admissibilidade (SARA 2.0)

> **Status do Projeto:** 🚀 Finalizado / Evolução Contínua  
> **Cliente:** Ministério das Mulheres (via Logiks)  
> **Tecnologias:** Power Apps, Power Automate, HTML Inline, SharePoint  
> **Nota de Ética:** Os dados sensíveis, nomes de servidores e números de processos foram anonimizados nas capturas de tela para preservar o sigilo institucional.

---

### 📝 Visão Geral
O **SARA 2.0** é uma solução de engenharia desenvolvida para transformar a gestão correcional ativa. O sistema substituiu controles manuais por um **motor de inteligência** que automatiza a triagem de admissibilidade, garantindo que processos críticos sejam identificados instantaneamente.

---

### 🛠️ Diferenciais Técnicos & Inovações

| Recurso | Descrição Técnica | Tecnologia |
| :--- | :--- | :--- |
| **Interface Advanced** | Implementação de visualização customizada via **HTML Inline**, permitindo uma hierarquia de dados rica e scannable. | Power Apps |
| **Motor de Cálculo** | Algoritmo em **Power Fx** que processa variáveis (prescrição, assédio, evidências) para gerar score de prioridade. | Power Apps |
| **Lógica Morte Súbita** | Filtro inteligente que identifica automaticamente processos que perderam o objeto ou prazo. | Power Apps |
| **Automação de TAC** | Workflows específicos para monitoramento de Termos de Ajustamento de Conduta com alertas de prazos. | Power Automate |

---

### 🎨 Experiência do Usuário (UI/UX)

#### 🖼️ Painel Principal de Dossiês (Layout Scannable)
*O design utiliza uma **hierarquia cromática** estratégica: Azul (#6366F1) para monitoramento, Roxo (#6D31A2) para governança e Bege para Logs de Auditoria. Isso permite que o técnico identifique o status do processo em milissegundos.*

> ![Dashboard SARA](./img/print_dashboard_sara.png)  
> *Legenda: Visão geral dos cards de processos com lógica de cores para priorização.*

#### 📊 Motor de Priorização e Auditoria
*Refatoração completa dos logs de edição para preservar a integridade das informações e visualização detalhada da pontuação de admissibilidade.*

> ![Pontuação SARA](./img/print_pontuacao_sara.png)  
> *Legenda: Detalhamento do cálculo de pontos (+5 pts, +10 pts) que define a urgência do caso.*

---

### 📈 Ganhos Mensuráveis e Resultados
- [x] **Eficiência Operacional:** Automação da triagem que reduziu o tempo de análise manual.
- [x] **Integridade de Dados:** Implementação de lógica para preservação de quebras de linha (Char 10) em históricos de auditoria.
- [x] **Gestão de Prazos:** Monitoramento automatizado de obrigações de TAC, reduzindo riscos de perda de prazo.

---

### ⚙️ Stack Tecnológica
- **Front-end:** Power Apps Canvas (Custom UI com HTML/CSS).
- **Back-end:** SharePoint Online (Listas Relacionadas).
- **Processamento:** Cloud Flows no Power Automate.
- **Prototipação:** Figma (Design System Institucional).

---

<p align="center">
  <a href="https://github.com/jenifferlayane">⬅️ Voltar ao Perfil Principal</a>
</p>
