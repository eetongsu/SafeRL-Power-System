# SafeRL-Power-System
The repository is for Safe Reinforcement Learning (RL) in power system applications, based on the paper [*A Review of Safe Reinforcement Learning Methods for Modern Power Systems*](https://arxiv.org/abs/2407.00304), where we explore various safe RL baselines, benchmarks, applications, and real-world deployments. 

If any papers are missing from this list, or if any authors prefer not to have their work included here, please feel free to contact [tongsu@uconn.edu](mailto:tongsu@uconn.edu). (This repository is under active development. We welcome and appreciate any constructive comments and suggestions.)

***

The README is organized as follows:

<!-- TOC start (generated with https://github.com/derlin/bitdowntoc) -->

   * [1. RL/DRL/Safe RL Base](#1-rldrlsafe-rl-base)
      + [1.1 General Safe RL Repositories](#11-general-safe-rl-repositories)
      + [1.2 General RL/DRL Review](#12-general-rldrl-review)
      + [1.3 RL Review for Power System](#13-rl-review-for-power-system)
      + [1.4 General Safe RL Review](#14-general-safe-rl-review)
   * [2. Benchmark Environments, Algorithms, and Software](#2-benchmark-environments-algorithms-and-software)
      + [2.1. General Benchmark Environments and Algorithms](#21-general-benchmark-environments-and-algorithms)
      + [2.2 Power System Benchmark Software](#22-power-system-benchmark-software)
         - [2.2.1 Commercial Software](#221-commercial-software)
         - [2.2.2 Open-Source and Free Software](#222-open-source-and-free-software)
      + [2.3 Tailored Benchmarks for Power System](#23-tailored-benchmarks-for-power-system)
   * [3 Power System Applications of Safe RL](#3-power-system-applications-of-safe-rl)
      + [3.1 Security Control](#31-security-control)
         - [3.1.1 Voltage Control](#311-voltage-control)
         - [3.1.2 Stability Control](#312-stability-control)
      + [3.2 Real-Time Operation](#32-real-time-operation)
         - [3.2.1 Economic Dispatch](#321-economic-dispatch)
         - [3.2.2 System Restoration](#322-system-restoration)
      + [3.3 Operational Planning](#33-operational-planning)
         - [3.3.1 Unit Commitment](#331-unit-commitment)
         - [3.3.2 Electricity Market](#332-electricity-market)
      + [3.4 Emerging Areas](#34-emerging-areas)
         - [3.4.1 EV Charging](#341-ev-charging)
         - [3.4.2 Building Energy Management](#342-building-energy-management)
   * [4 Real-World Deployment Cases](#4-real-world-deployment-cases)
- [Publication](#publication)

<!-- TOC end -->

***

### 1. RL/DRL/Safe RL Base

#### 1.1 General Safe RL Repositories

- [Safe-Reinforcement-Learning-Baselines](https://github.com/chauncygu/Safe-Reinforcement-Learning-Baselines)

#### 1.2 General RL/DRL Review

- [Deep reinforcement learning for multiagent systems: A review of challenges, solutions, and applications](https://ieeexplore.ieee.org/abstract/document/9043893/?casa_token=MUfVRZZDuqMAAAAA:nYToDbcPxdRl1zZEsuMr-d0PhskJ8zJzN-KZtcX8kXjDsZtfxs4VNABxTuWgg5eg-mFmvf3vqQ)
- [Deep reinforcement learning: An overview](https://arxiv.org/abs/1701.07274)
- [Deep reinforcement learning: A brief survey](https://ieeexplore.ieee.org/abstract/document/8103164/?casa_token=cH1P9RseroQAAAAA:-NvJvaH0O43AVtFw0QRwRoV_G7U7HAXsvmOikxDibZk9v4NRagTTfJUhodO-Js4lJZN0X8hjXg)
- [A brief survey of deep reinforcement learning](https://arxiv.org/abs/1708.05866)
- [Deep reinforcement learning: An overview](https://link.springer.com/chapter/10.1007/978-3-319-56991-8_32)
- [Explainable AI and reinforcement learning—a systematic review of current approaches and trends](https://www.frontiersin.org/articles/10.3389/frai.2021.550030/full)
- [Robust reinforcement learning: A review of foundations and recent advances](https://www.mdpi.com/2504-4990/4/1/13)
- [A survey on offline reinforcement learning: Taxonomy, review, and open problems](https://ieeexplore.ieee.org/abstract/document/10078377/)

#### 1.3 RL Review for Power System

- [Deep reinforcement learning for smart grid operations: Algorithms, applications, and prospects](https://ieeexplore.ieee.org/abstract/document/10241311/?casa_token=HZkAHAVjhS4AAAAA:HJDUP9G8e9Fq41siTq7jr4vIME3zlpF9CZ-rAqPs3NEZGp1chby59zoyPsS4VlLmrt3SDLKzcg)
- [Reinforcement learning for selective key applications in power systems: Recent advances and future challenges](https://ieeexplore.ieee.org/abstract/document/9721402/?casa_token=qvowa2ac1jUAAAAA:z6MXCDEOftlwoA0au4x1vE0vlR7hQASgC8wnCnqijfq44XiKeVbWuJRAPaIGNQWRodw08JJhZg)
- [Deep reinforcement learning for power system applications: An overview](https://ieeexplore.ieee.org/abstract/document/8859593/)
- [(Deep) reinforcement learning for electric power system control and related problems: A short review and perspectives](https://www.sciencedirect.com/science/article/pii/S1367578819301014)
- [Reinforcement learning and its applications in modern power and energy systems: A review](https://ieeexplore.ieee.org/abstract/document/9275593/)

#### 1.4 General Safe RL Review

- [A review of safe reinforcement learning: Methods, theories and applications](https://ieeexplore.ieee.org/abstract/document/10675394/?casa_token=Q9b8DqdGIAQAAAAA:SsfuqUQFEdVttZf65gOfzM77lwbN9siTrafeEl9HhFdKB32kmNgQmfMtWL4QUPkdBauocSRwjA)
- [A comprehensive survey on safe reinforcement learning](https://www.jmlr.org/papers/volume16/garcia15a/garcia15a.pdf)
- [State-wise safe reinforcement learning: A survey](https://arxiv.org/abs/2302.03122)
- [Safe reinforcement learning: A survey](http://www.aas.net.cn/article/doi/10.16383/j.aas.c220631)

### 2. Benchmark Environments, Algorithms, and Software

#### 2.1. General Benchmark Environments and Algorithms

- [AI Safety Gridworlds](https://github.com/deepmind/ai-safety-gridworlds)
- [Safety-Gym](https://github.com/openai/safety-gym)
- [Safety-Gymnasium](https://github.com/PKU-Alignment/safety-gymnasium)
- [Safe Multi-Agent Mujoco](https://github.com/chauncygu/Safe-Multi-Agent-Mujoco)
- [Safe Multi-Agent Isaac Gym](https://github.com/chauncygu/Safe-Multi-Agent-Isaac-Gym)
- [Safe Multi-Agent Robosuite](https://github.com/chauncygu/Safe-Multi-Agent-Robosuite)
- [Safe-Policy-Optimization(SafePO)](https://github.com/PKU-Alignment/Safe-Policy-Optimization)
- [OmniSafe](https://github.com/PKU-Alignment/omnisafe)

#### 2.2 Power System Benchmark Software

##### 2.2.1 Commercial Software

- PSSE: [Website](https://www.siemens.com/us/en/products/energy/grid-software/planning/pss-software/pss-e.html), [Python interface for state estimation](https://github.com/SajjadAsefi/PSSE), [Python interface for dynamic simulation 1](https://github.com/gajduk/vehicle2grid-dynamic-simulation-PSSE), [Python interface for dynamic simulation 2](https://github.com/TanBendong/PSSE-Python-Code), 
- PowerFactory: [Website](https://www.digsilent.de/en/), [Python interface](https://github.com/susantoj/powerfactory_python)
- PowerWorld: [Website](https://www.powerworld.com/), [WebHelp](https://www.powerworld.com/WebHelp/), [Python interface-ESA](https://github.com/mzy2240/ESA)
- EMTP: [Website](https://www.emtp.com/), [Manual](https://www.emtp.com/documentation/emtp-user-manual)
- ETAP: [Website](https://etap.com/)
- RTDS: [Website](https://www.rtds.com/)
- Simscape: [Website](https://www.mathworks.com/products/simscape.html)
- PSCAD: [Website](https://www.pscad.com/), [Course-Python-PSCAD](https://github.com/jsacostas/Course-Python-PSCAD)

##### 2.2.2 Open-Source and Free Software

- OpenDSS: [An open source platform for collaborating on smart grid research](https://ieeexplore.ieee.org/abstract/document/6039829/)
- GridLAB-D: [GridLAB-D: an agent-based simulation framework for smart grids](https://onlinelibrary.wiley.com/doi/abs/10.1155/2014/492320)
- MATPOWER: [MATPOWER: Steady-state operations, planning, and analysis tools for power systems research and education](https://ieeexplore.ieee.org/abstract/document/5491276/?casa_token=bIrTPAgUO_cAAAAA:bKA5si00XcOPxfttZKlAqqxdD0ElFaX0vkNFJnYJ8DEnVejU0rtf5iQg2tJBCDZIt4pjHre5pQ)
- Pandapower: [Pandapower—an open-source python tool for convenient modeling, analysis, and optimization of electric power systems](https://ieeexplore.ieee.org/abstract/document/8344496/?casa_token=aftkjfBp4tgAAAAA:0sjrceRyDQC-Q71GWl44MJlTN44YbSfUzXo4j1D5VNLdkIf3WjsoQ8EiNcgYB8osUEaOzdBxAQ)
- PyPSA: [PyPSA: Python for power system analysis](https://arxiv.org/abs/1707.09913)
- PowerModels: [Powermodels.jl: An open-source framework for exploring power flow formulations](https://ieeexplore.ieee.org/abstract/document/8442948/?casa_token=qdWK1uJN4q8AAAAA:CiqLt6HF3T0C33gm1w3eQgCY4q57P-BsWIshBsk7xLeYkoVtMtb1qRGYvCtMAzk5Je8-zGvWXA)
- PST: [A toolbox for power system dynamics and control engineering education and research](https://ieeexplore.ieee.org/abstract/document/207380/?casa_token=K8sL3ZOTVzAAAAAA:EGDFZaVmpuRHe4NimGnUerFpOnBMWoQzs1HsttRJmXaymJsDXmJi-dVHtkhiYCrpcdVf_tE3xw), [Software and manual](https://sites.ecse.rpi.edu/~chowj/)
- PSAT: [An open source power system analysis toolbox](https://ieeexplore.ieee.org/abstract/document/1490569/?casa_token=q8slDw_b5LcAAAAA:FuVgexHv3Udh9MKmOT7Z2n5RHQo0mm_M1NHI3366Xlc0sYvKqiO_eHdy8ZJbnqZO-Olhvm9SzQ), [Software and manual](http://faraday1.ucd.ie/psat.html)
- PowerSimulations.jl: [PowerSystems.jl—A power system data management package for large scale modeling](https://www.sciencedirect.com/science/article/pii/S2352711021000765)
- PowerModelsDistribution.jl: [PowerModelsDistribution.jl: An open-source framework for exploring distribution power flow formulations](https://www.sciencedirect.com/science/article/pii/S0378779620304673)
- ANDES: [Hybrid symbolic-numeric framework for power system modeling and analysis](https://ieeexplore.ieee.org/abstract/document/9169830/?casa_token=nRHVqqx1u4AAAAAA:7GgeMu3A5-dV1rve_CGQmEQD9UZ9d0-d0Mq5dnEeR68lu0_Y0tP3HU070NBkXPP3_NLA4VCNhg)
- PowerSimulationsDynamics.jl: [PowerSimulationsDynamics.jl-An open source modeling package for modern power systems with inverter-based resources](https://arxiv.org/abs/2308.02921)
- Dynaωo: [Towards an open-source solution using Modelica for time-domain simulation of power systems](https://ieeexplore.ieee.org/abstract/document/8571872/?casa_token=uqtVkIPWN_8AAAAA:HDaSKMco_AhA5ttrBxiqTNRG8_kIJInOFQsgZ-DOJcffV4YUCW5b1VJDXlnJNJ2IrK4zazKdaw)

#### 2.3 Tailored Benchmarks for Power System

- OMG: [OMG: A scalable and flexible simulation and testing environment toolbox for intelligent microgrid control](https://joss.theoj.org/papers/10.21105/joss.02435.pdf)
- RLGC: [RLGC](https://github.com/RLGC-Project/RLGC), [Adaptive power system emergency control using deep reinforcement learning](https://ieeexplore.ieee.org/abstract/document/8787888/?casa_token=N1wqcnPRslEAAAAA:DTCT5V8fVXD84c3Oo5qE46JSiEPNZoUWStYyWpQnaYw4Tr7MjPnfdvbVPQcOcUj6swvNiQYobg)
- PowerGym: [PowerGym: A reinforcement learning environment for Volt-VAR control in power distribution systems](https://proceedings.mlr.press/v168/fan22a.html)
- OPF-Gym: [OPF-Gym](https://github.com/Digitalized-Energy-Systems/opfgym), [Learning the optimal power flow: Environment design matters](https://www.sciencedirect.com/science/article/pii/S2666546824000764)
- CommonPower: [CommonPower](https://github.com/TUMcps/commonpower), [CommonPower: Supercharging machine learning for smart grids](https://ui.adsabs.harvard.edu/abs/2024arXiv240603231E/abstract)

### 3 Power System Applications of Safe RL

#### 3.1 Security Control

##### 3.1.1 Voltage Control

- [Data driven decentralized control of inverter based renewable energy sources using safe guaranteed multi-agent deep reinforcement learning](https://ieeexplore.ieee.org/abstract/document/10354415/)
- [Multi-agent safe graph reinforcement learning for PV inverters-based real-time decentralized volt/var control in zoned distribution networks](https://ieeexplore.ieee.org/abstract/document/10128717/)
- [Two-stage deep reinforcement learning for inverter-based Volt-VAR control in active distribution networks](https://ieeexplore.ieee.org/abstract/document/9274529/)
- [Safe off-policy deep reinforcement learning algorithm for Volt-VAR control in power distribution systems](https://ieeexplore.ieee.org/abstract/document/8944292/)
- [Volt-VAR control in power distribution systems with deep reinforcement learning](https://ieeexplore.ieee.org/abstract/document/8909741/)
- [Decentralized safe reinforcement learning for inverter-based voltage control](https://www.sciencedirect.com/science/article/pii/S037877962200685X)
- [Stability constrained reinforcement learning for real-time voltage control](https://ieeexplore.ieee.org/abstract/document/9867476/)
- [Physics-shielded multi-agent deep reinforcement learning for safe active voltage control with photovoltaic/battery energy storage systems](https://ieeexplore.ieee.org/abstract/document/9983850/)
- [Model-augmented safe reinforcement learning for Volt-VAR control in power distribution networks](https://www.sciencedirect.com/science/article/pii/S0306261922002148)
- [Online multi-agent reinforcement learning for decentralized inverter-based Volt-VAR control](https://ieeexplore.ieee.org/abstract/document/9356806/)
- [SAVER: Safe learning-based controller for real-time voltage regulation](https://ieeexplore.ieee.org/abstract/document/9917098/)
- [DNN assisted projection based deep reinforcement learning for safe control of distribution grids](https://ieeexplore.ieee.org/abstract/document/10334044/)
- [Safe deep reinforcement learning-based constrained optimal control scheme for active distribution networks](https://www.sciencedirect.com/science/article/pii/S0306261920302841)
- [Safe multi-agent deep reinforcement learning for real-time decentralized control of inverter based renewable energy resources considering communication delay](https://www.sciencedirect.com/science/article/pii/S0306261923010127)
- [Three-stage inverter-based peak shaving and Volt-VAR control in active distribution networks using online safe deep reinforcement learning](https://ieeexplore.ieee.org/abstract/document/9754695/)
- [Safety deep reinforcement learning approach to voltage control in flexible network topologies](https://ieeexplore.ieee.org/abstract/document/10595220/)
- [Explicit reinforcement learning safety layer for computationally efficient inverter-based voltage regulation](https://ieeexplore.ieee.org/abstract/document/10156201/)

##### 3.1.2 Stability Control

- [Reinforcement learning for optimal primary frequency control: A Lyapunov approach](https://ieeexplore.ieee.org/abstract/document/9779512/)
- [Online preventive control for transmission overload relief using safe reinforcement learning with enhanced spatial-temporal awareness](https://ieeexplore.ieee.org/abstract/document/10070802/)
- [Barrier function-based safe reinforcement learning for emergency control of power systems](https://ieeexplore.ieee.org/abstract/document/9683573/)
- [Bridging transient and steady-state performance in voltage control: A reinforcement learning approach with safe gradient flow](https://ieeexplore.ieee.org/abstract/document/10163934/)
- [Deep reinforcement learning-based active network management and emergency load-shedding control for power systems](https://ieeexplore.ieee.org/abstract/document/10210687/)
- [A safe policy learning-based method for decentralized and economic frequency control in isolated networked-microgrid systems](https://ieeexplore.ieee.org/abstract/document/9783051/)
- [AdapSafe: Adaptive and safe-certified deep reinforcement learning-based frequency control for carbon-neutral power systems](https://ojs.aaai.org/index.php/AAAI/article/view/25660)
- [Computationally efficient safe reinforcement learning for power systems](https://ieeexplore.ieee.org/abstract/document/9867652/)
- [Coordinated frequency control through safe reinforcement learning](https://ieeexplore.ieee.org/abstract/document/9916894/)
- [Coordinated wide-area damping control using deep neural networks and reinforcement learning](https://ieeexplore.ieee.org/abstract/document/9463673/)
- [Risk-constrained reinforcement learning for inverter-dominated power system controls](https://ieeexplore.ieee.org/abstract/document/10363432/)
- [Safe reinforcement learning for mitigation of model errors in facts setpoint control](https://ieeexplore.ieee.org/abstract/document/10257365/)
- [Stability-certified reinforcement learning: A control-theoretic perspective](https://ieeexplore.ieee.org/abstract/document/9296215/)
- [Recurrent neural network controllers synthesis with stability guarantees for partially observed systems](https://ojs.aaai.org/index.php/AAAI/article/view/20476)
- [A barrier-certificated reinforcement learning approach for enhancing power system transient stability](https://ieeexplore.ieee.org/abstract/document/10005839/)
- [Reinforcement learning for stability-guaranteed adaptive optimal primary frequency control of power systems using partially monotonic neural networks](https://ieeexplore.ieee.org/abstract/document/10947581/)

#### 3.2 Real-Time Operation

##### 3.2.1 Economic Dispatch

- [Learning to operate distribution networks with safe deep reinforcement learning](https://ieeexplore.ieee.org/abstract/document/9680706/)
- [Multi-agent safe policy learning for power management of networked microgrids](https://ieeexplore.ieee.org/abstract/document/9244070/)
- [Safe deep reinforcement learning for microgrid energy management in distribution networks with leveraged spatial–temporal perception](https://ieeexplore.ieee.org/abstract/document/10040615/)
- [Model-free economic dispatch for virtual power plants: An adversarial safe reinforcement learning approach](https://ieeexplore.ieee.org/abstract/document/10163055/)
- [A hybrid data-driven method for fast solution of security-constrained optimal power flow](https://ieeexplore.ieee.org/abstract/document/9709643/)
- [Robust energy management system with safe reinforcement learning using short-horizon forecasts](https://ieeexplore.ieee.org/abstract/document/10029882/)
- [Constrained reinforcement learning for predictive control in real-time stochastic dynamic optimal power flow](https://ieeexplore.ieee.org/abstract/document/10288542/)
- [Online operational decision-making for integrated electric-gas systems with safe reinforcement learning](https://ieeexplore.ieee.org/abstract/document/10266735/)
- [Real-time sequential security-constrained optimal power flow: A hybrid knowledge-data-driven reinforcement learning approach](https://ieeexplore.ieee.org/abstract/document/10086621/)
- [Online microgrid energy management based on safe deep reinforcement learning](https://ieeexplore.ieee.org/abstract/document/9659545/)
- [Distributed economic dispatch in microgrids based on cooperative reinforcement learning](https://ieeexplore.ieee.org/abstract/document/8306311)
- [Lyapunov-based safe reinforcement learning for microgrid energy management](https://ieeexplore.ieee.org/abstract/document/10795439)
- [Real-time optimal power flow method via safe deep reinforcement learning based on primal-dual and prior knowledge guidance](https://ieeexplore.ieee.org/abstract/document/10510660)
- [Feasibility constrained online calculation for real-time optimal power flow: A convex constrained deep reinforcement learning approach](https://ieeexplore.ieee.org/abstract/document/9944164)
- [Improved proximal policy optimization algorithm for sequential security-constrained optimal power flow based on expert knowledge and safety layer](https://ieeexplore.ieee.org/abstract/document/10316539/)
- [Networked multiagent-based safe reinforcement learning for low-carbon demand management in distribution networks](https://ieeexplore.ieee.org/abstract/document/10402056)
- [Optimal energy system scheduling using a constraint-aware reinforcement learning algorithm](https://www.sciencedirect.com/science/article/pii/S0142061523002879)
- [Real-time optimal power flow with linguistic stipulations: Integrating GPT-agent and deep reinforcement learning](https://ieeexplore.ieee.org/abstract/document/10339881)
- [Real-time optimal power flow: A Lagrangian based deep reinforcement learning approach](https://ieeexplore.ieee.org/abstract/document/9069289)
- [Safe reinforcement learning for multi-energy management systems with known constraint functions](https://www.sciencedirect.com/science/article/pii/S2666546822000738)
- [Secure energy management of multi-energy microgrid: A physical-informed safe reinforcement learning approach](https://www.sciencedirect.com/science/article/pii/S030626192300123X)
- [Safe multi-agent deep reinforcement learning for decentralized low-carbon operation in active distribution networks and multi-microgrids](https://www.sciencedirect.com/science/article/pii/S0306261925003393)
- [Active sensitivity coefficient-guided reinforcement learning for power grid real-time dispatching](https://www.sciencedirect.com/science/article/abs/pii/S0378779624011532)
- [Privacy-enhanced safe reinforcement learning for the dispatch of a local energy community](https://ieeexplore.ieee.org/abstract/document/10887028)
- [Carbon cap based multi-energy sharing among heterogeneous microgrids using multi-agent safe reinforcement learning method with credit assignment and sequential update](https://www.sciencedirect.com/science/article/abs/pii/S0306261925007482)
- [RL2: Reinforce large language model to assist safe reinforcement learning for energy management of active distribution networks](https://arxiv.org/abs/2412.01303)
- [Active sensitivity coefficient-guided reinforcement learning for power grid real-time dispatching](https://www.sciencedirect.com/science/article/abs/pii/S0378779624011532)
- [Multi-agent safe reinforcement learning based distributed optimal dispatch for active distribution network with incomplete information](https://ieeexplore.ieee.org/abstract/document/10838231)
- [Deep reinforcement learning approach for dynamic distribution network reconfiguration based on sequential masking](https://ieeexplore.ieee.org/abstract/document/11030288)

##### 3.2.2 System Restoration

- [Deep reinforcement learning from demonstrations to assist service restoration in islanded microgrids](https://ieeexplore.ieee.org/abstract/document/9705112)
- [Primal-dual differentiable programming for distribution system critical load restoration](https://ieeexplore.ieee.org/abstract/document/10252454)
- [Safe exploration reinforcement learning for load restoration using invalid action masking](https://ieeexplore.ieee.org/abstract/document/10253213)

#### 3.3 Operational Planning

##### 3.3.1 Unit Commitment

- [Deep reinforcement learning based unit commitment scheduling under load and wind power uncertainty](https://ieeexplore.ieee.org/abstract/document/9968131)
- [Risk-based reserve scheduling for active distribution networks based on an improved proximal policy optimization algorithm](https://ieeexplore.ieee.org/abstract/document/9992237/)

##### 3.3.2 Electricity Market

- [An augmented Lagrangian-based safe reinforcement learning algorithm for carbon-oriented optimal scheduling of EV aggregators](https://ieeexplore.ieee.org/abstract/document/10163488)
- [A budget-aware incentive mechanism for vehicle-to-grid via reinforcement learning](https://ieeexplore.ieee.org/abstract/document/10188695)
- [Dynamic incentive pricing on charging stations for real-time congestion management in distribution network: an adaptive model-based safe deep reinforcement learning method](https://ieeexplore.ieee.org/abstract/document/10298595)
- [SMA-PDPPO: Safe multiagent primal-dual deep reinforcement learning for industrial parks energy trading](https://ieeexplore.ieee.org/abstract/document/10812202)

#### 3.4 Emerging Areas

##### 3.4.1 EV Charging

- [Network-constrained reinforcement learning for optimal EV charging control](https://ieeexplore.ieee.org/abstract/document/10333926)
- [Data-driven coordinated charging for electric vehicles with continuous charging rates: A deep policy gradient approach](https://ieeexplore.ieee.org/abstract/document/9653670)
- [A deep reinforcement learning-based charging scheduling approach with augmented Lagrangian for electric vehicles](https://www.sciencedirect.com/science/article/pii/S0306261924020890)
- [A safe reinforcement learning-based charging strategy for electric vehicles in residential microgrid](https://www.sciencedirect.com/science/article/pii/S0306261923008541)
- [Constrained EV charging scheduling based on safe deep reinforcement learning](https://ieeexplore.ieee.org/abstract/document/8910361)
- [A deep reinforcement learning-based energy management framework with Lagrangian relaxation for plug-in hybrid electric vehicle](https://ieeexplore.ieee.org/abstract/document/9286514)
- [Safe deep reinforcement learning hybrid electric vehicle energy management](https://link.springer.com/chapter/10.1007/978-3-030-05453-3_8)
- [Rule-based shields embedded safe reinforcement learning approach for electric vehicle charging control](https://www.sciencedirect.com/science/article/pii/S014206152400084X)

##### 3.4.2 Building Energy Management

- [Reinforcement learning with dual safety policies for energy savings in building energy systems](https://www.mdpi.com/2075-5309/13/3/580)
- [Residual physics and post-posed shielding for safe deep reinforcement learning method](https://ieeexplore.ieee.org/abstract/document/9796122)
- [Optimal dispatch of an energy hub with compressed air energy storage: A safe reinforcement learning approach](https://www.sciencedirect.com/science/article/pii/S2352152X22021363)
- [A safe reinforcement learning approach for multi-energy management of smart home](https://www.sciencedirect.com/science/article/pii/S0378779622003443)
- [Deep reinforcement learning for tropical air free-cooled data center control](https://dl.acm.org/doi/abs/10.1145/3439332)
- [DRL-S: Toward safe real-world learning of dynamic thermal management in data center](https://www.sciencedirect.com/science/article/pii/S0957417422021649)
- [District cooling system control for providing operating reserve based on safe deep reinforcement learning](https://ieeexplore.ieee.org/abstract/document/10019581)
- [Safe building HVAC control via batch reinforcement learning](https://ieeexplore.ieee.org/abstract/document/9748006)
- [Safe reinforcement learning-based resilient proactive scheduling for a commercial building considering correlated demand response](https://ieeexplore.ieee.org/abstract/document/9371751/)
- [Safe reinforcement learning for real-time automatic control in a smart energy-hub](https://www.sciencedirect.com/science/article/pii/S030626192101638X)
- [Energy management based on safe multi-agent reinforcement learning for smart buildings in distribution networks](https://www.sciencedirect.com/science/article/pii/S0378778824005267)
- [Safe deep reinforcement learning for building energy management](https://www.sciencedirect.com/science/article/pii/S0306261924017112)
- [Green data center cooling control via physics-guided safe reinforcement learning](https://dl.acm.org/doi/abs/10.1145/3582577)
- [SafeCool: Safe and energy-efficient cooling management in data centers with model-based reinforcement learning](https://ieeexplore.ieee.org/abstract/document/10018918)
- [Toward model-assisted safe reinforcement learning for data center cooling control: A Lyapunov-based approach](https://dl.acm.org/doi/abs/10.1145/3575813.3597343)

### 4 Real-World Deployment Cases

- GT Auto Tuner: [GT Auto Tuner](https://www.siemens-energy.com/global/en/home/products-services/service/gt-autotuner.html)
- Building Cooling Systems: [Google](https://www.technologyreview.com/2018/08/17/140987/google-just-gave-control-over-data-center-cooling-to-an-ai/), [DeepMind](https://deepmind.google/discover/blog/safety-first-ai-for-autonomous-data-centre-cooling-and-industrial-control/), [Controlling commercial cooling systems using reinforcement learning](https://arxiv.org/abs/2211.07357), [TELUS and Vector Institute](https://www.telus.com/en/about/news-and-events/media-releases/using-ai-for-good-telus-and-vector-institute-partner-to-reduce-climate-impacts-from-data-centres), [SAB](https://techblog.foobot.io/hvac/control/ai/reinforcement_learning/sab_after_9.html)
- DeepThermal: [Deepthermal: Combustion optimization for thermal power generating units using offline reinforcement learning](https://ojs.aaai.org/index.php/AAAI/article/view/20393)

## Publication

If you find the repository useful, please cite the [paper](https://arxiv.org/abs/2407.00304):

```
@article{su2024review,
  title={A review of safe reinforcement learning methods for modern power systems},
  author={Su, Tong and Wu, Tong and Zhao, Junbo and Scaglione, Anna and Xie, Le},
  journal={arXiv preprint arXiv:2407.00304},
  year={2024}
}
```

