# raw
{"nlu":"## intent:validade_geografica_licenca\n- A licença de pescador amador é válida em todo o território nacional?\n- A Carteirinha de pescador amador é válida em todo o território nacional?\n## intent:licenca_crianca\n- minha filha precisa de licença?\n- meu filho precisa de licença?\n- Preciso obter licença de pescador amador para crianças?\n- Preciso emitir licença de pescador amador para crianças?\n- Preciso obter carteirinha de pescador amador para crianças?\n- Preciso emitir carteirinha de pescador amador para crianças?\n- É necessário emitir carteirinha de pescador amador para crianças?\n## intent:consulta_licenca\n- Como faço para consultar a minha carteirinha de pesca amadora no site?\n- Como faço para consultar a minha licença de pesca amadora no site?\n## intent:embarcada_ou_desembarcada\n- A modalidade de pesca desembarcada, contempla a pesca embarcada?\n- A modalidade de pesca embarcada, contempla a pesca desembarcada?\n- Fiz o cadastro e paguei pela modalidade embarcada, mas pesco também na modalidade desembarcada. A carteirinha na categoria embarcada também serve para pesca desembarcada?\n- Fiz o cadastro e paguei pela modalidade embarcada, mas pesco também na modalidade desembarcada. A licença na categoria embarcada também serve para pesca desembarcada?\n## intent:pagamento_duplicado\n- Quero reembolso da GRU, pois paguei duas vezes.\n- Paguei duas vezes a GRU, como proceder?\n- Efetuei o pagamento da GRU duas vezes, como proceder?\n- Realizei o pagamento da GRU duas vezes, como proceder?\n## intent:banco_gru\n- Por que o pagamento da GRU só pode ser realizado no Banco do Brasil –BB?\n- Por que o recolhimento da GRU só pode ser realizado no Banco do Brasil –BB?\n- Por que o pagamento da GRU só pode ser efetuado no Banco do Brasil –BB?\n- Por que o recolhimento da GRU só pode ser efetuado no Banco do Brasil –BB?\n## intent:licenca_estrangeiro\n- Sou estrangeiro e não tenho CPF, como proceder?\n- Como emitir a carteirinha de pesca amadora para estrangeiros?\n- Como emitir a licença de pesca amadora para estrangeiros?\n- Como obter a carteirinha de pesca amadora para estrangeiros?\n- Como obter a licença de pesca amadora para estrangeiros?\n## intent:licenca_provisoria\n- A Carteirinha provisória venceu e ainda não recebi a carteirinha definitiva.\n- A licença provisória venceu e ainda não recebi a licença definitiva.\n- Paguei a GRU e recebi a licença provisória com validade de 30 dias que venceu e ainda não obtive a liberação da licença definitiva de pesca amadora, como proceder?\n- Paguei a GRU e recebi a carteirinha provisória com validade de 30 dias que venceu e ainda não obtive a liberação da carteirinha definitiva de pesca amadora, como proceder?\n## intent:nao_encontro_protocolo\n- Ao acessar o site para consultar a licença de pesca amadora não consegui localizar o protocolo, como proceder?\n- Ao acessar o site para consultar a carteirinha de pesca amadora não consegui localizar o protocolo, como proceder?\n- Quero consultar a minha licença de pesca amadora, mas não consegui localizar o protocolo, o que devo fazer?\n- Quero consultar a minha carteirinha de pesca amadora, mas não consegui localizar o protocolo, o que devo fazer?\n## intent:emitir_licenca_amador\n- Quero renovar a carteirinha de pescador amador.\n- Quero emitir a licença de pescador amador.\n- Quero emitir a carteirinha de pescador amador.\n- Quero obter a licença de pescador amador.\n- Quero obter a carteirinha de pescador amador.\n- Como faço para conseguir a licença de pescador amador?\n- Como faço para conseguir a carteirinha de pescador amador?\n- Como faço para renovar a licença de pescador amador?\n- Como faço para obter a licença de pescador amador?\n- Como faço para emitir a licença de pescador amador?\n- Como faço para renovar a carteirinha de pescador amador?\n- Como faço para obter a carteirinha de pescador amador?\n- Como faço para emitir a carteirinha de pescador amador?\n\n","domain":"slots:\n\nentities:\n\nintents:\n- validade_geografica_licenca\n- licenca_crianca\n- consulta_licenca\n- embarcada_ou_desembarcada\n- pagamento_duplicado\n- banco_gru\n- licenca_estrangeiro\n- licenca_provisoria\n- nao_encontro_protocolo\n- emitir_licenca_amador\n\ntemplates:\n  utter_consulta_licenca:\n    - text: \"Acesse o link: http://www.agricultura.gov.br/assuntos/aquicultura-e-pesca/formulario-de-cadastro-de-pescador-amador , bastando informar apenas o CPF, terá acesso a sua licença.\"\n  utter_embarcada_ou_desembarcada:\n    - text: \"A licença de pesca na modalidade embarcada contempla a modalidade desembarcada, mas caso tenha apenas a licença na categoria desembarcada, esta não contempla a pesca embarcada, sendo necessário a emissão da carteirinha na modalidade embarcada.\"\n  utter_pagamento_duplicado:\n    - text: \"Informamos que não é possível ser realizado o reembolso, pois, os pagamentos são controlados pelo Tesouro Nacional. O que pode ser feito é verificarmos a possibilidade para liberação de uma outra carteira de pesca definitiva, utilizando um dos comprovantes de pagamento. Caso tenha algum conhecido que também deseja emitir a licença e ainda não efetuou o pagamento entre em contato pelo e-mail: pescadoramador.sap@agricultura.gov.br.\"\n  utter_gru:\n    - text: \"As regras e normativos são do Governo Federal, no site do Tesouro Nacional é possível verificar as exigências em relação ao pagamento em agências do Banco do Brasil. http://consulta.tesouro.fazenda.gov.br/gru_novosite/gru_simples.asp\"\n  utter_licenca_estrangeiro:\n    - text: \"Para o estrangeiro não residente no Brasil e sem CPF, o mesmo deverá requisitar o seu CPF nos postos da Receita Federal, ou pelo site https://servicos.receita.fazenda.gov.br/Servicos/CPF/InscricaoCpfEstrangeiro/default.asp .       O CPF é um dos itens obrigatórios para que se possa realizar o recolhimento da GRU para obter a licença de pesca amadora. Ao preencher o formulário o estrangeiro deverá informa no seu cadastro o endereço do hotel, pousada ou local onde o mesmo for ficar no Brasil, informamos também que o cadastro deverá ser realizado no Site do Ministério da Agricultura, Pecuária e Abastecimento - MAPA, conforme link: http://www.agricultura.gov.br/assuntos/aquicultura-e-pesca/formulario-de-cadastro-de-pescador-amador .\"\n  utter_licenca_provisoria:\n    - text: \"Caso o usuário tenha realizado o pagamento da GRU e até o presente momento e não obteve sua licença de pesca amadora definitiva, orientamos que aguarde a liberação da carteirinha, pois, a liberação está sendo realizada automaticamente após 30 dias contados da data em que foi realizado o pagamento. Lembrando que a licença provisória possui validade de 30 dias mediante apresentação de um documento de identificação com foto e o comprovante de pagamento. Caso a licença definitiva não seja liberada após os 30 dias a contar da data do pagamento, solicitamos que nos contate pelo e-mail: pescadoramador.sap@agricultura.gov.br  Entretanto, caso tenha realizado cadastro e efetuado o pagamento no site do Ministério do Desenvolvimento, Indústria e Comércio Exterior – MDIC solicitamos que o mesmo nos encaminhe uma cópia do comprovante de pagamento da GRU que conste os seus dados como nome e/ou CPF e a data do pagamento para o e-mail mencionado acima.\"\n  utter_protocolo:\n    - text: \"Caso tenha realizado o cadastro no site do Ministério do Desenvolvimento, Indústria e Comércio Exterior – MDIC e efetuado o pagamento da GRU emitida pelo antigo sistema, orientamos que seja feito um novo cadastro em nosso sistema.  Acesse o link: http://www.agricultura.gov.br/assuntos/aquicultura-e-pesca/formulario-de-cadastro-de-pescador-amador e realize um novo cadastro. Não é preciso imprimir a GRU e efetuar o pagamento, haja vista que a sua já está paga.  Assim que for feito um novo cadastro, encaminhe uma cópia do comprovante de pagamento da GRU que conste os seus dados como nome e/ou CPF e a data do pagamento para o e-mail pescadoramador.sap@agricultura.gov.br para que possamos solicitar junto a equipe técnica a liberação da sua licença definitiva.\"\n  utter_carteirinha:\n    - text: \"Para obter/renovar a licença de pesca amadora, emitida por esta Secretaria de Aquicultura e Pesca, com validade em todo território nacional, siga as instruções abaixo: 1º Utilizando o navegador Google Chrome, acesse o endereço: http://www.agricultura.gov.br/assuntos/aquicultura-e-pesca/formulario-de-cadastro-de-pescador-amador ; 2º Clique no link: \"Aquicultura e pesca lado esquerdo da tela\" , final da página link Registro Pescador realize o cadastro com suas informações pessoais conforme solicitado; 3º  Preencha o formulário e clique em ENVIAR FORMULÁRIO; 4º Após realizar o cadastro o sistema gerará um número de protocolo, um link para impressão da licença provisória válida por trinta dias e outro link para impressão do boleto (GRU) no valor de R$ 60,00 modalidade embarcada e R$ 20,00 modalidade desembarcada; 5º Realize o recolhimento (pagamento) do valor na categoria ora escolhida, lembrando que a carteirinha provisória possui validade apenas mediante apresentação de um documento de identificação com foto e o comprovante de pagamento; 6º A carteirinha definitiva com validade de um ano será liberada automaticamente após 30 dias contados da data em que foi realizado o pagamento.\"\n\nactions:\n- utter_validade_geografica_licenca\n- utter_licenca_crianca\n- utter_consulta_licenca\n- utter_embarcada_ou_desembarcada\n- utter_pagamento_duplicado\n- utter_gru\n- utter_licenca_estrangeiro\n- utter_licenca_provisoria\n- utter_protocolo\n- utter_carteirinha\n","stories":"## story_1570210417\n* validade_geografica_licenca\n - utter_validade_geografica_licenca\n## story_1570210408\n* licenca_crianca\n - utter_licenca_crianca\n## story_1570210397\n* consulta_licenca\n - utter_consulta_licenca\n## story_1570210378\n* embarcada_ou_desembarcada\n - utter_embarcada_ou_desembarcada\n## story_1570210367\n* pagamento_duplicado\n - utter_pagamento_duplicado\n## story_1570210354\n* licenca_estrangeiro\n - utter_licenca_estrangeiro\n## story_1570210338\n* licenca_provisoria\n - utter_licenca_provisoria\n## protocolo\n* nao_encontro_protocolo\n - utter_protocolo## story_1570209587\n* emitir_licenca_amador\n - utter_carteirinha\n","config":"language : \"pt\"\npipeline:\n  - name: \"WhitespaceTokenizer\"\n  - name: \"CRFEntityExtractor\"\n  - name: \"EntitySynonymMapper\"\n  - name: \"CountVectorsFeaturizer\"\n  - name: \"EmbeddingIntentClassifier\"\n  \npolicies:\n  - name: KerasPolicy\n    priority: 5\n    epochs: 25\n    batch_size: 10\n    featurizer:\n      - name: FullDialogueTrackerFeaturizer\n        state_featurizer:\n          - name: LabelTokenizerSingleStateFeaturizer\n  - name: FallbackPolicy\n    nlu_threshold: 0.6\n    core_threshold: 0.6\n    priority: 1\n  - name: MemoizationPolicy\n    priority: 2\n    max_history: 2","out":"pesca","force":"false"}

