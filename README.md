# MyAdmin

**Seu dinheiro, organizado no seu aparelho.**

MyAdmin é um app de finanças pessoais simples e direto: sem cadastro, sem senha e sem servidor. Tudo o que você registra fica salvo somente no seu aparelho.

O app está disponível em duas versões:

| Versão | Arquivo | Como usar |
|---|---|---|
| Android | [`MyAdmin.apk`](MyAdmin.apk) | Instale no celular Android |
| Web | [`MyAdmin.html`](MyAdmin.html) | Abra em qualquer navegador (celular ou computador) |

---

## Funcionalidades

- **Resumo do mês**: visão geral de receitas, despesas, lançamentos do dia, pendências e últimos lançamentos.
- **Contas**: cadastre suas contas e acompanhe o saldo de cada uma.
- **Cartões**: faturas, limite e vencimento em um só lugar, com compras parceladas, gastos por categoria e pagamento de fatura (que pode ser desfeito).
- **Gastos por categoria**: veja para onde vai o seu dinheiro.
- **Limites de gasto**: defina limites por categoria, válidos para todos os meses, e receba alertas ao ultrapassá-los.
- **Metas**: crie objetivos com prazo; o app calcula quanto guardar por mês para chegar lá.
- **Calendário**: veja os lançamentos de cada dia.
- **Planejamento e Economizar**: ferramentas para organizar o orçamento.
- **Cotações**: dólar, euro, libra e bitcoin em reais, com conversor de moedas.
- **Conquistas**: acompanhe sua jornada desbloqueando conquistas.
- **Backup**: exporte e importe todos os seus dados em um arquivo `.json`.

## Privacidade

- Nenhum cadastro ou login.
- Nenhum servidor: os dados ficam no armazenamento local do aparelho/navegador.
- A única conexão externa é a consulta de cotações de moedas ([AwesomeAPI](https://docs.awesomeapi.com.br/)).

> **Importante:** como os dados ficam apenas no aparelho, faça backups de vez em quando (menu **Mais → Seus dados**). Limpar os dados do navegador ou desinstalar o app apaga seus registros.

## Instalação

### Android (APK)

1. Baixe o arquivo [`MyAdmin.apk`](MyAdmin.apk) (ou pela aba [Releases](../../releases)).
2. Abra o arquivo no celular.
3. Se solicitado, permita a instalação de apps de fontes desconhecidas.
4. Conclua a instalação e abra o MyAdmin.

### Web (HTML)

1. Baixe o arquivo [`MyAdmin.html`](MyAdmin.html).
2. Abra-o em um navegador moderno (Chrome, Edge, Firefox, Safari).

O app é um único arquivo HTML, sem dependências externas, e funciona offline (exceto as cotações).

## Primeiros passos

1. Informe como quer ser chamado.
2. Cadastre suas contas e cartões.
3. Comece a registrar receitas e despesas.
4. Defina limites por categoria e crie suas metas.

## Estrutura do repositório

```
.
├── MyAdmin.apk    # App Android
├── MyAdmin.html   # Versão web (arquivo único)
└── README.md
```
