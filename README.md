# 📈 Automação de Postagens em Redes Sociais com IA

Este workflow do n8n automatiza a criação e publicação de conteúdo em múltiplas redes sociais com base em tendências do Google Trends e geração de texto por IA.

## 🚀 Visão Geral

- 🔍 **Busca por tendências** no Google Trends via SerpAPI
- 🤖 **Seleção e criação de conteúdo** usando Perplexity AI e OpenAI GPT-3.5
- 📣 **Publicação automática** no LinkedIn, Twitter/X e Facebook
- 📅 **Agendamento diário** de postagens (ex: 6h e 18h)
- 📊 **Registro em Google Sheets** com data, horário e desempenho

## 🛠️ Requisitos

- Instância do n8n (auto-hospedada ou na nuvem)
- Credenciais configuradas para:
  - SerpAPI (Google Trends)
  - Perplexity AI
  - OpenAI
  - LinkedIn API
  - Google Sheets

## ⚙️ Como Usar

1. **Importar o Workflow:**
   - Acesse: [n8n - AI Social Media Automation](https://n8n.io/workflows/4352-ai-powered-multi-social-media-post-automation-google-trends-and-perplexity-ai/)
   - Clique em **"Copiar modelo para a área de transferência (JSON)"**
   - No n8n, vá em **Workflows > Importar** e cole o JSON copiado

2. **Configurar Credenciais:**
   - No menu do n8n, acesse **Credenciais** e adicione suas chaves de API para cada serviço usado

3. **Personalizar o Conteúdo:**
   - Edite os prompts e filtros do Google Trends conforme seu nicho
   - Altere os horários do agendamento, se necessário

4. **Ativar o Workflow:**
   - Salve e ative o workflow para que ele execute automaticamente de forma agendada

## ✅ Dicas Úteis

- Ajuste os temas conforme o público-alvo da sua marca
- Combine com outros fluxos de automação para responder comentários ou analisar engajamento
- Mantenha registros das postagens no Google Sheets para gerar relatórios

## 📚 Recursos Adicionais

- [Documentação oficial do n8n](https://docs.n8n.io/)
- [Comunidade n8n](https://community.n8n.io/)

---

🔗 Criado com base no modelo: [AI-Powered Multi-Social Media Post Automation](https://n8n.io/workflows/4352-ai-powered-multi-social-media-post-automation-google-trends-and-perplexity-ai/)
