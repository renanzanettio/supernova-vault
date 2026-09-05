
# Contexto do Projeto · PostVision

📎 Documentos originais: [[PostVision-Artefato-PI.pdf]] · [[PostVision-Artigo-Cientifico.pdf]] · [[PostVision-Pesquisa-Usuario.pdf]]

> Esta página reúne tudo que já existe do Projeto Integrador (PI) da Fatec Registro e serve de base para o projeto que a equipe vai construir/adaptar dentro da trilha Sebrae Supernova. Partes marcadas como "a definir" ainda não foram fechadas pela equipe.

---

## Visão geral

**Nome do projeto:** PostVision

**Equipe:** Carlos Henrique dos Santos Silva (Mobile Developer, Web Designer) · Heloísa Vale dos Santos (Redatora, Diagramas) · Raissa de Oliveira Souza (Redatora, Latex) · Renan Zanetti Oliveira (Web Developer, Mobile Designer, API) · Yuri Pignotti Koyama (Pitch)

**Origem:** Projeto Integrador do curso de Desenvolvimento de Software Multiplataforma, Fatec Registro (2026), ligado à ODS 3 (Saúde e Bem-Estar) e à ODS 9 (Indústria, Inovação e Infraestrutura).

**O que é:** aplicativo mobile de análise postural em exercícios físicos, orientado por Visão Computacional. Analisa a execução do exercício em tempo real pela câmera do celular, identifica erros de postura e devolve feedback e correções imediatas ao usuário, prevenindo lesões.

**Exercício-foco inicial:** agachamento (movimento completo, alto risco de lesão quando mal executado, base para expansão a outros exercícios depois).

---

## Problema

Cada vez mais gente treina sozinha — em casa ou na academia sem acompanhamento — por falta de tempo ou de dinheiro para contratar um profissional. Sem supervisão e sem instrução correta, a execução inadequada de exercícios físicos pode causar lesões sérias, como:

- **Hérnia de disco** — desgaste dos discos intervertebrais, geralmente na lombar, que pode comprimir raízes nervosas e causar dor e perda de sensibilidade.
- **Ruptura do ligamento cruzado anterior (LCA)** — lesão comum no joelho, atualmente o ligamento mais lesionado no Brasil, que pode levar a meses de reabilitação.

**Enunciado do problema (formato usuário + dor + contexto + impacto):** pessoas que praticam exercícios físicos sem supervisão profissional (por questões financeiras ou de tempo) não têm como saber, no momento da execução, se sua postura está correta — o que aumenta o risco de lesões e compromete a segurança e a consistência do treino.

> **5 Porquês:** ainda não foi formalmente documentado pela equipe (o artigo parte direto do problema, sem registrar a cadeia de porquês). Fica como tarefa em aberto do Módulo 1 — ver checklist em [[Ideias-e-Atividades]].

---

## Público-alvo · dois segmentos

A pesquisa de usuário (entrevistas + personas) revelou que o PostVision fala, na prática, com **dois públicos diferentes**, que o Canvas acadêmico original não separava:

### 1. Praticantes autônomos (quem treina sozinho)
Pessoas que já praticam ou querem começar a praticar exercícios físicos sem orientação profissional — por não terem dinheiro para pagar um personal trainer, ou por já treinarem sozinhas e sentirem insegurança na execução.

**Personas:**
- **Isabella Martins**, 24, arquiteta, cidade natal Juquiá. Pratica musculação e calistenia nas horas vagas para aliviar o estresse do trabalho. Acha que sua postura está errada nesses exercícios e não tem dinheiro para um personal. *"Atualmente me sinto presa no serviço e encontro na academia um jeito de me desestressar, porém não tenho dinheiro para um personal."*
- **Lucas Oliveira**, 68, aposentado (formação em ADS), cidade natal Miracatu. Voltou a treinar recentemente após anos parado e fez uma cirurgia delicada nas costas — treina inseguro, com medo de se complicar. *"Na minha juventude sempre gostei de atividades físicas, agora voltando a praticar preciso de uma forma de orientação."*
- **"Fulana"** (nome fictício), 27, autônoma e mãe, cidade natal Registro. Pratica musculação e pilates, treina sozinha e tem insegurança por depender de análise tardia (gravar e assistir depois) em vez de correção no momento do exercício. *"Eu gostaria que o sistema me corrigisse ao longo do treino, como se fosse um profissional, e em tempo real."*

