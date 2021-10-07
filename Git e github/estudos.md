# Anotações das aulas da DIO
# Introdução ao Git

## Entendendo o que é Git e sua importância

O git é uma ferramenta de versionamento de código.

![Captura de Tela 2021-10-06 às 20.22.44.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cdc6521c-fd64-44ad-bdc1-3c9643a7ea75/Captura_de_Tela_2021-10-06_as_20.22.44.png)

# Navegação Via command line

## Comandos básicos para um bom desempenho no terminal

![Captura de Tela 2021-10-06 às 20.32.33.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d94246cf-9dc6-41c2-8563-1aa9a945b42c/Captura_de_Tela_2021-10-06_as_20.32.33.png)

cd → entrar em uma pasta

dir / ls → listas os conteudos da pasta atual

mkdir → criar nova pasta

cd .. → retroceder 1 nível na navegação

cls / clear (ctrl + l) → limpar terminal

(tab) → auto complete

echo mensagem > nome.tipoDoArquivo → cria arquivo

**windows**

del nomeDaPasta → apaga tudo dentro da pasta

rmdir nomeDaPasta /S /Q → apaga a pasta

**Unix**

rm -rf nomeDaPasta → apaga a pasta

## Realizando a instalação do GIT

[Git](https://git-scm.com/)

# Entendendo como o Git funciona por baixo dos panos

## Tópicos fundamentais para entender o funcionamento do Git

![Captura de Tela 2021-10-06 às 21.12.39.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/493e414b-860f-4d76-bfbf-2d10b055a9da/Captura_de_Tela_2021-10-06_as_21.12.39.png)

![Captura de Tela 2021-10-06 às 21.12.51.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7ee78433-18d8-4f56-97d5-74525f1a040b/Captura_de_Tela_2021-10-06_as_21.12.51.png)

![Captura de Tela 2021-10-06 às 21.13.33.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8bee06f4-415e-4309-960c-062cab0ed191/Captura_de_Tela_2021-10-06_as_21.13.33.png)

## Objetos internos do Git

### Blobs

![Captura de Tela 2021-10-06 às 21.30.07.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c4472cbd-4cba-4a93-bd45-c805e5cf91d7/Captura_de_Tela_2021-10-06_as_21.30.07.png)

### Tree

![Captura de Tela 2021-10-06 às 21.33.49.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5f71dc7e-3abd-4bc4-98fb-af24bd36301e/Captura_de_Tela_2021-10-06_as_21.33.49.png)

### Commit

![Captura de Tela 2021-10-06 às 21.34.14.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/29dec64d-e577-4e12-a0f5-1e7704ed857e/Captura_de_Tela_2021-10-06_as_21.34.14.png)

![Captura de Tela 2021-10-06 às 21.37.23.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cd960394-f3a1-4616-ba9a-8bdc6d09d20a/Captura_de_Tela_2021-10-06_as_21.37.23.png)

## Chave SSH e Token

# Primeiros comandos com Git

## Iniciando o Git e criando um commit

![Captura de Tela 2021-10-06 às 21.57.18.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2b268e93-abf8-4023-a06a-78706d44bab5/Captura_de_Tela_2021-10-06_as_21.57.18.png)

![Captura de Tela 2021-10-06 às 21.58.49.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e9d0de36-127d-47c7-a7fe-8d9acbed5867/Captura_de_Tela_2021-10-06_as_21.58.49.png)

user.name***

![Captura de Tela 2021-10-06 às 21.59.04.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/be9c4f40-d830-463d-9a9f-db7c6ed5f960/Captura_de_Tela_2021-10-06_as_21.59.04.png)

![Captura de Tela 2021-10-06 às 22.01.44.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ab32b356-aea0-4855-bc2b-8198aada6229/Captura_de_Tela_2021-10-06_as_22.01.44.png)

# Ciclo de vida dos arquivos no Git

## Passo a passo no ciclo de vida

git init

![Captura de Tela 2021-10-06 às 22.03.04.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/20f9f024-07d7-4713-8188-b733b8c67335/Captura_de_Tela_2021-10-06_as_22.03.04.png)

git add .

![Captura de Tela 2021-10-06 às 22.04.20.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2a29fbcf-3310-4c3d-9819-a8c9496aefdb/Captura_de_Tela_2021-10-06_as_22.04.20.png)

Arquivo ainda não modificado

![Captura de Tela 2021-10-06 às 22.04.46.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1dae4d16-0686-469b-bb88-82cec1678f68/Captura_de_Tela_2021-10-06_as_22.04.46.png)

git add .

![Captura de Tela 2021-10-06 às 22.05.04.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a2c802f2-c6e4-4794-914a-977e78222032/Captura_de_Tela_2021-10-06_as_22.05.04.png)

Remove o arquivo

![Captura de Tela 2021-10-06 às 22.05.20.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dbd03821-1570-4135-b72e-6df6120e84a0/Captura_de_Tela_2021-10-06_as_22.05.20.png)

git commit

![Captura de Tela 2021-10-06 às 22.05.33.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6b6b1992-5147-4705-a800-c8649ab071ba/Captura_de_Tela_2021-10-06_as_22.05.33.png)

---

git init

![Captura de Tela 2021-10-06 às 22.06.56.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d0bfe497-1320-4f17-891e-f42246558ad7/Captura_de_Tela_2021-10-06_as_22.06.56.png)

git add .

![Captura de Tela 2021-10-06 às 22.07.30.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b22dda90-2c4e-436f-8d33-3645fc5c5033/Captura_de_Tela_2021-10-06_as_22.07.30.png)

git commit

![Captura de Tela 2021-10-06 às 22.07.48.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/21741a33-f025-4d56-b588-558247d4a11b/Captura_de_Tela_2021-10-06_as_22.07.48.png)

git status → visualizar o status do git

# Introdução ao GitHub

## Trabalhando com o GitHub

[GitHub: Where the world builds software](https://github.com/)

# Resolvendo conflitos

## Como os conflitos acontecem no GitHub e como resolvê-los

![Captura de Tela 2021-10-06 às 22.11.49.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6b071658-474b-4677-bb71-12f83975cb0c/Captura_de_Tela_2021-10-06_as_22.11.49.png)

git push origin master

git pull  origin master

![Captura de Tela 2021-10-06 às 22.13.09.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5b120fba-95f1-4dfb-8e42-4686226d038e/Captura_de_Tela_2021-10-06_as_22.13.09.png)

![Captura de Tela 2021-10-06 às 22.14.44.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b7bcd84f-95ad-4f85-8239-a9db6c543c1e/Captura_de_Tela_2021-10-06_as_22.14.44.png)