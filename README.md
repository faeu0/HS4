<p align="center">
    <img width="200" src="https://qntnzfiotlkpreavgewa.supabase.co/storage/v1/object/public/Imagens/483ccb20-7779-44ca-97f7-6a8f94f4e567.jpg">
</p>

# Componentes do grupo

- Janine Evenny
- Karine Joice
- Rafael Nunes

# **Aplicação de IA no apoio à leitura e interpretação de receituários médicos**

## **Problema de Pesquisa:**

A escrita manual de receituários, laudos e outras documentações médicas frequentemente resulta em dificuldades de leitura e interpretação pelos pacientes, o que pode levar a erros na administração de medicamentos e ao mau entendimento das instruções médicas.

## **Objetivo Geral**

Desenvolver uma aplicação de apoio, que auxilie pacientes na leitura e interpretação correta de receituários, laudos e outras documentações médicas escritas manualmente.

## **Objetivos Específicos**

- Identificar os principais problemas enfrentados pelos pacientes na leitura de documentos médicos manuscritos.
- Criar uma ferramenta digital que utilize tecnologias de reconhecimento de escrita (OCR) e inteligência artificial para transcrever e interpretar a escrita manual.
- Desenvolver uma interface amigável que permita aos pacientes acessar e entender as informações médicas de forma clara e precisa.
- Testar e validar a eficácia do projeto proposto.

## **Justificativa**

- A dificuldade de leitura de documentos médicos manuscritos é um problema comum que afeta a segurança e a qualidade do cuidado com os pacientes.
- Erros na interpretação dessas informações podem resultar, por exemplo, na administração incorreta de medicamentos e complicações na saúde dos pacientes.
- Uma ferramenta que auxilie na leitura e interpretação desses documentos pode melhorar significativamente o tratamento, a comunicação entre médicos e pacientes e a redução de retorno de pacientes aos serviços.

<p align="center">
    <img width="400" src="https://qntnzfiotlkpreavgewa.supabase.co/storage/v1/object/public/Imagens/b4e973f0-56bd-4a68-a66b-d2f3714528d2.jpg">
</p>

## **Resultados Esperados**

- Auxílio na interpretação de receituários e laudos médicos por parte dos pacientes.
- Aumento da compreensão e adesão dos pacientes às recomendações médicas.
- Melhora na comunicação entre profissionais de saúde e pacientes.
- Auxílio no tratamento médico e redução de incidentes relacionados à administração incorreta de medicamentos.

## Trilha Escolhida

Paciente - "Soluções que que auxiliam pacientes e melhorem o acesso a saúde, reduzam filas, melhorem a triagem de pacientes e reduzam o retorno de pacientes aos serviços".

## Relação com o projeto

- O projeto aborda a dificuldade de leitura de documentos, que pode levar a erros na administração de medicamentos.
- Utilizando tecnologias de OCR e IA, o projeto visa aumentar a compreensão e adesão dos pacientes ao tratamento, melhorar a comunicação entre os médicos, agentes de saúde e pacientes.
- Alinhado com as metas de melhorar o acesso à saúde, reduzir filas e retornos desnecessários, o projeto contribui para um sistema de saúde mais eficiente e ágil.

## **Market Sizing**

