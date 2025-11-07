# WorkShopStella
GreenImpact


# 🌱 GreenImpact – Plataforma de Recompensas Sustentáveis

> **Hackathon: Inovação Aberta usando o Scaffold Stellar**  
> Aplicativo descentralizado (dApp) desenvolvido para demonstrar a velocidade e eficiência do framework **Scaffold Stellar**, utilizando **contratos inteligentes em Rust + Soroban**, **front-end em React/Vite**, e **integração com Stellar Wallet Kit**.

---

## 🚀 Visão Geral

**GreenImpact** é um dApp que incentiva ações sustentáveis através da distribuição de tokens digitais chamados **GreenRewardToken (GRT)**.  
Usuários ganham tokens ao completar “missões verdes” — como reciclar, participar de campanhas ecológicas ou usar transporte público — enquanto empresas e ONGs podem criar novas missões e recompensas.

O projeto demonstra:
- Contrato inteligente implantado (Soroban + Rust)
- Front-end moderno (React + TypeScript + Vite)
- Autenticação e transações via **Stellar Wallet Kit**

---

## ✨ Funcionalidades Principais

- 🔐 **Login com carteira Stellar**  
  Autenticação segura e rápida via Stellar Wallet Kit.

- 💰 **Token GRT (Green Reward Token)**  
  Contrato inteligente fungível (padrão OpenZeppelin adaptado ao Soroban).

- 🧩 **Sistema de Missões Sustentáveis**  
  Complete missões ecológicas e receba recompensas em tokens.

- 📊 **Dashboard de usuário**  
  Visualize saldo, histórico de missões e conquistas.

- 🌍 **Interface moderna e intuitiva**  
  Desenvolvida com React, Vite e Tailwind.

---

## 🧠 Arquitetura do Projeto

```bash
greenimpact/
├── contracts/              # Contratos inteligentes (Rust + Soroban)
│   ├── src/
│   ├── Cargo.toml
│   └── target/
├── frontend/               # Aplicação React/Vite + TypeScript
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.ts
├── .env                    # Variáveis de ambiente
└── README.md
