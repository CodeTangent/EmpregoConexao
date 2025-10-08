# Conexão Empregos – Sistema Automatizado de Envio de Currículos

## Visão Geral
Conexão Empregos é um projeto desenvolvido em Python com interface Tkinter que permite gerenciar e automatizar o envio de currículos para empresas listadas em uma planilha. O foco do projeto é demonstrar habilidades de automação, organização de dados e boas práticas de programação, sem expor informações sensíveis.

O sistema está estruturado de forma a separar dados, configurações e lógica de envio, garantindo segurança e modularidade.

## Funcionalidades Principais
- Leitura de lista de empresas e contatos a partir de planilha local (`contatox.xls`)  
- Configuração de envio com e-mail remetente seguro via senha de aplicativo (`senha_app.txt`)  
- Interface gráfica intuitiva construída com Tkinter  
- Controle de envio individual por empresa, permitindo enviar ou pular contatos  
- Registro de progresso do envio para acompanhamento visual  
- Organização de currículos por área (pastas `curriculos/administracao`, `curriculos/enfermagem`, `curriculos/téc. informática`)  

## Estrutura do Projeto
A estrutura de arquivos foi organizada para manter segurança e clareza:

| Arquivo / Pasta                        | Descrição                                                                                   |
|---------------------------------------|--------------------------------------------------------------------------------------------|
| `curriculos/administracao`             | Pasta para armazenar currículos da área de Administração                                   |
| `curriculos/enfermagem`                | Pasta para armazenar currículos da área de Enfermagem                                      |
| `curriculos/téc. informática`         | Pasta para armazenar currículos da área de Técnico de Informática                           |
| `contatox.xls`                         | Planilha que funciona como banco de dados local com empresas e contatos                     |
| `main.py`                              | Arquivo principal do projeto, responsável pela interface gráfica e controle de envio        |
| `senha_app.txt`                        | Arquivo local contendo a senha de app para autenticação do e-mail (não exposto no repositório) |

> Observação: Todos os arquivos foram criados com conteúdo “fantasma” ou placeholders para preservar segurança e confidencialidade de dados reais.  

## Conceitos Aplicados
- Python com Tkinter para interface gráfica  
- Automação de envio de e-mails via SMTP  
- Manipulação de planilhas Excel  
- Estrutura modular e organização de projeto  
- Boas práticas de segurança: não expor senhas ou dados sensíveis no repositório  

## Como Funciona
1. Abra o arquivo `main.py` com Python 3 instalado.  
2. Configure o e-mail remetente usando senha de app no arquivo `senha_app.txt`.  
3. Aplique a lista de contatos na planilha `contatox.xls` (estrutura de exemplo já fornecida).  
4. Organize os currículos nas pastas correspondentes dentro de `curriculos/`.  
5. Use a interface para selecionar empresas e enviar currículos.  
6. O sistema registra o envio e atualiza a interface para acompanhamento do progresso.  

## Status do Projeto
- Funcionalidade principal de envio automatizado implementada  
- Interface gráfica intuitiva pronta  
- Estrutura modular permite futuras melhorias, como integração com mais formatos de planilhas ou envio simultâneo  

## Observações
Este projeto foi criado com fins educativos e profissionais, demonstrando habilidades em automação e Python. Nenhum dado real foi exposto no repositório, mantendo confidencialidade.
