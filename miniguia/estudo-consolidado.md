# Guia de Estudo Consolidado: IA Generativa

## Resumos Estruturados

### O que é IA Generativa?
IA Generativa é um subcampo da inteligência artificial que cria novos conteúdos (texto, imagem, áudio, código) a partir de padrões aprendidos em grandes volumes de dados de treinamento. Diferente da IA discriminativa (que classifica ou identifica), ela **produz** conteúdo original.

### Arquitetura Transformer
- **Mecanismo de atenção:** permite que o modelo pondere a importância de diferentes palavras ao processar texto, focando no que é mais relevante para o contexto
- **Tokens:** unidades de processamento (palavras ou partes delas)
- **Context window:** quantidade de tokens que o modelo consegue processar e "lembrar" de uma só vez

### Principais Modelos
| Modelo | Empresa | Principais Características |
|--------|---------|---------------------------|
| GPT-4 | OpenAI | Multimodal, raciocínio avançado, 82% menos propenso a conteúdo não permitido |
| Claude 3 Opus | Anthropic | 200k tokens de contexto, mais inteligente para tarefas complexas |
| Claude 3 Sonnet | Anthropic | Equilíbrio entre inteligência e velocidade, 2x mais rápido |
| Claude 3 Haiku | Anthropic | Mais rápido do mercado, econômico para respostas instantâneas |

---

## Glossário de Conceitos

| Termo | Definição |
|-------|-----------|
| **LLM** | Large Language Model - modelo treinado em bilhões de parâmetros de texto |
| **Fine-tuning** | Ajuste fino de um modelo pré-treinado para uma tarefa específica |
| **Alucinação** | Quando o modelo gera informações incorretas com alta confiança |
| **Prompt Engineering** | Técnica de elaborar instruções eficazes para IA |
| **Multimodal** | Capacidade de processar diferentes tipos de dados (texto, imagem, áudio) |
| **Context Window** | Quantidade de tokens que o modelo pode processar de uma vez |
| **Transformer** | Arquitetura de rede neural que usa mecanismo de atenção |
| **RAG** | Retrieval-Augmented Generation - técnica que combina busca com geração |

---

## Prompts Reutilizáveis

1. **Explicação com analogia**  
   *"Explique [conceito] usando uma analogia com [domínio familiar]"*

2. **Comparação estruturada**  
   *"Compare [tópico A] e [tópico B] em uma tabela considerando: [critério 1], [critério 2]"*

3. **Guia prático**  
   *"Baseado nos materiais fornecidos, crie um guia passo a passo para [aplicação]"*

4. **Análise crítica**  
   *"Liste 5 limitações ou cuidados ao implementar [tecnologia]"*

---

*Este guia foi desenvolvido a partir das fontes da OpenAI, Anthropic, AWS e IBM, utilizando o NotebookLM para síntese do conhecimento.*
