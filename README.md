# Web-Scraping - Dados dos resultados das eleições do TSE

## Resumo do Projeto
Este repositório apresenta um exemplo prático de como utilizar o Selenium para realizar scraping de dados eleitorais do site do Tribunal Superior Eleitoral (TSE). O código permite a extração de informações sobre locais de votação e candidatos, a partir de critérios definidos pelo usuário, como município, zona e seção eleitoral.

## Principais Etapas do Código
Importação de Bibliotecas: Importa as bibliotecas necessárias para manipulação de dados (Pandas), gerenciamento de diretórios (os) e automação de navegador (Selenium).

Configuração do Navegador: Inicializa o navegador Chrome com opções específicas para garantir a compatibilidade com o site do TSE, que utiliza JavaScript.

Extração de Dados:
* Coleta dados de identificação da urna, como município, zona e seção eleitoral.
* Realiza scraping da quantidade de votos obtidos por cada candidato, armazenando essas informações em um DataFrame.

Resultados: O código gera um DataFrame contendo as informações de identificação da urna e os votos, permitindo a análise posterior.

## Exemplo de Uso
O usuário é solicitado a fornecer informações como o código do município, zona e seção. Com base nesses dados, o script acessa a página correspondente no TSE, coleta as informações desejadas e as armazena em um formato estruturado.
