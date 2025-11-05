<div align="center">

# Inteli - Instituto de Tecnologia e Liderança

</div>
<p align="center">
<img src="assets/data-spice-logo.jpg" alt="Data SPYce Logo" border="0" style="border-radius: 50%; width: 80%; max-width: 300px;"></a>
</p>


<div align="center">

# Data SPYce
</div>

## Integrantes:

- <a href="https://www.linkedin.com/in/amandamartinezdarosa/">Amanda Cristina Martinez da Rosa</a>
- <a href="https://www.linkedin.com/in/annycerazi/">Anny Jhulia Cerazi</a>
- <a href="https://www.linkedin.com/in/catarina-sayuri/">Catarina Sayuri Arashiro Braga Felipe</a>
- <a href="https://www.linkedin.com/in/giorgiascherer3/">Giorgia Rigatti Scherer</a>
- <a href="https://www.linkedin.com/in/giovanna-neves-rodrigues/">Giovanna Neves Rodrigues</a>
- <a href="https://www.linkedin.com/in/mariaclaraos/">Maria Clara Oliveira Santos</a>
- <a href="https://www.linkedin.com/in/rayssaguedess/">Rayssa Guedes</a>

## Professores:

### Orientador(a)

- <a href="https://www.linkedin.com/in/laizaribeiro/">Laíza Ribeiro Silva(a)</a>

### Instrutores

- <a href="https://www.linkedin.com/in/bruna-mayer/">Bruna Mayer</a>
- <a href="https://www.linkedin.com/in/cristiano-benites-ph-d-687647a8/">Cristiano Benites</a>
- <a href="https://www.linkedin.com/in/geraldo-magela-severino-vasconcelos-22b1b220/">Geraldo Magela Severino Vasconcelos</a>
- <a href="https://www.linkedin.com/in/marcelo-gonçalves-phd-a550652/">Marcelo Luiz do Amaral Gonçalves</a>
- <a href="https://www.linkedin.com/in/pedroteberga/">Pedro Teberga</a>

## Descrição

&ensp;O produto desenvolvido é um modelo preditivo de vendas, uma solução que transforma dados de lojas, produtos e clientes em análises estratégicas sobre o desempenho da categoria de óculos de grau. Ele apresenta os resultados por meio de gráficos e visualizações intuitivas, permitindo identificar padrões de consumo, acompanhar tendências e projetar cenários futuros de forma clara e confiável.

&ensp;O foco do projeto é fortalecer a categoria de óculos de grau, que ainda possui baixa penetração em comparação ao reconhecimento da marca em armações e óculos de sol. A solução permite compreender as barreiras de consumo, detectar oportunidades de crescimento e apoiar a definição de campanhas direcionadas, experiências diferenciadas em loja e serviços que agreguem valor à jornada do consumidor.

&ensp;O desenvolvimento do projeto ocorreu ao longo de dez semanas e foi conduzido por um grupo multidisciplinar de estudantes de Engenharia de Software, Engenharia da Computação, Sistemas de Informação e Ciência da Computação. Essa diversidade de formações possibilitou a criação de um modelo robusto, aliado à elaboração de visualizações baseadas em conceitos de UX e design da informação, garantindo que os resultados fossem estratégicos, acessíveis e fáceis de interpretar.

&ensp;O diferencial da solução está em unir análises quantitativas a insights estratégicos, oferecendo uma ferramenta capaz de orientar decisões de negócio, ampliar o ticket médio e consolidar a presença da categoria de grau no mercado. O projeto combina ciência de dados e visão estratégica, tornando-se uma solução prática e escalável para apoiar o crescimento do segmento.

<b>Link para vídeo demonstrativo:</b> <a href="https://youtu.be/ksHu5-4qdLE">Acesse o vídeo demonstrativo</a>

## 📁 Estrutura de pastas

Dentre os arquivos presentes na raiz do projeto, definem-se:

- <b>readme.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

- <b>assets</b>: todas as imagens e mídias utilizadas nos notebooks e documentação são posicionadas aqui.

- <b>documents</b>: aqui estarão todos os documentos do projeto. Há também uma pasta denominada <b>extras</b> onde estão presentes documentos complementares.

- <b>database</b>: pasta para armazenar os conjuntos de dados (datasets) utilizados no projeto, como arquivos .csv.

- <b>notebooks</b>: todos os Jupyter Notebooks criados para desenvolvimento do projeto.

