# VARIÁVEIS DE REFERÊNCIA EM FLUXOS DE TRABALHO
Variáveis de referência em fluxos de trabalho são usadas para armazenar informações temporárias que podem ser usadas em várias partes do fluxo. Elas são úteis para lembrar dados específicos do usuário, como respostas a perguntas anteriores ou valores obtidos de fontes externas. As variáveis de referência permitem que você mantenha informações e faça uso delas ao longo da conversa do chatbot. Aqui está como você pode usar variáveis de referência em fluxos de trabalho no Botpress:

1. **Definir uma Variável:**
   - Para definir uma variável de referência em um fluxo, você pode usar a ação "Definir Variável" ou uma ação semelhante disponível na interface do Botpress.
   - Por exemplo, para armazenar o nome do usuário, você pode usar a ação "Definir Variável" para criar uma variável chamada "nome" e atribuir a ela o valor obtido da entrada do usuário.

2. **Atribuir Valores às Variáveis:**
   - Você pode atribuir valores às variáveis de referência com base nas interações com o usuário. Por exemplo, quando o usuário responde a uma pergunta, você pode definir uma variável para armazenar a resposta.

3. **Recuperar Valores das Variáveis:**
   - Para recuperar valores armazenados em variáveis de referência, você pode usar essas variáveis em mensagens de texto ou em lógica condicional.
   - Por exemplo, você pode criar uma mensagem que inclua o nome do usuário, usando a variável "nome" em uma resposta.

4. **Atualizar Variáveis:**
   - Você pode atualizar o valor de uma variável de referência ao longo da conversa. Isso é útil quando você precisa rastrear informações em mudança, como um carrinho de compras ou dados de reserva.

5. **Exemplo de Uso de Variável de Referência:**
   - Suponha que você queira lembrar o nome do usuário e usar esse nome ao longo da conversa. Você pode fazer o seguinte:
     - Define uma variável de referência chamada "nome" e atribui o valor obtido da entrada do usuário.
     - Em mensagens posteriores, você pode se referir à variável "nome" para personalizar as respostas. Por exemplo, "Olá, {{nome}}! Como posso ajudar hoje?"

As variáveis de referência em fluxos de trabalho permitem que o chatbot forneça uma experiência mais personalizada e relevante para os usuários, armazenando e usando informações contextuais. Certifique-se de usar as variáveis apropriadamente e mantê-las atualizadas ao longo da conversa para atender às necessidades específicas do seu chatbot.