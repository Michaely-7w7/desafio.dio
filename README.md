# 🛡️ Desafio de Cibersegurança: Entendendo Ataques de Phishing com SEToolkit

## 📝 Descrição do Projeto
Este projeto tem como objetivo documentar o funcionamento teórico da ferramenta **SEToolkit** (Social-Engineer Toolkit) no Kali Linux. O foco principal é compreender a lógica por trás de ataques de engenharia social (phishing) e como podemos nos proteger contra eles.

---

## 🎯 Conceito Chave: O que é Engenharia Social?
A engenharia social é uma técnica de ataque focada no **fator humano**. Em vez de tentar quebrar senhas complexas ou invadir sistemas diretamente, o atacante tenta enganar a vítima para que ela própria forneça informações confidenciais (como logins e senhas).

---

## ⚙️ Como o SEToolkit Funciona (Passo a Passo Teórico)

O processo de simulação de phishing utilizando o **SEToolkit** divide-se em três etapas principais:

### 1. Seleção do Vetor de Ataque
* O usuário escolhe a opção de **Ataques de Engenharia Social** (*Social-Engineering Attacks*).
* Em seguida, seleciona **Vetores de Ataque a Sites** (*Website Attack Vectors*).

### 2. Clonagem da Página (A "Isca")
* Escolhe-se o método de **Coleta de Credenciais** (*Credential Harvester Attack Method*).
* O SEToolkit cria uma cópia idêntica (réplica) de um site conhecido (por exemplo, a página de login do Facebook).
* A vítima acessa esse site falso pensando ser a página oficial.

### 3. Captura dos Dados
* O sistema solicita o endereço IP da máquina do atacante.
* Quando a vítima digita o seu usuário e senha na página clonada, os dados são enviados diretamente para a máquina configurada e exibidos na tela.

---

## 🛡️ Como se Proteger (Mitigação)

Para evitar cair em ataques do tipo phishing, é fundamental seguir estas recomendações:
* **Verificar sempre a URL:** Confirmar na barra do navegador se o endereço do site é o oficial.
* **Autenticação de Dois Fatores (2FA):** Ativar a verificação em duas etapas em todas as contas.
* **Atenção a Links Suspeitos:** Não clicar em links recebidos por e-mail ou mensagens não solicitadas.

---

> *Projeto desenvolvido para fins educacionais no âmbito da plataforma DIO.*
