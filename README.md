# Numerical Methods for Exotic Derivatives
Instead of a traditional resume or cover letter, I wanted to showcase a hands-on project that demonstrates my ability to structure, price, and analyze exotic derivatives using numerical methods. This project highlights my abilities in applying theoretical concepts to practical problems in the derivatives space, particularly for exotic products such as barrier options, cliquets, variance swaps, and correlation-based structures. By no means does this project cover all aspects of derivatives pricing, but I hope it serves as a useful starting point for discussions about my skills and interests.

The goal of this notebook is not to serve as an exhaustive analysis or a purely academic exercise but rather to showcase my ability to:
- Implement numerical techniques like Monte Carlo simulation and finite difference methods.
- Handle complex derivative structures and path-dependent payoffs.
- Build reusable pricing frameworks for both vanilla and exotic options.

This project reflects my understanding of designing structured products to meet client needs while managing risk effectively. It also demonstrates my ability to work with numerical models that are critical for pricing and risk management in a trading environment. Although it might not be perfect or exhaustive, I hope this notebook sparks interesting conversations about the challenges and nuances of pricing exotic derivatives. Please feel free to skip sections that may seem too basic (e.g., vanilla options pricing) and focus on the parts most relevant to your interests.

Table of Contents:
1. Vanilla Options Pricing via Trees
    - Binomial Trees
    - Trinomial Trees
2. Finite Difference Methods
    - Crank-Nicolson Method
3. Monte Carlo
    - Naive Monte Carlo
    - Antithetic Variates
4. Exotics
    - Barrier Options
        - Barrier Options via Crank-Nicolson
        - Barrier Options via Monte Carlo
    - Correlation Products
        - Worst-of Options via Monte Carlo
        - Dispersion Options

Notes on the Project:
- Technical Complexity:
    We will try not to delve deeply into the mathematical concepts behind each method, but rather focus on the implementation and results. The goal is to provide a clear understanding of how each pricing method works.
- Code Design Philosophy:
    The code is written with clarity and functionality in mind. While I strive for readability, the focus here is on demonstrating the workings of each pricing method rather than creating a production-ready library.
- Greeks Calculation:
    While Greeks are essential for risk management, I have omitted their implementation here for brevity. They can be easily computed by perturbing input parameters (e.g., delta by shifting the underlying price) and recalculating prices.

Cheers!
