## Prática de Automação de Teste

Este exemplo demonstra como automatizar um cenário simples usando o Selenium Webdriver em Python.

### Pré-requisitos

1. O arquivo `sample-exercise.html` está localizado na pasta `docs` deste repositório e é servido como uma página online via GitHub Pages. Para facilitar o acesso, você pode encontrá-lo em [https://catherinefalvo.github.io/puc-2024-2-automacao-testes-selenium-python/sample-exercise.html](https://catherinefalvo.github.io/puc-2024-2-automacao-testes-selenium-python/sample-exercise.html). Essa configuração simplifica a execução do código em ambientes como o Google Colab.

### Cenário de Automação

1. Abra a página no navegador de sua preferência.
2. Localize e clique no botão `Generate`.
   - Um código será gerado abaixo do botão.
3. Capture o código gerado e insira-o no campo de texto.
4. Clique no botão `Test`.
5. Um alerta com a mensagem `Done!` será exibido.
6. Feche o alerta.
7. Verifique se a mensagem exibida no formato `It works! <código>!` está correta.
   - Capture essa mensagem para validação.

### Exemplo de Automação

Para ver o código de automação completo, consulte o arquivo [AutomacaoTestesSeleniumPython.ipynb](https://github.com/catherinefalvo/puc-2024-2-automacao-testes-selenium-python/blob/main/AutomacaoTestesSeleniumPython.ipynb).
