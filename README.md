# resumo-do-lab-computaco-rede
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

# O que eu Aprendi sobre Arquitetura e Serviços do Microsoft Azure (AZ-900)

Continuando meus estudos para a certificação AZ-900, aprofundei-me na arquitetura e nos serviços principais do Microsoft Azure. Estes são os principais conceitos que aprendi:

## Computação e Rede

### Tipos de Computação
No Azure, temos vários tipos de computação que se adaptam a diferentes necessidades:
- **Máquinas Virtuais (VMs)**: Emulações de computadores físicos, proporcionando controle total sobre hardware e software. Ideal para migrações diretas para a nuvem.
- **Conjuntos de Dimensionamento de VMs**: Escalam automaticamente as VMs de acordo com a demanda, aumentando ou reduzindo os recursos conforme necessário.
- **Área de Trabalho Virtual do Azure**: Virtualização de desktops que permite ambientes de trabalho acessíveis remotamente, reduzindo a necessidade de infraestrutura local.
- **Contêineres**: Ambientes leves e escaláveis, perfeitos para microsserviços e aplicações distribuídas.
- **Azure Kubernetes Service (AKS)**: Serviço de orquestração de contêineres para gerenciar grandes volumes de contêineres em arquiteturas complexas.
- **Azure Functions**: Computação sem servidor, executando código em resposta a eventos, sem a necessidade de servidores em tempo ocioso.

### Serviços de Aplicativo
Os **Serviços de Aplicativo do Azure** oferecem uma plataforma para criar, implantar e escalar aplicativos e APIs com alta segurança e desempenho. Compatível com várias linguagens, como .NET, Java e Python.

## Serviços de Rede

### Rede Virtual (VNet)
As **Redes Virtuais (VNet)** no Azure permitem a comunicação entre recursos do Azure, redes locais e a Internet. As VNets suportam:
- **Pontos de Extremidade Públicos**: Acessíveis de qualquer lugar.
- **Pontos de Extremidade Privados**: Acessíveis apenas internamente.

### Gateways e Conexões
- **Gateway de VPN**: Envia tráfego criptografado entre uma VNet do Azure e uma rede local.
- **ExpressRoute**: Conexão privada e segura entre redes locais e o Azure, sem passar pela Internet pública.

### DNS do Azure
O **DNS do Azure** oferece uma solução gerenciada para usar nomes de domínio personalizados nas redes virtuais, com segurança e monitoramento integrados, e suporte para registros de alias, permitindo apontar diretamente para recursos do Azure.

---

Esses conceitos são essenciais para entender a infraestrutura de computação e rede do Azure, ajudando a otimizar o uso da nuvem para diferentes necessidades e requisitos empresariais.
