# Emissão de Nota Fiscal
 Demonstração de conhecimentos sobre Automação Web e DataFrames para automatizar emissão de notas fiscais de uma empresa.

### Descrição dos arquivos:
- Emissão Nota Fiscal.ipynb - arquivo Jupyter onde se encontra a resolução do projeto
- NotasEmitir.xlsx - tabela em formato Excel, com informações de cada cliente a serem preenchidas na nota fiscal
- index.html - página HTML de index para a emissão de nota fiscal, exigindo o login do usuário encarregado de emitir notas fiscais
- login.html - página HTML de login, com um formulário a ser preenchido com informações do cliente. Ao completar o formulário, a página gera um arquivo XML para download da nota fiscal

### Passo a passo:
- Criar navegador: usar o Selenium para criar um navegador do Google Chrome para interagir com arquivos HTML
- Fazer login: abrir página de login e realizar um login de um usuário hipotético
- Importar DataFrame com informações a serem emitidas na nota fiscal: abrir NotasEmitir.xlsx com o Pandas
- Preencher site de nota fiscal com informações do DataFrame: usar informações do arquivo NotasEmitir.xlsx para emitir notas fiscais de cada cliente
- Fechar navegador: fechar navegador do Chrome por não estar sendo mais utilizado, concluindo o projeto