# config
language : "pt"
pipeline:
  - name: "WhitespaceTokenizer"
  - name: "CRFEntityExtractor"
  - name: "EntitySynonymMapper"
  - name: "CountVectorsFeaturizer"
  - name: "EmbeddingIntentClassifier"
  
policies:
  - name: KerasPolicy
    priority: 5
    epochs: 25
    batch_size: 10
    featurizer:
      - name: FullDialogueTrackerFeaturizer
        state_featurizer:
          - name: LabelTokenizerSingleStateFeaturizer
  - name: FallbackPolicy
    nlu_threshold: 0.6
    core_threshold: 0.6
    priority: 1
  - name: MemoizationPolicy
    priority: 2
    max_history: 2

# nlu data
## intent:validade_geografica_licenca
- A licença de pescador amador é válida em todo o território nacional?
- A Carteirinha de pescador amador é válida em todo o território nacional?
## intent:licenca_crianca
- minha filha precisa de licença?
- meu filho precisa de licença?
- Preciso obter licença de pescador amador para crianças?
- Preciso emitir licença de pescador amador para crianças?
- Preciso obter carteirinha de pescador amador para crianças?
- Preciso emitir carteirinha de pescador amador para crianças?
- É necessário emitir carteirinha de pescador amador para crianças?
## intent:consulta_licenca
- Como faço para consultar a minha carteirinha de pesca amadora no site?
- Como faço para consultar a minha licença de pesca amadora no site?
## intent:embarcada_ou_desembarcada
- A modalidade de pesca desembarcada, contempla a pesca embarcada?
- A modalidade de pesca embarcada, contempla a pesca desembarcada?
- Fiz o cadastro e paguei pela modalidade embarcada, mas pesco também na modalidade desembarcada. A carteirinha na categoria embarcada também serve para pesca desembarcada?
- Fiz o cadastro e paguei pela modalidade embarcada, mas pesco também na modalidade desembarcada. A licença na categoria embarcada também serve para pesca desembarcada?
## intent:pagamento_duplicado
- Quero reembolso da GRU, pois paguei duas vezes.
- Paguei duas vezes a GRU, como proceder?
- Efetuei o pagamento da GRU duas vezes, como proceder?
- Realizei o pagamento da GRU duas vezes, como proceder?
## intent:banco_gru
- Por que o pagamento da GRU só pode ser realizado no Banco do Brasil –BB?
- Por que o recolhimento da GRU só pode ser realizado no Banco do Brasil –BB?
- Por que o pagamento da GRU só pode ser efetuado no Banco do Brasil –BB?
- Por que o recolhimento da GRU só pode ser efetuado no Banco do Brasil –BB?
## intent:licenca_estrangeiro
- Sou estrangeiro e não tenho CPF, como proceder?
- Como emitir a carteirinha de pesca amadora para estrangeiros?
- Como emitir a licença de pesca amadora para estrangeiros?
- Como obter a carteirinha de pesca amadora para estrangeiros?
- Como obter a licença de pesca amadora para estrangeiros?
## intent:licenca_provisoria
- A Carteirinha provisória venceu e ainda não recebi a carteirinha definitiva.
- A licença provisória venceu e ainda não recebi a licença definitiva.
- Paguei a GRU e recebi a licença provisória com validade de 30 dias que venceu e ainda não obtive a liberação da licença definitiva de pesca amadora, como proceder?
- Paguei a GRU e recebi a carteirinha provisória com validade de 30 dias que venceu e ainda não obtive a liberação da carteirinha definitiva de pesca amadora, como proceder?
## intent:nao_encontro_protocolo
- Ao acessar o site para consultar a licença de pesca amadora não consegui localizar o protocolo, como proceder?
- Ao acessar o site para consultar a carteirinha de pesca amadora não consegui localizar o protocolo, como proceder?
- Quero consultar a minha licença de pesca amadora, mas não consegui localizar o protocolo, o que devo fazer?
- Quero consultar a minha carteirinha de pesca amadora, mas não consegui localizar o protocolo, o que devo fazer?
## intent:emitir_licenca_amador
- Quero renovar a carteirinha de pescador amador.
- Quero emitir a licença de pescador amador.
- Quero emitir a carteirinha de pescador amador.
- Quero obter a licença de pescador amador.
- Quero obter a carteirinha de pescador amador.
- Como faço para conseguir a licença de pescador amador?
- Como faço para conseguir a carteirinha de pescador amador?
- Como faço para renovar a licença de pescador amador?
- Como faço para obter a licença de pescador amador?
- Como faço para emitir a licença de pescador amador?
- Como faço para renovar a carteirinha de pescador amador?
- Como faço para obter a carteirinha de pescador amador?
- Como faço para emitir a carteirinha de pescador amador?


