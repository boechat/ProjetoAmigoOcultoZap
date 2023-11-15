# ProjetoAmigoOcultoZap
Projeto de Automação Web com Selenium para Criar um Amigo Oculto
<br>

**Descrição do Projeto:**

Do Tratamento de Dados:

* Usuário vai prover um documento excel denominado 'Amigo_Oculto_bangu.xlsx' que deverá ser lido.
* Será criada uma nova coluna na tabela, lendo a lista de nomes e associando aleatoriamente um dos nomes.
* * Há condições que devem ser atendidas:
  * Um mesmo nome não pode se 'tirar'
  * Há uma lista 'especial' de pessoas que não podem se tirar entre si, que será providenciada pelo usuário
  * Deverá ser verificado se os telefones são válidos

Da Validação:
 * Deverá ser enviado para um email do bot a lista final, para conferência futura.
 * * O email deve constar a data com hora do envio.
 * Para cada mensagem enviada no Processo de Automação, deverá ser registrado o envio com sucesso, possivelmente capturando a tela para validação.
   
Da Automação:
  * Após feito o tratamento, o programa deverá acessar o Whatsapp Web ( https://web.whatsapp.com/ ) e enviar o nome das pessoas tiradas para cada pessoa da lista.