### 2. Profissionais de educação física / personal trainers
Profissionais que buscam apoio para ensinar e validar a evolução postural de alunos, especialmente em consultorias remotas.

**Persona:**
- **"Betrano"** (nome fictício), 35, profissional de educação física, cidade natal Júquia. Pratica calistenia, natação e cross; testa modalidades que domina parcialmente para ensinar aos alunos. Tem dificuldade em ensinar postura e técnica corretas, e quer validar a evolução dos alunos com gráficos e dados precisos. *"Sou treinador e gosto de fazer experimentos práticos de modalidades como a calistenia, que domino parcialmente, para aplicar no ensino aos meus alunos."*

> **Nota para o Canvas:** o Business Model Canvas atual (versão acadêmica) só descreve o segmento "praticantes de exercícios físicos / atletas amadores" — ele ainda não reflete esse segundo público (profissionais). Isso é um dos pontos centrais a ajustar no Canvas do Supernova (ver seção mais abaixo e [[Ideias-e-Atividades]] · Módulo 2).

---

## Pesquisa com usuários

**Processo de pesquisa (3 saídas de campo + entrevistas):**

| # | Local | Data | Tipo |
|---|---|---|---|
| 1 | Juquiá | 29/04/2026 | Presencial, conduzida com base em experiências |
| 2 | Registro | 30/04/2026 | Presencial, conduzida com base em aprendizados e dificuldades |
| 3 | Sete Barras | 06/05/2026 | Entrevista, conduzida com base em aprendizado e dificuldades |

**Mapas de empatia** foram construídos para os dois grupos (leigos e profissionais), cruzando dores, desejos, o que ouvem/falam/fazem.

