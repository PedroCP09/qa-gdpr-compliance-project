# Step 1 — Casos de Teste Funcionais e em API baseados no RGPD

## Projeto - Na busca pela conformidade de dados com base nos mandamentos da legislação especial da Regulamento Geral Sobre Proteção de Dados - RGPD

### Etapa 1.0
Nesta primeira etapa do projeto serão apresentados os tipos de testes genéricos e essenciais que devem ser aplicados em produtos digitais que lidam com dados pessoais e, especialmente, dados sensíveis. O objetivo é demonstrar como validar, de forma funcional e via API, os requisitos mínimos necessários para que uma aplicação esteja alinhada aos princípios e obrigações definidos pelo RGPD - legislação europeia que regula o tratamento, segurança e transparência no uso de dados pessoais.

A proposta deste Step 1 é transformar exigências legais do RGPD em bases de testes práticas, estruturadas e aplicáveis, permitindo avaliar funcionalidades de consentimento, transparência, retificação e eliminação de dados, bem como o comportamento esperado em endpoints de APIs responsáveis pelo processamento dessas operações.

### Base de testes:
RGPD - REGULAMENTO GERAL SOBRE PROTEÇÃO DE DADOS  
Art. 7 (consentimento); Art. 12 (transparência); Art. 15 (acesso); Art. 16 (retificação); Art. 17 (apagamento); Art. 19 (notificação a terceiros).

---

# CASOS DE TESTE - FUNCIONAIS

## ID: RGPD01
NOME: O ato de consentimento deve ser evidente.  
OBJETIVO: O usuário deve observar uma tela ou texto destacado acerca do consentimento, separado de outros assuntos.  
PRÉ-CONDIÇÕES: Usuário acede ao sistema pela primeira vez, sem conta vinculada e inicia à criação de conta.  
PASSOS:  
1. Acessar ao site/app;  
2. Prosseguir a aba para criação de conta;  
3. Avançar para o cadastro onde é solicitado o consentimento;  
RESULTADO ESPERADO: O sistema apresenta um texto de consentimento separado de outras informações.  
REFERENTE À LEGISLAÇÃO: Art. 7º da RGPD  

---

## ID: RGPD02
NOME: Validar se o usuário consegue retirar o consentimento de forma tão simples quanto concedeu.  
OBJETIVO: Verificar se o usuário consegue retirar o consentimento previamente dado para o tratamento de seus dados pessoais de maneira clara, acessível e sem obstáculos.  
PRÉ-CONDIÇÕES: Usuário acessa o sistema com uma conta previamente criada e já possui consentimento ativo registrado na plataforma.  
PASSOS:  
1. Acessar o site/app;  
2. Realizar login com conta válida;  
3. Acessar a área destinada à gestão de privacidade ou consentimentos;  
4. Selecionar a opção para retirar o consentimento;  
5. Confirmar a retirada, caso o sistema apresente diálogo de confirmação.  
RESULTADO ESPERADO: O sistema deve permitir que o usuário retire seu consentimento de forma simples, clara e direta, sem exigir procedimentos excessivos, e deve refletir a retirada imediatamente na interface ou por mensagem informativa.  
REFERENTE À LEGISLAÇÃO: Art. 7 da RGPD.

---

## ID: RGPD03
NOME: Validar se o texto de consentimento é apresentado de forma clara e separada de outras informações.  
OBJETIVO: Verificar se, durante o processo de criação de conta, o sistema apresenta ao usuário um texto de consentimento escrito de forma clara, simples e de fácil compreensão, garantindo que a informação esteja destacada e entendível antes do processamento de dados pessoais.  
PRÉ-CONDIÇÕES: Usuário acessa o sistema pela primeira vez, sem conta vinculada e inicia a criação de conta.  
PASSOS:  
1. Acessar ao site/app;  
2. Prosseguir para criação de conta;  
3. Avançar para o cadastro onde é solicitado o consentimento;  
RESULTADO ESPERADO: O sistema apresenta um texto de consentimento separado de outras informações, com linguagem clara e simples, e exige uma interação explícita do usuário.  
REFERENTE À LEGISLAÇÃO: Art. 12 da RGPD

---

## ID: RGPD04
NOME: Avaliar se a informação sobre o tratamento de dados é facilmente acessível através da interface.  
OBJETIVO: Analisar se o usuário encontra de forma clara e rápida as informações relativas ao tratamento de seus dados pessoais.  
PRÉ-CONDIÇÕES: Usuário acessa o sistema pela primeira vez, sem conta vinculada.  
PASSOS:  
1. Acessar o site/app;  
2. Prosseguir para criação de conta;  
3. Avançar para o cadastro onde é solicitado o consentimento;  
RESULTADO ESPERADO: O usuário deve localizar facilmente, sem navegação excessiva, a seção que apresenta informações sobre o tratamento de dados pessoais.  
REFERENTE À LEGISLAÇÃO: Art. 12 da RGPD

