# T20 Token Variables Journal

### Descrição

Esta macro automatiza a criação de um journal detalhado contendo todas as variáveis associadas a um token selecionado no Foundry VTT para o sistema Tormenta 20. O journal resultante inclui duas páginas:

1. Variáveis de Personagem: Lista todas as variáveis do personagem.
2. Variáveis de Rolagem: Lista todas as variáveis disponíveis para uso em rolagens.

### Como Usar

1. No Foundry VTT, selecione um token na cena.
2. Execute a macro.
3. Um novo journal será criado com o nome "T20_Variaveis_[Nome do Token]".
4. O journal será automaticamente aberto para visualização.

### Funcionamento

A macro realiza as seguintes operações:

1. Verifica se um token está selecionado.
2. Obtém o ator associado ao token.
3. Extrai e achata todas as variáveis do ator e de rolagem.
4. Cria um novo journal entry com duas páginas, cada uma contendo uma tabela com as variáveis respectivas.
5. Nomeia o journal de acordo com o nome do token selecionado.

## English

### Description

This macro automates the creation of a detailed journal containing all variables associated with a selected token in Foundry VTT for the Tormenta 20 system. The resulting journal includes two pages:

1. Character Variables: Lists all character variables.
2. Roll Variables: Lists all variables available for use in rolls.

### How to Use

1. In Foundry VTT, select a token on the scene.
2. Run the macro.
3. A new journal will be created named "T20_Variaveis_[Token Name]".
4. The journal will automatically open for viewing.

### Functionality

The macro performs the following operations:

1. Checks if a token is selected.
2. Retrieves the actor associated with the token.
3. Extracts and flattens all actor and roll variables.
4. Creates a new journal entry with two pages, each containing a table with the respective variables.
5. Names the journal according to the selected token's name.
