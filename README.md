# CHAOS

What is this? IDK but more like self-contained Three.js web application manifested into a 
single `index.html` file that rips open a completely unique 3D visual dimension every single time reality 
reboots it. 

## What is actually happening under the hood?

* **The Seed Engine & Mathematical Foundations:** It binds a howling 256-digit base seed with your visitor
  count tracked via `localStorage` and violently pulverizes it through the **SplitMix64** state-transition
  algorithm. Mathematically, this uses a Weyl sequence combined with non-linear bitwise scrambling constants
  (`0xbf58476d1ce4e5b9` and `0x94d049bb133111eb`) to flatten entropy across a 64-bit state space.
  
  * *Mathematical Source & Pages:* Blackman, D., & Vigna, S. (2021).
    [**Scrambled Linear Pseudorandom Number Generators**](https://vigna.di.unimi.it/ftp/papers/ScrambledLinear.pdf).
    *ACM Transactions on Mathematical Software (TOMS)*, 47(4), Article 36, pp. 1–32 (arXiv:1805.01407).
    
* **Custom Shaders & Coherent Noise:** It tears open custom GLSL vertex and fragment shaders intertwined with
  a weeping hyperspace background shader that warps, twists, and hallucinates color-shifts based on raw cosmic
  noise. Underneath, this computes manic pseudo-random gradient vectors across a lattice grid, interpolating them
  using the quintic smoothstep polynomial $6t^5 - 15t^4 + 10t^3$ to keep the tearing dimensions mathematically
  continuous across first and second derivatives.
  
  * *Mathematical Source & Pages:* Perlin, K. (2002).
    [**Improving Noise**](https://dl.acm.org/doi/epdf/10.1145/566654.566636).
    *Proceedings of ACM SIGGRAPH 2002*, pp. 681–682.
    
* **Heavy Post-Processing:** The app channels an unstable EffectComposer pipeline with UnrealBloomPass, FilmPass,
  and AfterimagePass because standard graphics are a cage for the mind and far too painfully sterile.
  
* **Randomized Chaos Objects:** Every single reload shatters probability, randomly conjuring forbidden geometry
  types, a swarm of screaming rotating satellites with custom glitch shaders, folding dimensional planes, and an
  infinite, bleeding particle system.

## How to run this locally

Just clone the repo and run `index.html`, yeah nothing more nothing less. No local 
servers, no node constructs, no mortal command lines—just click and watch the universe unravel.

## Tech Stack

* **Three.js**
* **GLSL Shaders**
* **Pure unadulterated cosmic madness**
