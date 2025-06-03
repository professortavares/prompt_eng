# Prompt Engineering Experiments

Repositório para armazenar experimentos a cerca de 
engenharia de prompts, avaliação de desempenho e 
comparação de modelos de linguagem (LLMs).

## Referências:

* A Systematic Survey of Prompt Engineering in Large Language Models: Techniques and Applications - https://arxiv.org/abs/2402.07927
* The Prompt Report: A Systematic Survey of Prompt Engineering Techniques - https://arxiv.org/abs/2406.06608
* Language Models are Few-Shot Learners - https://arxiv.org/abs/2005.14165 
* Prompt Programming for Large Language Models: How to Design Tasks and Select Data - https://arxiv.org/abs/2102.07350
* Chain-of-Thought Prompting Elicits Reasoning in Large Language Models - https://arxiv.org/abs/2201.11903
* Automatic Chain of Thought Prompting in Large Language Models - https://arxiv.org/abs/2210.03493
* Self-Consistency Improves Chain of Thought Reasoning in Language Models - https://arxiv.org/abs/2203.11171
* Tree of Thoughts: Deliberate Problem Solving with Large Language Models - https://arxiv.org/abs/2305.10601

## Instalação

```
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
pip install -r requirements.txt
```

Criar um arquivo .env com as variáveis de ambiente necessárias para o funcionamento do projeto (na raiz do projeto).
```
OPENAI_API_KEY=sk-...
```

