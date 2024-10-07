# Ideia do Projeto
Automatizar o processo de notas do Guarda Volumes do Meu sogro. 

### Explicação detalhada do problema 
Meu sogro possui um guarda volumes onde vendedores ambulantes guardam suas mercadorias diariamente. Toda semana é gerada uma lista com os armários ocupados e cada armário ocupado gera um valor a ser cobrado. Todo o processo é extremamente manual, um funcionário registra os armários ocupados e em seguida fornece a lista para meu sogro. Minha esposa auxilia gerando notas para cada armário de acordo com o valor de cada um. 

### Inputs 
- Armários ocupados 
- Valor de cada armário 

### Outputs 
- Notas preenchidas com o valor a ser cobrado 

### Especificacoes Importantes 
- O preenchimento dos arquivos deve se manter por enquanto de forma manual. Futuramente podemos desenvolver um sistema mais robusto para inclusive receber os armários de forma automática.  
- Sendo assim, pensei em utilizar visao computacional com IA para extrair o texto de fotos com as informacoes de cada armário. Em seguida carregar esses dados em uma classe de armários e gerar um arquivo que possa ser impresso por uma impressora de notas. 
-  