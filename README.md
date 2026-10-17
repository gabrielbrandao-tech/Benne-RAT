# Sistema RAT Digital

Sistema web desenvolvido para preenchimento digital e geração de Relatórios de Atendimento Técnico (RAT) em PDF. 

O projeto foi criado com foco em praticidade, permitindo que o técnico preencha as informações diretamente pelo celular ou computador em campo, registre assinaturas digitais na tela e gere o documento final em PDF de forma automatizada e segura.

## Funcionalidades

- **Gestão de Atendimento:** Preenchimento de dados do cliente, registro de endereço, número de chamado e dados de contato.
- **Controle de Ativos:** Cadastro detalhado de equipamentos e registro de materiais utilizados durante a visita.
- **Parecer Técnico:** Campo dedicado para laudo técnico e registro exato de horários de início e término.
- **Validação Digital:** Captura de assinatura digital do cliente e do técnico diretamente na tela do dispositivo.
- **Processamento de Documentos:** Preenchimento automático de um modelo PDF padronizado com os dados informados.
- **Compartilhamento Ágil:** Integração nativa para compartilhamento do PDF pelo dispositivo (WhatsApp, E-mail, etc.) ou download automático via navegador.
- **Segurança:** Autenticação de utilizadores e bloqueio de rotas para garantir que apenas técnicos autorizados acedam aos relatórios.
- **Design Responsivo:** Interface totalmente adaptada (Mobile-First) para uso em smartphones, tablets e computadores.

## Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3, JavaScript
- **UI/UX:** Bootstrap 5, Bootstrap Icons
- **Manipulação de PDF:** PDF-LIB
- **Backend & Autenticação:** Supabase (Auth & Edge Functions)
- **APIs Nativas:** HTML Canvas API (Assinaturas), Web Share API (Compartilhamento)

## Estrutura Básica do Projeto

```text
/
├── index.html  
├── login.html 
├── rat-modelo-1.html 
├── rat-modelo-2.html  
├── rat-modelo-3.html 
├── rat-base.pdf  
├── /img 
└── README.md
```

## Objetivo

Digitalizar e modernizar o processo de elaboração de Relatórios de Atendimento Técnico para empresas de Field Service. O sistema reduz drasticamente a necessidade de preenchimento manual em papel, evita perda de documentos, agiliza a entrega do relatório ao cliente final e torna o fluxo operacional mais rastreável e organizado.

## Direitos Autorais e Licença

**© 2026 B.I.T Soluções em T.I. Todos os direitos reservados.**

Este projeto é de autoria própria e está disponibilizado neste repositório exclusivamente para fins de demonstração e portfólio.

**NÃO É PERMITIDA**, sem autorização prévia e por escrito do autor:
- Cópia total ou parcial do código;
- Redistribuição ou hospedagem do projeto;
- Reprodução ou publicação do projeto como sendo de terceiros;
- Uso em ambiente comercial ou produtivo;
- Modificação estrutural para criação de projetos derivados;
- Utilização deste projeto como base (template) para outro sistema comercial.

*A visualização do código neste repositório público não constitui concessão de licença Open-Source para copiar, modificar, distribuir ou comercializar o projeto.* Para solicitar autorização de uso corporativo ou obter informações sobre licenciamento, entre em contato diretamente com o autor.

## Autor

**B.I.T Soluções em T.I.** (Gabriel Brandão)
- **GitHub:** [gabrielbrandao-tech](https://github.com/gabrielbrandao-tech)
- **Portfólio:** [gabriel-brandao.dev](https://gabriel-brandao.dev)

> *Este repositório faz parte do portfólio de desenvolvimento e demonstra conhecimentos práticos em desenvolvimento web frontend, integração de serviços BaaS (Supabase), segurança de rotas, manipulação de PDFs via código e criação de interfaces adaptativas.*