# Proposta de Solução para Sistema de Automação Residencial Escalável

Este documento detalha uma proposta de solução para um sistema de automação residencial, com foco na escalabilidade para atender até 10.000 residências. Utilizando a modelagem RM-ODP (Reference Model of Open Distributed Processing), que nos permite abordar o sistema sob cinco visões distintas.

## Problemática

Inicialmente, o projeto visava a automação de uma única casa, com funcionalidades de detecção de presença para controle de iluminação e segurança contra invasores. A problemática é expandir essa capacidade para 10.000 moradias. Isso implica em uma abstração e modelagem do sistema que considere não apenas o ambiente interno de cada moradia (sensores e atuadores), mas também a interconexão em uma rede local e, posteriormente, em uma rede maior, com uma estrutura hierárquica que englobe agrupamentos de moradias.

### Visão 1: Drivers de Negócio (O Porquê)

