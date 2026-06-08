# README do artigo

## Titulo do manuscrito

An Intelligent Behavioral Monitoring Platform for Observational Learning Analytics in Basic Education

## Objetivo do artigo

Este artigo apresenta uma plataforma inteligente de monitoramento comportamental voltada ao apoio da analise observacional da aprendizagem na educacao basica. O objetivo central e demonstrar a viabilidade de integrar Inteligencia Artificial, Learning Analytics e Visao Computacional para auxiliar professores e pesquisadores na observacao de padroes comportamentais visiveis em sala de aula.

A proposta nao busca substituir a avaliacao pedagogica do professor, nem realizar diagnosticos emocionais, psicologicos, medicos ou disciplinares. O sistema foi concebido como uma ferramenta de apoio a reflexao pedagogica, permitindo acompanhar tendencias observaveis de engajamento, participacao e movimentacao ao longo do tempo.

## Problema abordado

Em contextos presenciais de ensino, especialmente na educacao basica, o professor precisa conduzir a aula, organizar a turma, acompanhar a participacao dos estudantes e perceber sinais de atencao, distracao ou interacao. Essa observacao ocorre sob limitacoes de tempo, carga cognitiva e heterogeneidade da sala.

O artigo parte desse desafio para investigar como tecnologias de monitoramento visual podem apoiar a producao de indicadores observacionais, sem reduzir o comportamento estudantil a julgamentos automaticos ou inferencias afetivas.

## Proposta da pesquisa

A plataforma proposta integra:

- YOLOv11-Pose para estimativa de pose humana em tempo real;
- InsightFace com embeddings ArcFace para identificacao facial baseada em vetores;
- PostgreSQL com PGVector para armazenamento e busca por similaridade vetorial;
- analise geometrica de pontos corporais para interpretar padroes comportamentais observaveis;
- relatorios temporais para apoiar analises longitudinais de comportamento em sala.

Os comportamentos considerados no estudo incluem postura atenta, tendencias de distracao, agitacao, postura prolongada com cabeca baixa e gestos associados a questionamentos, como a mao levantada.

## Contribuicao principal

A principal contribuicao do artigo e propor um framework educacional interpretavel e eticamente orientado para monitoramento comportamental em sala de aula. Diferentemente de abordagens centradas em reconhecimento emocional, a plataforma trabalha com indicadores observaveis derivados de relacoes geometricas entre pontos corporais, favorecendo transparencia, acompanhamento temporal e apoio a tomada de decisao pedagogica.

## Escopo e limites

O estudo foi validado em ambiente laboratorial controlado, com fluxos de video RTSP simulando condicoes de monitoramento em sala de aula. Portanto, os resultados demonstram viabilidade tecnica e potencial pedagogico, mas nao representam uma validacao definitiva em salas reais, com variacoes amplas de iluminacao, oclusao, posicionamento de cameras, numero de estudantes e dinamicas escolares.

O uso da plataforma deve ser compreendido exclusivamente no contexto de pesquisa educacional, Learning Analytics e apoio observacional ao professor.

## Arquivos principais

- `sn-article.tex`: manuscrito principal em LaTeX.
- `references.bib`: base bibliografica utilizada no artigo.
- `sn-article.pdf`: versao compilada do artigo.
- `architecture.png`: arquitetura geral da plataforma.
- `pose_estimation.png`: exemplo de estimativa de pose.
- `behaviors.png`: estrutura de interpretacao comportamental.
- `dashboard.png`: interface de acompanhamento/visualizacao.
- `embeddings.png`: representacao conceitual de embeddings.
- `arcface_cnn.png`: representacao de embeddings faciais.
- `monitoring_realtime.png`: exemplo de monitoramento em tempo real.
- `graphic_pizza.png`, `graphic_pizza1.png`, `graphic_type.png`, `graphic_time.png`, `graphic_temporal.png`, `temporal_behavioral_distribution.png`: graficos e distribuicoes comportamentais usados na discussao dos resultados.

## Instrucoes para Overleaf

1. Envie todos os arquivos desta pasta para o Overleaf.
2. Abra o arquivo `sn-article.tex`.
3. Clique em `Recompile`.
4. Esta versao usa a classe padrao `article` e nao depende do arquivo `sn-jnl.cls`, por isso deve compilar mesmo em um projeto limpo.
5. Depois que o texto estiver finalizado, pode-se migrar novamente para o template oficial da Springer Nature.
6. Verifique se todas as imagens listadas no manuscrito foram enviadas ao projeto e mantem os mesmos nomes dos arquivos locais.

## Palavras-chave

Artificial Intelligence in Education; Learning Analytics; Computer Vision; Behavioral Monitoring; Intelligent Educational Systems; Educational Technology.
