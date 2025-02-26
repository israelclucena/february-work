# february-work
Some codes worked in February

Scenario: Centro de Ajuda
Given that I am at Menu
When I click in on the “Centro de ajuda” shortcut
Then I should be directed to the Help Center section where support and assistance options are available.
Scenario: Centro de Ajuda- Create new Section – “Em que podemos ajudar?”
Given that I am at Menu
When I enter the "Centro de ajuda" screen
Then I should see the section – “Em que podemos ajudar?”
Scenario: Centro de Ajuda - Create Shortcuts
Given that I am at Menu
When I enter the "Centro de ajuda" screen
Then I should see the shortcuts at the section – ”Em que podemos ajudar?”
“Os meus pedidos”
“O meu gestor\meu balcão”
Scenario: Centro de Ajuda - Create Shortcuts
Given that I am at Menu
When I enter the "Centro de ajuda" screen
Then I should see the options in the first level
Scenario: FAQ - Display Content EN e PT
Given I am on the "Centro de ajuda" screen
And is set to a specific language
When I navigate to the FAQ screen
Then I should see the question and its content displayed in language specific
Scenario: Selecting an option from the first level and navigating to the second level
Given the user is exploring the options in the first level
When the user selects an option from the first level
Then the user should be directed to the second level with additional related options.
Scenario: Choosing an option from the second level and progressing to the third level
Given the user is exploring the options in the second level
When the user chooses an option from the second level
Then the user should advance to the third level displaying further relevant options.
Scenario: FAQ - Apenas Conteúdo
Given I am on the second-level options screen
When I navigate to the FAQ screen
Then I should see the question and its content.
Content:
Question
Answer
May contain: video, images or both
Scenario: FAQ - Conteúdo com Imagem
Given I am on the second-level options screen
When I navigate to the FAQ screen
Then I should see the question, its content, and an image.
Scenario: FAQ - Conteúdo com Imagem e video.
Given I am on the second-level options screen
When I navigate to the FAQ screen
Then I should see the question, its content, image and an video.
Scenario: FAQ - Conteúdo com video.
Given I am on the second-level options screen
When I navigate to the FAQ screen
Then I should see the question, its content and an video.
Scenario: FAQ - Funcionalidade + Resolve
Given I am on the second-level options screen
When I navigate to the FAQ screen
Then I should see a question with its content
And I should see the buttons for “Funcionalidade” (deeplink) and “Resolve”.
Scenario: FAQ - Funcionalidade ou Resolve
Given I am on the second-level options screen
When I navigate to the FAQ screen
Then I should see a question with its content
And I should see either a button for “Funcionalidade” (deeplink) or “Resolve”.
Scenario: FAQ - Superlinha (Mobile)
Given I am on the second-level options screen
When I navigate to the FAQ screen
Then I should see a question with its content
And I should see a “Superlinha” button.
Scenario: FAQ - Artigos Relacionados
Given I am on the second-level options screen
When I navigate to the FAQ screen
Then I should see a question with its content
And I should see the section – “Artigos relacionados”
