<p align="center">
  <img src="screenshots/02-visao-geral.png" alt="RoProfit — visão geral" width="100%">
</p>

<h1 align="center">RoProfit</h1>

<p align="center">
  Painel administrativo para a gestão de uma operação de revenda de Robux e Limiteds do Roblox:<br>
  estoque, contas, vendas, caixa e planejamento em um só lugar.
</p>

<p align="center">
  <img alt="React" src="https://img.shields.io/badge/React-20232a?style=flat&logo=react&logoColor=61DAFB">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-0F172A?style=flat&logo=tailwindcss&logoColor=38BDF8">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-1f2a1f?style=flat&logo=nodedotjs&logoColor=5FA04E">
  <img alt="Discord" src="https://img.shields.io/badge/Bot_Discord-5865F2?style=flat&logo=discord&logoColor=white">
</p>

---

## Sobre

O RoProfit é um painel administrativo para gerenciar a revenda de Robux e itens Limited do Roblox. O painel acompanha o estoque da compra à venda e mostra quais itens estão em período de retenção, quais já podem ser vendidos e quais vendas ainda aguardam a liberação dos Robux.

A visão geral reúne faturamento, lucro realizado, saldo em caixa e progresso da meta mensal. Na área de contas, é possível acompanhar quanto cada conta já movimentou e quanto ainda pode enviar no mês. O otimizador usa essa capacidade para sugerir a distribuição dos itens. O simulador estima cenários de crescimento a partir do capital disponível, e a área financeira reúne o livro-caixa e as despesas da operação.

As capturas abaixo mostram a dashboard em funcionamento com dados fictícios.

## Destaques

- **Visão geral** — caixa, lucro realizado, faturamento, meta do mês e capacidade das contas.
- **Estoque de Limiteds** — ciclo de cada item (em hold → pronto para vender → Robux pendentes → Robux liberados) e uma galeria com todo o inventário.
- **Contas** — situação automática de cada conta, uso da capacidade e lucro por conta.
- **Otimizador** — sugere em qual conta cada Limited deve ficar para aproveitar ao máximo o limite de envio.
- **Simulador** — projeções de crescimento e de metas a partir do capital disponível.
- **Financeiro** — livro-caixa, despesas e resultado do mês.
- **Responsivo** — pensado também para o celular.
- **Integração com Discord** — bot que acompanha pedidos e avisa sobre anúncios de troca.

## Telas

| | |
|:---:|:---:|
| <img src="screenshots/01-login.png" alt="Login"> | <img src="screenshots/03-limiteds-ciclo.png" alt="Ciclo dos Limiteds"> |
| **Login** | **Ciclo dos Limiteds** |
| <img src="screenshots/04-limiteds-galeria.png" alt="Galeria do estoque"> | <img src="screenshots/05-contas.png" alt="Contas"> |
| **Galeria do estoque** | **Contas** |
| <img src="screenshots/06-otimizador.png" alt="Otimizador"> | <img src="screenshots/07-simulador.png" alt="Simulador"> |
| **Otimizador** | **Simulador** |
| <img src="screenshots/08-financeiro.png" alt="Financeiro"> | <img src="screenshots/09-robux.png" alt="Robux"> |
| **Financeiro** | **Robux** |

### No celular

<p align="center">
  <img src="screenshots/10-mobile-visao-geral.png" alt="Visão geral no celular" width="280">
  &nbsp;&nbsp;
  <img src="screenshots/11-mobile-galeria.png" alt="Galeria no celular" width="280">
</p>

---

## Como funciona o otimizador

O otimizador sugere como distribuir Limiteds entre contas respeitando a capacidade mensal de cada uma. Ele oferece dois modos: acomodar só o que cabe ou distribuir todos os itens minimizando o excedente. O painel indica se a solução encontrada é ótima comprovada ou viável dentro do tempo disponível.

## Direitos de uso

Esta vitrine apresenta o projeto para fins de portfólio. © 2026 RoProfit. Todos os direitos reservados. Consulte o [aviso de direitos autorais](LICENSE).
