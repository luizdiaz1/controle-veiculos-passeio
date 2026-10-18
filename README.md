# Controle de Veículos de Passeio

Sistema que desenvolvi na DIME Distribuidora para controlar os carros usados pela equipe comercial (promotores) nas visitas a clientes.

Este repositório tem a **versão de demonstração**. Empresa, pessoas, placas e valores são fictícios, e o banco de dados foi trocado por um banco simulado que roda no navegador. O sistema real roda internamente e não é público.

**Testar a demo:**
- Painel de controle: https://portfolio-luizdias.vercel.app/promotor/ (login `admin@exemplo.com`, qualquer senha)
- Área do condutor: https://portfolio-luizdias.vercel.app/promotor/#/condutor (login `condutor@exemplo.com`, qualquer senha)

## Por que fiz

Era preciso saber quem estava com cada carro, por onde ele tinha passado e em que estado voltou. Também faltava uma comprovação da retirada e da devolução que não dependesse de papel.

## O que o sistema faz

- Saída e devolução com assinatura digital do condutor
- Roteiro de clientes do dia no mapa, com atalho para Waze e Google Maps e fotos de antes e depois de cada atendimento
- Área do condutor feita para o celular, separada do painel de controle
- Manutenções, ocorrências, histórico por veículo e por condutor, e relatórios
- Perfis de acesso (Administrador, Gestor, Visualizador e Condutor) e auditoria

## Situação

Publicado e em evolução. Fiz o levantamento com a equipe, defini o fluxo de retirada e devolução e desenvolvi o sistema.

## Tecnologias

HTML, CSS e JavaScript · Supabase · Leaflet (mapas) · PWA

## Rodar localmente

É um site estático, sem etapa de build. Basta servir a pasta:

```bash
npx serve .
```

---

Outros projetos e contato: [portfolio-luizdias.vercel.app](https://portfolio-luizdias.vercel.app)