---

## ID: RGPD05
NOME: Validar se as informações sobre o tratamento de dados são disponibilizadas ao usuário por meio eletrônico de forma clara e acessível.  
OBJETIVO: Verificar se, ao solicitar informações sobre o tratamento dos seus dados pessoais através da interface, o usuário recebe essa informação de forma eletrônica, clara e facilmente consultável.  
PRÉ-CONDIÇÕES: Usuário acessa o sistema pela primeira vez, sem conta vinculada.  
PASSOS:  
1. Acessar o site/app;  
2. Prosseguir para criação de conta;  
3. Avançar para o cadastro onde é solicitado o consentimento;  
RESULTADO ESPERADO: O sistema deve apresentar ao usuário as informações sobre o tratamento de dados pessoais em formato eletrónico de forma clara, acessível e compreensível, permitindo leitura direta e livre.  
REFERENTE À LEGISLAÇÃO: Art. 12 da RGPD  

---

## ID: RGPD06
NOME: Validar se o usuário consegue visualizar seus dados pessoais armazenados pelo sistema.  
OBJETIVO: Verificar se, ao aceder à área destinada ao titular, o usuário consegue visualizar de forma clara os seus dados pessoais armazenados pelo sistema.  
PRÉ-CONDIÇÕES: Usuário acede ao sistema com uma conta previamente criada.  
PASSOS:  
1. Acessar ao site/app;  
2. Realizar login com conta válida;  
3. Acessar à área onde são exibidos os dados pessoais do usuário.  
RESULTADO ESPERADO: O usuário deve visualizar, de forma clara e compreensível, os dados pessoais que lhe dizem respeito (ex.: nome, email, informações de perfil).  
REFERENTE À LEGISLAÇÃO: Art. 15 da RGPD.

---

## ID: RGPD07
NOME: Validar se o usuário consegue visualizar informações complementares relativas ao tratamento dos seus dados pessoais.  
OBJETIVO: Analisar se o sistema disponibiliza ao usuário informações complementares sobre o tratamento dos seus dados.  
PRÉ-CONDIÇÕES: Usuário acede ao sistema com uma conta previamente criada.  
PASSOS:  
1. Acessar ao site/app;  
2. Realizar login com conta válida;  
3. Acessar à seção dedicada às informações adicionais sobre o tratamento dos dados pessoais.  
RESULTADO ESPERADO: O usuário deve visualizar claramente informações complementares relativas ao tratamento dos seus dados pessoais.  
REFERENTE À LEGISLAÇÃO: Art. 15 da RGPD.

---

## ID: RGPD08
NOME: Validar se o usuário consegue retificar dados pessoais inexatos através da interface.  
OBJETIVO: Verificar se o usuário consegue corrigir dados pessoais inexatos armazenados pelo sistema.  
PRÉ-CONDIÇÕES: Conta criada contendo pelo menos um dado incorreto.  
PASSOS:  
1. Acessar ao site/app;  
2. Realizar login;  
3. Acessar edição dos dados pessoais;  
4. Alterar o dado inexato.  
RESULTADO ESPERADO: O sistema deve permitir a retificação corretamente.  
REFERENTE À LEGISLAÇÃO: Art. 16 da RGPD.

---

## ID: RGPD09
NOME: Validar se o usuário consegue solicitar o apagamento de seus dados pessoais através da interface.  
OBJETIVO: Verificar se o usuário consegue solicitar o apagamento de forma clara.  
PRÉ-CONDIÇÕES: Conta criada.  
PASSOS:  
1. Acessar o site/app;  
2. Login;  
3. Área de gestão da conta;  
4. Solicitar apagamento.  
RESULTADO ESPERADO: Solicitação deve ser aceita e exibida claramente.  
REFERENTE À LEGISLAÇÃO: Art. 17 da RGPD.

---

## ID: RGPD10
NOME: Validar se o sistema apresenta confirmação após solicitação de apagamento.  
OBJETIVO: Confirmar que o sistema informa o recebimento do pedido.  
PRÉ-CONDIÇÕES: Solicitação de apagamento feita.  
PASSOS:  
1. Acessar;  
2. Login;  
3. Gestão da conta;  
4. Solicitar apagamento;  
5. Ver mensagem.  
RESULTADO ESPERADO: Mensagem clara de confirmação.  
REFERENTE À LEGISLAÇÃO: Art. 17 da RGPD.

---

## ID: RGPD11
NOME: Validar se o usuário consegue solicitar informações sobre os destinatários que receberam seus dados pessoais.  
OBJETIVO: Confirmar transparência quanto ao compartilhamento.  
PRÉ-CONDIÇÕES: Dados compartilhados anteriormente.  
PASSOS:  
1. Login;  
2. Gestão de privacidade;  
3. Solicitar destinatários.  
RESULTADO ESPERADO: Lista clara dos destinatários.  
REFERENTE À LEGISLAÇÃO: Art. 19 da RGPD.

