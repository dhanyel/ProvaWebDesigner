# Prova Frontend Pentagrama
## Instruções para realização da prova

### Considerações gerais:

**Prova:**
- **Deve ser realizada em até 24 horas**
- **A entrega será realizado por meio de um arquivo zipado que será enviado por e-mail para rh@pentagrama.com.br.**

Html:
- O HTML poderá ser alterado a fim de organizar o layout, porém todas as informações propostas devem ser exibidas nas devidas seções.
- Manter o codigo limpo

Css
- Poderá utilizar qualquer pré-processador comum do mercado. (De preferencia less ou sass)
- De preferência para organizar o código css em uma pasta separada do projeto
- Tentar manter a responsividade desktop-mobile

Sections:
- Cada seção deve ter no mínimo o tamanho total da página

___
### Seções
Menu:
- Menu deve ser fixo no topo contendo a logo e os links na horizontal
- Deve ter um tamanho maior quando a página estiver no topo, e reduzir ao descer a página
- Os links do menu devem indicar as respectivas seções

Home:
- Utilizar imagem de fundo disponibilizada

Sobre:
- As informações contidas na div hover-info devem ser exibidas ao passar o mouse no devido menu.

Ex:

![Exemplo 1 Sobre](exemplos/imagens_exemplo/hover-info1.png)
![Exemplo 2 Sobre](exemplos/imagens_exemplo/hover-info2.png)

Fábrica:
- Nesta seção os itens accordion-collapse deve sem exibidos ao clicar nos botoes de cada accordion-item
- [ [Exemplo: arquivo exemplo_accordion.mp4](exemplos/videos_exemplo/exemplo_select.mp4) ]

Tecnologias:
- As informações dessa seção devem ser exibidas em forma de uma grade de cartões

Contato:
- Regras do formulário:
     - **Select motivo de contato**
	    - Não deve exibir os options ao clicar, e sim o span contact-reson-select_options, que deve ser estilizado e vinculado ao clique do select.
	    - Cada item do span deve ser destacado ao passar o mouse sobre ele.
	    - Ao clicar em um item do span o select motivo de contato deve ser setado com a devida opção selecionada
        - [ [Exemplo: arquivo exemplo_select.mp4](exemplos/videos_exemplo/exemplo_select.mp4) ]

    - **Select como deseja ser contatado**
	    - Dependendo do que for selecionado liberar a exibição do input relacionado: e-mail, phone ou whatsapp
	    
- Ao enviar o formulário apenas exibir as informações no console ou em um alerta.
- Colocar validação do formulário, sendo obrigatórios os campos nome e (ou telefone, ou e-mail ou whatsApp). Destacar em vermelho caso o campo obrigatório não tenha sido preenchido.  

Footer:
- Exibir as informações de forma limpa e organizada

___
### Extra

Float Button:
- Botão flutuante fixo no canto inferior direito da tela com a funcionalidade de voltar ao topo
