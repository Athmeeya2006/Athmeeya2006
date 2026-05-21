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

> Math olympiad qualifier, national-level swimmer, and table tennis player - I'm drawn to speed, precision, and how things break under pressure. Currently a second-year dual degree student (B.Tech CS + MS Computational Natural Sciences) at IIIT Hyderabad, where I research how complex systems collapse - from phase transitions in random graphs to cascading failures in financial networks.

---

## 🔬 Research

**Undergraduate Researcher · CCNSB Lab, IIIT Hyderabad · Prof. Chittaranjan Hens**

Investigating the mathematical structure of irreversible transitions in complex networks. Current work spans three interconnected directions:

**Signed Network Dynamics**
Exploring how signed edge weights (excitatory and inhibitory connections) in heterogeneous networks drive systems toward irreversible dynamical phase transitions. Connecting signed Laplacian spectral properties to large-scale connectivity collapse and the emergence of bistable regimes.

**Explosive Synchronization and Flash Crashes**
Modeling first-order synchronization transitions in Kuramoto and Stuart-Landau oscillator networks on Erdős-Rényi and Barabási-Albert topologies. Quantifying hysteresis loop width and characterizing flash-crash desynchronization events under abrupt coupling attenuation - bridging dynamical systems theory and systemic risk.

**Financial Contagion via Percolation Theory**
Extending the Erdős-Rényi random graph framework to model systemic risk propagation in interbank networks. Implementing DebtRank (Battiston et al., 2012), Watts threshold cascades, and bond percolation contagion protocols to identify critical collapse thresholds and map safe operating regions.

*Research manuscript in preparation.*

---

## 🗂️ Projects

<table>
<tr>
<td width="50%" valign="top">

### [GTO Poker Bot](https://github.com/Athmeeya2006/GTO_Poker_Bot)

Four CFR-family solvers (Vanilla CFR, CFR+, DCFR, External Sampling MCCFR) computing 
Nash-approximate strategies from Kuhn Poker (12 info sets) through Leduc Poker (288 info sets).

- **Convergence:** Exploitability below 0.001 chips/game within 10k iterations, cross-validated 
  against brute-force enumeration on Kuhn (agreement within 0.002)
- **Financial Bridge:** Maps CFR bluff frequency to Glosten-Milgrom (1985) adverse selection 
  spread estimates via the informed-trader/bluffer isomorphism
- **Architecture:** Real-time CLI bot with Dirichlet posterior opponent model and SPRT leak 
  detector (5% FP/FN), 119 tests

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)

</td>
<td width="50%" valign="top">

### [No-Regret Market Making Engine](https://github.com/Athmeeya2006/No-Regret-Market-Maker)

End-to-end simulation of no-regret learning in market making. C++17 limit order book with 
price-time priority and O(log N) insertion, exposed to Python via pybind11.

- **Benchmarks:** 6 algorithms across 10,000-round simulations in 4 market regimes, with abrupt 
  and gradual regime transitions
- **Theory:** Empirical regret stays below the O(√TK ln K) bound across all runs
- **Analytics:** Three-component PnL decomposition (spread capture, adverse selection, inventory 
  loss) with bootstrap CIs across 200 resamples. 8 test modules.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![pybind11](https://img.shields.io/badge/pybind11-00ff88?style=flat-square&logoColor=black)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Explosive Synchronization & Flash Crash](https://github.com/Athmeeya2006/Explosive-Sync-Flash-Crash)

High-performance numerical framework for Kuramoto and Stuart-Landau oscillator dynamics on 
Erdős-Rényi and Barabási-Albert topologies.

- **Performance:** Custom C++17 RK4 engine achieves 30x speedup over SciPy adaptive solvers, 
  enabling 525-run parameter sweeps in minutes
- **Validation:** Finite-size scaling (N = 50 to N = 800) recovers theoretical K_c = √(8/π) 
  ≈ 1.5957 to within 2% empirically
- **Diagnostics:** Lyapunov exponent pipeline (Benettin method) for chaos onset detection. 95% 
  test coverage

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

</td>
<td width="50%" valign="top">

### [Erdős-Rényi Contagion](https://github.com/Athmeeya2006/Erdos-Renyi-Contagion)

Large-scale Monte Carlo evaluation of G(n,p), validating 3 classical phase-transition scaling 
laws and extending the framework to financial contagion.

- **Theory:** Confirmed s^(-3/2) cluster power law via 10,980 simulation runs; recovered 
  Δλ ~ n^(-1/3) via log-log OLS regression
- **Empirical:** S&P 500 correlation network yields clustering Z-score > 30σ against 1,000 ER 
  null graphs (p < 10^-300)
- **Models:** DebtRank, Watts threshold cascades, bond percolation. 21 publication-quality 
  figures, Manim phase transition animation

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NetworkX](https://img.shields.io/badge/NetworkX-00ff88?style=flat-square&logoColor=black)
![Manim](https://img.shields.io/badge/Manim-343434?style=flat-square&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Felicity Fest Management System](https://github.com/Athmeeya2006/Felicity-Fest-Management-System)

3-role MERN event portal for IIIT Hyderabad's annual cultural fest. **70+ REST endpoints**, Socket.IO real-time chat, browser-camera QR attendance, merchandise payment approval workflow, JWT authentication with role-based route guards.

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

</td>
<td width="50%" valign="top">

### [You Matter Wellness](https://github.com/Athmeeya2006/You-Matter-Wellness)

**🏆 9th of 100+ teams** · Star Union Dai-ichi National Tech Hackathon. Decoupled microservice wellness platform with streak tracking, challenge systems, real-time leaderboards, and ML-powered activity forecasts. Deployed on Vercel and Railway.

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

</td>
</tr>
</table>

---

## 🏆 Achievements

<div align="center">

| Achievement | Details |
|:---|:---|
| 🥇 **INMOTC 2022** | INMO Training Camp · **1 of 22 selected from Karnataka** · ICTS-TIFR Bengaluru |
| 📐 **INMO Qualifier 2022** | Indian National Mathematical Olympiad · **Top 300 nationally** · IOQM → RMO → INMO |
| 🔭 **NSEA 2023** | National Standard Examination in Astronomy · **Top 1% statewide** · IAPT |
| 🏊 **SGFI Nationals** | Represented Karnataka in Swimming · School Games Federation of India Nationals · Breaststroke 200m |
| 🏓 **State-Level Table Tennis** | Competitive circuit player, state tournament appearances |
| 💻 **Competitive Programming** | 300+ problems solved · DP, graph algorithms, number theory, combinatorics |

</div>

---

## 📚 Current Focus

```
Probability Theory         Measure-theoretic foundations, sigma-algebras, convergence theorems
Stochastic Processes       Markov chains, martingales, Brownian motion, Itô calculus
Random Graph Theory        Connectivity thresholds, giant component, spectral methods
Statistical Inference      MLE, Bayesian estimation, hypothesis testing, bootstrap theory
Combinatorics              Extremal graph theory, generating functions, algebraic methods
```

---

## 🛠️ Stack

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=python,cpp,c,js,ts,react,nodejs,express,postgres,mongodb,git&theme=dark)](https://skillicons.dev)

</div>

<br/>

```
Research     NumPy · SciPy · NetworkX · Matplotlib · Pandas · Manim · Monte Carlo
Core         Probability Theory · Stochastic Processes · Graph Theory · Statistical Mechanics
Systems      C++17 · pybind11 · CMake · PostgreSQL · MongoDB · Linux
Web          React.js · Node.js · Express.js · Socket.IO · Prisma ORM · Tailwind CSS
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

*If everything seems under control, you're not going fast enough.*

</div>