---
title: YAML- Uma Linguagem para Configuração e Dados
date: 2024-01-20

authors: [Thais Mesquita]
tags:
  - assuntos
  - internet
  - redes de computadores
---

<p align="justify">
    YAML, que significa "Yet Another Markup Language" ou "YAML Ain't Markup Language," é uma linguagem de serialização de dados amplamente utilizada na criação de arquivos de configuração. Ao contrário de linguagens de marcação, YAML é focado em dados e não em documentos. </p>

## Sintaxe do YAML

<p align="justify">
    Os arquivos YAML têm extensões .yml ou .yaml e seguem regras específicas de sintaxe. A linguagem incorpora características de Perl, C, XML, HTML e outras, sendo também um superconjunto do JSON. </p>

<p align="justify">
    A estrutura dos arquivos YAML é baseada em recuos, utilizando espaços em branco para indicar a hierarquia e o aninhamento dos dados. Comentários, identificados pelo símbolo '#' (hash), são práticas recomendadas para descrever a intenção do código. </p>

## Exemplo Básico de Arquivo YAML

<p align="justify">
    Aqui está um exemplo básico de um arquivo YAML representando uma lista de compras de supermercado: </p>

```yaml
# Comentário: Esta é uma lista de supermercado usando YAML
# Observe que o caractere '-' representa a lista
---
food:
  - vegetables: tomatoes  # primeiro item da lista
  - fruits:
      citrics: oranges
      tropical: bananas
      nuts: peanuts
      sweets: raisins
```
<p align="justify">
    A estrutura do arquivo segue uma hierarquia, onde "food" é um mapa contendo itens como "vegetables" e "fruits", que são listas. </p>

## Uso Comum do YAML

<p align="justify">
    Um caso comum de uso do YAML é na criação de arquivos de configuração, sendo recomendado para essa finalidade em comparação com JSON devido à sua legibilidade. O Ansible, uma ferramenta de automação, utiliza YAML para definir processos em seus playbooks. </p>

<p align="justify">
    Além disso, o YAML é amplamente adotado em implantações e recursos do Kubernetes, onde arquivos YAML descrevem o estado desejado do cluster. </p>

## YAML no Ansible e Kubernetes

<p align="justify">
    No Ansible, os Playbooks, que orquestram processos de TI, são escritos em YAML. Os Playbooks contêm listas e mapas para definir o estado desejado do sistema. </p>

<p align="justify">
    No Kubernetes, arquivos YAML descrevem objetos que representam o estado do cluster. O Kubernetes utiliza esses arquivos para garantir que o estado real corresponda ao estado desejado. </p>

## Conclusão

<p align="justify">
    O YAML é uma ferramenta poderosa para representação de dados e configuração, amplamente adotada em diversos cenários, desde automação com Ansible até configuração de clusters Kubernetes. Sua sintaxe limpa e legível facilita o trabalho de desenvolvedores e administradores de sistemas. Ao criar arquivos YAML, é importante seguir as regras de sintaxe e garantir a validade do arquivo usando ferramentas como "yamllint." </p>