---

## ID: RGPD12
NOME: Validar se o sistema informa ao usuário que terceiros serão notificados após retificação ou apagamento.  
OBJETIVO: Confirmar notificação obrigatória prevista na lei.  
PRÉ-CONDIÇÕES: Solicitação de retificação ou apagamento.  
PASSOS:  
1. Login;  
2. Gestão da conta;  
3. Solicitar retificação ou apagamento.  
RESULTADO ESPERADO: Sistema informa que terceiros serão notificados.  
REFERENTE À LEGISLAÇÃO: Art. 19 da RGPD.


## INICIO CASOS DE TESTES API ##

## ID: RGPD_API01
GET – Retornar dados pessoais do usuário
Objetivo: Verificar se o endpoint retorna corretamente os dados pessoais do usuário autenticado.

Endpoint:
GET /usuarios/{id}

Headers:
Authorization: Bearer <token_valido>
Accept: application/json

Requisição exemplo:
GET /usuarios/123

Resposta esperada: Status: 200

{
  "id": 123,
  "nome": "Marcos Teste",
  "email": "marcos.teste@example.com",
  "telefone": null
}

Validações:
Retorna status 200
ID corresponde ao usuário autenticado
Campos essenciais presentes
Não retorna dados desnecessários
Valores coerentes com o cadastro

Referente à legislação: Art. 15 da RGPD

----
## ID: RGPD_API02
GET – Retornar informações complementares sobre o tratamento dos dados pessoais
Objetivo: Verificar se o endpoint retorna informações adicionais sobre o tratamento dos dados pessoais.

Endpoint: 
GET /usuarios/{id}/informacoes

Headers:

Authorization: Bearer <token_valido>

Accept: application/json

Requisição exemplo: 
GET /usuarios/123/informacoes

Resposta esperada: Status: 200

{
  "id": 123,
  "finalidade": "Gerenciamento de conta e acesso à plataforma",
  "categoriasDados": ["nome", "email", "telefone"],
  "ultimaAtualizacao": "XXXXXXXXXXXX"
}

Validações:
Retorna status 200
Informações coerentes com o tratamento real
Finalidade e categorias obrigatórias
Sem dados irrelevantes

Referente à legislação: Art. 15 da RGPD

----

## ID: RGPD_API03
GET – Impedir acesso às informações de tratamento sem auten ticação válida
Objetivo: Garantir que o endpoint não retorna informações sem autenticação válida.

Endpoint: 
GET /usuarios/{id}/informacoes

Headers inválidos:
Authorization: Bearer <token_invalido_ou_ausente>
Accept: application/json

Requisição exemplo:
GET /usuarios/123/informacoes

Resposta esperada: Status: 401

{
  "erro": "Não autorizado",
  "mensagem": "Token de autenticação inválido ou ausente."
}

Validações:
Retorna 401
Nenhuma informação pessoal é retornada
Mensagem clara sem detalhes internos

Referente à legislação: Art. 15 da RGPD

----

## ID: RGPD_API04
PATCH – Retificar dados pessoais inexatos
Objetivo: Verificar se o endpoint permite corrigir dados pessoais incorretos.

Endpoint: 
PATCH /usuarios/{id}

Headers:

Authorization: Bearer <token_valido>

Content-Type: application/json

Accept: application/json

Body enviado:

{
  "nome": "Marcos "
}

Requisição exemplo: 
PATCH /usuarios/123

Resposta esperada: Status: 200

{
  "id": 123,
  "nome": "Marcos Teste",
  "email": "marcos.teste@example.com"
}

Validações:
Retorna 200
Apenas o campo alterado é atualizado
Rejeita valores inválidos
Mantém consistência do usuário

Referente à legislação: Art. 16 da RGPD

----
## ID: RGPD_API05
PATCH – Completar dados pessoais incompletos
Objetivo: Verificar se o endpoint permite adicionar dados faltantes.

Endpoint:
PATCH /usuarios/{id}

Headers:
Authorization: Bearer <token_valido>
Content-Type: application/json
Accept: application/json

Body enviado:

{
  "telefone": "+351912345678"
}

Requisição exemplo:
PATCH /usuarios/123

Resposta esperada: Status: 200
{
  "id": 123,
  "nome": "Marcos Teste",
  "email": "marcos.teste@example.com",
  "telefone": "+351912345678"
}

Validações:
Retorna 200
Campo ausente é preenchido
Nenhum outro campo é alterado
Rejeita formatos inválidos

Referente à legislação: Art. 16 da RGPD

----

