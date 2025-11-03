# Order Book Simulator

A lightweight Python simulation of an electronic limit order book — inspired by real-world market microstructure.  
Designed to explore how stochastic order flow and matching logic produce emergent price and volume behavior.

## Overview

This project simulates the dynamics of a simple exchange:
- Random buy/sell orders arrive following a **Poisson process**.
- Orders are matched using a **price-time priority** engine implemented with heaps.
- Executed trades are logged and analyzed for price evolution and volume.

The goal is to model short-term market microstructure phenomena like:
- Bid/ask spread behavior
- Mid-price evolution
- Volume accumulation and volatility clustering

---

## Repository Structure