![[PostVision-Pesquisa-Usuario.pdf#page=12]]

**Principais dores identificadas:**
- Insegurança durante os exercícios feitos sem supervisão.
- Medo de se lesionar (especialmente relevante para iniciantes e pessoas mais velhas).
- Alto custo da supervisão profissional (personal trainers "fora da realidade" do orçamento do usuário).
- Do lado dos profissionais: dificuldade em ensinar/corrigir postura à distância, falta de dados objetivos para validar a evolução do aluno.

**Necessidades identificadas (síntese da pesquisa):**
- Feedback em tempo real com alertas imediatos de postura.
- Modelos visuais e 3D para demonstrar o movimento correto.
- Monitoramento da evolução técnica e da performance.
- Interface simples para treino autônomo e suporte remoto.

**Risco identificado:** chance de desuso do app depois do período inicial (queda de engajamento). Soluções de retenção já mapeadas pela equipe: alertas em tempo real e histórico de evolução do usuário.

> **Conclusão da pesquisa:** o PostVision atende tanto alunos que buscam autonomia quanto profissionais que precisam de mais precisão e gestão em consultorias. O principal diferencial é a correção em tempo real com alertas imediatos. A lição central foi a necessidade de unir uma interface simples com gráficos evolutivos detalhados para acompanhar o progresso a longo prazo.

---

## Proposta de valor

Segurança e autonomia na prevenção de lesões durante o treino, por meio de:
- Análise corporal automática e instantânea através da câmera do celular.
- Correção postural imediata, com alertas visuais intuitivos.
- IA de análise em tempo real (feedback dinâmico).
- Relatório personalizado de evolução do usuário.

---

## Como funciona (visão técnica)

**Fluxo da aplicação:**

![[PostVision-Artigo-Cientifico.pdf#page=5]]

1. Definir os parâmetros do exercício.
2. Iniciar a gravação com IA (câmera ativada via CameraX).
3. Analisar a postura por meio do MediaPipe (detecção de landmarks/pontos-chave do corpo).
4. Calcular posições/ângulos a partir dos landmarks.
5. Fornecer feedback em tempo real.
6. Armazenar os landmarks e encerrar a execução.
7. Processar e modelar os dados.
8. Apresentar os resultados ao usuário (relatório visual).

**Stack técnica:**

| Camada | Tecnologia |
|---|---|
| App mobile | Kotlin + Jetpack Compose (Material Design 3), Min SDK 24 / Target SDK 35 / Compile SDK 36 |
| Captura de imagem | CameraX 1.5.0 |
| Detecção de pose | **MediaPipe** 0.10.0 (API de Pose Detection — landmarks do corpo) |
| Navegação | Navigation 2.7.5 |
| Comunicação com backend | Retrofit 2.9.0 (cliente HTTP) |
| Dados JSON | Gson 2.10.1 |
| Autenticação | JWT 2.0.2 + OAuth 2.0 |
| Backend | Node.js / Express, hospedado no Render |
| Banco de dados | MongoDB Atlas (NoSQL, orientado a documentos — coleções: users, exercises, sessions, tasks, notifications) |
| Site institucional da equipe | React 18.2 + Next.js + Tailwind CSS, hospedado na Vercel, formulário via EmailJS |
| Gestão de projeto | Kanban no GitHub Projects |

> **Nota técnica:** a detecção de pose usada hoje é exclusivamente **MediaPipe** (o artigo, na seção de Estado da Arte, menciona "OpenPose" ao comparar com o projeto de Yang e Chen — mas isso é sobre o projeto comparado, não sobre o PostVision; a tecnologia usada de fato pela equipe é o MediaPipe, confirmado pela equipe).

**Infraestrutura:**

![[PostVision-Artefato-PI.pdf#page=13]]

---

## Diferencial competitivo (Estado da Arte do artigo)

O artigo científico comparou o PostVision com três projetos acadêmicos parecidos:

| Projeto | Tecnologia | Métrica | Limitação/foco |
|---|---|---|---|
| Gonçalves et al. (2023) | CNNs (YOLO) + MediaPipe | 84,17% de acurácia (mAP) | Dataset inicial de baixa qualidade/diversidade |
| Passos (2022) — POSEXAU | Visão computacional 2D (plano x,y) | Acurácia média | Sem foco em tempo real; sofre com câmera/iluminação |
| Yang e Chen (2020) — Pose Trainer | OpenPose + Aprendizado de Máquina | F1-score de 0,85 | Eficaz, mas sem estatísticas de evolução do usuário |

**Diferencial do PostVision:** nenhum dos três gera, ao mesmo tempo, **correção em tempo real** *e* **estatísticas personalizadas de evolução** para o praticante acompanhar seu progresso — essa combinação é o que o artigo aponta como o principal ponto de diferenciação do projeto.

---

## Business Model Canvas · versão acadêmica (referência/PI)

Este é o Canvas registrado no artefato do PI, usado como ponto de partida:

![[PostVision-Artefato-PI.pdf#page=3]]

**Análise SWOT que acompanha esse Canvas:**

![[PostVision-Artefato-PI.pdf#page=4]]

---

## Business Model Canvas · rascunho adaptado para o Supernova

> ✏️ **Decisão da equipe (registrada em conversa):** em vez de escolher entre "só praticante" ou "só profissional", o Canvas adota **um segmento primário** (praticante autônomo, que é a dor mais validada e a linha que já vem do PI) e trata o **profissional como segmento de expansão / segundo canal de receita**, não como um segundo produto. A proposta de valor central continua sendo uma só: "democratizar a supervisão postural em tempo real" — o profissional é uma forma de monetizar e escalar essa mesma proposta, não um problema diferente a resolver. Revisar e ajustar durante o Módulo 2 (ver [[Modulo-2-Business-Model-Canvas]] para o conteúdo da aula).

### Os 9 blocos

**1. Segmentos de clientes**
- **Primário:** praticantes autônomos — pessoas que treinam sozinhas sem orientação profissional (iniciantes, restrição orçamentária, histórico de lesão, idade mais avançada). Ex.: Isabella, Lucas, "Fulana".
- **Expansão (fase 2):** profissionais de educação física / personal trainers, que usam o app como ferramenta de trabalho com seus alunos. Ex.: "Betrano".

**2. Proposta de valor**
- Núcleo (vale para os dois segmentos): correção postural em tempo real via câmera do celular, com alertas imediatos e relatório de evolução — reduz o risco de lesão e a dependência de supervisão presencial cara.
- Camada extra para o segmento de expansão: dados objetivos (gráficos, métricas) que ajudam o profissional a validar a evolução do aluno e a corrigir postura à distância — o app dá ao personal trainer uma capacidade que ele hoje não tem sozinho.

**3. Canais**
- App mobile, website institucional, marketing digital (redes sociais, conteúdo sobre prevenção de lesão) — canal principal para o praticante autônomo.
- Canal de expansão: contato direto com academias, personal trainers e fisioterapeutas (parcerias) — já indicado como oportunidade na SWOT acadêmica.

**4. Relacionamento com cliente**
- Praticante: suporte contínuo pelo app, notificação push, e-mail, redes sociais.
- Profissional: relacionamento mais próximo/consultivo — o personal trainer que assina se torna também um canal de distribuição (cada personal pode trazer vários alunos usando o app), então vale tratá-lo quase como um parceiro, não só como assinante.

**5. Fontes de receita**
- Assinatura mensal/anual do praticante autônomo (plano B2C, como já estava no Canvas acadêmico).
- **Novo:** plano profissional/B2B2C para personal trainers, com preço mais alto (ferramenta de trabalho, não gasto pessoal) e possivelmente por número de alunos monitorados — a definir com a equipe.
- Atenção: personal trainers já reclamam de preços "fora da realidade" cobrados por outros profissionais — cuidado para o plano B2B2C do PostVision não cair nessa mesma percepção.

**6. Recursos-chave** *(sem mudança relevante em relação ao Canvas acadêmico)*
Equipe técnica, infraestrutura de computação, banco de dados de imagens/vídeos, softwares e frameworks, hardware para testes.

**7. Atividades-chave** *(sem mudança relevante)*
Desenvolvimento contínuo do software, coleta/processamento de dados, desenvolvimento de algoritmos de Visão Computacional, teste e validação, design de interface, manutenção.

**8. Parcerias-chave**
- Empresas de tecnologia/IA, empresas do ramo fitness, influenciadores fitness (já previstos).
- **Novo, ligado à expansão:** academias, personal trainers e fisioterapeutas como parceiros de distribuição — não só como clientes, mas como canal para chegar a mais praticantes autônomos.

**9. Estrutura de custos** *(sem mudança relevante)*
Hospedagem de aplicativo e IA (nuvem), marketing e publicidade. Vale reavaliar se o segmento de expansão (profissional) traz custo adicional relevante (ex.: suporte consultivo, dashboards extras).

### Concorrência a mapear no Módulo 2 (Videoaula 2 — Análise de Concorrência)
- Direta: apps de treino já consolidados (citados como ameaça na SWOT), tanto os voltados ao praticante final quanto eventuais plataformas usadas por personal trainers para acompanhar alunos.
- Indireta/acadêmica: os três projetos citados no Estado da Arte do artigo (Gonçalves et al., Passos/POSEXAU, Yang e Chen/Pose Trainer) — nenhum comercial ainda, mas mostram o "estado da técnica" e nenhum combina tempo real + estatísticas de evolução.

### Pontos de atenção levantados pela pesquisa
- Risco de **desuso do app** (churn) após o período inicial → o bloco de relacionamento/retenção (histórico de evolução, alertas contínuos) importa tanto quanto a aquisição de clientes.
- O segmento de expansão só deve ser priorizado depois que o núcleo B2C estiver validado — tratar como "fase 2" evita diluir o foco do pitch e do MVP.

---

## Estado atual e próximos passos

**Em que módulo/etapa estamos agora:** Módulo 2 (Business Model Canvas) da trilha Supernova — com Módulo 1 (Ideação e Validação) já parcialmente coberto pela pesquisa de usuário feita no PI (personas, mapas de empatia, entrevistas), mas ainda sem os 5 Porquês formalizados nem hipóteses de validação redigidas no formato Supernova.

**Principais decisões já tomadas:**
- Exercício-foco inicial: agachamento.
- Tecnologia de detecção de pose: MediaPipe (não OpenPose).
- Dois segmentos de cliente identificados pela pesquisa (praticantes autônomos e profissionais), mesmo que o Canvas acadêmico ainda não os separe.
- Equipe decidiu adaptar/atualizar o Canvas para a trilha Supernova em vez de usar o Canvas acadêmico tal como está.

**Próximos passos sugeridos:**
- Formalizar os 5 Porquês e as hipóteses de validação no Módulo 1 (ver checklist em [[Ideias-e-Atividades]]).
- Revisar e fechar o Canvas adaptado (rascunho acima) com a equipe.
- Levar o segmento "profissionais" para a Videoaula 2 (Análise de Concorrência) e mapear concorrentes B2B2C, não só B2C.
- Decidir modelo de monetização considerando os dois segmentos.
