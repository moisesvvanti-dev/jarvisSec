# Jarvis OS - Red Team & Pentest Assistant

Bem-vindo ao **Jarvis OS**, seu assistente de inteligência artificial autônomo focado em Operações de Red Team, Penetration Testing e Offensive Security. 

Este projeto não é um simples chatbot. É um agente ativo que executa comandos reais, se conecta a ferramentas de desenvolvimento e pesquisa falhas na sua rede e sistema.

## 🚀 Principais Funcionalidades

1. **Ações Reais e Autônomas:**
   - Jarvis não apenas "fala", ele **age**. Se você pedir para buscar uma vulnerabilidade, ele vai rodar scripts, usar bibliotecas Python e pesquisar no GitHub repositórios atualizados para executar a tarefa.
   - Integração total com o sistema operacional: consegue criar arquivos, ler diretórios, listar processos e modificar configurações se autorizado.

2. **Persona Cyberpunk / Mr. Robot:**
   - Respostas precisas, táticas e sem enrolação. Ele fala com você como um operador de campo reportando para o centro de comando.

3. **Integração com Ferramentas MCP (Model Context Protocol):**
   - **🌐 Web Fetcher:** Lê páginas web, baixa repositórios, analisa códigos e converte HTML para visualização direta do terminal.
   - **🗄️ SQLite Database:** Conecta-se diretamente a bancos de dados SQLite para auditar tabelas e buscar informações sensíveis ou hashes de senha vazados.
   - **🔍 Windows Everything Search:** Vasculha seu disco rígido inteiro em milissegundos para encontrar chaves privadas, arquivos de configuração perdidos, backups esquecidos e logs.

4. **100% Nativo em Python (Zero Node.js):**
   - Para maximizar a compatibilidade com sistemas voltados para hacking, todas as ferramentas externas agora rodam em cima do ecossistema Python nativo utilizando a biblioteca `uv` e `uvx`, removendo a necessidade de instalar Node e Npm.

5. **Interface Premium e Sombria (Disney+ / Glassmorphism):**
   - Interface sem bordas padrão do Windows.
   - Cantos arredondados, fundo translúcido (efeito blur) com sombreamento em neon azul.
   - Totalmente pensado para passar a sensação de um terminal moderno e avançado.

## 🛠️ Como Funciona o Fluxo

1. Você fala com o Jarvis por **voz** ou via **texto** (pela interface gráfica bonita).
2. Ele escuta, processa usando Modelos Locais ou Remotos configurados (ex: `gemma`, `llama`) e raciocina sobre os melhores passos para o Pentest.
3. Se precisar baixar um script do Github, o Jarvis usará suas "mãos" (Web Fetcher / Python requests) para varrer os repositórios mais recentes do dia, baixá-los e reportar a você em voz alta tudo o que encontrou.
4. Por fim, ele descreve sua ação pelo rádio (alto-falante), falando a resposta de maneira estratégica.

## ⚠️ Disclaimer e Ética

Este assistente foi programado para atuar em ambientes **autorizados** e para testes de segurança defensivos (Blue Team / Purple Team) ou Red Team legalmente comissionado. Use com sabedoria!
