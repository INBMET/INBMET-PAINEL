# INBMET • Painel Meteorológico V9

Painel meteorológico completo em **um único arquivo HTML**.  
Funciona offline no navegador (após carregar), usa APIs públicas e não precisa de backend.

## 🚀 Como usar

1. Abra o arquivo `index.html` no navegador  
   **ou**
2. Faça o deploy no GitHub Pages / Netlify / Vercel (basta apontar a pasta raiz).

```bash
# Clone e abra
git clone https://github.com/SEU_USUARIO/inbmet-painel.git
cd inbmet-painel
# Abra index.html no navegador
```

## ✨ Funcionalidades

- Previsão completa (Open-Meteo)
- Condições atuais (OpenWeather opcional com chave)
- Convecção (CAPE, CIN, LI, shear)
- Qualidade do ar
- Mapa geográfico (OpenStreetMap)
- Tema claro / escuro
- Cidades rápidas (Avaré, São Paulo, Botucatu, Campinas…)
- Detalhes técnicos (vento em vários níveis, solo, ET₀, etc.)

## 📁 Estrutura (só 4 arquivos)

```
inbmet-painel/
├── index.html          # Todo o painel (único arquivo de código)
├── README.md           # Este arquivo
├── LICENSE             # MIT
└── .gitignore          # Arquivos a ignorar
```

## 🔑 Chave OpenWeather (opcional)

No painel → **Ajustes** → cole sua chave gratuita de [openweathermap.org](https://openweathermap.org/api).

## 📜 Licença

MIT — use, modifique e distribua livremente.

---

**INBMET** – Painel Meteorológico  
Arquivo único • Pronto para GitHub Pages
