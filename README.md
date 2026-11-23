# Apurato — Gestão Completa para Microempreendedores Individuais (MEI)

Aplicativo Web Progressivo (**PWA**) 100% gratuito, código aberto e offline-first, desenvolvido por **[saulomgg](https://saulomgg.github.io)** para que o MEI organize todo o negócio em um só lugar — direto do navegador ou instalado no celular.

## Funcionalidades Principais

### 1. Painel Geral & Radar do Negócio
- Acompanhamento em tempo real do faturamento anual vs teto **R$ 81.000,00**.
- Resultado líquido mensal (Receitas - Despesas PJ), status da guia **DAS-MEI (dia 20)** e saldo separado **PJ × PF**.
- Alertas inteligentes de contas a pagar/receber vencidas, estoque baixo e obrigações pendentes.

### 2. Operação Diária (Vendas & Atendimento)
- **Orçamentos & Recibos com QR Code PIX**: Emissão com itens, desconto, impressão em PDF, texto formatado para WhatsApp e conversão em faturamento com 1 clique.
- **Clientes & Fornecedores**: Cadastro completo com atalho direto para WhatsApp.
- **Catálogo & Estoque**: Controle de preços, margens e alerta de estoque mínimo.
- **Calculadora de Precificação MEI**: Calcula preço sugerido incluindo materiais, hora trabalhada, taxa de cartão/app e rateio do DAS.

### 3. Financeiro & Relatório Mensal Oficial
- **Faturamento R$ 81k**: Registro por categoria (Serviços, Comércio, Indústria, Transporte) com filtro e exportação CSV contábil (faturamento + despesas + DAS).
- **Relatório Mensal das Receitas Brutas**: Modelo oficial pronto para impressão (com e sem emissão de Nota Fiscal).
- **Contas a Pagar & Receber**: Controle de vencimentos futuros com baixa automática no caixa.
- **Contas PF × CNPJ**: Controle separado com transferência rápida de **Pró-Labore (PJ → PF)**.

### 4. Fiscal MEI & Obrigações
- **Calendário DAS-MEI (12 meses)** com presets por enquadramento (Comércio, Serviços, Misto, Caminhoneiro).
- **Simulador DASN-SIMEI & IRPF**: Cálculo automático de lucro isento (8%, 16%, 32%), parcela tributável e alerta da regra legal de 80% de compras.
- **Checklist de Obrigações & Limites Legais**.

### 5. Backup no Google Drive (Apps Script) & Backup Manual
- Código pronto de **Google Apps Script (`Code.gs`)** com cópia em 1 clique para o usuário salvar e restaurar backups direto na pasta `Apurato_Backups` do próprio Google Drive.
- **Backup Manual** completo via arquivo JSON e exportação de planilha CSV com histórico de faturamento e despesas.

### 6. PWA Instalável, 4 Temas & Área de Apoio
- Botão nativo **Instalar App / Baixar App** (`beforeinstallprompt` no Chrome + guia para iOS Safari).
- 4 temas visuais (**Estúdio Claro**, **Obsidiana Pro**, **Executivo Azul** e **Finanças Verde**).
- Seção **Apoiar** com links diretos (Mercado Pago, Stripe, Hub de Apps, redes sociais) e **Roadmap Público**.

## Executar e Compilar

```bash
npm install
npm run dev
npm run build
```

Desenvolvido por **[saulomgg](https://saulomgg.github.io)**.
