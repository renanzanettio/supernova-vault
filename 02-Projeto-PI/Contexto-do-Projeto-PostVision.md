# Contexto do Projeto · PostVision

📎 Documentos originais: [[PostVision-Artefato-PI.pdf]] · [[PostVision-Artigo-Cientifico.pdf]] · [[PostVision-Pesquisa-Usuario.pdf]] · [[PostVision-Canvas-Atual.pdf]]

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

## Business Model Canvas · versão atual (Supernova)

📎 Canvas original (imagem/ferramenta): [[PostVision-Canvas-Atual.pdf]]

> ✅ **Este Canvas já foi fechado pela equipe** — não é mais rascunho. Ele parte da mesma decisão discutida anteriormente (um segmento primário + um segmento de expansão, em vez de escolher só um lado), mas a equipe formalizou os detalhes à própria maneira ao montá-lo na ferramenta. Abaixo, os 9 blocos exatamente como estão no Canvas, mais algumas observações de leitura.

### Os 9 blocos (conforme o Canvas da equipe)

**1. Segmento de mercado**
- **B2B2C:** personal trainers e profissionais de Educação Física.
- **B2C:** usuários que praticam exercícios sem auxílio de profissional.

**2. Proposta de valor**
- Correção postural em tempo real pela câmera do celular, com alertas e relatórios de evolução.
- Redução do risco de lesões e da dependência de supervisão presencial cara.
- Métricas e gráficos objetivos para acompanhamento e validação do aluno à distância.

**3. Canais**
- Marketing digital e redes sociais (foco em prevenção de lesões).
- Parcerias diretas com academias e personal trainers.

**4. Relacionamento com o cliente**
- Suporte e notificações push automatizados no app.
- Retenção via histórico contínuo de evolução.
- Atendimento próximo e consultivo para personal trainers.

**5. Fontes de renda**
- Plano B2B2C para personal trainers (por licença ou volume de alunos).
- Plano B2C Freemium.

**6. Recursos-chave**
- Equipe técnica e desenvolvedores.
- Infraestrutura de nuvem e banco de dados visual.
- Algoritmos de Visão Computacional (MediaPipe).

**7. Atividades-chave**
- Desenvolvimento do software e algoritmos de pose tracking.
- Processamento de dados e testes com os exercícios.
- Design de interface (UI/UX) e manutenção do app.

**8. Parceiros-chave**
- Empresas de tecnologia/IA e marcas do meio fitness.
- Influenciadores digitais da área de saúde/treino.
- Academias e personal trainers.

**9. Estrutura de custos**
- Servidores, hospedagem e processamento de IA em nuvem.
- Investimento em marketing e aquisição de clientes (CAC).
- Suporte e infraestrutura para dashboards do plano profissional.

### O que mudou em relação ao Canvas acadêmico (PI)
- **Segmentação explícita em dois públicos** (B2B2C e B2C), em vez de um só segmento genérico de "praticantes/atletas amadores".
- **Modelo de receita redesenhado:** o plano B2C agora é **Freemium** (gratuito com upgrade), e quem sustenta a receita principal é o **plano B2B2C** vendido a personal trainers — diferente da ideia inicial de assinatura paga nos dois lados. Isso resolve bem o risco de objeção de preço no público autônomo (usar o freemium para crescer a base) e concentra a monetização onde há maior disposição a pagar (profissional, ferramenta de trabalho).
- **Parcerias-chave ganham papel duplo:** academias e personal trainers aparecem tanto como parceiros de distribuição quanto como o próprio cliente B2B2C.
- **Relacionamento com cliente diferenciado por segmento:** automatizado/self-service para o praticante (push, histórico), consultivo para o profissional.
- **Estrutura de custos já prevê o custo específico do plano profissional** (suporte e infraestrutura de dashboards).

> 💬 **Ponto que vale confirmar com a equipe:** o Canvas lista o segmento B2B2C antes do B2C. Se isso for só a ordem da ferramenta, não muda nada — mas se for intencional (ex.: decidiram priorizar o profissional como entrada principal, e não mais o praticante autônomo como "primário"), vale atualizar essa leitura no pitch e no MVP também, já que a direção discutida antes era o oposto (praticante como núcleo, profissional como expansão).

### Concorrência a mapear no Módulo 2 (Videoaula 2 — Análise de Concorrência)
- Direta: apps de treino já consolidados (citados como ameaça na SWOT), tanto os voltados ao praticante final quanto eventuais plataformas usadas por personal trainers para acompanhar alunos.
- Indireta/acadêmica: os três projetos citados no Estado da Arte do artigo (Gonçalves et al., Passos/POSEXAU, Yang e Chen/Pose Trainer) — nenhum comercial ainda, mas mostram o "estado da técnica" e nenhum combina tempo real + estatísticas de evolução.

### Pontos de atenção levantados pela pesquisa
- Risco de **desuso do app** (churn) após o período inicial — o bloco de relacionamento/retenção (histórico de evolução, alertas contínuos) importa tanto quanto a aquisição de clientes.
- Modelo Freemium no B2C ajuda a crescer a base de usuários, mas precisa de um gatilho claro de upgrade — vale definir isso como próximo passo (o que é grátis vs. o que é pago no plano B2C?).

---

## Estado atual e próximos passos

**Em que módulo/etapa estamos agora:** Módulo 5 (Finanças) da trilha Supernova — Módulos 1 a 4 já cobertos em algum grau; o Canvas (Módulo 2) já está fechado pela equipe na ferramenta própria. Falta formalizar os 5 Porquês no formato Supernova (Módulo 1) e aplicar os exercícios de precificação do Módulo 5 ao modelo Freemium + B2B2C.

**Principais decisões já tomadas:**
- Exercício-foco inicial: agachamento.
- Tecnologia de detecção de pose: MediaPipe (não OpenPose).
- Dois segmentos de cliente identificados pela pesquisa (praticantes autônomos / B2C e profissionais / B2B2C) — já formalizados no Canvas.
- Canvas adaptado ao Supernova concluído: B2C em Freemium, B2B2C (personal trainers) como plano pago principal.

**Próximos passos sugeridos:**
- Formalizar os 5 Porquês e as hipóteses de validação no Módulo 1 (ver checklist em [[Ideias-e-Atividades]]).
- Confirmar com a equipe se a ordem B2B2C → B2C no Canvas reflete prioridade real ou é só a ordem da ferramenta (ver observação na seção do Canvas acima).
- Levar o segmento "profissionais" para a Videoaula 2 (Análise de Concorrência) e mapear concorrentes B2B2C, não só B2C.
- Definir o gatilho de upgrade do plano Freemium (o que é grátis vs. pago no B2C) usando a lógica de precificação do Módulo 5.
- Aplicar a planilha de custos fixos/variáveis (Módulo 5) à estrutura de custos do Canvas (servidores/IA, marketing/CAC, suporte ao plano profissional).
- Decidir modelo de monetização considerando os dois segmentos.
