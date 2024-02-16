# Documentação do Projeto Python

## Introdução

Este documento fornece uma visão geral do projeto Python fornecido, incluindo os detalhes sobre o programa e as dependências necessárias para executá-lo. O projeto consiste em uma aplicação FastAPI que oferece endpoints para acessar dados de cardápios de restaurantes. Além disso, o projeto inclui um ambiente virtual Python (venv) para isolar suas dependências.

## Visão Geral do Programa

O programa Python consiste em um servidor FastAPI que fornece dois endpoints:

1. `/api/hello`: Retorna uma mensagem simples "Hello World".
2. `/api/restaurantes/`: Permite visualizar os cardápios dos restaurantes.

## Dependências

Para executar o programa Python, as seguintes dependências são necessárias:

- `fastapi`: FastAPI é um framework web assíncrono para construir APIs com Python 3.7+.
- `requests`: Requests é uma biblioteca HTTP elegante e simples para Python, usada para fazer solicitações HTTP.
- `json`: JSON (JavaScript Object Notation) é um formato leve de troca de dados.

## Ambiente Virtual (venv)

O projeto inclui um ambiente virtual Python (venv) para isolar suas dependências do sistema global. Isso permite que você trabalhe em um ambiente Python limpo e evita conflitos de dependências entre projetos.

### Ativação do Ambiente Virtual

Para ativar o ambiente virtual, siga estas etapas:

1. No terminal (Prompt de Comando, PowerShell ou Git Bash), navegue até o diretório raiz do projeto onde o ambiente virtual está localizado.

2. Dependendo do terminal que você está utilizando, use o comando apropriado para ativar o ambiente virtual:
   
   - **Prompt de Comando**:
     ```plaintext
     \caminho\para\o\projeto\venv\Scripts\activate
     ```
   - **PowerShell**:
     ```plaintext
     \caminho\para\o\projeto\venv\Scripts\Activate.ps1
     ```
   - **Git Bash**:
     ```bash
     source /caminho/para/o/projeto/venv/Scripts/activate
     ```

### Desativação do Ambiente Virtual

Para desativar o ambiente virtual, basta fechar a janela do terminal onde o ambiente virtual está ativo. Isso o levará de volta ao ambiente padrão do sistema.

## Instalação de Dependências

As dependências do projeto podem ser instaladas facilmente usando o gerenciador de pacotes `pip`. Certifique-se de que o ambiente virtual esteja ativado e execute os seguintes comandos no terminal:

```bash
pip install fastapi
pip install requests
```

Após a instalação das dependências, o programa estará pronto para ser executado.

## Execução do Programa

Para executar o programa, você pode simplesmente executar o arquivo Python que contém o código fornecido. Certifique-se de estar no diretório correto onde o arquivo Python está localizado e execute o arquivo.

Exemplo:

```bash
python nome_do_arquivo.py
```

## Funcionalidade Adicional

Além dos endpoints FastAPI, o programa também faz uma solicitação HTTP para um endpoint remoto que fornece dados sobre os cardápios dos restaurantes. Ele processa os dados recebidos e os armazena em arquivos JSON locais.

## Conclusão

Este documento fornece uma visão geral do projeto Sabor Express feito em Python na #Alura, suas dependências e instruções sobre como instalar, ativar e desativar o ambiente virtual e executar o programa. Ele também destaca a funcionalidade adicional do programa em relação à obtenção e armazenamento de dados de cardápios de restaurantes.
Com esse Curso pude ver como o Python realmente se destaca como uma das principais escolhas para lidar com aquisição de dados em aplicações de backend, proporcionando eficiência, facilidade de uso e uma vasta gama de recursos para lidar com uma variedade de casos de uso.
@josef_jr🥷
