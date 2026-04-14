# Relatório - Coelinhos da Páscoa

> [!CAUTION]
> - Lembre-se que você <ins>**não pode utilizar ferramentas de IA para
>   escrever este relatório**</ins>

## Dados do aluno

- **Cartão UFRGS**: <mark>`333315`</mark>
- **Nome**: <mark>`João Raphael Fontoura Dorneles`</mark>

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

> [!IMPORTANT]
> - Coloque aqui todas as informações necessárias para que alguém
>   (pessoa ou ferramenta de IA) possa reproduzir os seus passos para
>   solucionar o problema
> - Escreva em formato imperativo, como se fosse um *prompt* com as
>   instruções a serem seguidas na solução do problema
> - Seja objetivo e conciso: quanto *menos palavras* você utilizar,
>   melhor
> - Seja técnico e use terminologia adequada: assuma que quem irá ler
>   os seus passos possui conhecimento de Ciência da Computação e
>   Computação Gráfica
> - Caso você queira incluir informações "longas" (como algum *prompt*
>   grande usado com alguma ferramenta de IA), crie arquivos à parte e
>   adicione links no texto (por exemplo, crie o arquivo `PROMPTS.md`
>   e adicione um link markdown `[os prompts detalhados estão
>   aqui](PROMPTS.md)`)
> - Novamente, lembre-se que você *não pode utilizar ferramentas
>   de IA para escrever este relatório*

- Alterar o tamanho para ocupar 100% da janela.
- Desligar os textos de debug (variável g_ShowInfoText).
- Aumentar a distância da câmera para mostrar a cena inteira.
- Aumentar o limite de visão da câmera, resolvendo o problema de clipping quando zoom out era aplicado.
- Aumentar a escala do chão para comportar todos os objetos.
- Substituir o desenho estático por um loop for para desenharos 16 coelhos e 16 ovos.
- Calcular as posições X e Z usando seno e cosseno baseados no tempo para criar o movimento de carrossel.
- Aplicar uma matriz de rotação para fazer os objetos darem piruetas no ar.
- Multiplicar as matrizes (de translação e de rotação, nessa ordem) para que o objeto gire em torno do próprio eixo.
- Alternar a renderização entre coelho e esfera.

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

- O Makefile estava adaptado para o Mac M1, precisei adaptar para o Mac M3.

## Você acha que conseguiu resolver o problema de forma adequada?

Sim, mas a intercalação de subir e descer poderia ter ficado melhor.

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

N/A

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

N/A
