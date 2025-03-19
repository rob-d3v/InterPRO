---
<meta name="google-site-verification" content="wMGRH6KboHDuFVs3paIcO03t6KYZjwIhEG-uzqcjxq0" />
Sistema de Internacionalização de Interfaces de Software

![Versão](https://img.shields.io/badge/versão-2025.03.06.10-blue)
![Plataforma](https://img.shields.io/badge/plataforma-Windows%20%7C%20Linux%20%7C%20MacOS-lightgrey)


## 📋 Visão Geral

O InterPRO é uma ferramenta definitiva para internacionalização de software, revolucionando a maneira como você adapta suas interfaces para diferentes idiomas e culturas. Transforme sua aplicação em uma solução verdadeiramente global com nossa plataforma completa de internacionalização, agora potencializada com Inteligência Artificial.

![InterPRO Interface](images/screenshot.png)
<!-- Imagem da interface do InterPRO mostrando o painel principal com opções de coleta de strings, internacionalização e o guia de utilização -->

## ✨ Recursos Principais

- **Suporte Multilinguagem**: Compatível com diversas linguagens de Programação, Marcação e Documentação
- **Flexibilidade Multiplataforma**: Windows, Linux e Mac OS
- **Motor de Regex Avançado**: Identificação e substituição de palavras e textos
- **Sistema de Sincronização Inteligente**: Integração perfeita com sua estrutura de internacionalização existente
- **Integração CI/CD**: Interação com sistemas de Integração Contínua/Entrega Contínua
- **Tradutor Automático**: Suporte a mais de 100 idiomas para traduções rápidas
- **Automação de Testes**: Sistema inovador de Auto-Run para testes unitários (em breve)
- **🆕 Coleta de Textos com IA**: Identificação inteligente de conteúdo para internacionalização utilizando API de modelos de inteligência artificial
- **🆕 Tradução Avançada com IA**: Traduções de alta qualidade preservando contexto e nuances culturais via API

## 🚀 Começando

### Pré-requisitos

- Java Runtime Environment (JRE) 17 ou superior (Com Instalador Windows não é necessário, está imbutido)
- Conexão com a internet para recursos de tradução online

### Instalação

#### Windows
1. Baixe o instalador `setup.exe` da página de releases (link será disponibilizado)
2. Execute o instalador e siga as instruções na tela
3. Lance o InterPRO a partir do menu Iniciar ou do atalho na área de trabalho

#### Linux
1. Certifique-se de que o Java 17 ou superior está instalado
2. Baixe o arquivo JAR da página de releases (link será disponibilizado)
3. Execute com:
   ```bash
   java --enable-preview --module-path lib/ --add-modules  javafx.controls,javafx.fxml,javafx.graphics,javafx.base,javafx.swing -jar InterPRO.jar
   ```

#### macOS
1. Certifique-se de que o Java 17 ou superior está instalado
2. Baixe o arquivo JAR da página de releases (link será disponibilizado)
3. Execute com:
   ```bash
   java --enable-preview --module-path lib/ --add-modules  javafx.controls,javafx.fxml,javafx.graphics,javafx.base,javafx.swing -jar InterPRO.jar
   ```

## 💡 Como Usar

### Guia de Utilização

1. Selecione as opções desejadas nos painéis à esquerda
2. Clique em "Coletar Strings" para retirar as strings do seu projeto e deixar uma referência
3. Com o arquivo de Strings coletadas pronto, crie outros em vários idiomas, clique em "Internacionalizar"
4. Implemente um sistema para utilizar os arquivos de referência em seu projeto, ou baixe no repositório GitHub oficial do InterPRO

### Painéis de Configuração

- **Configurações**: Ajuste as preferências gerais do aplicativo
- **Diretórios**: Defina os diretórios que deseja incluir na coleta de strings
- **Arquivos Ignorados**: Especifique arquivos que devem ser excluídos da análise
- **Padrões Ignorados**: Configure padrões de texto que não devem ser coletados
- **Padrões Aceitos**: Defina os padrões de texto que devem ser considerados para internacionalização

## 🧠 Recursos de IA

### Coleta Inteligente de Textos

O InterPRO agora utiliza o modelo Claude 3.7 Sonnet para identificar com precisão textos que precisam ser internacionalizados, incluindo:

- Identificação contextual de strings em código-fonte
- Reconhecimento de mensagens culturalmente específicas
- Diferenciação entre textos que devem ser traduzidos e termos técnicos que devem permanecer inalterados
- Sugestão de contextos e comentários para tradutores

### Tradução Contextual Avançada

Nosso novo sistema de tradução com IA oferece:

- Traduções que preservam o tom e contexto do original
- Adaptação cultural de expressões idiomáticas
- Consistência terminológica em todo o projeto
- Suporte para terminologia técnica específica do domínio
- Manutenção da formatação e estilos no texto traduzido

## 🧩 Exemplos de Regex por Linguagem

Neste repositório serão adicionados exemplos de expressões regulares (regex) para cada linguagem de programação, marcação ou documentação suportada pelo InterPRO. Isso permitirá a identificação e extração eficiente de strings para internacionalização em diferentes contextos de desenvolvimento.

Os exemplos de regex serão organizados por linguagem e incluirão padrões otimizados para:
- Captura de strings literais
- Textos em componentes de interface
- Mensagens de log/erro
- Conteúdo de documentação

## 🔌 Exemplos de Implementação

Este repositório também será atualizado com exemplos completos de implementação para integração do sistema de internacionalização em diferentes plataformas e frameworks, incluindo:

- Implementações para carregamento e gerenciamento de arquivos de tradução
- Implementação de seletores de idioma
- Métodos para detecção automática de idioma do usuário
- Integração com frameworks populares

Cada exemplo será fornecido com documentação detalhada e instruções de uso.

## 📚 Documentação

A documentação completa, incluindo tutoriais detalhados e guias de implementação, será disponibilizada futuramente neste repositório. Por enquanto, consulte o guia básico de utilização incluído na aplicação.

## 🔄 Modos e Planos

O InterPRO oferece diferentes modos de uso:

### Modo Gratuito
- Consegue fazer tudo exceto recursos de IA, (delay proposital e idiomas limitados mensais)

### Benefícios para Doadores
- Escaneamento rápido de strings
- Tradutor automático super rápido e rodando traduções em paralelo
- Acesso antecipado a novos recursos
- 🆕 Acesso aos recursos de IA com Claude 3.7 Sonnet (baseado em pontos de doação)
- 🆕 Coleta inteligente de textos com IA
- 🆕 Tradução avançada com preservação de contexto e nuances culturais
- 🆕 Processamento em lote de múltiplos idiomas simultaneamente
- 🆕 Exportação de glossários(tags) e memórias de tradução criados pela IA

## 🔄 Sistema de Pontos de Doação

O InterPRO utiliza um sistema de pontos de doação para acesso aos recursos avançados:

### Como Obter Pontos
- Doações diretas via PIX, cartão ou BTC (1 real = 1 ponto) (Valores poderão ter mudança após lançamento oficial/comercial da aplicação)
- Contribuições para o projeto (correções de bugs, melhorias, traduções)
- Participação ativa na comunidade 
- Indicação

Os pontos não expiram e podem ser acumulados ao longo do tempo. 
## 📄 Documentos Importantes

- [Política de Privacidade](privacy-policy.html)
- [Termos de Serviço](terms-of-service.html)

## 🙏 Agradecimentos

O InterPRO é um projeto independente desenvolvido por robd3v, mantido por meio de doações da comunidade. Agradecemos a todos os apoiadores que tornaram este projeto possível.

## 📞 Contato

- Desenvolvedor: Robson Pereira (robd3v)
- Email: robs.eng@outlook.com
- Discord: [Em breve]

© 2025 InterPRO. Todos os direitos reservados.# InterPRO