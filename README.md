# 💱 Currency Exchange Rate Dashboard

A lightweight, client-side currency exchange rate dashboard built with HTML, CSS, and Chart.js. No backend, no API key required — just open and use.

🔗 **Live Demo:** [albertchoong-tech.github.io/currency](https://albertchoong-tech.github.io/currency/)

---

## 📊 Currency Pairs Tracked

| Pair | Description |
|------|-------------|
| USD/JPY | US Dollar to Japanese Yen |
| USD/MYR | US Dollar to Malaysian Ringgit |
| GBP/MYR | British Pound to Malaysian Ringgit |
| SGD/MYR | Singapore Dollar to Malaysian Ringgit |
| MYR/JPY | Malaysian Ringgit to Japanese Yen |
| MYR/THB | Malaysian Ringgit to Thai Baht |

> GBP/MYR, SGD/MYR, MYR/JPY and MYR/THB are cross rates derived from USD base pairs.

---

## ✨ Features

- 📈 Interactive line charts with crosshair hover (vertical + horizontal guide lines)
- 🏷️ Live rate label on Y-axis when hovering over a chart
- 📅 Selectable time ranges: 7D · 1M · 3M · 6M · 1Y · 5Y
- 🔄 One-click Refresh to fetch latest data
- 📉 Period high / low and % change displayed per pair
- 🌙 Dark-themed, responsive layout (mobile-friendly)
- ⚡ No API key, no server — runs entirely in the browser

---

## 🛠️ Built With

- [Chart.js 4.4.1](https://www.chartjs.org/) — charting library
- [Frankfurter API](https://www.frankfurter.dev/) — free ECB exchange rate data (no key needed)
- Pure HTML / CSS / Vanilla JavaScript

---

## 🚀 Deployment

Hosted via **GitHub Pages** from the `main` branch.

To deploy your own copy:
1. Fork or clone this repository
2. Enable GitHub Pages under **Settings → Pages → Branch: main**
3. Visit `https://<your-username>.github.io/currency/`

---

## 📡 Data Source

Daily reference rates provided by the **European Central Bank (ECB)** via the [Frankfurter API](https://www.frankfurter.dev/). Data is fetched live on page load — no data is stored or cached on any server.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

*Built and maintained by [albertchoong-tech](https://github.com/albertchoong-tech)*
