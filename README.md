📈 Gráfico de Pareto no Excel
🎯 Objetivo
O Gráfico de Pareto é muito utilizado para melhoria de processos de negócios, ajudando a identificar as causas mais significativas de um problema. Ele é baseado no Princípio de Pareto, que sugere que 80% dos problemas estão relacionados a 20% das causas.

📝 Passo a Passo para Construção
1. 📊 Estrutura da Planilha
Crie uma planilha com quatro colunas e insira 9 itens (exemplo: nomes de produtos):

| Produto | Valor | Acumulado | % Acumulado |
| ------- | ----- | --------- | ----------- |
| Sprite  | 30    |           |             |
| Pepsi   | 50    |           |             |
| ...     | ...   | ...       | ...         |

...	...	...	...

Você pode usar os nomes e valores que preferir.

2. 📈 Preenchimento da Coluna "Acumulado"
Ordene os valores da coluna B (Valor) do maior para o menor.

Na coluna C (Acumulado), insira a fórmula para somar o valor atual com o acumulado anterior:

Exemplo:

C2: mesmo valor de B2

C3: =B3+C2 → soma o valor atual com o acumulado anterior

Continue esse padrão nas linhas seguintes.

3. 📉 Preenchimento da Coluna "% Acumulado"
Na coluna D (% Acumulado), divida o valor acumulado pela soma total do acumulado (linha final da coluna C).

Exemplo:

D2: =C2/C10

D3: =C3/$C$10 → use F4 para travar a célula da soma total (C10), garantindo que a fórmula funcione corretamente ao arrastar.

🔍 Análise
Com os percentuais acumulados em mãos, você poderá identificar os itens que representam aproximadamente 80% do total. No exemplo, os quatro primeiros produtos representam esse percentual e, portanto, merecem maior foco e atenção.

📊 Criação do Gráfico de Pareto no Excel
Selecione apenas as colunas A (Produto) e B (Valor).

Vá em Inserir > Gráficos Recomendados.

Clique na aba Todos os Gráficos.

Escolha a opção Histograma.

Selecione o segundo modelo, chamado Pareto.

Pronto! O seu gráfico de Pareto será gerado automaticamente.

✅ Conclusão
O Gráfico de Pareto ajuda a priorizar esforços nas causas que mais impactam os resultados. Com isso, é possível tomar decisões mais estratégicas e eficazes para o seu negócio.

