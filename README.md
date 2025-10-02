# 🤖 Hexapod - Diário de Desenvolvimento

**Equipe:** IEEE RAS - UEFS

## 📝 Visão Geral

Este repositório serve como o diário de desenvolvimento oficial do projeto Hexapod. Nosso objetivo é construir um robô hexápode, com todas as 6 patas independentes, cada qual com um grau de liberdade. Aqui, documentamos nosso progresso, desafios e aprendizados em todas as frentes: software, hardware, eletrônica e design mecânico.

## 👥 Equipe

| Nome                 | Cargo no projeto             | GitHub                                     |
| -------------------- | ------------------------- | ------------------------------------------ |
| Walace de J. Venas   | Líder de Projeto | [@LordWalace](https://github.com/LordWalace)   |
| Marcelo Tavares   | Secretario de Mesa   | [@Marcelosgc1](https://github.com/Marcelosgc1)   |
| David Neves   | Projetista   | [@davidm34](https://github.com/davidm34)   |
| Paulo Gabriel da Rocha   | Projetista             | [@Paulo1302](https://github.com/Paulo1302)   |

## 🎯 Metas do Projeto

### Metas atuais

  * **Hardware:** WIP.
  * **Software:** WIP.
  * **Modelagem 3D:** WIP.

### Objetivos Gerais

  - **Hardware:**
      - [ ] Projetar e montar um chassi robusto.
      - [ ] ---
      - [ ] ---
  - **Software:**
      - [ ] ---
      - [ ] ---
      - [ ] ---

## 🛠️ Tecnologias e Ferramentas

| Categoria         | Ferramentas                                       |
| ----------------- | ------------------------------------------------- |
| **Linguagens** | C++                                       |
| **Frameworks** | ---  |
| **Hardware** | Arduino Uno   |
| **Modelagem 3D** | ---                   |
| **Design de PCB** | ---                     |
| **Simulação** | ---                       |

-----

## 📓 Diário de Desenvolvimento

Aqui registramos nosso progresso semanalmente. Cada entrada inclui atualizações de hardware e software, os desafios que encontramos e as decisões que tomamos.

### Semana 1: (08/09/2025)

**Foco da Semana:** Planejamento Inicial e Prototipagem

  * **Desafios:**
      * Fazer o levantamento de requisitos de materiais necessários para a construção do robô.
  * **Decisões:**
      * Optamos pelos seguintes materiais, devido à familiaridade quanto disponibilidade no laboratório:
        * Microcontrolador: Arduino Uno
        * Atuadores: 4x Micro Servomotores (modelos SG90 ou MG90S)
        * Alimentação: 4x Bateria LiPo 2S (7.4V) ou 4x Pilhas AA recarregáveis
        * Infra: Suporte para 4 pilhas AA ou Conector JST/XT60 para a bateria LiPo
        * Conexões: Fios Jumper (macho-macho & macho-fêmea)
        * Estrutura: Chassi e pernas feitos através de impressão 3D
       
   ### Semana 2: (15/09/2025)

**Foco da Semana:** Planejamento Inicial e Prototipagem

  * **Desafios:**
      * Criar o modelo 3d do Hexapod para imprimir e fazer a montagem
  * **Decisões:**
      * Optamos pelo uso de um modelo pronto de chassi para o Hexapod assim facilitando a criação

 ### Semana 3: (22/09/2025)

**Foco da Semana:** Planejamento e Impressão do chassi

  * **Desafios:**
      * Adaptar o modelo que escolhemos para suprir os materias que faltam ou são diferentes
      * Os novos materias seram adicionados na lista na proxima semana e atualizado aqui
  *  **Decisões:**
      * Foi decidido que iremos usar menos servos motores
      * Não iremos usar o suporte para pilha e nem pilhas nessa versão do Hexapod

   
## 🚀 Como Contribuir

Somos um projeto de código e hardware abertos\! Se você deseja contribuir:

1. **Faça um Fork** deste repositório.
2. **Crie uma Branch** para sua feature (`git checkout -b feature/SuaFeature`).
3. **Faça o Commit** de suas mudanças (`git commit -m 'Adiciona SuaFeature'`).
4. **Faça o Push** para a Branch (`git push origin feature/SuaFeature`).
5. Abra um **Pull Request**.

Para problemas ou sugestões, por favor, abra uma **Issue**.

## 📄 Licença

Este projeto está licenciado sob a Licença GNU V2.0. Veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.
