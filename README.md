![GitHub Actions imagem cabeçalho](./img/image.png)

# Introdução

O GitHub a um bom tempo tem sido popularmente a maior ferramenta de hospedagem de código gratuita na internet. Uma feature muito interessante é o GitHub Actions, permitindo automatizar fluxos de build e deploy sem a necessidade de integração com outras plataformas (Azure DevOps, Jenkins, CircleCI).

Outro ponto é a capacidade de usar os próprios agentes do GitHub, eliminando a necessidade de criar ambientes personalizados para executar nossos fluxos de CI/CD. Isso acelera a configuração e execução dos workflows, além de reduzir os custos de implantação, já que a infraestrutura necessária está pronta para uso.

## GitHub Actions: O que é?

GitHub Actions é uma popular plataforma de integração contínua e entrega contínua (CI/CD). Com isso, desenvolvedores podem programar tarefas repetitivas enquanto reduzem a intervenção manual.

GitHub Actions é montada em cima de um arquivo YAML, descrevendo assim diferentes etapas do workflow. Estas etapas (steps) incluem rodar um script, testar, fazer um deploy ou mandar notificações.

### Componentes do GitHub Actions
Como trata-se de uma plataforma de CI/CD, a mesma é formada por alguns componentes descritos na documentação, sendo eles:

 - **Workflow**: É onde vamos descrever todo o processo de automação para podermos compilar, testar e fazer deploy do nosso sistema;
 - **Events**: É uma atividade em particular que "dispara" um Workflow. Pode ser um push, uma PR ou até mesmo uma nova issue;
 - **Jobs**: Job é a etapa que compoem um Workflow. Eles são executas em um mesmo Runner;
 - **Action**: ;
 - **Runner**: É a máquina responsável por executar o workflow e as actions e nos prover o feedback do nosso processo. O Runner pode ser o GitHub-hosted, provido pelo próprio time ou self-hosted runner, onde você é responsável por gerenciar o servidor e os serviços instalados nele;

### Principais features da plataforma:

Nos próximos tópicos vamos listar algumas features interessantes da plataforma.

### Variáveis em Workflows

Lorem Ipsum is simply dummy text of the printing and typesetting industry.

### Adição de Scripts ao Workflow

Lorem Ipsum is simply dummy text of the printing and typesetting industry.

### Compartilhando informações entre Jobs

Lorem Ipsum is simply dummy text of the printing and typesetting industry.

### Criando nossa primeira pipeline no GitHub Actions

Lorem Ipsum is simply dummy text of the printing and typesetting industry.

### Iniciando configurações

### Rodando os arquivos

________
### Repositórios Relacionados

Dois mini projetos foram criados para simular o fluxo de desenvolvimento e testar o uso das actions:

 - [Frontend Angular](https://github.com/biduco07/IFMT-Devops-AOMS);
 - [Backend NestJs](https://github.com/tonkunz/ifmt-articles-api);

### Ferramentas Utilizadas

 - [Angular](https://angular.dev/);
 - [NestJs](https://nestjs.com/);
 - [Heroku](https://dashboard.heroku.com/);
 - [Railway](https://railway.app/);
 - [Prisma](https://www.prisma.io/);

 ### Membros da atividade

- André Luiz Rabello da Silva;
- Everton Henrique Oliveira Kunz;
- João André Ferreira de Almeida;
- Pedro Henrique Veloso de Melo;
- Thiago Nascimento da Silva;