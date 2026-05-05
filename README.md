# Como rodar o Projeto:

## No terminal, entre na pasta do projeto:
    - cd <caminho_diretório_projeto>

## Verificar o ficheiro sites.json
    1. Abre o ficheiro:
        - sites.json
    
    2. Garante que contém uma lista de links a visitar.
        - Exemplo:
            - [{
                    "title": "Exemplo",
                    "link": "https://example.com"
                }] 

        - Podes editar o arquivo, colocando os links pretendidos.               

## Executar o crawler
    - Com o terminal dentro da pasta do projeto, execute:
        - python Crawler.py