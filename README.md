# 🧠 Curso de Processamento de Linguagem Natural (PLN)

> Repositório oficial do curso de PLN — notebooks, exercícios, resoluções e recursos de configuração de ambiente.

---

## 📌 Sobre o Curso

Este repositório contém o material completo de um curso introdutório de **Processamento de Linguagem Natural (PLN)**, desenvolvido com foco em alunos iniciantes. Todo o conteúdo é apresentado em **Jupyter Notebooks**, compatíveis com **Google Colab** e com execução local via **Miniconda**.

O curso percorre um caminho progressivo: dos fundamentos teóricos (representação do significado das palavras) até aplicações reais (chatbots, motores de busca, assistentes virtuais), passando por ferramentas, arquiteturas de redes neurais e modelos de linguagem de última geração.

---

## 🗂️ Estrutura do Repositório

```
pln-curso/
│
├── 📁 aula_01_representacoes_conceituais/
│   ├── Aula_01_Representacoes_Conceituais.ipynb
│   ├── Aula_01b_BabelNet_APIKey.ipynb
│   ├── Aula_01c_BabelNet_Explorando_Synsets.ipynb
│   └── Aula_01d_Fechamento.ipynb
│
├── 📁 aula_02_tecnologias_ferramentas/
│   └── Aula_02_Tecnologias_e_Ferramentas.ipynb
│
├── 📁 aula_03_arquiteturas_pln/
│   └── Aula_03_Arquiteturas_RNN_LSTM_Transformer.ipynb
│
├── 📁 aula_04_modelos_pretreinados/
│   └── Aula_04_BERT_GPT_Transformers.ipynb
│
├── 📁 aula_05_aplicacoes_multimodais/
│   └── Aula_05_Aplicacoes_Multimodais.ipynb
│
├── 📁 aula_06_aplicacoes_pln/
│   └── Aula_06_Traducao_Sumarizacao_Sentimento.ipynb
│
├── 📁 aula_07_casos_de_uso/
│   └── Aula_07_Chatbots_Busca_Assistentes.ipynb
│
├── 📄 environment.yml          ← Ambiente para Linux/macOS
├── 📄 environment_win.yml      ← Ambiente para Windows
├── 📄 LEIA-ME-WINDOWS.txt      ← Guia de instalação no Windows
├── 📄 verificacao_ambiente.ipynb
└── 📄 README.md
```

---

## 📚 Conteúdo das Aulas

### Aula 1 — Representações Conceituais de Palavras
> *Como o computador entende o significado das palavras?*

| Tópico | Descrição |
|---|---|
| Ontologias | Estruturas formais de conceitos e relações |
| Grafos de Conhecimento | Representação visual com nós e arestas |
| WordNet | Banco léxico da língua inglesa (Princeton) |
| BabelNet | WordNet multilíngue com 500+ idiomas e API REST |
| Similaridade semântica | Calcular proximidade entre conceitos |
| Ambiguidade lexical | Uma palavra, múltiplos significados |

**Ferramentas:** `nltk` · `networkx` · `matplotlib` · `requests` · `python-dotenv`

---

### Aula 2 — Tecnologias e Ferramentas para PLN
> *As principais ferramentas usadas por profissionais de PLN.*

| Tópico | Descrição |
|---|---|
| spaCy | Pipeline industrial: tokenização, POS, NER, dependências |
| NLTK | Suíte completa de ferramentas linguísticas |
| Hugging Face | Repositório de modelos e datasets pré-treinados |
| OpenCV | Processamento de imagens para PLN multimodal |
| TensorFlow | Framework de deep learning para PLN |

**Ferramentas:** `spacy` · `nltk` · `transformers` · `datasets` · `opencv-python` · `tensorflow`

---

### Aula 3 — Arquiteturas para PLN
> *Como os modelos de linguagem são construídos internamente?*

| Tópico | Descrição |
|---|---|
| RNNs | Redes neurais recorrentes e processamento sequencial |
| LSTMs | Memória de longo prazo e solução do vanishing gradient |
| GRUs | Alternativa simplificada às LSTMs |
| Mecanismo de Atenção | Foco seletivo em partes relevantes do texto |
| Transformers | Arquitetura que revolucionou o PLN moderno |

**Ferramentas:** `torch` · `tensorflow` · `keras` · `matplotlib`

---

