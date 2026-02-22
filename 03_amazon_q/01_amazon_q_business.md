# Amazon Q Business

- Fully managed GenAI assistant for employees
- Based on companies knowledge and data
  - Answer questions, provide summaries, etc
  - Send meeting invites, submit PTO requests
- Built on Amazon Bedrock
  - You can't select underlying models

- Data Connectors
  - Fully managed RAG
    - Integrates with Amazon Services
    - Integrates with other enterprise services
      - Salesforce
      - M365
      - Slack
    - 3rd Party Plugins
    - Custom Plugins
      - Build custom plugins with APIs

- Authenticaton
  - Users authenticated using IAM Identity Center
  - Users receive responses only from documents and resources they have access to
  - Can use external identity providers
    - Google
    - Entra ID

- Admin Controls
  - Guardrails
  - Block specific words or topics
  - Respond only with internal information
  - Global and Topic level controls
    - Topic controls are more granular