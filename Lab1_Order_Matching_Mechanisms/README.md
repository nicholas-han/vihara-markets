# Lab 1: Order Matching Mechanisms

---

### Core Research Question

Why do most exchanges use Continuous Limit Order Books?

Is Continuous Matching really optimal?

What alternative matching mechanisms exist?

---

## Research Objectives

To understand and compare

1. Continuous Double Auction (CDA)
2. Call Auction
3. Frequent Batch Auction (FBA)
4. Automated Market Makers (AMM)
5. RFQ Markets

To analyze their variations in

* Liquidity
* Price Discovery
* Market Quality
* Fairness
* Latency Sensitivity
* Information Efficiency

---

# Phase 1: Build a Mental Model

Duration: Month 1

Goal: To establish a full map of matching mechanisms

建立完整的撮合机制地图。

---

### Mechanism A: Continuous Double Auction (CDA)

Examples:

* Binance
* Coinbase
* Nasdaq
* NYSE

Characteristics:

* Continuous matching
* Price-time priority
* Dominant modern exchange model

---

### Mechanism B: Call Auction

Examples:

* Tokyo Stock Exchange Open
* Shanghai Stock Exchange Open
* Hong Kong Exchange Open

Characteristics:

* Periodic matching
* Single clearing price

---

### Mechanism C: Frequent Batch Auction

Examples:

* IEX research direction

Characteristics:

* Orders aggregated into batches
* Reduce latency advantage

---

### Mechanism D: AMM

Examples:

* Uniswap
* Curve

Characteristics:

* No order book
* Mathematical pricing

---

### Mechanism E: Request for Quotes (RFQ)

Examples:

* Paradigm
* OTC Markets

Characteristics:

* Quote-based
* Bilateral execution

---

# Reading List

## Must Read Book: _Trading and Exchanges_

Author: Larry Harris

Focus Chapters:

* Market Structure
* Liquidity
* Traders
* Auctions

Goal:

Build market microstructure intuition.

---

# Must Read Papers

## Paper 1: _The High-Frequency Trading Arms Race_

Author: Eric Budish

Core Question:

Does continuous trading create an unnecessary latency race?

Key Concept:

Frequent Batch Auctions

---

## Paper 2: _Continuous Auctions and Insider Trading_

Author: Albert Kyle

Year: 1985

Core Question: How does information enter prices?

Key Concept: Kyle Lambda

---

## Paper 3: _Bid, Ask and Transaction Prices in a Specialist Market_

Authors: Glosten & Milgrom

Year: 1985

Core Question: Why does bid-ask spread exist?

Key Concept: Adverse Selection

---

# Phase 2: Build a Matching Simulator

Duration: Month 2

Goal: Implement multiple matching mechanisms under identical order flow.

---

### Experiment A: Continuous Auction

Implement:

* Limit Orders
* Market Orders
* Price-Time Priority

---

### Experiment B: Call Auction

Implement:

* Order Collection
* Clearing Price Determination

---

### Experiment C: Frequent Batch Auction

Implement:

* Batch Interval
* Uniform Clearing

---

# Metrics

Compare:

* Fill Rate
* Spread
* Price Impact
* Volatility
* Execution Quality
* Welfare

Goal:

Understand trade-offs between mechanisms.

---

# Phase 3: Real-World Case Studies

Duration: Month 3

---

### Case Study 1: IEX

Research Question: Why introduce Speed Bumps?

---

### Case Study 2: Nasdaq

Research Question: Why maintain continuous auctions?

---

### Case Study 3: Hyperliquid

Research Question: What are the challenges of on-chain order books?

---

### Case Study 4: Uniswap

Research Question: Why abandon order books entirely?

---

# Deliverables at the end of Project 1

---

## Artifact 1: Matching Simulator

Including:

* CDA
* Call Auction
* FBA

---

## Artifact 2: Experiment Results

* Charts
* Metrics
* Comparisons

---

## Artifact 3: Research Report

Suggested title:

"Is Continuous Order Matching Really Optimal?"

or

"Comparing Continuous Auctions, Call Auctions and Frequent Batch Auctions in Modern Electronic Markets"

Length:

20–30 pages

---

# Acceptance Criteria

At the end of Project 1, I should be able to answer:

1. Why did most exchanges converge on Continuous Limit Order Books?

2. What are the weaknesses of Continuous Matching?

3. What problems are Frequent Batch Auctions trying to solve?

4. Why did DeFi evolve toward AMMs?

5. What matching mechanism might be optimal under different market environments?

If these questions can be answered rigorously with both theory and experiments, Project 1 is considered successful.

---