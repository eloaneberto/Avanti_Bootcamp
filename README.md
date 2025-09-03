Anotações – Laboratório AWS (EC2)
Objetivo do laboratório

Consolidar conhecimentos em gerenciamento de instâncias EC2 na AWS.

Produzir um repositório organizado com anotações e insights adquiridos.

Servir como material de apoio para estudos e futuras implementações.


Pontos principais (EC2 – Elastic Compute Cloud)

Serviço que fornece máquinas virtuais escaláveis na nuvem.

Permite configurar:

Tipo de instância (capacidade de CPU, memória, armazenamento, rede).

Sistema operacional (Linux, Windows, etc.).

Armazenamento (EBS, volumes adicionais).

Segurança (grupos de segurança, regras de firewall, chaves SSH).

Boas práticas aprendidas no laboratório

Criar e gerenciar pares de chaves (key pairs) para acesso seguro.

Definir grupos de segurança de acordo com a necessidade mínima de portas abertas (princípio do menor privilégio).

Monitorar a instância com CloudWatch.

Organizar com tags para facilitar gerenciamento e billing.


Insights adquiridos

A EC2 é o coração da AWS para computação: quase todo projeto usa em algum momento.

Escalabilidade: é possível iniciar instâncias sob demanda e encerrar quando não são mais necessárias, otimizando custos.

Flexibilidade: diferentes AMIs (Amazon Machine Images) permitem ambientes prontos para uso (ex: Ubuntu, Amazon Linux, Windows Server).

Custos: sempre encerrar instâncias ao final do laboratório para evitar cobranças desnecessárias.