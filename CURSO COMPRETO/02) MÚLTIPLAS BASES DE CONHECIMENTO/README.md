# MÚLTIPLAS BASES DE CONHECIMENTO
O Botpress permite que você crie e gerencie múltiplas bases de conhecimento, o que é útil quando você deseja segmentar diferentes públicos ou casos de uso com diferentes conjuntos de dados de conhecimento. Cada base de conhecimento é essencialmente um ambiente isolado onde você pode definir fluxos, intenções e configurações específicas. Aqui estão os passos gerais para criar e gerenciar múltiplas bases de conhecimento no Botpress:

1. **Acesse o Painel de Administração do Botpress:**
   - Inicie o Botpress e acesse o painel de administração usando um navegador da web. Isso é feito acessando a URL em que o Botpress está hospedado, geralmente na porta 3000 (por exemplo, http://localhost:3000).

2. **Crie uma Nova Base de Conhecimento:**
   - No painel de administração, vá para a seção "Conhecimento" ou "Bases de Conhecimento" (a nomenclatura pode variar dependendo da versão do Botpress).
   - Clique em "Criar Nova Base de Conhecimento" ou um botão semelhante.
   - Defina um nome e uma descrição para a nova base de conhecimento.
   - Configure outras opções, como o idioma padrão da base de conhecimento, se necessário.

3. **Gerencie Fluxos, Intenções e Configurações:**
   - Após criar uma base de conhecimento, você pode definir fluxos específicos, intenções e configurações dentro dela. Isso permite que você personalize o comportamento do chatbot para essa base de conhecimento.

4. **Configure a Rota do Bot para a Base de Conhecimento:**
   - Para que os usuários acessem a base de conhecimento específica, você precisa configurar a rota correta para ela. Isso pode ser feito por meio de roteamento, geralmente no arquivo de configuração do Botpress.
   - Quando os usuários acessam o bot (por exemplo, através de um site ou aplicativo), o sistema de roteamento direciona as solicitações para a base de conhecimento apropriada com base em critérios como o domínio, o idioma ou outros parâmetros.

5. **Teste e Implante a Base de Conhecimento:**
   - Antes de colocar sua base de conhecimento em produção, é importante testá-la para garantir que tudo funcione conforme o esperado.
   - Após os testes, você pode implantar a base de conhecimento para que os usuários reais possam interagir com o chatbot.

Esses são os passos gerais para criar e gerenciar múltiplas bases de conhecimento no Botpress. Cada base de conhecimento pode ser personalizada de acordo com as necessidades específicas, permitindo que você atenda a diferentes públicos ou casos de uso com facilidade. Certifique-se de consultar a documentação específica do Botpress para obter instruções detalhadas, pois a interface e os procedimentos exatos podem variar com base na versão do software.