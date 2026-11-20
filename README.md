# Meu Kit de IA

Desafio de Projeto da [DIO](https://dio.me): monte o seu kit de IA para o dia a dia e delegue uma tarefa real, com você no comando.

O kit foi criado pelo Expert Bruno Lima com os prompts, templates, checklists e skills usados nas Aulas. Ele não é uma apostila: abra a pasta que resolve o seu problema, copie o modelo, adapte e use.

**Copie → adapte → teste → confira → melhore**

## Como Fazer o Desafio

Você não precisa instalar nada nem saber programar. Tudo acontece no navegador.

1. Clique em **Use this template**, depois em **Create a new repository**. Dê um nome simples, como `meu-kit-de-ia`, deixe **Public** e confirme.
2. Siga os passos abaixo com uma tarefa real da sua semana.
3. Preencha a seção [Minha Entrega](#minha-entrega) da sua cópia e entregue o link dela na DIO.

## Os Passos

1. **Escolha uma tarefa real.** Comece pelo trabalho que se repete na sua semana, como preparar uma reunião ou montar um relatório, e não pela ferramenta.
2. **Pegue um modelo.** Abra a pasta do kit que combina com a sua tarefa. Cada modelo tem um botão de copiar no canto.
3. **Adapte.** Troque o que está entre colchetes pelo seu contexto, objetivo, dados, limites e formato.
4. **Teste.** A primeira resposta é um ponto de partida. Ajuste até funcionar para a sua realidade.
5. **Delegue.** Com o [template de delegação](02-templates/03-delegacao.md), entregue a tarefa à IA. Peça o plano antes de ela começar, acompanhe e valide o resultado.
6. **Confira.** Provável não é o mesmo que verdadeiro. Revise com o [Pare, Confira, Use](03-checklists/01-pare-confira-use.md) antes de usar.

## O Que Tem no Kit

| Pasta | Para que serve |
|---|---|
| [01-prompts](01-prompts) | Pedidos prontos para adaptar: escrita, comunicação, pesquisa, comparação e preparação de reuniões |
| [02-templates](02-templates) | Estruturas para preencher: bom pedido, pesquisa e decisão, e delegação |
| [03-checklists](03-checklists) | Revisão de respostas, de textos e de tarefas delegadas |
| [04-skills](04-skills) | Como criar uma skill, e a Skill Preparador de Reuniões usada nas Aulas |
| [05-delegacao-e-automacao](05-delegacao-e-automacao) | Gatilhos de automação, supervisão e checkpoints |

## Os Frameworks das Aulas

- **Bom pedido:** contexto + instrução + objetivo + formato. Quanto menos a IA precisa adivinhar, melhor você consegue avaliar a resposta.
- **Pesquisa e decisão:** pergunta → pesquisa → critérios → comparação → você. Peça fontes quando precisar de informação externa. A decisão final é sua.
- **Segurança:** pare → confira → use. Valide fatos, números, datas, fontes e contexto.
- **Atalhos reutilizáveis:** criar → testar → ajustar → salvar. Separe as instruções fixas das informações que mudam a cada uso.
- **Delegação:** objetivo + contexto + recursos + limites + sucesso. Autonomia funciona melhor quando o resultado esperado está claro.
- **Supervisão:** definir → delegar → acompanhar → validar. Em tarefas maiores, confira o plano, acompanhe os checkpoints e valide o resultado.

> A IA pode ajudar você a escrever, pesquisar, organizar e executar. A responsabilidade pelo resultado continua sendo sua.

---

## Minha Entrega

Na sua cópia, abra este README, clique no lápis (**Edit this file**) e role até aqui. Troque cada frase em itálico pelo que você fez e cole o texto dentro dos blocos já prontos. Para pôr um print, é só colar a imagem com Ctrl+V. No fim, clique em **Commit changes**.

Nada de e-mail, nome de cliente, dado da empresa, senha ou informação pessoal nos textos e nos prints.

### Minha Tarefa Real

Escolhi a organização da pré-produção de projetos audiovisuais: transformar um briefing bruto (notas de reunião, referências e objetivos de campanha) em um roteiro estruturado, plano de captação/enquadramentos e checklist de pré-produção. Essa tarefa se repete toda semana, consome bastante tempo manual organizando informações soltas e tem alto impacto no resultado final — qualquer detalhe esquecido antes da gravação vira retrabalho no set ou na edição. Delegar a estruturação inicial para a IA acelera o preparo sem abrir mão da minha direção criativa e validação técnica antes de aprovar qualquer material.

### Meus Atalhos

Adaptei dois modelos do kit para a minha rotina de pré-produção audiovisual: o template de Bom Pedido (01-prompts e 02-templates) para estruturar roteiro e plano de captação, e a estrutura de Skill + Checklist (04-skills e 03-checklists, inspirada na Skill Preparador de Reuniões) para auditar a pré-produção antes do dia da gravação.

O que ficou fixo: o papel técnico da IA (direção de pré-produção), o rigor cinematográfico (enquadramentos, lentes, iluminação e movimento de câmera), o formato padronizado de saída e as regras de segurança (não inventar dados ausentes, sinalizar lacunas e separar fatos do briefing de sugestões criativas).

O que muda a cada uso: os campos entre [colchetes], como objetivo da campanha, duração, público-alvo, locações, equipamentos disponíveis e notas brutas do briefing.

```text
Atue como assistente de pré-produção e direção de fotografia audiovisual.

CONTEXTO DO PROJETO:
- Tipo de vídeo: [ex: institucional / comercial / conteúdo para redes sociais]
- Duração estimada: [ex: 60 segundos]
- Formato de entrega: [ex: 16:9 widescreen / 9:16 vertical]
- Público-alvo: [descrever perfil do público]
- Notas brutas do briefing: [colar anotações e referências sem dados sensíveis]

INSTRUÇÃO:
Transforme o briefing acima em uma proposta inicial de roteiro e plano técnico de captação.

REGRAS OBRIGATÓRIAS:
- Separe claramente o que é [FATO DO BRIEFING] do que é [SUGESTÃO CRIATIVA].
- Não invente dados técnicos, locações, orçamentos ou prazos que não estejam no briefing.
- Sinalize explicitamente qualquer informação ausente ou ambígua em uma seção de dúvidas.

FORMATO DE SAÍDA:
1. Conceito central e tom de voz
2. Roteiro estruturado em tabela (Tempo | Cena | Áudio/Locução | Visual/Ação)
3. Plano técnico de captação (enquadramentos, sugestão de lentes, movimentos de câmera e proposta de iluminação)
4. Lacunas do briefing e perguntas para validação antes da gravação
```

```text
SKILL: Auditor e Checklist de Pré-Produção Audiovisual

OBJETIVO:
Revisar um roteiro e um plano de captação antes da gravação para evitar falhas de continuidade, lacunas técnicas e retrabalho no set ou na edição.

ENTRADAS VARIÁVEIS:
- Roteiro e plano de captação: [colar rascunho aprovado]
- Restrições conhecidas (equipe, tempo de set, locação): [listar restrições]

PROCEDIMENTO:
1. Verificar se todas as cenas têm requisitos claros de locação, iluminação, áudio e equipamento.
2. Mapear dependências críticas (autorizações de imagem/locação, figurino, props, backup de áudio e mídia).
3. Identificar riscos de cronograma ou pontos ambíguos que possam atrasar a gravação.
4. Gerar um checklist prático dividido por etapa (Antes do Set | No Set | Pós-Captação).
5. Entregar o material para revisão humana.

REGRAS:
- Não assumir disponibilidade de equipamentos ou locações não informadas.
- Não enviar mensagens, convocar equipe nem alterar datas de cronograma.
- Sinalizar dúvidas em vez de preencher lacunas por conta própria.

FORMATO DE SAÍDA:
1. Pontos de atenção e riscos mapeados
2. Checklist de pré-produção (com caixas [ ])
3. Decisões pendentes para aprovação do diretor
```

### Minha Delegação

```text
OBJETIVO:
Estruturar o pacote inicial de pré-produção (roteiro, plano de captação e checklist de riscos) para um vídeo institucional fictício de 60 segundos (Projeto Alfa — lançamento de serviço de energia limpa para pequenos comércios).

CONTEXTO:
Tenho apenas notas soltas de alinhamento e preciso chegar à reunião de pré-produção com um documento organizado para revisão. O vídeo será gravado em 1 diária, com equipe enxuta, no formato 16:9 com margem segura para adaptação em 9:16.

RECURSOS FORNECIDOS:
- Mensagem principal: redução de custos operacionais com instalação rápida e sem obras complexas.
- Tom desejado: cinematográfico, humano, direto e confiável (sem jargões técnicos excessivos).
- Locações previstas: 1 comércio local iluminado naturalmente e 1 ambiente de escritório.
- Atalhos de referência: Estruturador de Briefing e Skill Auditor de Pré-Produção.

LIMITES E REGRAS DE SEGURANÇA:
- Não redigir nem enviar e-mails/mensagens para equipe ou clientes.
- Não inventar depoimentos, números de economia ou nomes de pessoas/empresas.
- Separar explicitamente fatos do briefing de sugestões criativas.
- Checkpoint obrigatório: apresentar apenas o PLANO DE EXECUÇÃO antes de produzir o roteiro e o checklist, aguardando minha aprovação e eventuais ajustes.

CRITÉRIO DE SUCESSO:
Entregar um documento claro, dividido em Roteiro em tabela (60s), Plano Técnico de Captação, Checklist de Pré-Produção e Lista de Pendências, pronto para revisão humana antes da gravação.
```

### O Plano da IA

<img width="911" height="648" alt="image" src="https://github.com/user-attachments/assets/1a4021b2-b4d2-4428-83e8-7eaa1f75fd2c" />

<img width="892" height="557" alt="image" src="https://github.com/user-attachments/assets/1bebc021-2845-4d89-be18-153ed4272306" />

Antes de liberar a execução, revisei o plano de ponta a ponta para confirmar que a IA respeitaria as travas de segurança (sem inventar números, depoimentos ou disparar mensagens) e sinalizaria as lacunas do briefing como pontos de confirmação antes do set. Com o escopo e os checkpoints validados, autorizei a geração do roteiro, plano técnico e checklist.

### O Resultado

<img width="721" height="640" alt="image" src="https://github.com/user-attachments/assets/8e13aa9f-8ac0-4e94-b1a2-c8710befdc3e" />

<img width="725" height="567" alt="image" src="https://github.com/user-attachments/assets/3e5d706a-a808-49a7-8c02-b58f8f766047" />

<img width="691" height="630" alt="image" src="https://github.com/user-attachments/assets/b15a0a61-73be-4daf-aeb0-f22594123e1d" />

<img width="645" height="635" alt="image" src="https://github.com/user-attachments/assets/7fc530b5-f45c-4201-879f-bb4176da4fc5" />

<img width="712" height="611" alt="image" src="https://github.com/user-attachments/assets/ff8c724c-8de2-4426-b4a7-dba19e5ff66e" />

<img width="699" height="557" alt="image" src="https://github.com/user-attachments/assets/b98038e0-b24f-4672-931f-21ee296e9a42" />

<img width="671" height="424" alt="image" src="https://github.com/user-attachments/assets/1e915a28-503b-48eb-81eb-2db42778eb5e" />

Antes de aprovar o pacote de pré-produção para uso, apliquei a conferência **Pare, Confira, Use**:

- **Fatos vs. sugestões:** verifiquei que a IA separou corretamente `[FATO DO BRIEFING]` de `[SUGESTÃO CRIATIVA]` e não inventou números de economia, depoimentos, nomes de clientes nem equipamentos não informados.
- **Viabilidade técnica no set:** conferi se o kit sugerido (lentes 35mm e 50mm/85mm, tripé + gimbal leve e aproveitamento de luz natural com negative fill/rebatedor) cabe em 1 diária com equipe enxuta e respeita o formato 16:9 com *safe zone* 9:16.
- **Auditoria de riscos:** validei os alertas da *Skill Auditor* sobre variação de luz natural ao longo do dia, ruído e autorização de imagem caso o comércio esteja aberto, gravação de *room tone* e backup duplo dos cartões.
- **Limites de segurança:** confirmei que nenhuma mensagem externa foi redigida ou enviada e que todas as decisões em aberto permaneceram sob aprovação humana.

### Como Foi para Você

Trabalhar com atalhos reutilizáveis e checkpoint de plano antes da execução transformou a etapa de pré-produção audiovisual. Em vez de reescrever prompts longos toda semana ou revisar respostas cheias de suposições, agora transformo notas soltas de briefing em um pacote técnico organizado em poucos minutos — mantendo meu critério de direção, a segurança dos dados e a aprovação final em cada decisão.

