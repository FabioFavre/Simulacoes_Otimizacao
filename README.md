# Simulações — Controle Não-Linear

Notebooks desenvolvidos em **Python**, usando o **Google Colab**, para as atividades práticas da disciplina de **Controle Não-Linear** do CEFET/RJ.

A proposta deste repositório é reunir os códigos das simulações, os gráficos e os resultados de cada exercício em um só lugar. Os notebooks estão separados por atividade, com os enunciados e explicações junto dos códigos.

## Simulações

| Notebook | Conteúdo |
| --- | --- |
| [Simulação 1](Simulacao_1_Colab_Aluno.ipynb) | Minimização de três funções de uma variável com `scipy.optimize.minimize_scalar` e visualização dos gráficos. |
| [Simulação 2](Simulacao_2_Colab_Aluno.ipynb) | Método de Newton para maximização e método do gradiente com tabelas de iterações, curvas de nível e gráfico 3D. |
| [Simulação 3](Simulacao_3_LQR_Colab_Aluno.ipynb) | Projeto de um controlador LQR, cálculo do ganho de realimentação e análise da resposta ao degrau dos estados do sistema. |

## Como executar

1. Abra o notebook desejado no GitHub.
2. Escolha **Open in Colab**, se essa opção aparecer, ou acesse [Google Colab](https://colab.research.google.com/).
3. No Colab, use **Arquivo → Fazer upload de notebook** para abrir o arquivo `.ipynb`, se necessário.
4. Execute as células em ordem, do início ao fim.

Não é necessário instalar Python no computador para usar o Colab. As simulações utilizam principalmente **NumPy**, **SciPy** e **Matplotlib**, bibliotecas normalmente disponíveis no ambiente.

## Observações sobre as atividades

- **Simulação 1:** no exercício da função $4x\sin(x)$, o intervalo é aberto. Assim, o ínfimo é zero, mas não há mínimo atingido no intervalo.
- **Simulação 2:** o segundo enunciado menciona maximização, porém a função apresentada é convexa e não tem máximo sem restrições. O procedimento aplicado encontra o mínimo.
- **Simulação 3:** reproduzimos o exemplo LQR da folha, inclusive a resposta ao degrau com os três estados. Também incluímos algumas verificações complementares.

## Organização

```text
.
├── README.md
├── Simulacao_1_Colab_Aluno.ipynb
├── Simulacao_2_Colab_Aluno.ipynb
└── Simulacao_3_LQR_Colab_Aluno.ipynb
```

Os notebooks foram organizados para facilitar a execução, a conferência dos resultados e a consulta durante a disciplina.
