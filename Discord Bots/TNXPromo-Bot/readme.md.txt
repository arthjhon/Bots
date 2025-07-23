# 🔎 TNXPromo

**TNXPromo** é um bot que monitora automaticamente sites de ofertas e promoções na internet, enviando as melhores oportunidades encontradas diretamente para canais do **Discord**, **Telegram**, ou qualquer outro sistema integrado.

---

## 🛍️ O que o TNXPromo faz?

- 🔄 Busca periódica por promoções em sites como:
  - Amazon
  - Kabum
  - Magalu
  - Aliexpress
  - Americanas
- 🧠 Filtros inteligentes para evitar promoções irrelevantes
- 🔔 Notificações automáticas via bot
- 🕒 Atualizações em tempo real ou em intervalos configuráveis
- 📦 Pode ser usado para monitorar produtos específicos ou categorias

---

## ⚙️ Tecnologias Utilizadas

- **Python**
- **BeautifulSoup** / **Selenium**
- **Requests** / **APIs públicas**
- **discord.py** / **python-telegram-bot**
- **dotenv**
- **Docker (opcional)**

---

## 🚀 Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/TNXPromo.git
   cd TNXPromo
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
3. Configure seu arquivo .env com os tokens e preferências:
   ```env
   DISCORD_TOKEN=seu_token_discord
   TELEGRAM_TOKEN=seu_token_telegram
   TELEGRAM_CHAT_ID=seu_chat_id
   BUSCA_INTERVALO=300
4. Execute o Bot
   ```bash
   python bot.py

## 📌 Exemplo de Notificação
   ```yaml
   💥 Promoção Encontrada!

   🛒 Produto: SSD Kingston 500GB
   💰 Preço: R$ 179,90
   🔗 Link: https://www.kabum.com.br/produto/ssd...

   📦 Loja: Kabum

## 🧠 Funcionalidades Planejadas
 Painel Web para gerenciamento de filtros

 Histórico de preços

 Integração com WhatsApp

 Modo “monitorar produto específico”

## 📄 Licença
Distribuído sob a licença MIT.
Veja o arquivo LICENSE para mais detalhes.

## 🤝 Contribuições
Contribuições são bem-vindas!
Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## 📫 Contato
Email: contato@arthlabs.inf.br




