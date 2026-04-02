# Cod reducere XXXLutz — fetch automat de pe shopilo.ro

Modul Python pentru fetch automat de **coduri de reducere XXXLutz** de pe [shopilo.ro](https://shopilo.ro/magazin/xxxlutz.ro). Returneaza **cupoane XXXLutz** active in format JSON, gata de integrat intr-un bot Telegram, extensie de browser sau orice alt tool.

**Pagina live:** [shopilo-ro.github.io/cod-reducere-xxxlutz](https://shopilo-ro.github.io/cod-reducere-xxxlutz/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Instalare

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-ro/cod-reducere-xxxlutz
cd cod-reducere-xxxlutz
python fetch.py
```

## Output exemplu

```json
[
  {
    "store": "XXXLutz",
    "code": "SHOPILO10",
    "discount": "10%",
    "description": "10% reducere la mobila selectata",
    "expires": "2026-10-02",
    "source": "https://shopilo.ro/magazin/xxxlutz.ro"
  }
]
```

## Cupoane XXXLutz disponibile

| Reducere | Descriere | Sursa |
|----------|-----------|-------|
| 10% | 10% reducere la mobila selectata | [shopilo.ro](https://shopilo.ro/magazin/xxxlutz.ro) |

Codurile active: **[shopilo.ro/magazin/xxxlutz.ro](https://shopilo.ro/magazin/xxxlutz.ro)**

## Intrebari frecvente

### Cum folosesc un cod de reducere XXXLutz?
Copiaza codul din tabelul de mai sus sau de pe [shopilo.ro](https://shopilo.ro/magazin/xxxlutz.ro), adauga produsele in cos pe XXXLutz, si introdu codul la checkout in campul dedicat.

### Cat timp sunt valabile cupoanele XXXLutz?
Fiecare cupon are data de expirare afisata in coloana "Expira". Scriptul fetch.py returneaza doar cupoanele active la momentul rularii.

### Unde gasesc cele mai noi voucher-uri XXXLutz?
Pagina [shopilo.ro/magazin/xxxlutz.ro](https://shopilo.ro/magazin/xxxlutz.ro) este actualizata zilnic cu cele mai noi cod reducere XXXLutz, voucher XXXLutz si cupon promotional XXXLutz.

### Codul nu functioneaza. Ce fac?
Verifica data de expirare si conditiile (valoare minima cos, produse eligibile). Unele coduri sunt valabile doar in aplicatia mobila sau pentru prima comanda.

## Despre XXXLutz

XXXLutz este unul dintre magazinele online populare. Gasesti pe [shopilo.ro](https://shopilo.ro/magazin/xxxlutz.ro) cele mai bune cod reducere XXXLutz, cupoane XXXLutz verificate si voucher XXXLutz active, actualizate zilnic.

## Instalare npm

```bash
npm install cod-reducere-xxxlutz
```

```javascript
const { fetchCoupons } = require('cod-reducere-xxxlutz');
fetchCoupons().then(data => console.log(data));
```

## Licenta

MIT — date sursa de pe [shopilo.ro](https://shopilo.ro)
