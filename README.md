<div align="center">

# APURATO

### `Gratuito` · `Offline-first` · `Gestão MEI`

[![App](https://img.shields.io/badge/app-abrir_painel-2563EB?style=for-the-badge)](https://apurato.github.io/)
[![Site](https://img.shields.io/badge/site-oficial-059669?style=for-the-badge)](https://apurato.github.io/)
[![Repositório](https://img.shields.io/badge/c%C3%B3digo-fonte-181717?style=for-the-badge&logo=github)](https://github.com/apurato/apurato.github.io)
[![Apoie](https://img.shields.io/badge/apoie-o_projeto-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://link.mercadopago.com.br/saulomgg)

</div>

---

## `> whoami`

```bash
$ cat /dev/apurato
Nome:   Apurato · gestão para MEI
Foco:   vendas · operação · financeiro · fiscal
Modo:   PWA instalável · offline-first · backups locais
Custo:  gratuito · sem mensalidade
```

O **Apurato** ajuda microempreendedores individuais a organizar a operação do negócio em um só lugar. Registre vendas e despesas, acompanhe o faturamento, prepare orçamentos e recibos e consulte ferramentas de apoio para a rotina do MEI.

O painel é apresentado como um app gratuito e **offline-first**. Você pode usar pelo navegador ou instalar no celular ou computador. A sincronização com o Google Drive é opcional e precisa ser configurada pelo próprio usuário.

---

## `> ls ./recursos`

| Recurso | O que você encontra |
| --- | --- |
| 📊 **Painel e Radar do Negócio** | Acompanhamento do faturamento, resultado mensal, DAS, contas em aberto, estoque e obrigações |
| 🧾 **Vendas e recibos** | Orçamentos e recibos com QR Code PIX, opção de baixar em PDF, imprimir ou compartilhar pelo WhatsApp |
| 👥 **Clientes e fornecedores** | Cadastro e organização dos contatos do negócio |
| 🏷️ **Catálogo e estoque** | Produtos e serviços, preços, margens e alertas de estoque mínimo |
| 🧮 **Calculadora de preços** | Apoio à formação de preço, considerando custos e despesas do negócio |
| 💰 **Financeiro** | Registro de faturamento por categoria, despesas, contas a pagar e a receber e separação entre PF e CNPJ |
| 📈 **Relatórios** | Relatório mensal de receitas brutas e exportação de dados financeiros em CSV |
| 🗓️ **Fiscal MEI** | Calendário DAS-MEI, simulador DASN-SIMEI e IRPF e checklist de obrigações |
| 💾 **Backup** | Backup completo em JSON, exportação financeira em CSV e sincronização opcional com seu Google Drive |
| 🎨 **Temas** | Quatro opções de aparência, incluindo temas claro, escuro, azul e verde |

---

## `> cat ./privacidade`

```json
{
  "modelo": "offline-first",
  "backup_local": ["JSON", "CSV"],
  "google_drive": "opcional, configurado pelo usuário",
  "modo_demonstracao": "dados de exemplo preenchidos",
  "instalacao": "PWA no navegador ou dispositivo"
}
```

- **Offline-first:** o Apurato foi projetado para priorizar o uso offline. Recursos que acessam serviços externos, como a sincronização com o Drive, precisam de conexão.

- **Backup local:** baixe um backup completo em JSON e importe um arquivo salvo anteriormente. Também é possível exportar faturamento e despesas em CSV.

- **Google Drive opcional:** a sincronização usa Google Apps Script e a conta Google do usuário. É necessário configurar o script e conectar o app antes de enviar ou restaurar backups na nuvem.

- **Dados de demonstração:** o painel pode abrir com informações de exemplo para mostrar os recursos. Use **Limpar Autopreenchimento** antes de começar a registrar os dados reais do seu negócio.

> [!NOTE]
Faça backups regulares e guarde uma cópia em local seguro. A sincronização com Google Drive depende da configuração da sua conta e de acesso à internet.

---

## `> ./iniciar`

```bash
1. Acesse   apurato.github.io
2. Explore  confira o painel de demonstração ou limpe os dados de exemplo
3. Configure preencha os dados da sua empresa em Ajustes
4. Instale  use "Instalar App" quando a opção estiver disponível no navegador
5. Proteja  baixe um backup JSON ou configure o Google Drive opcional
```

[▶ **Abrir o Apurato**](https://apurato.github.io/)

---

## `> ping apoio`

O Apurato é gratuito. Se ele ajuda na rotina do seu negócio, você pode apoiar voluntariamente o desenvolvimento e as próximas melhorias.

[![Apoie pelo Mercado Pago](https://img.shields.io/badge/%F0%9F%92%9B_Apoie_pelo_Mercado_Pago-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://link.mercadopago.com.br/saulomgg)

[Roadmap e outros meios de apoio](https://apurato.github.io/)

---

## `> ping links`

| Canal | Link |
| --- | --- |
| Apurato · Painel | [apurato.github.io](https://apurato.github.io/) |
| Repositório | [github.com/apurato/apurato.github.io](https://github.com/apurato/apurato.github.io) |
| Hub de apps | [saulomgg.github.io](https://saulomgg.github.io/) |
| Instagram | [@saulo_mgg](https://instagram.com/saulo_mgg) |
| YouTube | [@saulomgg](https://youtube.com/@saulomgg) |
| Telegram | [S0M9Net](https://t.me/S0M9Net) |
| LinkedIn | [saulomgg](https://linkedin.com/in/saulomgg) |
| Apoio · Mercado Pago | [link.mercadopago.com.br/saulomgg](https://link.mercadopago.com.br/saulomgg) |

---

## `> cat ./LICENSE`

Consulte o arquivo [`LICENSE`](./LICENSE) para os termos de uso e direitos autorais. A licença deste pacote é proprietária e **não** é uma licença open-source permissiva. A página do Apurato atualmente o descreve como “código aberto”; essa descrição precisa ser alinhada à licença antes de apresentar o projeto publicamente como open-source.

---

<div align="center">

Desenvolvido por [**Saulo (saulomgg)**](https://saulomgg.github.io/) · gestão simples para o seu MEI

```
┌─────────────────────────────────────────────┐
│  [ SYSTEM ]  Apurato · gestão MEI           │
│  [ STATUS ]  Gratuito · offline-first       │
│  [ BACKUP ]  JSON local · CSV · Drive*      │
│  [ * ]       Google Drive opcional           │
└─────────────────────────────────────────────┘
```

</div>
