# Azure OpenAI - DIO
Resumo do conteúdo aprendido durante o curso de Azure OpenAI na DIO

## O que é o Playground do Azure OpenAI?
- Ambiente interativo para testar e ajustar modelos da OpenAI no Azure.
- Permite desenvolver e otimizar prompts antes da integração em aplicações.
- Suporta modelos de IA para geração de texto, imagens e outros formatos.

## Recursos do Playground
- Ajuste de parâmetros como temperatura, Top-P, penalidades, etc.
- Possibilidade de testar interações multimodais com diferentes entradas.
- Interface para experimentação e aprendizado sobre IA generativa.

## Tokenização
- Processo que divide o texto em pequenas unidades chamadas tokens.
- Tokens podem ser palavras, partes de palavras ou caracteres, dependendo do idioma.
- O custo da execução do modelo é baseado na quantidade de tokens usados.

## System Message
- Define o comportamento do modelo antes da interação com o usuário.
- Ajuda a guiar as respostas para um tom ou contexto específico.
- Influencia a forma como a IA interpreta e responde às entradas do usuário.

## Temperatura vs Top-P
- **Temperatura**: Controla a aleatoriedade das respostas (valores mais altos = mais criatividade).
- **Top-P**: Define um limite de probabilidade para seleção de palavras (valores baixos = respostas mais previsíveis).
- Geralmente, apenas um desses parâmetros é ajustado para manter controle sobre a resposta.

## Frequency Penalty vs Presence Penalty
- **Frequency Penalty**: Reduz a repetição de palavras ou frases na saída.
- **Presence Penalty**: Incentiva a IA a introduzir novas palavras não mencionadas antes.
- Ambos são usados para evitar repetições excessivas ou respostas pouco variadas.

## Multimodalidade
- Capacidade dos modelos de processar diferentes tipos de dados, como texto, imagem e áudio.
- Permite interações mais ricas e complexas em aplicações de IA.
- Modelos como GPT-4-turbo podem gerar texto e compreender imagens simultaneamente.

## Como escrever um bom prompt
- **Seja claro**: Especifique o que deseja obter com detalhes.
- **Dê contexto**: Inclua informações relevantes para direcionar a resposta.
- **Use exemplos**: Demonstre o formato ou estilo desejado na resposta esperada.
