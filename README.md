# Projeto de Previsão do Tempo - Aplicação Web

Este projeto consiste em uma aplicação web que exibe a previsão do tempo para qualquer cidade do mundo, utilizando a API da OpenWeatherMap. 
A interface foi desenvolvida com HTML, CSS e JavaScript, e permite que o usuário insira o nome de uma cidade para consultar as condições climáticas em tempo real.

### Funcionalidades:
- Busca personalizada: O usuário pode pesquisar a previsão do tempo ao digitar o nome da cidade desejada.
- Exibição de dados meteorológicos:
   - Nome da cidade.
   - Temperatura atual (em graus Celsius).
   - Descrição das condições climáticas (ex.: "nublado", "ensolarado").
   - Umidade do ar.
   - Ícone de condições climáticas: Um ícone representativo do clima (fornecido pela API) é exibido junto à descrição.

### Tecnologias Utilizadas:
- HTML: Estrutura do layout da aplicação.
- CSS: Estilização da interface, garantindo uma experiência visual agradável.
- JavaScript: Implementação da lógica de busca, integração com a API e manipulação dinâmica do DOM.
- API OpenWeatherMap: Fonte dos dados meteorológicos consumidos pela aplicação.

### Destaques Técnicos:
- Fetch API: Utilizada para realizar chamadas assíncronas à API de previsão do tempo.
- Manipulação de DOM: Atualização dinâmica dos elementos da página com base nos dados recebidos.
- Unidades métricas e idioma: Configuradas para exibir as informações em português e temperatura em graus Celsius.

### Como Funciona?
- O usuário insere o nome de uma cidade no campo de texto.
- Ao clicar no botão de busca, a aplicação envia uma requisição para a API OpenWeatherMap.
- Os dados meteorológicos retornados pela API são processados e exibidos na tela.
- Caso a cidade não seja encontrada ou ocorra algum erro, o usuário recebe uma mensagem informativa.
