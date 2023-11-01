# EMBED A CHATBOT THAT TALKS FIRST
Para incorporar um chatbot no Botpress que inicie a conversa com uma saudação ou mensagem de boas-vindas, você precisará criar um fluxo de conversa específico que inclua a mensagem de saudação. Aqui está um exemplo de como você pode fazer isso:

1. **Crie um Fluxo de Conversa:** No painel de controle do Botpress, crie um novo fluxo de conversa ou use um fluxo de conversa existente onde deseja que o chatbot inicie a conversa com uma saudação.

2. **Adicione um Nó de Texto:** Dentro do fluxo de conversa, adicione um nó de texto que conterá a mensagem de saudação. Para fazer isso, clique no botão "Adicionar Nó" e escolha a opção "Texto" ou "Mensagem" (dependendo da terminologia usada na versão atual do Botpress).

3. **Digite a Saudação:** No nó de texto, insira a mensagem de saudação que você deseja que o chatbot exiba quando a conversa começar. Por exemplo, "Olá! Como posso ajudá-lo hoje?"

4. **Conecte o Nó Inicial:** Certifique-se de que o nó de texto com a saudação esteja conectado ao nó inicial do fluxo de conversa. O nó inicial é o ponto de partida da conversa.

5. **Configuração de Gatilho:** Se desejar que a saudação seja exibida automaticamente quando os usuários iniciarem a conversa, você pode configurar um gatilho ou condição para ativar o fluxo de conversa. Por exemplo, você pode configurar um gatilho para acionar a saudação sempre que um novo usuário iniciar a conversa.

6. **Teste a Saudação:** Execute um teste para garantir que a saudação seja exibida corretamente quando a conversa é iniciada.

7. **Personalize a Resposta:** Além da saudação inicial, você pode adicionar lógica para personalizar a resposta do chatbot com base nas ações do usuário ou nas informações coletadas durante a conversa.

8. **Adicione Fluxos de Conversa Adicionais:** Após a saudação inicial, você pode criar outros fluxos de conversa para lidar com as interações subsequentes dos usuários.

Lembrando que o processo exato pode variar dependendo da versão específica do Botpress que você está usando. Certifique-se de consultar a documentação e as diretrizes da versão atual do Botpress para obter informações detalhadas sobre como criar saudações e fluxos de conversa. A saudação inicial é uma parte crucial da experiência do usuário, pois é a primeira impressão que o chatbot oferece aos visitantes do seu site ou aplicativo. Portanto, é importante personalizá-la de acordo com o contexto e as necessidades da sua marca ou projeto.