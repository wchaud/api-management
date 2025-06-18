# api-management
Estudos sobre Api Managemente do Azure

Anotações:

1. Proteger APIs
Autenticação por chave de assinatura, JWT, OAuth 2.0, etc.

Limitar uso com políticas de throttling e rate-limiting

Controle de acesso por IP ou região

2. Monitorar o uso das APIs
Ver estatísticas detalhadas por operação, consumidor, tempo de resposta

Exportar logs para o Azure Monitor, Application Insights, Log Analytics

3. Transformar e manipular requisições e respostas
Políticas (definidas em XML) para:

Modificar headers e corpos

Converter formatos (ex: JSON ↔ XML)

Adicionar ou remover parâmetros

Fazer cache de respostas

Redirecionar requisições

Aplicar lógica condicional

4. Simular APIs (Mock)
Permite criar APIs fictícias (sem backend) para testes e desenvolvimento frontend.

5. Gerar portal para desenvolvedores
Um portal customizável para que terceiros (internos ou externos):

Descubram suas APIs

Façam testes

Solicitem acesso

Leiam documentação gerada automaticamente (via Swagger/OpenAPI)

6. Gerenciar o ciclo de vida da API
Versionamento de APIs

Agrupamento de operações em produtos

Controle de quais usuários ou grupos acessam cada versão ou produto

7. Importar APIs facilmente
A partir de:

OpenAPI (Swagger)

WSDL (SOAP)

Azure Functions

Logic Apps

APIs já existentes no App Services

8. Integrar com outras soluções Azure
Azure Functions, App Services, Event Grid

Azure Key Vault (para armazenar segredos de forma segura)

Azure Application Gateway e Front Door (para controle de tráfego e alta disponibilidade)

Casos de uso comuns
Expôr APIs internas com segurança para apps móveis/web

Centralizar o acesso a múltiplos serviços e microserviços

Criar ambientes de sandbox para parceiros e desenvolvedores externos

Aplicar regras e limites sem alterar o código da API