### Aula 4 — Modelos de Linguagem Pré-Treinados
> *BERT, GPT e a era dos grandes modelos de linguagem.*

| Tópico | Descrição |
|---|---|
| Transfer Learning | Reutilizar modelos treinados em grandes corpora |
| BERT | Modelo bidirecional da Google para compreensão de texto |
| GPT | Modelo autorregressivo da OpenAI para geração de texto |
| DistilBERT | Versão compacta do BERT (ideal para CPU) |
| Fine-tuning | Adaptar modelos pré-treinados para tarefas específicas |

**Ferramentas:** `transformers` · `datasets` · `tokenizers` · `accelerate` · `torch`

---

### Aula 5 — Aplicações Multimodais
> *PLN além do texto: combinando linguagem com visão computacional.*

| Tópico | Descrição |
|---|---|
| Recuperação Multimodal | Buscar informações em texto + imagem |
| Modelos Bidirecionais | Processar informação nos dois sentidos |
| Modelos Crossmodal | Conectar representações de texto e imagem |
| Sentence Transformers | Embeddings semânticos de sentenças |
| Aplicações práticas | Busca por imagem com descrição textual |

**Ferramentas:** `sentence-transformers` · `Pillow` · `opencv-python` · `transformers`

---

### Aula 6 — Aplicações de PLN
> *Tradução, sumarização e análise de sentimento na prática.*

| Tópico | Descrição |
|---|---|
| Tradução Automática | Modelos seq2seq e avaliação com BLEU |
| Sumarização | Sumarização extrativa e abstrativa com ROUGE |
| Análise de Sentimento | Classificação de polaridade em textos |
| Avaliação de modelos | Métricas BLEU, ROUGE e F1 |

**Ferramentas:** `transformers` · `sacrebleu` · `rouge-score` · `textblob`

---

### Aula 7 — Casos de Uso Reais
> *PLN nos produtos que usamos todos os dias.*

| Tópico | Descrição |
|---|---|
| Chatbots | Construção de bots conversacionais com PLN |
| Motores de Busca | Busca semântica e recuperação de informação |
| Assistentes Virtuais | Reconhecimento de intenção e entidades |
| Prototipagem rápida | Interfaces interativas com Gradio |

**Ferramentas:** `transformers` · `gradio` · `spacy` · `sentence-transformers`

---

## ⚙️ Configuração do Ambiente

### Pré-requisitos

