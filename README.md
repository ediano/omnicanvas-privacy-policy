# Omnihub Chromium Suite 🚀

Bem-vindo ao repositório central de governança, conformidade e políticas de privacidade das extensões desenvolvidas para o ecossistema global **Chromium** (atendendo a navegadores como Google Chrome, Microsoft Edge, Brave, Vivaldi, Opera e demais navegadores baseados nesta arquitetura).

Este repositório público atua como a central oficial de transparência exigida pelas diretrizes do **Google Chrome Web Store Developer Program** e lojas correlatas, estando diretamente integrado e autenticado sob o nosso projeto unificado de credenciais no Google Cloud Platform (GCP) para automação de deploys.

---

## 🔒 Hub de Políticas de Privacidade (Privacy Policies)

Para garantir o cumprimento estrito das políticas de **Uso Mínimo de Dados e Processamento Local**, cada extensão desenvolvida possui um documento de governança e privacidade dedicado, detalhando suas respectivas finalidades, permissões declaradas no Manifesto (V3) e escopo de atuação dentro dos navegadores baseados em Chromium.

Selecione a extensão abaixo para acessar sua respectiva Política de Privacidade:

*   [**Code Syntax Hub** - Política de Privacidade](./PRIVACY_CODE_SYNTAX_HUB.md) — *Formatador e visualizador inteligente de código (JSON, JS e CSS).*
*   [**Omni Canvas Privacy** - Política de Privacidade](./PRIVACY_OMNICANVAS_PRIVACY.md) — *Ferramenta avançada de privacidade corporativa e conformidade de telas.*

> 💡 **Nota para Revisores e Analistas de Lojas (Chromium Ecosystem):** Este repositório é atualizado dinamicamente à medida que novas ferramentas utilitárias são integradas à nossa suíte de extensões. Todos os nossos produtos seguem a premissa de processamento 100% em nível de cliente (*client-side*), com zero coleta ou transmissão de dados para servidores externos.

---

## 🛠️ Diretrizes de Governança para Novas Extensões

Sempre que uma nova extensão for acoplada a este ecossistema Chromium, a estrutura de privacidade deve seguir o seguinte padrão de governança:
1. Criação de um arquivo de privacidade isolado na raiz do projeto seguindo a nomenclatura `PRIVACY_NOME_DA_EXTENSAO.md`.
2. Vinculação do link direto do arquivo Markdown (visualização pública do GitHub) na guia correspondente às políticas de privacidade de dados do painel de desenvolvedor.
3. Atualização do índice acima neste arquivo `README.md`.

---

## 📄 Licença e Termos

O uso das ferramentas mapeadas neste repositório rege-se pelos termos locais estabelecidos em cada uma das extensões individuais. Para dúvidas de segurança ou reporte de vulnerabilidades, por favor abra uma *Issue* diretamente neste repositório.
