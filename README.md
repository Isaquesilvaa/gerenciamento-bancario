# 💼 Gerenciamento Bancário — Projeto SQL

Sistema de gerenciamento bancário feito com **MySQL 5.7**, focado em operações reais como depósito, transferência, saldo, extrato, auditoria e controle de clientes. Ideal pra quem quer praticar SQL com procedures e entender como funciona um banco por trás dos bastidores.

<table>
  <tr>
    <td>
      💡 Projeto com uso de procedimentos armazenados, lógica financeira, e geração de logs — tudo num banco organizado e fácil de restaurar.
    </td>
    <td>
      <img src="https://github.com/Isaquesilvaa/My-desc-/blob/main/tumblr_ntip7ywsIw1tgzy56o1_400.gif?raw=true" width="220"/>
    </td>
  </tr>
</table>

---

## 📂 Conteúdo do projeto

- Arquivo principal: `banco_completo.sql`
- Procedures inclusas:
  - `DEPOSITO`
  - `EXTRATO_CONTA`
  - `TRANSFERENCIA`
  - `INSERT_CLIENTE`
  - `REGISTRAR_LOG`
  - `AUTO_CONTA`
  - `SALDO`
  - `SALDO_MEDIO_POR_TIPO_CONTA`
  - E outras que garantem controle e segurança dos dados 💾

---

## ⚙️ Funcionalidades

- Cadastro automático de clientes
- Geração de extratos individuais
- Controle de saldo e movimentações
- Transferência entre contas
- Auditoria por logs
- Verificação de saldos negativos
- Média de saldo por tipo de conta
- Relatórios e filtros por tipo e horário

---

## 🚀 Como restaurar o banco

Se você tiver o MySQL instalado:

```bash
mysql -u root -p banco < banco_completo.sql