## ID: RGPD_API06
DELETE – Solicitar o apagamento dos dados pessoais
Objetivo: Verificar se o endpoint permite solicitar o apagamento completo dos dados.

Endpoint: 
DELETE /usuarios/{id}/excluir

Headers:
Authorization: Bearer <token_valido>
Accept: application/json

Requisição exemplo: 
DELETE /usuarios/123/excluir

Resposta esperada: Status: 200

{
  "id": 123,
  "mensagem": "Solicitação de apagamento registrada com sucesso."
}

Validações:
Retorna 200
Mensagem clara
Não retorna dados pessoais
Sem etapas desnecessárias

Referente à legislação: Art. 17 da RGPD

----
## ID: RGPD_API07
GET – Impedir acesso após solicitação de apagamento
Objetivo: Garantir que, após o apagamento, nenhum dado seja acessível.

Endpoint: 
GET /usuarios/{id}

Headers:
Authorization: Bearer <token_valido>
Accept: application/json
Pré-condição: Apagamento solicitado anteriormente.

Requisição exemplo:
GET /usuarios/123

Resposta esperada: Status: 404

{
  "erro": "Usuário não encontrado",
  "mensagem": "Os dados relacionados ao usuário solicitado não estão mais disponíveis."
}

Validações:
Retorna 404 ou 410
Nenhum dado pessoal é retornado
Mensagem clara
Sem inconsistências entre endpoints

Referente à legislação: Art. 17 da RGPD  

----
## ID: RGPD_API08
DELETE – Impedir apagamento quando existe fundamento jurídico
Objetivo: Garantir que o sistema bloqueia o apagamento quando há base legal para manter os dados.

Endpoint: 
DELETE /usuarios/{id}/excluir

Headers:
Authorization: Bearer <token_valido>
Accept: application/json
Cenário: Usuário possui obrigação legal que impede exclusão.

Requisição exemplo:
DELETE /usuarios/123/excluir

Resposta esperada: Status: 403

{
  "erro": "Apagamento não permitido",
  "motivo": "Existe fundamento jurídico que exige a manutenção dos dados pessoais.",
  "referencia": "Artigo 17.º, n.º 3 do RGPD"
}

Validações:
Retorna 403 ou 409
Nenhum dado é apagado
Mensagem clara sem detalhes sensíveis
x
Referente à legislação: Art. 17(3) da RGPD

----
## ID: RGPD_API09
GET – Consultar destinatários que receberam os dados pessoais
Objetivo: Verificar se o usuário consegue consultar os destinatários dos seus dados.

Endpoint:
GET /usuarios/{id}/destinatarios

Headers:
Authorization: Bearer <token_valido>
Accept: application/json

Requisição exemplo:
GET /usuarios/123/destinatarios

Resposta esperada: Status: 200

{
  "id": 123,
  "destinatarios": [
    {
      "nome": "Serviço de Faturação",
      "finalidade": "Processamento de pagamentos",
      "dataCompartilhamento": "2024-01-05T12:30:00Z"
    },
    {
      "nome": "Plataforma de Análises Internas",
      "finalidade": "Melhoria de desempenho e métricas",
      "dataCompartilhamento": "2024-01-07T09:00:00Z"
    }
  ]
}

Validações:
Retorna 200
Lista clara e estruturada
Informações mínimas obrigatórias
Lista vazia quando não houver destinatários

Referente à legislação: Art. 19 da RGPD.

----

## ID: RGPD_API10
PATCH/DELETE – Indicar notificação a terceiros após retificação ou apagamento

#Cenário 1 — PATCH (Retificação)

Endpoint:
PATCH /usuarios/{id}

Body enviado:
{
  "telefone": "+351912345678"
}

Resposta esperada: Status: 200
{
  "id": 123,
  "mensagem": "Dados atualizados com sucesso. Os destinatários relevantes serão notificados.",
  "notificacaoTerceiros": true
}

#Cenário 2 — DELETE (Apagamento)

Endpoint: 
DELETE /usuarios/{id}/excluir

Resposta esperada: Status: 200

{
  "id": 123,
  "mensagem": "Solicitação de apagamento registrada. Os destinatários relevantes serão notificados.",
  "notificacaoTerceiros": true
}

Validações comuns:
Retorna 200
Indica claramente que terceiros serão notificados
Campo notificacaoTerceiros deve ser true
Mensagem clara e sem dados sensíveis
Comportamento consistente entre PATCH e DELETE

Referente à legislação: Art. 19 da RGPD

----

Com a conclusão deste Step 1, estabelecemos a base técnica e documental necessária para validar a conformidade do sistema com os princípios essenciais do RGPD. 
A partir daqui, o projeto segue com maior clareza, segurança e consistência para as próximas etapas de evolução e maturidade em privacidade de dados.

[Meu LinkedIn](linkedin.com/in/qapedroaugustopaiva)