# stories
## story_1570210417
* validade_geografica_licenca
 - utter_validade_geografica_licenca
## story_1570210408
* licenca_crianca
 - utter_licenca_crianca
## story_1570210397
* consulta_licenca
 - utter_consulta_licenca
## story_1570210378
* embarcada_ou_desembarcada
 - utter_embarcada_ou_desembarcada
## story_1570210367
* pagamento_duplicado
 - utter_pagamento_duplicado
## story_1570210354
* licenca_estrangeiro
 - utter_licenca_estrangeiro
## story_1570210338
* licenca_provisoria
 - utter_licenca_provisoria
## protocolo
* nao_encontro_protocolo
 - utter_protocolo
## story_1570209587
* emitir_licenca_amador
 - utter_carteirinha

# domain
slots:

entities:

intents:
- validade_geografica_licenca
- licenca_crianca
- consulta_licenca
- embarcada_ou_desembarcada
- pagamento_duplicado
- banco_gru
- licenca_estrangeiro
- licenca_provisoria
- nao_encontro_protocolo
- emitir_licenca_amador

templates:
  utter_consulta_licenca:
    - text: "Acesse o link: http://www.agricultura.gov.br/assuntos/aquicultura-e-pesca/formulario-de-cadastro-de-pescador-amador , bastando informar apenas o CPF, terá acesso a sua licença."
  utter_embarcada_ou_desembarcada:
    - text: "A licença de pesca na modalidade embarcada contempla a modalidade desembarcada, mas caso tenha apenas a licença na categoria desembarcada, esta não contempla a pesca embarcada, sendo necessário a emissão da carteirinha na modalidade embarcada."
  utter_pagamento_duplicado:
    - text: "Informamos que não é possível ser realizado o reembolso, pois, os pagamentos são controlados pelo Tesouro Nacional. O que pode ser feito é verificarmos a possibilidade para liberação de uma outra carteira de pesca definitiva, utilizando um dos comprovantes de pagamento. Caso tenha algum conhecido que também deseja emitir a licença e ainda não efetuou o pagamento entre em contato pelo e-mail: pescadoramador.sap@agricultura.gov.br."
  utter_gru:
    - text: "As regras e normativos são do Governo Federal, no site do Tesouro Nacional é possível verificar as exigências em relação ao pagamento em agências do Banco do Brasil. http://consulta.tesouro.fazenda.gov.br/gru_novosite/gru_simples.asp"
  utter_licenca_estrangeiro:
    - text: "Para o estrangeiro não residente no Brasil e sem CPF, o mesmo deverá requisitar o seu CPF nos postos da Receita Federal, ou pelo site https://servicos.receita.fazenda.gov.br/Servicos/CPF/InscricaoCpfEstrangeiro/default.asp .       O CPF é um dos itens obrigatórios para que se possa realizar o recolhimento da GRU para obter a licença de pesca amadora. Ao preencher o formulário o estrangeiro deverá informa no seu cadastro o endereço do hotel, pousada ou local onde o mesmo for ficar no Brasil, informamos também que o cadastro deverá ser realizado no Site do Ministério da Agricultura, Pecuária e Abastecimento - MAPA, conforme link: http://www.agricultura.gov.br/assuntos/aquicultura-e-pesca/formulario-de-cadastro-de-pescador-amador ."
  utter_licenca_provisoria:
    - text: "Caso o usuário tenha realizado o pagamento da GRU e até o presente momento e não obteve sua licença de pesca amadora definitiva, orientamos que aguarde a liberação da carteirinha, pois, a liberação está sendo realizada automaticamente após 30 dias contados da data em que foi realizado o pagamento. Lembrando que a licença provisória possui validade de 30 dias mediante apresentação de um documento de identificação com foto e o comprovante de pagamento. Caso a licença definitiva não seja liberada após os 30 dias a contar da data do pagamento, solicitamos que nos contate pelo e-mail: pescadoramador.sap@agricultura.gov.br  Entretanto, caso tenha realizado cadastro e efetuado o pagamento no site do Ministério do Desenvolvimento, Indústria e Comércio Exterior – MDIC solicitamos que o mesmo nos encaminhe uma cópia do comprovante de pagamento da GRU que conste os seus dados como nome e/ou CPF e a data do pagamento para o e-mail mencionado acima."
  utter_protocolo:
    - text: "Caso tenha realizado o cadastro no site do Ministério do Desenvolvimento, Indústria e Comércio Exterior – MDIC e efetuado o pagamento da GRU emitida pelo antigo sistema, orientamos que seja feito um novo cadastro em nosso sistema.  Acesse o link: http://www.agricultura.gov.br/assuntos/aquicultura-e-pesca/formulario-de-cadastro-de-pescador-amador e realize um novo cadastro. Não é preciso imprimir a GRU e efetuar o pagamento, haja vista que a sua já está paga.  Assim que for feito um novo cadastro, encaminhe uma cópia do comprovante de pagamento da GRU que conste os seus dados como nome e/ou CPF e a data do pagamento para o e-mail pescadoramador.sap@agricultura.gov.br para que possamos solicitar junto a equipe técnica a liberação da sua licença definitiva."
  utter_carteirinha:
    - text: "Para obter/renovar a licença de pesca amadora, emitida por esta Secretaria de Aquicultura e Pesca, com validade em todo território nacional, siga as instruções abaixo: 1º Utilizando o navegador Google Chrome, acesse o endereço: http://www.agricultura.gov.br/assuntos/aquicultura-e-pesca/formulario-de-cadastro-de-pescador-amador ; 2º Clique no link: "Aquicultura e pesca lado esquerdo da tela" , final da página link Registro Pescador realize o cadastro com suas informações pessoais conforme solicitado; 3º  Preencha o formulário e clique em ENVIAR FORMULÁRIO; 4º Após realizar o cadastro o sistema gerará um número de protocolo, um link para impressão da licença provisória válida por trinta dias e outro link para impressão do boleto (GRU) no valor de R$ 60,00 modalidade embarcada e R$ 20,00 modalidade desembarcada; 5º Realize o recolhimento (pagamento) do valor na categoria ora escolhida, lembrando que a carteirinha provisória possui validade apenas mediante apresentação de um documento de identificação com foto e o comprovante de pagamento; 6º A carteirinha definitiva com validade de um ano será liberada automaticamente após 30 dias contados da data em que foi realizado o pagamento."

actions:
- utter_validade_geografica_licenca
- utter_licenca_crianca
- utter_consulta_licenca
- utter_embarcada_ou_desembarcada
- utter_pagamento_duplicado
- utter_gru
- utter_licenca_estrangeiro
- utter_licenca_provisoria
- utter_protocolo
- utter_carteirinha