- [Miniconda](https://docs.conda.io/en/latest/miniconda.html) instalado
- Python 3.10
- Conexão com a internet (para download de modelos)

---

### 🐧 Linux / macOS

```bash
# 1. Clonar o repositório
git clone https://github.com/seu-usuario/pln-curso.git
cd pln-curso

# 2. Criar o ambiente conda
conda env create -f environment.yml

# 3. Ativar o ambiente
conda activate pln-curso

# 4. Registrar o kernel no Jupyter
python -m ipykernel install --user --name pln-curso --display-name "PLN Curso"

# 5. Abrir o Jupyter
jupyter notebook
```

---

### 🪟 Windows

> ⚠️ O Windows requer passos adicionais por conta de conflitos de DLL com o PyTorch.  
> Siga o arquivo [`LEIA-ME-WINDOWS.txt`](./LEIA-ME-WINDOWS.txt) para o guia completo.

```bash
# 1. Instalar o Visual C++ Redistributable
#    https://aka.ms/vs/17/release/vc_redist.x64.exe
#    → Reiniciar o computador após instalar

# 2. Criar o ambiente (sem PyTorch)
conda env create -f environment_win.yml

# 3. Ativar o ambiente
conda activate pln-curso

# 4. Instalar PyTorch via pip (evita conflito de DLL)
pip install torch==2.2.0 torchvision==0.17.0 --index-url https://download.pytorch.org/whl/cpu

# 5. Instalar OpenCV
pip install opencv-python-headless==4.9.0.80

# 6. Registrar o kernel
python -m ipykernel install --user --name pln-curso --display-name "PLN Curso"

# 7. Abrir o Jupyter
jupyter notebook
```

---

### ✅ Verificar a instalação

Após configurar, abra e execute o notebook de verificação:

```
verificacao_ambiente.ipynb
```

Todas as células devem terminar com ✅. Se alguma falhar, consulte a seção de erros comuns abaixo.

---

## 🔑 BabelNet — Configuração da API Key

A Aula 1 utiliza a API do BabelNet. Para configurá-la:

1. Crie uma conta gratuita em [babelnet.org](https://babelnet.org/)
2. Copie sua API Key em [babelnet.org/profile](https://babelnet.org/profile)
3. Crie um arquivo `.env` na pasta da aula com o seguinte conteúdo:

```
BABELNET_KEY=sua-chave-aqui
```

> ⚠️ **Nunca compartilhe ou suba o arquivo `.env` para o GitHub!**  
> Ele já está listado no `.gitignore` deste repositório.

**Limite gratuito:** 1.000 requisições/dia — suficiente para todas as atividades do curso.

---

## 🚨 Erros Comuns e Soluções

| Erro | Causa | Solução |
|---|---|---|
| `ModuleNotFoundError` | Ambiente não ativado | `conda activate pln-curso` |
| `fbgemm.dll` (Windows) | PyTorch via conda | Instalar PyTorch via pip (ver LEIA-ME-WINDOWS.txt) |
| `No module named 'cv2'` | OpenCV não instalado | `pip install opencv-python-headless` |
| Kernel errado no Jupyter | Selecionou "Python 3" | Selecionar kernel "PLN Curso" |
| BabelNet: erro 403 | API Key inválida | Verificar arquivo `.env` |
| BERT muito lento | Sem GPU | Usar `distilbert-base-uncased` |

---

## 🗓️ Cronograma Sugerido

| Semana | Aula | Carga horária estimada |
|---|---|---|
| 1 | Aula 1 — Representações Conceituais | 3h teoria + 2h prática |
| 2 | Aula 2 — Tecnologias e Ferramentas | 2h teoria + 3h prática |
| 3 | Aula 3 — Arquiteturas para PLN | 4h teoria + 2h prática |
| 4 | Aula 4 — Modelos Pré-Treinados | 3h teoria + 3h prática |
| 5 | Aula 5 — Aplicações Multimodais | 3h teoria + 2h prática |
| 6 | Aula 6 — Aplicações de PLN | 2h teoria + 3h prática |
| 7 | Aula 7 — Casos de Uso | 2h teoria + 3h prática |

---

## 🛠️ Principais Bibliotecas Utilizadas

| Biblioteca | Versão | Finalidade |
|---|---|---|
| `nltk` | 3.8.1 | WordNet, tokenização, corpora |
| `spacy` | 3.7.4 | Pipeline industrial de PLN |
| `transformers` | 4.38.2 | BERT, GPT, DistilBERT (Hugging Face) |
| `torch` | 2.2.0 | Deep learning (PyTorch) |
| `tensorflow` | 2.15.0 | Deep learning (TensorFlow/Keras) |
| `datasets` | 2.18.0 | Datasets do Hugging Face |
| `sentence-transformers` | 2.6.0 | Embeddings semânticos |
| `opencv-python` | 4.9.0.80 | Visão computacional |
| `networkx` | 3.2.1 | Grafos de conhecimento |
| `gradio` | 4.19.2 | Prototipagem de interfaces |
| `sacrebleu` | 2.4.0 | Avaliação de tradução |
| `rouge-score` | 0.1.2 | Avaliação de sumarização |

---

## 📖 Referências e Recursos

| Recurso | Link |
|---|---|
| WordNet | https://wordnet.princeton.edu |
| BabelNet | https://babelnet.org |
| NLTK Book | https://www.nltk.org/book |
| spaCy Docs | https://spacy.io/usage |
| Hugging Face | https://huggingface.co |
| PyTorch | https://pytorch.org |
| TensorFlow | https://www.tensorflow.org |
| Paper: Attention Is All You Need | https://arxiv.org/abs/1706.03762 |
| Paper: BERT | https://arxiv.org/abs/1810.04805 |

---

## 🤝 Contribuições

Contribuições são bem-vindas! Para reportar erros ou sugerir melhorias:

1. Abra uma **Issue** descrevendo o problema ou sugestão
2. Para contribuir com código, faça um **Fork** e abra um **Pull Request**

---

## 📄 Licença

Este material é disponibilizado para fins **educacionais**.  
Consulte o arquivo `LICENSE` para mais detalhes.

---

*Curso de Processamento de Linguagem Natural — Jupyter Notebooks para iniciantes*
