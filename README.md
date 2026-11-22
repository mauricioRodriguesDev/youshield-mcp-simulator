# YouShield MCP - Protótipo Funcional

> Projeto desenvolvido para o Desafio Técnico do **Programa de Estágio YouShop 2027**.  
> **Trilha:** Desenvolvimento: Integrações com Agentes de IA (MCP)  
> **Candidato:** Mauricio Rodrigues Alves Raquel  

---

## 🌐 Demonstração Online (GitHub Pages)

A simulação pode ser testada diretamente no navegador sem necessidade de instalação:

👉 **[Acessar a Simulação Online](https://SEU_USUARIO.github.io/SEU_REPOSITORIO/)**  
*(Substitua a URL acima pelo link do seu GitHub Pages)*

---

## 📌 Sobre a Aplicação

Este protótipo demonstra em tempo real como o **Model Context Protocol (MCP)** conecta agentes de IA às APIs de e-commerce e pagamentos da YouShop, garantindo atendimento ágil e auditoria determinística.

A aplicação foi construída com **HTML5, CSS3 e JavaScript puro (Vanilla JS)**, sem frameworks ou dependências externas, garantindo execução leve e imediata em qualquer navegador.

### Principais Módulos da Simulação:

1. **Copiloto de Atendimento (Suporte Assistido):** Simula a resolução de chamados frequentes (falhas de envio de acesso a cursos, dúvidas de comissões de afiliados) acionando ferramentas MCP e mantendo supervisão humana (*Human-in-the-Loop*).
2. **Monitor de Transações e Risco:** Analisa lotes de eventos de checkout e tráfego de links de afiliação, identificando anomalias e prevenindo contestações/chargebacks.
3. **Inspetor JSON-RPC (MCP):** Exibe os schemas, contratos de entrada e respostas das ferramentas do servidor MCP (`get_transaction_audit`, `verify_affiliate_attribution`, `check_content_delivery`).

---

## 🚀 Como Executar Localmente

Caso prefira rodar o projeto localmente na sua máquina:

### Opção 1: Execução Direta
1. Clone ou baixe este repositório.
2. Dê um duplo clique no arquivo `index.html` (ou clique com o botão direito e selecione seu navegador de preferência: Chrome, Edge, Firefox ou Safari).

### Opção 2: Servidor Local (Opcional)
Se preferir servir via HTTP local:

```bash
# Com Python 3
python -m http.server 8000

# Ou com Node.js
npx serve
```
Em seguida, abra o navegador e acesse: `http://localhost:8000`.

---

## 🛠️ Tecnologias Utilizadas

- **Frontend:** HTML5 semântico, CSS3 moderno (Flexbox/Grid), JavaScript ES6+ (Vanilla JS).
- **Arquitetura de IA:** Model Context Protocol (MCP) com contratos tipados JSON-RPC 2.0.
- **Padrão de Segurança:** Human-in-the-Loop para ações financeiras e mascaramento de dados sensíveis (LGPD).

---

## 👨‍💻 Contato do Candidato

- **Nome:** Mauricio Rodrigues Alves Raquel  
- **E-mail:** [mauriciorodrigues.dev94@gmail.com](mailto:mauriciorodrigues.dev94@gmail.com)  
- **LinkedIn:** [linkedin.com/in/mauriciorodrigues-exe](https://linkedin.com/in/mauriciorodrigues-exe)  
- **GitHub:** [github.com/mauricioRodriguesDev](https://github.com/mauricioRodriguesDev)  
