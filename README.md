# Azue-vm-lab

# Laboratório: Máquinas Virtuais na Azure ☁️

Este repositório documenta a experiência prática de criação e gerenciamento de uma Máquina Virtual (VM) no Microsoft Azure. O objetivo é consolidar os conhecimentos teóricos sobre infraestrutura em nuvem com foco em IaaS (Infraestrutura como Serviço).

## 🧠 Objetivos do Laboratório

- Criar uma VM no portal do Azure
- Configurar opções como SO, tamanho e autenticação
- Acessar a VM remotamente (SSH ou RDP)
- Instalar e rodar algum serviço ou aplicação simples
- Documentar o processo de forma clara

## 🛠️ Tecnologias Utilizadas

- Microsoft Azure
- Ubuntu Server 20.04 (imagem da VM)
- SSH para acesso remoto
- GitHub para versionamento e documentação

## 📌 Etapas Realizadas

1. Acesso ao portal do Azure
2. Criação de um grupo de recursos
3. Criação da Máquina Virtual (Ubuntu)
4. Configuração de regras de entrada (porta 22 para SSH)
5. Acesso via terminal usando chave SSH
6. Instalação de pacote (ex: Apache ou Nginx)
7. Testes de funcionamento

## 📸 Capturas de Tela

### Criação da VM
![Criação da VM](/imagens/criacao-vm.png)

### Configuração de rede/firewall
![Configuração de rede](/imagens/config-firewall.png)

### Acesso remoto via SSH
![Acesso via SSH](/imagens/acesso-ssh.png)

### Página padrão do Apache após instalação
![Apache rodando](/imagens/result-finish.png)

## 📁 Estrutura do Projeto

```plaintext
azure-vm-lab/
├── README.md
├── images/
│   ├── criacao-vm.png
│   ├── acesso-ssh.png
│   └── resultado-final.png
