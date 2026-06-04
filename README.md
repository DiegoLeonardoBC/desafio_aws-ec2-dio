# Gerenciando Instâncias EC2 na AWS

## Descrição do Projeto

Este repositório foi desenvolvido como parte do desafio prático do Bootcamp **GFT - Fundamentos de Cloud com AWS**, oferecido pela DIO.

O objetivo deste laboratório foi consolidar os conhecimentos adquiridos sobre computação em nuvem e os principais serviços da AWS, com foco na criação, configuração e gerenciamento de instâncias EC2.

---

## Objetivos de Aprendizagem

* Compreender os conceitos fundamentais da computação em nuvem.
* Conhecer a infraestrutura global da AWS.
* Configurar uma conta AWS de forma segura.
* Aplicar boas práticas de controle de acesso e custos.
* Criar e gerenciar instâncias EC2.
* Utilizar serviços de armazenamento como Amazon EBS e Amazon S3.
* Documentar experiências técnicas utilizando GitHub.

---

## Introdução à AWS e ao Universo da Computação em Nuvem

A computação em nuvem permite o fornecimento de recursos de tecnologia sob demanda pela internet, eliminando a necessidade de grandes investimentos em infraestrutura física.

Principais benefícios:

* Escalabilidade
* Elasticidade
* Alta disponibilidade
* Redução de custos
* Segurança
* Pagamento conforme o uso

A Amazon Web Services (AWS) é uma das maiores plataformas de computação em nuvem do mundo, oferecendo centenas de serviços para empresas e profissionais de tecnologia.

---

## Fundamentos Essenciais da Infraestrutura AWS

A infraestrutura AWS é organizada em:

### Regiões (Regions)

São áreas geográficas onde a AWS mantém seus datacenters.

Exemplo:

* us-east-1 (Norte da Virgínia)
* sa-east-1 (São Paulo)

### Zonas de Disponibilidade (Availability Zones)

Cada região possui uma ou mais zonas de disponibilidade independentes, garantindo alta disponibilidade e redundância.

### Edge Locations

Utilizadas para acelerar a entrega de conteúdo através de serviços como CloudFront.

---

## Configurando sua Conta AWS com Segurança e Eficiência

Durante a configuração da conta AWS, foram abordadas práticas essenciais de segurança:

### Boas Práticas

* Utilização de MFA (Autenticação Multifator)
* Proteção da conta Root
* Criação de usuários administrativos através do IAM
* Uso do princípio do menor privilégio

### IAM (Identity and Access Management)

Serviço responsável pelo gerenciamento de:

* Usuários
* Grupos
* Funções
* Políticas de acesso

---

## Primeiros Passos com Acesso Seguro e Controle de Custos

Para evitar cobranças inesperadas, foram estudados mecanismos de controle financeiro.

### Ferramentas Utilizadas

* AWS Billing Dashboard
* AWS Cost Explorer
* AWS Budgets

### Benefícios

* Monitoramento de gastos
* Definição de alertas
* Planejamento financeiro

---

## Entendendo as Instâncias EC2 e a Otimização de Recursos AWS

O Amazon EC2 (Elastic Compute Cloud) permite criar servidores virtuais na nuvem.

### Principais Componentes

* AMI (Amazon Machine Image)
* Tipo de Instância
* Chave de Acesso (Key Pair)
* Security Groups
* Rede (VPC)

### Estados de uma Instância

* Pending
* Running
* Stopping
* Stopped
* Terminated

### Vantagens

* Escalabilidade
* Flexibilidade
* Pagamento sob demanda
* Implantação rápida

---

## Armazenamento na Nuvem com Amazon EBS e S3

### Amazon EBS (Elastic Block Store)

Serviço de armazenamento em blocos utilizado junto às instâncias EC2.

Características:

* Alta performance
* Persistência dos dados
* Possibilidade de snapshots

### Amazon S3 (Simple Storage Service)

Serviço de armazenamento de objetos utilizado para:

* Backups
* Arquivos
* Sites estáticos
* Compartilhamento de documentos

Benefícios:

* Alta durabilidade
* Escalabilidade praticamente ilimitada
* Integração com diversos serviços AWS

---

## Gerenciando Instâncias EC2 na AWS

Durante o laboratório foram executadas atividades relacionadas ao gerenciamento de instâncias.

### Atividades Realizadas

* Criação de uma instância EC2
* Configuração de Security Groups
* Criação e utilização de Key Pair
* Inicialização da instância
* Parada da instância
* Reinicialização da instância
* Encerramento da instância

### Conceitos Importantes

#### Security Groups

Funcionam como um firewall virtual, controlando o tráfego de entrada e saída das instâncias.

#### Key Pair

Utilizada para autenticação segura no acesso às instâncias Linux via SSH.

#### Monitoramento

A AWS oferece monitoramento através do CloudWatch para acompanhamento de desempenho e utilização de recursos.

---

## Aprendizados Obtidos

Durante este desafio, foi possível compreender de forma prática:

* O funcionamento da infraestrutura AWS.
* A importância da segurança em ambientes de nuvem.
* Como controlar custos utilizando ferramentas nativas da AWS.
* O processo de criação e gerenciamento de servidores virtuais através do EC2.
* As diferenças entre armazenamento em blocos (EBS) e armazenamento de objetos (S3).
* A importância do gerenciamento eficiente de recursos em ambientes cloud.

---

## Conclusão

A realização deste laboratório proporcionou uma visão prática dos principais conceitos da computação em nuvem utilizando AWS.

Os conhecimentos adquiridos servem como base para aprofundamento em serviços mais avançados da plataforma, contribuindo para a formação profissional em Cloud Computing e Arquitetura de Soluções.

---

## Referências

* Documentação Oficial da AWS
* AWS EC2 User Guide
* AWS IAM Documentation
* AWS S3 Documentation
* AWS EBS Documentation
* Bootcamp GFT - Fundamentos de Cloud com AWS
