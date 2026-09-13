# N10-009 Drill

Personal CompTIA Network+ study app built around weak areas from MeasureUp.

**108 questions** (was 54). Same categories, more stems:

- Routing / FHRP (VRRP vs GLBP vs BGP, AD vs longest prefix, floating static, SIA, ABR)
- SVI vs router subinterface
- Switching / STP / native VLAN / PortFast / BPDU Guard
- Cabling (split pair vs crossover, PoE, 100 m, OTDR)
- Spine-leaf vs collapsed core, east-west vs north-south
- Media / SFP family
- Wireless (1/6/11, 6E, SAE, CAPWAP, 802.1X)
- DHCP / DNS / APIPA
- OSI layers

Answer letters are shuffled every time a question is shown.

## Use it

Open `index.html` locally, or enable GitHub Pages:

1. Repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / root
4. Site URL will be `https://sleepysmurfgg.github.io/netplus-drill/`

No login. Missed questions are stored in the browser (`localStorage`).

## Modes

- Category drill
- 10-minute mix (12 random questions)
- Missed only

Not affiliated with CompTIA.
