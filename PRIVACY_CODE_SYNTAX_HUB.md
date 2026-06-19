# Política de Privacidade - Code Syntax Hub

**Última atualização:** Junho de 2026

[**Code Syntax Hub** - Chrome Web Store](https://chromewebstore.google.com/detail/neojcaeeoommblkjjdcalokledibfimn?utm_source=item-share-cb)

Esta Política de Privacidade descreve como o **Code Syntax Hub** ("nós", "nosso" ou "a extensão") lida com as informações e dados dos usuários. Nós levamos a sua privacidade a sério e operamos sob o princípio do **uso mínimo de dados e processamento estritamente local**.

Ao instalar e usar o Code Syntax Hub, você concorda com as práticas descritas nesta política.

---

## 1. Coleta e Uso de Informações

O Code Syntax Hub é uma ferramenta utilitária de produtividade para desenvolvedores. 

* **Nenhum Dado Pessoal é Coletado:** Nós não coletamos, não solicitamos, não rastreamos e não armazenamos nenhuma informação de identificação pessoal (como nome, e-mail, endereço ou dados de conta).
* **Nenhum Dado de Navegação é Monitorado:** A extensão não rastreia o seu histórico de navegação, cookies ou comportamento em páginas HTML comuns. A extensão atua de forma estritamente reativa, agindo apenas quando detecta que a página corrente é um arquivo bruto de JSON, JavaScript ou CSS.
* **Segurança de Payloads e APIs:** Todo o processamento de código, formatação (*pretty print*) e coloração de sintaxe (*syntax highlighting*) ocorrem de forma **100% local e isolada** na memória do seu próprio navegador. O conteúdo dos seus arquivos ou respostas de APIs nunca é lido por nós, transferido ou exposto.

---

## 2. Armazenamento e Persistência Local

Para entregar uma experiência personalizada e consistente, a extensão utiliza a API de armazenamento local do navegador (`chrome.storage.local` ou `localStorage`). Os únicos dados salvos de forma persistente são as suas preferências de interface:

1. **Preferências de UI:** O tema visual selecionado (Dark Mode ou Light Mode) e o tamanho da fonte (padrão 18px).
2. **Configurações de Monitoramento Global:** O estado das caixas de seleção do menu pop-up (se o monitoramento automático para JSON, JS ou CSS está ativado ou desativado).
3. **Lista de Bloqueio Local (Blacklist):** O mapeamento de domínios e tipos de arquivos específicos nos quais você clicou para ignorar o funcionamento da extensão.

> 🔒 **Nota de Segurança:** Todos esses dados de configuração permanecem armazenados localmente no seu dispositivo. Eles não são sincronizados com servidores externos e são totalmente apagados caso você desinstale a extensão.

---

## 3. Transferência e Compartilhamento de Dados com Terceiros

* **Venda de Dados:** Nós **nunca** vendemos, alugamos, trocamos ou transferimos qualquer dado de usuário para terceiros.
* **Código Remoto:** Em total conformidade com as diretrizes do Manifest V3 da Chrome Web Store, o Code Syntax Hub não faz uso de scripts, bibliotecas ou códigos hospedados remotamente. Todo o ecossistema da extensão é auto-contido em seu pacote local.

---

## 4. Permissões do Manifesto e Suas Justificativas

Para executar suas funções de forma transparente, a extensão declara e justifica o uso das seguintes permissões:

* **`storage`:** Necessária unicamente para salvar localmente suas preferências de tema, tamanho de fonte e lista de sites ignorados.
* **`activeTab`:** Utilizada temporariamente para conceder permissão segura às ações disparadas por você no cabeçalho (como copiar o código ou baixar o arquivo formatado).
* **Permissões de Host (`<all_urls>` ou regras globais):** Necessária porque payloads de APIs (JSON) e arquivos de desenvolvimento (JS/CSS) podem ser servidos a partir de qualquer servidor, subdomínio ou porta local (ex: localhost) na internet. O script utiliza esse acesso para checar o cabeçalho `Content-Type` e decidir se deve ou não aplicar a interface de formatação.

---

## 5. Alterações nesta Política de Privacidade

Podemos atualizar nossa Política de Privacidade periodicamente para refletir melhorias na extensão ou mudanças nas diretrizes das lojas de navegadores. Recomendamos que você revise esta página ocasionalmente para se manter informado.

---

## 6. Contato

Se você tiver alguma dúvida, feedback ou preocupação sobre as práticas de privacidade desta extensão, sinta-se à vontade para abrir uma *Issue* diretamente neste repositório do GitHub.
