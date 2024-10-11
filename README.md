# Computação na Nuvem critérios de disponibilidade **SLA**(Service Level Agreement)

Os acordos de disponibilidades variam de acordo com o serviço e podem ser consultados na documentação [nesse link](https://www.microsoft.com/licensing/docs/view/Service-Level-Agreements-SLA-for-Online-Services?lang=1) vc encontrará o doc com as mais recentes niveis **SLA**.

## Quanto ao armazenamento

A alta disponibilidade em um serviço de armazenamento vai depender da redundancia que servira como ação de alteração de zona, região, rota de rede, ou até mesmo para outro disco fisico para que a disponibilidade continue, todos esses serviços podem ser selecionado na criação do armazenamento.

## Qual disponibilidade tem a VM

A criação da VM pode inserir disponibilidade de ZONA e em caso de inserir 3 zonas será sugerido a configuração do balanceamento de carga da utilização de cada zona com base na utilização ou agendamento.

## E o custo.

Todo aumento na disponibilidade (**SLA**) de utilização dos serviços vão implicar diretamente no aumento do custo, sendo assim, este assunto sempre é delicado ao se adquirir, devido primeiramente ao mau planejamento e dimensionamento de uma aplicação, para disponibilizar aderir a um recurso não será facil de propor.

## Benefícios da Nuvem

- *Escalabilidade*: Ajustar o recurso a necessidade.
- *Elasticidade*: Ajusta o recurso para aumento de consumo repentino exemplo: ****BlackFriday****.
- *Confiabilidade*: redundância a falhas, descentralizado, suporte acessivel e facil.
- *Previsibilidade*: prever e garantir o desempenho e a disponibilidade dos serviços em nuvem.
- *Segurança*: os mais atuais e sofisticados metodos de garantia de autenticação segura e integridade dos dados. **Resalva: dependem de serem bem configurados e gerenciados**. 
- *Governança*: A governança na nuvem permite processos e fluxos de trabalho automatizados, eficiencia que implica redução de custos e segurança.
