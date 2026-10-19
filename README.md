# Analisador e Filtro de Sinais

Projeto desenvolvido para a disciplina de **Métodos Matemáticos**.

## Objetivo

Analisar, filtrar e reconstruir um sinal sintético com ruído, utilizando conceitos de Séries de Fourier, Transformada de Fourier e Transformada de Laplace.

## Etapas do projeto

1. **Série de Fourier:** aproximação de uma onda quadrada utilizando diferentes quantidades de harmônicos.
2. **Transformada de Fourier (FFT):** identificação das frequências de 10 Hz e 30 Hz presentes no sinal.
3. **Filtragem:** remoção do ruído e reconstrução do sinal utilizando a Transformada Inversa de Fourier.
4. **Transformada de Laplace:** modelagem de um filtro RC, análise de polos e zeros e verificação da estabilidade.

## Tecnologias utilizadas

- Python
- Google Colab
- NumPy
- Matplotlib
- SciPy
- SymPy

## Como executar

1. Abra o arquivo `Analisador_de_Sinais.ipynb` no Google Colab.
2. Selecione **Ambiente de execução → Executar tudo**.
3. Observe os gráficos e as análises apresentadas.

## Resultados

O filtro seletivo baseado na FFT conseguiu preservar as frequências desejadas e remover as demais componentes do sinal sintético. Também foi analisado um filtro RC de primeira ordem, demonstrando sua estabilidade e resposta em frequência.