Estrutura visual:

```text

├── README.md                # arquivo de documentação do projeto
├── assets                   # imagens e mídias
│    └── gráficos            # gráficos gerados e utilizados na documentação
├── documents                # documentos do projeto
├── database                 # datasets
│   ├── datasets_iniciais
│   └── datasets_gerados
├── notebooks               # notebooks do projeto
│   ├── documentação        # notebooks de documentação
│   ├── gráficos            # notebooks de gráficos
│   ├── novas_features      # notebooks de novas features
│   └── modelos             # notebooks de modelos preditivos
│       ├── modelos_candidatos
│       └── modelo_final
├── gitignore                 # arquivos a serem ignorados pelo git
│
└── git attributes               # arquivos com atributos especiais para o git
```

## Execução dos projetos

### Requisitos mínimos

- Python 3.10+ (recomendado 3.11)
- Git
- VS Code com extensões: Python, Jupyter
- (Opcional) requirements.txt no repositório

Principais bibliotecas utilizadas (instale manualmente caso não exista requirements.txt):
pandas numpy scikit-learn scipy statsmodels matplotlib seaborn plotly jupyter ipykernel notebook

### Execução local (VS Code)

1. Clonar o repositório:
   git clone https://github.com/SEU_USUARIO/2025-2A-T17-IN03-G03.git
2. Entrar na pasta:
   cd 2025-2A-T17-IN03-G03
3. Criar ambiente virtual:
   python -m venv .venv
4. Ativar:
   - Windows: .venv\Scripts\activate
   - Linux/Mac: source .venv/bin/activate
5. Instalar dependências:
   - Com arquivo: pip install -r requirements.txt
   - Sem arquivo: pip install pandas numpy scikit-learn scipy statsmodels matplotlib seaborn plotly jupyter ipykernel
6. Registrar kernel (opcional):
   python -m ipykernel install --user --name spyce-env --display-name "Spyce Env"
7. Organizar dados:
   Colocar arquivos brutos em database/datasets_iniciais
   Arquivos derivados irão para database/datasets_gerados
8. Abrir notebooks:
   code .
   Executar células em ordem (Restart & Run All ao validar)
9. Exportar resultados (se aplicável) para pasta assets/gráficos ou database/datasets_gerados

### Execução no Google Colab

1. Abrir notebook desejado enviando-o para o Colab (Upload) OU arrastar da máquina.
2. Salvar uma cópia em seu Drive: Arquivo > Salvar uma cópia no Drive (necessário para persistir alterações).
3. Criar pasta no Colab /content/database/datasets_iniciais ou montar Drive:
   from google.colab import drive
   drive.mount('/content/drive')
4. Upload dos datasets (Interface ou:
   !mkdir -p database/datasets_iniciais
   ) e mover/colocar ali.
5. Instalar dependências na primeira célula:
   !pip install pandas numpy scikit-learn scipy statsmodels matplotlib seaborn plotly
6. (Opcional) Ativar GPU se fizer sentido: Runtime > Change runtime type > GPU.
7. Executar sequencialmente (Run all). Repetir execução após alterações de pré-processamento.
8. Baixar artefatos (gráficos/datasets) manualmente ou mover para /content/drive para persistir.

> No Colab, alterações só são mantidas se a cópia estiver salva no seu Drive. Upload simples do arquivo .ipynb não persiste edições após fechar a sessão.

### Ordem sugerida dos notebooks

1. notebooks/documentação (contexto e exploração inicial)
2. notebooks/gráficos (EDA visual)
3. notebooks/novas_features (engenharia de atributos)
4. notebooks/modelos/modelos_candidatos (comparação / tuning)
5. notebooks/modelos/modelo_final (pipeline consolidado)

### Convenção de caminhos no código

- Dados brutos: database/datasets_iniciais/arquivo.csv
- Dados processados: database/datasets_gerados/feature_set.parquet
- Gráficos: assets/gráficos/
- Modelo final (ex.): notebooks/modelos/modelo_final/modelo.pkl

### Reprodutibilidade

- Fixar seeds:
  import numpy as np, random, os
  import torch # se usar
  SEED = 42
  random.seed(SEED); np.random.seed(SEED)
- Documentar versões (pip freeze > versions.txt)
- Evitar executar células fora de ordem (usar Run All)

### Troubleshooting rápido

