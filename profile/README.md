# Gerenciador de Newsletter

Este é um sistema de gerenciamento de newsletters, desenvolvido para facilitar a criação, agendamento e envio de emails para listas de assinantes. O sistema permite que administradores gerenciem campanhas de marketing por email de forma eficiente e personalizada, com opções de agendamento e formatação de conteúdo.

## Sobre o Projeto

O gerenciador de newsletters permite que os usuários:
- Criem e personalizem templates de email.
- Agendem envios de newsletters para listas de assinantes.

Esse tipo de aplicação é ideal para empresas que desejam automatizar e profissionalizar sua comunicação com clientes, promovendo engajamento e mantendo os usuários atualizados sobre novidades, promoções e conteúdos relevantes.

## Tecnologias Utilizadas

### Backend
- **Java 21** - Linguagem principal utilizada para o desenvolvimento do backend.
- **Maven** - Gerenciador de dependências e automação de builds.
- **Docker** - Contêineres para facilitar o deployment e a replicação da aplicação.
- **MongoDB** - Banco de dados NoSQL utilizado para armazenar informações sobre os assinantes e histórico de newsletters.
- **Quartz** - Biblioteca de agendamento para gerenciar o envio de emails em horários específicos.
- **JavaMailSender** - Utilizado para o envio de emails.

### Frontend
- **React** - Biblioteca JavaScript para construção de interfaces de usuário.
- **Vite** - Ferramenta de build e desenvolvimento rápido, usada para o bundling do projeto React.
- **Axios** - Biblioteca para realizar requisições HTTP ao backend.

## Arquitetura Geral

![Diagrama de Casos de Uso](https://cdn.discordapp.com/attachments/1028712344110514176/1304529755563102259/protips-casos-de-uso.png?ex=672fb982&is=672e6802&hm=7535a6c22e6e6782d89fbcecf76f09e3e87fba03ee4c9e16a79f202f1161acc5&)

## Funcionalidades Principais

- **Criação de Templates**: Permite a formatação personalizada das newsletters para garantir uma aparência profissional e alinhada à identidade visual da empresa.
- **Agendamento de Envios**: Com a integração do Quartz Scheduler, é possível definir data e horário específicos para o envio das campanhas.

## Configuração do Ambiente

### Requisitos
- Java 21+
- Docker
- Maven
- Node.js (para o frontend)

### Links

frontend: 
 - admin: https://github.com/seminario-interdiciplinar-uniasselvi/protips-admin-front
 - assinantes: https://github.com/seminario-interdiciplinar-uniasselvi/protips-subscribers-front

backend:
 - https://github.com/seminario-interdiciplinar-uniasselvi/protips-api

### Melhorias Futuras
- **Gerenciamento de Assinantes**: Possibilidade de organizar e segmentar assinantes em diferentes listas, facilitando campanhas direcionadas.
- **Dashboard de Monitoramento**: Exibe estatísticas e status das campanhas, permitindo análise de desempenho e ajuste de estratégias.