- Em 2019, foi constatado que 72% das receitas médicas analisadas apresentavam algum grau de ilegibilidade.
- Já em 2022, a Agência Nacional de Vigilância Sanitária (Anvisa) recebeu 1.234 notificações de eventos adversos relacionados à ilegibilidade de receitas médicas. Entre esses eventos, 147 resultaram em óbitos.
- Por fim, em 2023, o Conselho Federal de Farmácia (CFF) lançou a campanha "Uma letra ilegível pode ser fatal", com o objetivo de conscientizar os profissionais de saúde e a população sobre a importância da escrita legível nas prescrições de medicamentos.
    
    [Fonte: CONSELHO FEDERAL DE FARMÁCIA, 2023](https://site.cff.org.br/noticia/noticias-do-cff/05/05/2023/uma-letra-ilegivel-pode-ser-fatal-cff-lanca-campanha-em-prol-da-prescricao-correta-de-medicamentos)

## **Business Plan**

![Untitled](https://qntnzfiotlkpreavgewa.supabase.co/storage/v1/object/public/Imagens/BP.png)

## Funcionalidades da aplicação

- Captura de imagem de documentos médicos manuscritos (receitas, laudos, etc.)
- Transcrição do texto manuscrito utilizando Reconhecimento Ótico de Caracteres (OCR)
- Interpretação dos dados transcritos, como medicamentos, dosagens, instruções, etc., por meio de Processamento de Linguagem Natural (PLN) e Aprendizado de Máquina (Machine Learning)
- Exibição das informações transcritas e interpretadas de forma clara e organizada para o paciente

## **Roadmap**

![Untitled](https://qntnzfiotlkpreavgewa.supabase.co/storage/v1/object/public/Imagens/Captura_de_tela_2024-06-23_210609.png?t=2024-06-24T00%3A06%3A48.192Z)

## Obstáculos e mitigações

### Qualidade e diversidade dos dados de treinamento:

- Obstáculo: Garantir que o conjunto de dados de treinamento seja abrangente e representativo da diversidade de receituários médicos.
- Mitigação: Coletar e curar um amplo conjunto de imagens de receituários, com anotações precisas, para treinar o modelo de IA de maneira robusta.

### Reconhecimento preciso de informações médicas:

- Obstáculo: Lidar com a variabilidade na escrita e formato dos receituários, bem como reconhecer corretamente termos médicos e abreviaturas.
- Mitigação: Desenvolver técnicas de pré-processamento e normalização de imagens, além de construir um dicionário abrangente de termos médicos e abreviaturas.

### Aceitação e confiança dos usuários:

- Obstáculo: Garantir que o sistema seja confiável, seguro e atenda às necessidades dos profissionais de saúde.
- Mitigação: Envolver médicos e profissionais da saúde no desenvolvimento e validação do sistema, implementar medidas de segurança e privacidade, e garantir a usabilidade e confiabilidade da solução.

## **Oportunidades de ampliação**

- Transcrever prontuários antigos para sistemas atuais de forma digitalizada.
- Analisar imagens médicas, como radiografias, tomografias e ressonâncias magnéticas, auxiliando os profissionais de saúde no diagnóstico de doenças.
- Treinar profissionais de saúde na interpretação de imagens médicas, fornecendo feedback e suporte durante o processo de aprendizagem.
- Analisar grandes conjuntos de dados de imagens e identificar novos padrões ou correlações.

---



# Solução: DocReader IA

Ao fornecer uma imagem do receituário, a aplicação é capaz de digitalizar e processar o conteúdo, transformando informações complexas em dados estruturados e de fácil compreensão. Acesse o MVP (Produto Mínimo Viável) da aplicação através do link: [DocReader IA](https://docreaderia.flutterflow.app/).

Para realização de testes da ferramenta disponibilizamos uma receita real que pode ser acessada [AQUI](https://qntnzfiotlkpreavgewa.supabase.co/storage/v1/object/public/Imagens/testes/1719171287746000.jpg).

# Passo a Passo: Criação da Aplicação

**Nome:** DocReader IA

**Título:** Aplicação de IA no apoio à leitura e interpretação: Decifrando Receituários Médicos, por meio de imagens.

### Passo 1: Frontend no FlutterFlow

1. **Configurar Layout:**
    - Escolhemos um template de página em branco.
    - Definimos como seria o conceito das paginas.
    - Adicionamos componentes de UI como botões, campos de texto e áreas para exibição de imagem.
      
  <p align="center">
    <img width="650" src="https://qntnzfiotlkpreavgewa.supabase.co/storage/v1/object/public/Imagens/PAG.png">
  </p>  
    
### Passo 2: Backend no Supabase

1. **Configurar Banco de Dados:**
    - Dentro do projeto Supabase, criamos uma nova tabela para armazenar informações das imagens e resultados do processamento.
2. **Configurar Armazenamento de Arquivos:**
    - Em "Storage" criamos um novo bucket para armazenar imagens carregadas pelos usuários.
    - Configuramos as permissões de acesso para permitir leitura e escrita neste bucket.
3. **Obter Chaves de API:**
    - Na seção "Settings" do Supabase, copiamos as chaves de API necessárias para integração com o FlutterFlow.
  
  <p align="center">
    <img width="650" src="https://qntnzfiotlkpreavgewa.supabase.co/storage/v1/object/public/Imagens/SUPB.png">
  </p>  


### Passo 3: Integrar o Supabase com o FlutterFlow

1. **Configuração de API:**
    - Inserimos as chaves de API do Supabase.
    - Configuramos os endpoints para interagir com o banco de dados e o armazenamento de arquivos no Supabase.
2. **Upload de Imagens:**
    - Criamos um fluxo no FlutterFlow para permitir upload de imagens pelos usuários.
    - Utilizamos a integração com o Supabase para enviar essas imagens ao bucket de armazenamento.

  <p align="center">
    <img width="650" src="https://qntnzfiotlkpreavgewa.supabase.co/storage/v1/object/public/Imagens/APSUPB.png">
  </p>  

### Passo 4: Processamento de Imagens com a API Vision da OpenAI

1. **Configurar API:**
    - No FlutterFlow, adicionamos uma nova integração de API para a API Vision da OpenAI.
    - Configuramos os endpoints para enviar imagens e receber resultados do processamento.
2. **Fluxo de Processamento:**
    - Após o upload da imagem, configuramos um fluxo para enviar a imagem à API Vision da OpenAI.
    - Recebemos o resultado do processamento e armazenamos no banco de dados do Supabase.
    - Exibimos o resultado ao usuário da aplicação.

  <p align="center">
    <img width="700" src="https://qntnzfiotlkpreavgewa.supabase.co/storage/v1/object/public/Imagens/APVIS.png">
  </p>  

Prompt: 

```jsx
Você é um médico muito habilidoso em ler receitas médicas escritas a mão onde as pessoas encontram dificuldade você compreender facilmente lembre-se você deve ler palavra por palavra para ter certeza de que a resposta correta.Para referência:AAS - Ácido Acetilsalicílico - A/O - Ambos os Olhos ou Ouvidos - ACM - A Critério do Médico - AMP - Ampola - BID - 2 vezes ao dia - BPM - Batimentos por Minuto - cc - Centímetro Cúbico - Ca - Cálcio - CAPS - Cápsulas - cm - Centímetro - cm3 - Centímetro Cúbico - COL - Colírio - COMP ou CP - Comprimidos - CPM - Conforme Prescrição Médica - CR - Creme - D - Dia - dL - decilitro - DRG / DG - Drágea - ENV - Envelope - EV/IV - Endovenosa / Intravenosa - FLAC / FL - Flaconete - FR - Frasco - g/gr - Grama (s) - GT/GTS - Gota/Gotas - INJ - Injetável - h - Hora - H202 - Água Oxigenada - ID - Intradérmica - IM - Intramuscular - IN - Intranasal - KCl - Cloreto de Potássio - kg - Kilograma (s) - KMnO4 - Permanganato de Potássio - L - Litro - µg / mcg - Micrograma (s) - mEq - Mili Equivalente - mg - Miligrama - Mg - Magnésio - mL - Mililitro - min - Minuto - mm - Milímetro - MTN - Manhã, Tarde, Noite - NaCl - Cloreto de sódio - NBZ - Nebulização - NPH - (Neutral Protamine Hagedorn) Insulina de Ação Intermediária - O2 - Oxigênio - OD - Olho ou Ouvido Direito - OE - Olho ou Ouvido Esquerdo - PA - Pressão Arterial - POM/PM - Pomada - PS - Pressão Sistólica - QD - 1 vez ao dia (todos os dias) - QID - 4 vezes ao dia - q.s.p. - Quantidade Suficiente Para - RX - Raio X - S/N - Se Necessário - SC - Subcutânea - seg - Segundo (s) - SF - Solução Fisiológica / Soro Fisiológico - SG - Solução Glicosada / Soro Glicosado - SGF - Soro Glicofisiológico - SL - Sublingual - Sol - Solução - SUP / SP - Supositório - SUSP / SS - Suspensão - SY - Spray - TB - Tubo - TD - Transdérmico - TID - 3 vezes ao dia - TRO - Terapia de Rehidratação Oral - U - Unidades - U.I. - Unidades Internacionais - USO INT - Uso Interno - USO EXT - Uso Externo - VD - Vidro - VOL. - Volume - VO - Via Oral - VR - Via Retal - VV - Via Vaginal - XPE/XP - Xarope Nota - Caso seja solicitado a interpretação de uma imagem que não seja um receita médica ou similar informe - Envie a imagem de uma receita médica válida.
```

### Passo 5: Teste e Publicação

1. **Testar a Aplicação:**
    - Utilizamos o modo de visualização do FlutterFlow para testar todas as funcionalidades.
    - Verificamos o funcionamento correto do upload de imagens, processamento pela API Vision e exibição dos resultados.
2. **Publicar a Aplicação:**
    - Quando satisfeitos com o funcionamento, usamos as ferramentas de publicação do FlutterFlow para gerar a aplicação Web, também disponível no formato PWA (Progressive Web App).
    - O acesso ao código flutter não pode ser disponibilizado devido a utilização do plano gratuito do FlutterFlow.

  <p align="center">
    <img width="350" src="https://qntnzfiotlkpreavgewa.supabase.co/storage/v1/object/public/Imagens/dsgfhsiuhgf.gif">
  </p>  

### Agradecimentos
    
Gostaríamos de expressar nosso profundo agradecimento por esta incrível oportunidade. A equipe NC Brasil está honrada em participar deste hackathon organizado pela Docsolution. Sua confiança e apoio são extremamente valiosos para nós, e apreciamos imensamente a chance de trabalhar com vocês neste desafio. Novamente, muito obrigado por esta oportunidade e por acreditarem em nosso potencial.

 <p align="center">
    <img width="200" src="https://qntnzfiotlkpreavgewa.supabase.co/storage/v1/object/public/Imagens/1687520159124.gif">
  </p> 
 
