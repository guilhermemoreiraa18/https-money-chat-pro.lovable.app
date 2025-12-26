📱 App de Finanças Conversacional — MVP

PRD — App de Finanças Conversacional (MVP)

1) Visão Geral
Problema: Pessoas desistem de controlar finanças por exigirem entradas manuais complexas e interfaces pouco personalizadas.
Solução: Um aplicativo que funciona por conversas naturais, registra e classifica automaticamente gastos, ajuda a definir metas, fornece dicas de economia e mostra relatórios simples.
Objetivo do MVP: Validar se a interface conversacional reduz atrito para registrar gastos e se as dicas personalizadas aumentam a retenção e o atingimento de metas financeiras.

2) Objetivos de Negócio
- Aumentar adesão ao controle financeiro.
- Elevar frequência de uso via chat e lembretes úteis.
- Demonstrar valor com metas atingidas e economia percebida.
KPIs:
- % usuários que registram 3 gastos na primeira semana.
- Tempo médio para primeiro registro < 60s após onboarding.
- % metas definidas e atingidas.
- Acurácia classificação automática ≥ 85%.
- NPS/CSAT ≥ 4/5.

3) Público-Alvo & Personas
- Iniciante Organizado: quer começar sem planilha.
- Autônomo Prático: renda variável, precisa agilidade.
- Aperfeiçoador: já testou apps, quer menos burocracia.

4) Escopo do MVP
Must:
- Registrar gastos via chat em linguagem natural.
- Classificação automática por categoria.
- Definir e acompanhar meta mensal.
- Dicas do “Agente Financeiro”.
- Relatórios simples (gastos por categoria, evolução da meta).
Should:
- Reconhecimento de datas relativas, locais.
- Edição/remoção de gastos via chat.
Won’t:
- Conexão automática a bancos.
- Planejamento de longo prazo.

5) Experiência do Usuário
Fluxos:
- Onboarding simples.
- Registrar gasto via chat.
- Definir meta.
- Ver relatório.
- Receber dica.
Componentes:
- Tela de Conversa.
- Tela de Metas.
- Tela de Relatórios.
- Tela de Dicas.

6) Requisitos Funcionais
- NLU para extrair valor, data, categoria.
- Registro e edição de transações.
- Metas mensais com alertas.
- Dicas baseadas em comportamento.
- Relatórios com gráficos simples.

7) Requisitos Não Funcionais
- LGPD: consentimento, exclusão, portabilidade.
- Desempenho: resposta < 2s.
- Disponibilidade: 99% no MVP.
- Acessibilidade: contraste AA, suporte leitor de tela.

8) Dados & Modelo
Entidades: User, Transaction, Goal, Tip.
Categorias: alimentação, transporte, moradia, contas, saúde, educação, lazer, assinaturas, outros.

9) Integrações
- Push/local notifications.
- Storage: SQLite local + sincronização cloud.

10) Segurança & Conformidade
- Criptografia AES-256 e TLS.
- Consentimento LGPD.

11) Métricas & Instrumentação
Eventos: app_opened, transaction_created, goal_created, tip_viewed, report_viewed.
Funis: Onboarding → 1º gasto → 1ª meta → relatório.

12) Critérios de Aceite
- Chat registra gasto corretamente.
- Classificação ≥ 85%.
- Metas atualizam em tempo real.
- Dicas úteis semanais.
- Relatórios rápidos (<1s para até 500 transações).

13) Plano de Validação
- Teste com 10–20 usuários.
- Hipóteses: chat reduz atrito, dicas geram ações, metas aumentam consciência.
- Métricas: ≥ 60% registram 3+ gastos na 1ª semana.

14) Roadmap (8 semanas)
S1: Infra + onboarding.
S2: NLU + registro.
S3: Metas.
S4: Relatórios.
S5: Dicas.
S6: Acessibilidade + notificações.
S7: Qualidade.
S8: Beta fechado.

15) Requisitos Técnicos
- Frontend: React Native/Flutter.
- Backend: Node.js / Python FastAPI.
- DB: SQLite + Postgres.
- NLU: regras + classificadores simples.

16) Conteúdo & Tom de Voz
- Educativo, acessível, encorajador.
- Evitar jargão financeiro.

17) Riscos & Mitigações
- Acurácia NLU baixa → confirmação.
- Baixa retenção → lembretes e metas.
- Privacidade → LGPD rigorosa.

18) Backlog Pós-MVP
- Conexão com bancos.
- Metas semanais.
- IA generativa para dicas.
- Gamificação.

19) Critérios de Lançamento
- Critérios de aceite atendidos.
- KPIs mínimos alcançados.
- Bugs críticos resolvidos.
- Revisão LGPD concluída.
📌 Resumo do App
O App de Finanças Conversacional é uma solução simples e intuitiva para quem quer organizar suas finanças sem burocracia.
Em vez de formulários complexos, o usuário conversa com um Agente Financeiro Virtual para:

Registrar gastos em linguagem natural (ex.: “Gastei R$50 no mercado”).
Classificar automaticamente as transações por categoria.
Definir metas financeiras e acompanhar o progresso.
Receber dicas personalizadas para economizar.
Visualizar relatórios simples com gráficos e insights.

O objetivo é tornar o controle financeiro fácil, rápido e acessível, especialmente para iniciantes.
<img width="616" height="934" alt="image" src="https://github.com/user-attachments/assets/66c347b1-b2df-4d2e-a510-129942fa4f7f" />


💭 Reflexão sobre o Processo
✅ O que funcionou bem?

Clareza na definição do MVP: Conversar com a IA ajudou a estruturar rapidamente escopo, funcionalidades e critérios de aceite.
Organização do PRD: A IA forneceu um documento completo, cobrindo desde UX até requisitos técnicos.
Sugestões de roadmap e fluxos visuais: Facilitou visualizar etapas e priorizar entregas.

⚠️ O que não funcionou como esperado?

Geração de imagem: O wireframe gerado foi útil, mas simples demais para prototipagem avançada.
Detalhes técnicos: Algumas escolhas (ex.: arquitetura) ainda precisam ser validadas com desenvolvedores.

📚 O que aprendi sobre conversar com IAs?

Quanto mais contexto, melhor: Fornecer problema, público-alvo e funcionalidades-chave fez a IA entregar respostas muito mais precisas.
Iteração é essencial: Refinar pedidos (ex.: PRD, roadmap, README) gera resultados cada vez mais completos.
IA como parceiro de ideação: Excelente para estruturar ideias, mas decisões finais devem ser validadas com especialistas e usuários.


🚀 Próximos Passos

Criar wireframes detalhados com base no fluxo visual.
Implementar MVP seguindo o roadmap.
Validar com usuários reais e ajustar conforme feedback.