- Erro de kernel: recriar venv e reinstalar dependências.
- Módulo não encontrado no Colab: reinstalar na célula e reiniciar runtime.
- Divergência de métricas: confirmar seed e se o split train/test foi recriado inadvertidamente.
- Arquivo não encontrado: validar caminho relativo partindo da raiz do projeto.

## Histórico de lançamentos

### 1.0.0 - 26/06/2025 (Sprint 5)

- **Publicação e padronização final**
  - Adequação geral aos critérios de publicação institucional
  - Preparação do material para divulgação e entrega ao parceiro
- **Modelo final e documentação**
  - Entrega do modelo preditivo final no Colab
  - Preenchimento / revisão das Seções 2, 4.5 e 5
- **Revisões finais**
  - Revisão completa (código + documentação) conforme apontamentos anteriores
  - Consolidação de ajustes de clareza e consistência técnica

### 0.4.0 - 13/06/2025 (Sprint 4)

- **Comparação e seleção de modelos**
  - Definição das métricas comparativas alinhadas ao problema
  - Pelo menos três modelos candidatos com tuning de hiperparâmetros
  - Registro estruturado das métricas obtidas
- **Documentação e Colab**
  - Notebook de comparação de modelos
  - Preenchimento da Seção 4.4

### 0.3.0 - 30/05/2025 (Sprint 3)

- **Preparação e modelagem inicial**
  - Preparação de dados e definição de features
  - Primeira modelagem (candidato inicial) e análise de métricas (≥3)
- **Documentação e revisão**
  - Preenchimento das Seções 3 e 4.3
  - Revisões conforme issues apontadas
- **Cenários supervisionado / não supervisionado**
  - (Supervisionado) Justificativa das features e discussão dos resultados
  - (Não supervisionado) Modelo candidato, definição e justificativa do K ou tipo de recomendação
  - **Abordagem híbrida**
  - Implementação de pipeline combinando modelo supervisionado (predição) e etapa não supervisionada (agrupamento/análise estrutural) para enriquecer as features e interpretação dos resultados

### 0.2.0 - 16/05/2025 (Sprint 2)

- **Exploração e pré-processamento**
  - Estatística descritiva (tipagem numérica/categórica)
  - Limpeza: missing values, outliers; transformação: normalização / codificação
  - Pelo menos 3 gráficos relacionando variáveis
- **Hipóteses e testes**

  - 3 hipóteses levantadas
  - Testes de normalidade (3 variáveis) com hipótese, p-valor, conclusões e histogramas

- **Escalonamento**
  - Justificativa do método por variável
  - Equações com substituição dos parâmetros
  - Histogramas antes/depois + tabelas (originais x escalonadas)
- **Documentação e UX**
  - Preenchimento da Seção 4.2
  - Inclusão das Jornadas de Usuário (Seção 4.1.7)

### 0.1.0 - 02/05/2025 (Sprint 1)

- **Documentação inicial do negócio**
  - Seções 1, 4.1.1 a 4.1.5, 4.1.8 preenchidas
- **Análises estratégicas**
  - Contexto setorial, 5 Forças de Porter, 3 concorrentes, tendências e modelo de negócio
  - Análise SWOT em quadrante
- **Planejamento e proposta**
  - Planejamento geral da solução (dados, uso, benefícios, critérios de sucesso)
  - Value Proposition Canvas
- **Riscos e compliance**
  - Matriz de Riscos
  - Política de Privacidade (LGPD)
- **Personas**
  - Seção 4.1.6 (personas) adicionada

## Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.dev/Intelihub/Template_M3">MODELO GIT SPICE-GIRLS</a> by <a href="https://www.linkedin.com/in/amandamartinezdarosa/">Amanda da Rosa</a>, <a href="https://www.linkedin.com/in/annycerazi/">Anny Cerazi</a>, <a href="https://www.linkedin.com/in/catarina-sayuri/">Catarina Sayuri </a>, <a href="https://www.linkedin.com/in/giorgiascherer3/">Giorgia Scherer</a>, <a href="https://www.linkedin.com/in/giovanna-neves-rodrigues/">Giovanna Neves</a>, <a href="https://www.linkedin.com/in/mariaclaraos/">Maria Clara Santos</a>
, <a href="https://www.linkedin.com/in/rayssaguedess/">Rayssa Guedes</a> is licensed under a <a rel="license noopener noreferrer" href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank">Attribution 4.0 International License</a>.</p>

