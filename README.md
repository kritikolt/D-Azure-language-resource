# Configurando um Recurso de Linguagem no Azure

Este guia fornece um passo a passo para criar um recurso de Linguagem no Azure e configurá-lo para uso com o Azure AI Language Studio.

## Passo 1: Criar um Recurso de Linguagem

Se você ainda não o fez, siga estas etapas para criar um recurso de Linguagem em sua assinatura do Azure:

1. Abra o [portal Azure](https://portal.azure.com) em outra aba do navegador e faça login com sua conta de assinatura do Azure.

2. Clique no botão **＋Create a resource** e procure por **Language service**.

3. Selecione **create**. Você será levado a uma página para selecionar recursos adicionais. Mantenha a seleção padrão e clique em **Continue to create your resource** para criar seu recurso.

4. Na página de criação de Linguagem, configure com as seguintes configurações:
   - **Subscription**: Sua assinatura do Azure.
   - **Resource group**: Selecione ou crie um grupo de recursos com um nome único.
   - **Region**: East US.
   - **Name**: Insira um nome único.
   - **Pricing tier**: Free F0 ou S se o Free F0 não estiver disponível.
   - Marque a caixa reconhecendo os termos.

5. Clique em **Review + create**, depois em **Create** e aguarde a implantação ser concluída.

## Passo 2: Configurar seu Recurso no Azure AI Language Studio

1. Em outra aba do navegador, abra o **Language Studio** em [language.cognitive.azure.com](https://language.cognitive.azure.com) e faça login.

2. Quando solicitado a selecionar um recurso do Azure, faça as seguintes configurações:
   - **Azure directory**: Diretório Padrão, o diretório que você está usando.
   - **Azure subscription**: Selecione a assinatura que você está usando.
   - **Resource type**: Linguagem.
   - **Resource name**: Selecione o recurso de serviço de linguagem que você acabou de criar.

3. Em seguida, selecione **Done**.

## Passo 3: Analisar avaliações no Azure AI Language Studio

1. Em um navegador da web, acesse o **Language Studio** em [language.cognitive.azure.com](https://language.cognitive.azure.com).

2. Na página inicial do Language Studio, selecione a aba **Classify text** e depois selecione **Analyze sentiment and mine opinions**.

3. **Select text language**, selecione o idioma desejado.

4. **Select your Azure resource**, selecione o recurso que você configurou anteriormente.

5. **Enter your own text, upload a file, or use one of our sample texts**, você pode fornecer o texto que deseja analisar.

6. Marque a caixa para reconhecer que a demonstração poderá incorrer em uso e custos, e então selecione **Run**.

7. Revise a saída. Observe que o documento é analisado quanto ao sentimento, assim como cada frase. Selecione uma frase específica para mostrar a análise de sentimento para aquela frase.

Este é um guia passo a passo para configurar um recurso de Linguagem no Azure e utilizar o Azure AI Language Studio para análise de texto.

## Testes gerados

1. "Despite facing numerous challenges, she remained optimistic and determined to pursue her dreams, finding strength in her resilience and unwavering perseverance."

2. "The breathtaking beauty of the sunset over the majestic mountains left him feeling a sense of awe and tranquility, reminding him of the precious moments in life worth cherishing."

3. "After facing repeated setbacks and disappointments, the realization that his dreams may never come to fruition filled him with a deep sense of disillusionment and despair, leaving him questioning the purpose of his efforts."