Objetivo: Automatizar a execução dos testes para garantir qualidade contínua.

Etapas da Pipeline

Checkout do código
Instalação de dependências
Execução de testes de API
Execução de testes E2E (quando aplicável)
Geração de relatórios

Gatilhos: Push em branch principal
Pull Request

Critérios de Falha: Qualquer teste crítico falhar

Resultado Esperado: Feedback rápido sobre a qualidade do código e estabilidade das features críticas.