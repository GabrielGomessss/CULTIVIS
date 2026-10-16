# 🌱 CULTIVIS — Sistema Inteligente de Gerenciamento e Monitoramento Agrícola

**Projeto de Trabalho de Conclusão de Curso (TCC) — 2026**

O CULTIVIS é um sistema inteligente voltado ao gerenciamento e monitoramento agrícola, desenvolvido com o objetivo de centralizar informações de propriedades rurais e auxiliar produtores no acompanhamento das condições ambientais das plantações por meio da integração entre software, hardware e Internet das Coisas (IoT).

O projeto busca contribuir para uma gestão agrícola mais organizada, acessível e eficiente, utilizando tecnologias para coleta de dados, monitoramento de variáveis ambientais e disponibilização de informações relevantes para a tomada de decisões.

## 🎯 Objetivos do projeto

- Centralizar o gerenciamento de propriedades agrícolas, plantações e produção.
- Monitorar variáveis ambientais, como temperatura, umidade e pH do solo.
- Integrar sensores físicos a um sistema de gerenciamento digital.
- Facilitar a identificação de alterações nas condições monitoradas.
- Disponibilizar informações que auxiliem o produtor no acompanhamento de sua propriedade.

## 👨‍💻 Minha contribuição no projeto

Minha participação no CULTIVIS está concentrada principalmente no **desenvolvimento de firmware, sistemas embarcados, integração de hardware e aplicação de IoT no monitoramento agrícola**.

Também participei diretamente do planejamento e desenvolvimento da estrutura física utilizada para organizar os componentes eletrônicos do projeto.

### 1. Desenvolvimento de firmware e sistemas embarcados

Desenvolvimento da programação em C/C++ para o microcontrolador ESP32, utilizando a Arduino IDE para implementar a lógica de funcionamento dos componentes eletrônicos e a leitura dos sensores.

Principais atividades:

- Desenvolvimento de firmware em C/C++ para o ESP32.
- Implementação da lógica de leitura dos sensores conectados ao microcontrolador.
- Utilização de bibliotecas para comunicação e aquisição de dados dos sensores.
- Integração entre o microcontrolador e os componentes eletrônicos do circuito.
- Desenvolvimento da lógica necessária para coletar e preparar os dados obtidos pelos sensores para utilização no sistema.

### 2. Integração de hardware e sensores

Participação na montagem e integração do circuito eletrônico responsável pela aquisição de dados ambientais.

**Componentes utilizados:**

| Componente | Finalidade |
|---|---|
| ESP32 DevKit V1 | Executar o firmware e realizar a comunicação com os sensores |
| DHT11 | Realizar medições de temperatura e umidade |
| Módulo sensor de pH 4502C | Permitir a medição do pH por meio de um sensor compatível |
| Protoboard | Facilitar a montagem e conexão dos componentes |
| Resistores e jumpers | Auxiliar nas conexões e na adequação elétrica do circuito |
| Bateria recarregável | Componente previsto para a alimentação do conjunto |

Essa etapa envolve a organização dos componentes, a montagem do circuito e a integração entre o hardware e o firmware desenvolvido para o microcontrolador.

### 3. Desenvolvimento da CULTIVIbox

Também participei diretamente do planejamento e desenvolvimento da **CULTIVIbox**, estrutura projetada para acomodar e organizar os componentes eletrônicos do sistema de monitoramento.

Minhas atividades envolveram:

- Definição e medição das dimensões necessárias para acomodar os componentes.
- Planejamento da estrutura física e da disposição dos elementos internos.
- Consideração da ventilação e da organização do circuito eletrônico.
- Seleção e aquisição dos materiais necessários para a construção.
- Planejamento do espaço destinado ao microcontrolador, às conexões e aos sensores.

A CULTIVIbox integra a proposta de hardware do CULTIVIS, contribuindo para a organização física dos componentes utilizados no monitoramento agrícola.

## ⚙️ Tecnologias e ferramentas da minha atuação

- **Linguagens:** C/C++.
- **Microcontrolador:** ESP32 DevKit V1.
- **Ambiente de desenvolvimento:** Arduino IDE.
- **Sensores:** DHT11 e módulo de pH 4502C.
- **Conceitos:** firmware, sistemas embarcados, aquisição de dados, integração de hardware e Internet das Coisas (IoT).
- **Montagem eletrônica:** protoboard, resistores, jumpers e componentes de alimentação.
- **Desenvolvimento físico:** planejamento dimensional e estrutural da CULTIVIbox.

## 🏗️ Visão geral da arquitetura do CULTIVIS

O CULTIVIS reúne diferentes componentes tecnológicos que trabalham em conjunto para permitir o monitoramento agrícola.

### Hardware e aquisição de dados

O ESP32 executa o firmware responsável pela interação com os sensores e pela aquisição das medições ambientais.

### Back-End e integração

A camada de Back-End é responsável pela lógica de processamento e integração dos dados com os serviços do sistema, utilizando APIs para a comunicação entre os componentes, conforme a implementação do projeto.

### Banco de dados

O sistema utiliza PostgreSQL, com Supabase e Prisma ORM na estrutura de persistência e acesso aos dados.

### Aplicativo

A interface do sistema é desenvolvida com React Native e Expo, permitindo organizar as informações agrícolas e apresentar os dados de monitoramento ao usuário.

### Fluxo conceitual

**Sensores → ESP32 e firmware → Comunicação com o Back-End → Banco de dados → Aplicativo CULTIVIS**

O fluxo representa a arquitetura proposta para conectar a aquisição física de dados à disponibilização das informações no sistema. A comunicação depende da integração implementada entre as camadas.

## 🧰 Tecnologias utilizadas no projeto

| Área | Tecnologias |
|---|---|
| Firmware e hardware | C/C++, ESP32, Arduino IDE |
| Sensores | DHT11, módulo de pH 4502C |
| Aplicativo | React Native, Expo, JavaScript |
| Back-End | Node.js, Express, TypeScript |
| Validação de dados | Zod |
| Banco de dados | PostgreSQL, Supabase, Prisma ORM |
| Autenticação | Supabase Auth |
| Integração | APIs REST |

## 📚 Conhecimentos desenvolvidos

A participação no CULTIVIS proporcionou a aplicação prática de conhecimentos relacionados a:

- Programação em C/C++.
- Desenvolvimento de firmware para microcontroladores.
- Sistemas embarcados e Internet das Coisas.
- Integração entre sensores e circuitos eletrônicos.
- Aquisição de dados ambientais.
- Planejamento e desenvolvimento de estruturas físicas para dispositivos eletrônicos.
- Integração entre componentes de hardware e sistemas de software.
- Trabalho colaborativo no desenvolvimento de uma solução tecnológica multidisciplinar.

## 🎓 Contexto acadêmico

O CULTIVIS é um projeto de Trabalho de Conclusão de Curso desenvolvido no curso técnico em Análise e Desenvolvimento de Sistemas da ETEC Jacinto Ferreira de Sá, em Ourinhos — SP.

O projeto reúne conhecimentos de desenvolvimento de software, bancos de dados, eletrônica e IoT para propor uma solução tecnológica voltada às necessidades do gerenciamento agrícola.

---

**CULTIVIS — Sistema Inteligente de Gerenciamento e Monitoramento Agrícola.** 🌱
