# Sumário

- [Docker - Documentação](#docker---documentao)
  - [Docker é um container runtime onde roda as aplicações, mas também ele consegue fazer](#docker-é-um-container-runtime-onde-roda-as-aplicações-mas-também-ele-consegue-fazer)
  - [O que é um container?](#o-que-é-um-container)
  - [Quanto custa o docker desktop?](#quanto-custa-o-docker-desktop)

# Docker - Documentação

Uma ferramenta open source expecificamente para rodar no linux (open source)
> Docker desktop - Ferramenta proprietária não open source.

## Docker é um container runtime onde roda as aplicações, mas também ele consegue fazer

- Com que os nossos container se comuniquem atravésde redes.
- Mapear volumes do nsso computador
- Buildar imagens
- Baixar imagens
- Ele não se limita só em rodar container

___

## O que é um container?

Um container é um processo que roda encima sistema operacional, porem se você entra dentro dele, ele pensa que ele é um sistema operacional, mas na verdade, toda vez que ele faz uma chamada, essa chamada bate do docker, que bate no sistema operacional. (bibliotecas, kernels, etc. rodam de forma compartilhada)

- Esse processo roda de forma  isolada para não afetar outros processos do sistema operacional

- Pode-se isolar a quantidade de recursos que esse container irá utilizar

- Você consegue garantir que o que estiver rodando na minha máquina que esta rodando com container, é extamente o que vai rodar pra produção pois eles são baseados na mesma imagem (ISO).

## Quanto custa o docker desktop?

### Licensa Personal
>Gratuita

Dica: *<span style="opacity:0.4">Usar [WSL2](https://learn.microsoft.com/pt-br/windows/wsl/about) caso for usuário de windows.</span>*


