# CAPTURE MULTIPLE VARIABLES
Para capturar múltiplas variáveis em um bot Botpress, você pode usar a lógica de programação da plataforma para coletar informações de usuário de uma só vez ou passo a passo. Aqui estão os passos gerais para capturar várias variáveis de usuário:

1. **Crie um Fluxo de Conversa Personalizado:** No painel de controle do Botpress, crie um fluxo de conversa personalizado para lidar com a captura de informações. Por exemplo, você pode criar um fluxo de conversa chamado "Coletar Informações".

2. **Configure Intenções:** Defina intenções que correspondam a perguntas específicas que o bot fará ao usuário. Por exemplo, crie intenções como "Perguntar Nome," "Perguntar Sobrenome," "Perguntar Email," etc.

3. **Crie Ações de Script:** Crie ações de script em cada intenção para coletar as variáveis. Por exemplo, na intenção "Perguntar Nome," crie uma ação que solicite ao usuário que insira seu nome e armazene a resposta em uma variável.

4. **Encadeie as Intenções:** Encadeie as intenções no fluxo de conversa para seguir uma sequência lógica. Por exemplo, após a pergunta do nome, encadeie a intenção para perguntar o sobrenome e assim por diante.

5. **Armazene Variáveis:** Configure o bot para armazenar as respostas do usuário em variáveis de usuário. Por exemplo, armazene o nome em uma variável chamada "nome," o sobrenome em uma variável chamada "sobrenome," e assim por diante.

6. **Valide e Trate os Dados:** Adicione lógica para validar e tratar os dados inseridos pelo usuário, como garantir que os campos obrigatórios estejam preenchidos e que os dados sejam válidos.

7. **Responda e Avance:** Após coletar todas as informações necessárias, você pode fornecer uma confirmação ao usuário e avançar na conversa para o próximo passo.

8. **Personalize as Respostas:** Use as variáveis armazenadas para personalizar as respostas do bot, incluindo o nome, sobrenome e outras informações coletadas.

Lembre-se de que a implementação exata pode variar dependendo das necessidades do seu bot e da complexidade das variáveis a serem coletadas. O Botpress oferece flexibilidade para criar fluxos de conversa e capturar informações de maneira personalizada. Certifique-se de explorar a documentação do Botpress e a lógica de programação disponível na plataforma para criar fluxos de conversa eficazes.