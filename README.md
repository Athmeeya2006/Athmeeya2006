<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Athmeeya%20M%20Kashyap&fontSize=48&fontColor=fff&animation=twinkling&fontAlignY=36&desc=Undergraduate%20Researcher%20%C2%B7%20IIIT%20Hyderabad&descSize=18&descAlignY=58&descColor=00ff88" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1000&color=00FF88&center=true&vCenter=true&width=720&lines=INMO+Qualifier+%7C+Top+300+Nationally;INMOTC+2022+%7C+1+of+22+from+Karnataka+%7C+ICTS-TIFR+Bengaluru;Undergraduate+Researcher+%40+CCNSB+Lab%2C+IIIT+Hyderabad;Complex+Networks+%C2%B7+Dynamical+Systems+%C2%B7+Phase+Transitions)](https://github.com/Athmeeya2006)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-00ff88?style=for-the-badge&logo=github&logoColor=black)](https://athmeeya2006.github.io/webpage/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/athmeeya-kashyap)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/athmeeyakashyap)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:athmeeyakashyap@gmail.com)

</div>

<br/>

```
athmeeya@iiit-h:~$ whoami
Second-year dual degree (B.Tech CS + MS CNS) @ IIIT Hyderabad
Undergraduate Researcher @ CCNSB Lab

athmeeya@iiit-h:~$ cat research.txt
complex_networks   phase_transitions   financial_contagion

athmeeya@iiit-h:~$ ./achievements --list
INMOTC 2022 ................. 1 of 22 from Karnataka, ICTS-TIFR Bengaluru   [OK]
INMO Qualifier 2022 ......... Top 300 nationally                            [OK]
NSEA 2023 ................... Top 1% statewide, IAPT                        [OK]
SGFI Nationals .............. Karnataka Swimming, Breaststroke 200m         [OK]

athmeeya@iiit-h:~$ ls projects/
GTO_Poker_Bot/   No-Regret-Market-Maker/   Explosive-Sync-Flash-Crash/   Erdos-Renyi-Contagion/
```

<div align="center">

![](https://img.shields.io/badge/Exploitability-0.001_chips%2Fgame-00ff88?style=for-the-badge)
![](https://img.shields.io/badge/C%2B%2B_Speedup-30x_vs_SciPy-00ff88?style=for-the-badge)
![](https://img.shields.io/badge/Simulation_Runs-10%2C980-00ff88?style=for-the-badge)
![](https://img.shields.io/badge/CFR_Iterations-10%2C000-00ff88?style=for-the-badge)

</div>

---

## Research Architecture

```mermaid
graph LR
    CN[Complex Networks] --> ES[Explosive Sync & Flash Crash]
    CN --> ER[Erdos-Renyi Contagion]
    PT[Phase Transitions] --> ES
    PT --> ER
    MM[Market Microstructure] --> GTO[GTO Poker Bot]
    MM --> NR[No-Regret Market Maker]
    PT --> GTO
    CN --> NR
```

---

## Projects

### [GTO Poker Bot](https://github.com/Athmeeya2006/GTO_Poker_Bot)

Four CFR-family solvers (Vanilla CFR, CFR+, DCFR, MCCFR) computing Nash-approximate strategies across Kuhn and Leduc Poker. Exploitability below 0.001 chips/game within 10k iterations. Maps CFR bluff frequency to Glosten-Milgrom adverse selection spread via the informed-trader/bluffer isomorphism.

> **Key result:** Exploitability below 0.001 chips/game within 10k iterations

```mermaid
graph LR
    A[Game Tree] --> B[CFR Iteration]
    B --> C[Strategy Update]
    C --> D[Exploitability Check]
    D -->|> 0.001| B
    D -->|≤ 0.001| E[Nash Equilibrium]
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)

---

### [No-Regret Market Making Engine](https://github.com/Athmeeya2006/No-Regret-Market-Maker)

C++17 limit order book with price-time priority, exposed to Python via pybind11. Benchmarks 6 no-regret algorithms across 10,000-round simulations in 4 market regimes. Empirical regret stays below the O(sqrt(TK ln K)) bound across all runs.

> **Key result:** Empirical regret below O(sqrt(TK ln K)) bound across all runs

```mermaid
graph LR
    A[Market Regime] --> B[Limit Order Book]
    B --> C[No-Regret Algorithm]
    C --> D[Regret Evaluation]
    D --> B
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![pybind11](https://img.shields.io/badge/pybind11-00ff88?style=flat-square&logoColor=black)

---

### [Explosive Synchronization & Flash Crash](https://github.com/Athmeeya2006/Explosive-Sync-Flash-Crash)

Kuramoto and Stuart-Landau oscillator dynamics on ER and BA topologies. Custom C++17 RK4 engine runs 30x faster than SciPy adaptive solvers. Finite-size scaling across N = 50 to 800 recovers theoretical K_c to within 2%.

> **Key result:** 30x faster than SciPy adaptive solvers, K_c recovered to within 2%

```mermaid
graph LR
    A[ER / BA Topology] --> B[Kuramoto Oscillators]
    B --> C[C++ RK4 Engine]
    C --> D[Order Parameter]
    D --> E[Finite-Size Scaling]
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

---

### [Erdos-Renyi Contagion](https://github.com/Athmeeya2006/Erdos-Renyi-Contagion)

Monte Carlo validation of G(n,p) phase-transition scaling laws across 10,980 simulation runs, extended to financial contagion via DebtRank, Watts cascades, and bond percolation. S&P 500 correlation network yields clustering Z-score above 30 sigma against 1,000 ER null graphs.

> **Key result:** Clustering Z-score above 30 sigma against 1,000 ER null graphs

```mermaid
graph LR
    A[G n,p Model] --> B[Monte Carlo Simulation]
    B --> C[Phase Transition Detection]
    C --> D[DebtRank / Watts Cascade]
    D --> E[S&P 500 Validation]
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NetworkX](https://img.shields.io/badge/NetworkX-00ff88?style=flat-square&logoColor=black)
![Manim](https://img.shields.io/badge/Manim-343434?style=flat-square&logoColor=white)

---

## Stack

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=python,cpp,ts,js,postgres,bash,kotlin,nodejs,express,prisma,mongodb,react,tailwind,sklearn,linux,git,docker,cmake&theme=dark&perline=9)](https://skillicons.dev)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

*If everything seems under control, you're not going fast enough.*

</div>