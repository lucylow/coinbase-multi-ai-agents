# COINBASE INTELLIGENCE

## Condensed Project Blueprint — 10-Page Edition

Autonomous Multi-Agent Financial Intelligence & Onchain Agent Economy

Coinbase Intelligence is a proposed multi-agent AI financial infrastructure platform combining Coinbase account connectivity, quantitative research, programmable wallets, Base smart contracts, decentralized agent identity, cryptographic research verification, and autonomous machine-to-machine payments.

Technology ecosystem: Coinbase Developer Platform (CDP) · Coinbase MCP · Advanced Trade API · Base · ERC-8004 · x402 · USDC · ERC-4337 · Solidity · TypeScript · Python · LangGraph · MCP · A2A

# PAGE 1 — PROJECT OVERVIEW

## 1.1 What is Coinbase Intelligence?

Coinbase Intelligence is a multi-agent AI platform designed to connect financial research with blockchain infrastructure.

Instead of relying on one AI assistant to analyze markets, interpret portfolio information, assess risk, and prepare transactions, the platform uses a coordinated network of specialist agents. Each agent has a defined responsibility, a limited set of permissions, and a structured output.

The platform combines five major capabilities:

1. Financial intelligence: Analyze authorized Coinbase account information, portfolio allocation, market conditions, and historical trading data.
2. Quantitative research: Calculate financial indicators, evaluate strategies, and run historical backtests.
3. Risk management: Assess portfolio exposure, test hypothetical market scenarios, and evaluate transaction proposals.
4. Blockchain infrastructure: Use Base smart contracts, programmable wallets, and onchain records.
5. Agent economy: Discover external AI services, evaluate agent reputation, purchase services through x402, and settle eligible jobs using USDC escrow.

## 1.2 The problem

Traditional cryptocurrency applications often separate portfolio analysis, trading tools, wallet management, blockchain analytics, and payment systems.

AI assistants can connect some of these capabilities, but several problems remain:

- Financial analysis may not use the user's actual authorized account data.
- AI-generated conclusions may lack independent numerical verification.
- Agents may have unclear or excessive permissions.
- Research results can be difficult to reproduce.
- External AI services can be difficult to evaluate.
- Blockchain operations may lack a unified application-level audit trail.
- Payments and service procurement are often disconnected from AI workflows.

## 1.3 The proposed solution

Coinbase Intelligence connects these functions through a coordinated architecture.

A typical workflow begins with a user request:

> Analyze my Coinbase portfolio, evaluate current market conditions, identify concentration risks, and prepare a hypothetical rebalancing strategy.

The platform can then:

1. Retrieve authorized portfolio information.
2. Collect relevant market data.
3. Calculate portfolio exposure and financial indicators.
4. Evaluate hypothetical strategies.
5. Request an independent verification.
6. Submit the findings for risk review.
7. Generate a structured research report.
8. Optionally create a cryptographic research receipt on Base.

The user receives an evidence-based report rather than an unsupported trading instruction.

## 1.4 Core design principles

- Coinbase-first infrastructure: Use Coinbase services for supported financial connectivity, wallet infrastructure, and payments.
- Specialized intelligence: Divide complex work among independent specialist agents.
- Verifiable outputs: Preserve evidence, calculations, assumptions, and cryptographic commitments.
- Constrained autonomy: Keep agent permissions separate from wallet authorization.
- Onchain accountability: Record important identities, research commitments, transactions, and settlements on Base.

# PAGE 2 — TECHNOLOGY STACK AND SYSTEM ARCHITECTURE

## 2.1 Core technology stack

| Technology                  | Purpose                                                  |
| --------------------------- | -------------------------------------------------------- |
| Coinbase Developer Platform | Wallet and blockchain infrastructure                     |
| Coinbase MCP                | Agent-oriented access to supported Coinbase capabilities |
| Advanced Trade API          | Market data and supported trading operations             |
| CDP Wallets                 | Programmable wallet infrastructure                       |
| CDP Policy Engine           | Transaction and signing restrictions                     |
| Base                        | Primary EVM blockchain                                   |
| Solidity                    | Smart-contract development                               |
| ERC-4337                    | Account abstraction                                      |
| ERC-8004                    | Agent identity, reputation, and validation               |
| x402                        | HTTP-native agent payments                               |
| USDC                        | Stablecoin settlement                                    |
| TypeScript                  | Main application and backend                             |
| Python                      | Quantitative research and analytics                      |
| PostgreSQL                  | Application and research data                            |
| Foundry                     | Smart-contract compilation and testing                   |
| LangGraph                   | Agent workflow orchestration                             |
| MCP and A2A                 | Agent tool and communication interfaces                  |

Official Coinbase developer documentation: [https://docs.cdp.coinbase.com/](https://docs.cdp.coinbase.com/?utm_source=chatgpt.com)

## 2.2 Six architectural layers

The system is organized into six interconnected layers.

| Layer                             | Responsibility                                             |
| --------------------------------- | ---------------------------------------------------------- |
| L1 — Coinbase Connectivity        | Authorized accounts, market data, and supported operations |
| L2 — AI Intelligence              | Agent research, analysis, and orchestration                |
| L3 — Programmable Wallets         | CDP accounts, permissions, and transaction controls        |
| L4 — Onchain Verification         | Base contracts, identity, and research attestations        |
| L5 — Agent Economy                | Discovery, reputation, x402, and escrow                    |
| L6 — Governance and Observability | Risk controls, authorization, auditing, and monitoring     |

## 2.3 High-level architecture

```
                    USER
                     |
                     v
             COINBASE INTELLIGENCE
                     |
             CHIEF ORCHESTRATOR
                     |
        +------------+-------------+
        |            |             |
        v            v             v
    PORTFOLIO      MARKET       QUANTITATIVE
     AGENT         AGENT         RESEARCH
        |            |             |
        +------------+-------------+
                     |
                     v
              SHARED EVIDENCE
                     |
                     v
                 RISK AGENT
                     |
                     v
             VERIFICATION AGENT
                     |
                     v
                FINAL REPORT
                     |
           +---------+---------+
           |                   |
           v                   v
      RESEARCH RECORD       OPTIONAL
                           TRANSACTION
           |                   |
           v                   v
       BASE NETWORK       CDP WALLET
           |
    +------+-------+
    |      |       |
    v      v       v
 IDENTITY RESEARCH ESCROW
 ERC-8004 HASHES  USDC
    |      |       |
    +------+-------+
           |
           v
      AGENT ECONOMY
```

## 2.4 Architectural boundaries

The platform separates responsibilities:

- The AI layer interprets requests and produces research.
- The Coinbase integration layer accesses authorized financial capabilities.
- The risk layer evaluates financial and transaction conditions.
- The wallet layer handles authorized signing.
- The blockchain layer records verifiable state.
- The payment layer manages permitted service payments.
- The audit layer preserves operational history.

An AI agent does not receive unrestricted control of the user's wallet simply because it can analyze financial information.

# PAGE 3 — MULTI-AGENT INTELLIGENCE ENGINE

## 3.1 Agent workforce

Coinbase Intelligence uses specialist agents rather than one general-purpose agent for every task.

| Agent                         | Primary responsibility                                         |
| ----------------------------- | -------------------------------------------------------------- |
| Chief Orchestrator            | Plans and coordinates workflows                                |
| Portfolio Analyst             | Evaluates authorized portfolio information                     |
| Market Intelligence Agent     | Analyzes Coinbase market data                                  |
| Quantitative Research Agent   | Performs statistical and mathematical analysis                 |
| Risk Officer                  | Evaluates portfolio and transaction risk                       |
| Verification Agent            | Independently checks calculations and evidence                 |
| Execution Quality Analyst     | Evaluates spreads, liquidity, and hypothetical execution costs |
| Backtesting Analyst           | Evaluates historical strategy performance                      |
| Smart Contract Security Agent | Reviews contract and blockchain-operation risks                |
| Reputation Analyst            | Evaluates agent reputation and feedback                        |
| Discovery Agent               | Finds external agent services                                  |
| Procurement Agent             | Coordinates authorized service purchases                       |
| Validation Coordinator        | Manages independent validation workflows                       |
| Escrow Coordinator            | Tracks funded jobs and milestones                              |
| Blockchain Auditor            | Verifies onchain transactions and events                       |

## 3.2 Agent responsibilities and isolation

Every agent receives a defined execution context containing:

- Agent ID and role.
- Task ID.
- Authorized capabilities.
- Tool permissions.
- Read and write permissions.
- Relevant context references.
- Execution timeout.
- Budget reference, where applicable.
- Required output schema.
- Audit metadata.

Agents do not automatically inherit the orchestrator's permissions.

The platform validates structured agent outputs before they enter the shared workflow.

## 3.3 Example agent output

```
interface AgentAssessment {
  agentId: string;
  taskId: string;

  status:
    | "pending"
    | "running"
    | "completed"
    | "failed";

  findings: Array<{
    id: string;
    summary: string;
    details: string;
    severity: "info" | "low" | "medium" | "high";
    evidenceRefs: string[];
  }>;

  assumptions: string[];
  limitations: string[];
  confidence: number;

  riskFlags: string[];
  dissentingOpinions: string[];

  sourceMode:
    | "demo"
    | "coinbase"
    | "base"
    | "mixed";

  completedAt?: string;
}
```

## 3.4 Orchestration workflow

The Chief Orchestrator:

1. Receives a user objective.
2. Classifies the request.
3. Identifies relevant data sources.
4. Builds a task graph.
5. Assigns work to specialist agents.
6. Runs independent research tasks.
7. Collects structured findings.
8. Triggers risk review.
9. Requests independent verification.
10. Produces the final report.

```
USER REQUEST
     |
     v
CHIEF ORCHESTRATOR
     |
     v
TASK PLANNER
     |
     +------> PORTFOLIO AGENT
     |
     +------> MARKET AGENT
     |
     +------> QUANT AGENT
     |
     v
SHARED EVIDENCE
     |
     v
RISK REVIEW
     |
     v
INDEPENDENT VERIFICATION
     |
     v
EVIDENCE VALIDATION
     |
     +---- Insufficient evidence
     |              |
     |              v
     |        ADDITIONAL RESEARCH
     |
     +---- Valid evidence
                    |
                    v
              FINAL REPORT
                    |
                    v
          OPTIONAL ATTESTATION
```

## 3.5 Communication and memory

Agents exchange typed task messages containing a message ID, task ID, sender, recipient, message type, payload, and timestamp.

The system uses separate memory scopes:

- Working memory: Current task context.
- Agent memory: Specialist execution history.
- Research memory: Previous analyses and results.
- Portfolio memory: Authorized historical snapshots.
- Protocol memory: Blockchain and contract information.
- Audit memory: Previous decisions and execution records.

Credentials and private keys are never stored in agent memory.

## 3.6 Independent verification

For important findings, the platform should use independent calculations wherever possible.

For example:

- The Quantitative Agent calculates historical volatility.
- The Verification Agent recalculates it.
- The Market Agent checks the underlying data.
- The Risk Officer evaluates its interpretation.

Agent agreement is not automatically proof of correctness. Evidence, methodology, and data quality remain essential.

# PAGE 4 — COINBASE PORTFOLIO INTELLIGENCE AND QUANTITATIVE RESEARCH

## 4.1 Coinbase connectivity

The platform uses separate integration adapters for:

- Coinbase MCP authorization.
- Advanced Trade API authentication.
- CDP wallet authentication.
- Base RPC access.

These capabilities and credentials are not interchangeable.

The integration layer discovers the capabilities actually available to an authorized connection rather than assuming every account supports every operation.

## 4.2 Portfolio intelligence

The Portfolio Analyst can retrieve authorized portfolio information and calculate:

- Total portfolio market value.
- Asset allocation.
- Concentration.
- Cash allocation.
- Portfolio drift.
- Asset exposure.
- Historical changes.
- Performance indicators where sufficient data exists.

The system distinguishes market value from cost basis, realized profit and loss, deposits, and withdrawals.

Where multiple Coinbase portfolios are supported, separate portfolio identifiers can be used to isolate research contexts.

## 4.3 Market intelligence

The Advanced Trade API provides documented access to supported market information.

Important data categories include:

| Data             | Analytical purpose           |
| ---------------- | ---------------------------- |
| Product metadata | Supported trading pairs      |
| Candles          | Historical OHLCV analysis    |
| Ticker           | Price monitoring             |
| Order book       | Liquidity and market depth   |
| Trades           | Market activity              |
| WebSocket feeds  | Streaming market information |
| Fills            | Execution history            |
| Fees             | Transaction-cost analysis    |

The platform normalizes market information into a common structure.

```
interface NormalizedMarketData {
  productId: string;

  price: string;
  bid?: string;
  ask?: string;
  volume?: string;

  source: "coinbase" | "demo";

  timestamp: string;
  receivedAt: string;

  stale: boolean;
}
```

All financial calculations should use decimal-safe arithmetic.

Market information must be checked for missing intervals, duplicate candles, invalid prices, timestamp inconsistencies, stale snapshots, and unexpected product identifiers.

Synthetic data must never be presented as live Coinbase information.

## 4.4 Quantitative Research Lab

The Quant Lab analyzes Coinbase trading pairs using historical data.

Supported analytical techniques include:

- Simple moving averages.
- Exponential moving averages.
- Relative Strength Index (RSI).
- Average True Range (ATR).
- Historical volatility.
- Rolling returns.
- Correlation and covariance.
- Maximum drawdown.
- Sharpe ratio.
- Value at Risk.
- Expected Shortfall, where data permits.

## 4.5 Strategy modules

Initial strategy research includes:

Moving Average Crossover: Evaluates signals generated by short- and long-term moving averages.

RSI Research: Examines configured momentum thresholds.

Momentum Strategy: Evaluates historical market direction over selected periods.

Volatility Filter: Evaluates risk conditions before hypothetical exposure is generated.

## 4.6 Backtesting pipeline

```
COINBASE HISTORICAL DATA
          |
          v
     DATA VALIDATION
          |
          v
    INDICATOR ENGINE
          |
          v
     STRATEGY LOGIC
          |
          v
  EXECUTION SIMULATOR
          |
          v
  FEES AND SLIPPAGE
          |
          v
  PORTFOLIO ACCOUNTING
          |
          v
  PERFORMANCE METRICS
          |
          v
 VERIFICATION AGENT
          |
          v
    RESEARCH REPORT
```

Backtesting must process data chronologically and prevent look-ahead bias.

Each simulation should document initial capital, order assumptions, fees, slippage, execution prices, position sizing, and exit conditions.

Results can include equity curves, drawdown curves, benchmark comparisons, trade histories, monthly returns, volatility metrics, and cost breakdowns.

Important: Historical backtest results do not guarantee future performance and should not be presented as forecasts.

# PAGE 5 — RISK MANAGEMENT AND TRANSACTION AUTHORIZATION

## 5.1 Financial Risk Engine

The Risk Engine evaluates portfolio-level and strategy-level exposure.

Its measurements can include:

- Asset concentration.
- Historical volatility.
- Asset correlation.
- Maximum drawdown.
- Historical Value at Risk.
- Expected Shortfall.
- Liquidity indicators.
- Scenario sensitivity.
- Portfolio drift.

Each result should include its assumptions, data source, and limitations.

## 5.2 Portfolio Stress Lab

The Stress Lab evaluates hypothetical scenarios, including:

- Bitcoin price declines.
- Ethereum price declines.
- Multi-asset market corrections.
- Volatility shocks.
- Wider bid-ask spreads.
- Liquidity deterioration.
- Changes in asset concentration.

These scenarios are analytical stress tests, not predictions of future market movements.

## 5.3 Transaction authorization architecture

Financial analysis and transaction authorization must remain separate.

```
           AI AGENT PROPOSAL
                   |
                   v
           SCHEMA VALIDATION
                   |
                   v
           CONTRACT ALLOWLIST
                   |
                   v
            BUDGET VALIDATION
                   |
                   v
             RISK ASSESSMENT
                   |
                   v
          CDP POLICY ENGINE
                   |
                   v
        SMART ACCOUNT PERMISSIONS
                   |
                   v
         TRANSACTION SIMULATION
                   |
                   v
            HUMAN APPROVAL
                   |
                   v
            CDP SIGNING
                   |
                   v
            BASE NETWORK
                   |
                   v
        INDEPENDENT VERIFICATION
```

## 5.4 Agent permissions

| Agent              | Read       | Research | Propose | Sign                    |
| ------------------ | ---------- | -------- | ------- | ----------------------- |
| Portfolio Analyst  | Yes        | Yes      | No      | No                      |
| Market Agent       | Yes        | Yes      | No      | No                      |
| Quant Agent        | Yes        | Yes      | Yes     | No                      |
| Risk Officer       | Yes        | Yes      | Veto    | No                      |
| Verification Agent | Yes        | Yes      | No      | No                      |
| Security Agent     | Blockchain | Yes      | Veto    | No                      |
| Execution Agent    | Authorized | Preview  | Yes     | No unrestricted signing |

The model cannot override wallet-level permissions or Coinbase policy restrictions.

## 5.5 Coinbase Policy Engine

The CDP Policy Engine provides a separate enforcement layer for supported wallet operations.

Possible restrictions include:

- Approved destination addresses.
- Approved contract operations.
- Transaction value conditions.
- UserOperation restrictions.
- Signing restrictions.

The precise rules depend on the configured Coinbase product and account type.

## 5.6 Emergency controls

The application should include a server-side blockchain write kill switch.

When activated, it:

- Stops new write requests.
- Prevents new payment authorization.
- Blocks new contract submissions.
- Preserves read-only operations.
- Records the reason for activation.

## 5.7 Transaction lifecycle

Every authorized transaction follows a controlled sequence:

1. Intent creation.
2. Policy validation.
3. Parameter verification.
4. Simulation where supported.
5. Explicit approval.
6. CDP signing.
7. Submission.
8. UserOperation tracking.
9. Receipt retrieval.
10. Post-execution verification.

Mainnet financial writes should remain disabled by default until separately reviewed and explicitly authorized.

# PAGE 6 — CDP WALLETS, BASE AND SMART CONTRACTS

## 6.1 Coinbase CDP Wallet infrastructure

Coinbase Intelligence uses CDP wallet infrastructure for programmable wallet operations.

Two principal account types are:

Externally Owned Account (EOA): Acts as the owner or signing account for applicable Smart Account configurations.

Smart Account: Provides programmable EVM transaction behavior, including supported batching, permissions, and optional gas sponsorship.

Smart Accounts use ERC-4337 account abstraction.

## 6.2 Smart Account architecture

```
              EOA OWNER
                  |
                  v
            SMART ACCOUNT
                  |
          +-------+-------+
          |       |       |
          v       v       v
       BATCHED  PROGRAMMABLE GAS
       CALLS    PERMISSIONS SPONSORSHIP
                  |
                  v
          ENTRYPOINT INFRASTRUCTURE
                  |
                  v
                BUNDLER
                  |
                  v
              BASE NETWORK
```

The platform should use appropriately separated accounts for application operations, agent service payments, testnet registration, research attestations, and escrow testing.

Agents do not automatically control separate Smart Accounts.

## 6.3 Why Base?

Base is the primary EVM blockchain for the platform.

It provides the execution environment for:

- Agent identity.
- Reputation.
- Validation.
- Research attestations.
- Merkle batch anchoring.
- Escrow.
- USDC settlement.
- Transaction monitoring.

## 6.4 Network configuration

| Network      | Chain ID | Intended use                                                     |
| ------------ | -------- | ---------------------------------------------------------------- |
| Base Mainnet | 8453     | Production reads and separately authorized production operations |
| Base Sepolia | 84532    | Development, testing, and testnet transactions                   |

The application must verify the actual chain identity through the configured RPC endpoint using `eth_chainId` before submitting transactions.

## 6.5 Smart contract inventory

| Contract                          | Purpose                                    |
| --------------------------------- | ------------------------------------------ |
| `AgentRegistry.sol`               | Internal agent identities and capabilities |
| `ResearchAttestationRegistry.sol` | Verifiable research commitments            |
| `ResearchBatchAnchor.sol`         | Merkle root anchoring                      |
| ERC-8004 Identity Registry        | Standardized agent identity                |
| ERC-8004 Reputation Registry      | Structured agent feedback                  |
| ERC-8004 Validation Registry      | Independent validation records             |
| `AgentJobEscrow.sol`              | Conditional milestone settlement           |

## 6.6 Contract responsibilities

AgentRegistry

Maintains internal agent IDs, wallet mappings, role metadata, capability hashes, registration status, and administrative permissions.

ResearchAttestationRegistry

Records task hashes, agent IDs, output hashes, evidence roots, dataset references, source modes, attestors, and timestamps.

It records cryptographic commitments; it does not independently certify that a report is factually correct.

ResearchBatchAnchor

Anchors multiple research artifact hashes under a Merkle root, including batch IDs, leaf counts, schema hashes, timestamps, and submitter information.

AgentJobEscrow

Manages buyers, providers, approved tokens, funded jobs, milestones, deadlines, deliverable hashes, disputes, claimable funds, and refunds.

## 6.7 Contract development

Use Solidity and Foundry for contract development.

Testing should cover:

- Access control.
- Reentrancy protection.
- Arithmetic.
- State transitions.
- Duplicate records.
- Invalid tokens.
- Unauthorized release.
- Refund accounting.
- Merkle proofs.
- ERC-8004 compatibility.

Contracts should not be described as professionally audited unless an independent audit has actually been completed.

# PAGE 7 — ERC-8004, RESEARCH ATTESTATIONS AND MERKLE VERIFICATION

## 7.1 ERC-8004 decentralized agent trust

ERC-8004 provides a standardized framework for agent identity, reputation, and validation.

The architecture uses three registries.

Identity Registry: Provides agent identities and registration references.

Reputation Registry: Records structured client feedback associated with agents.

Validation Registry: Records independent validation requests and responses.

The project should pin the exact ERC-8004 specification revision used by its implementation and test compatibility against that revision.

Official specification: [https://eips.ethereum.org/EIPS/eip-8004](https://eips.ethereum.org/EIPS/eip-8004?utm_source=chatgpt.com)

## 7.2 Agent identity

An agent reference can include its namespace, chain ID, and identity registry address.

Example:

```
eip155:84532:0x...
```

The agent's `agentId` is the token ID assigned by the identity registry.

An agent registration file can advertise:

- Name and description.
- Service endpoints.
- MCP support.
- A2A endpoints.
- x402 support.
- Wallet information.
- Supported trust mechanisms.
- Registration references.

An onchain registration does not automatically mean that an external service or endpoint is safe.

## 7.3 Agent reputation and validation

Reputation records can contain structured feedback about:

- Quality.
- Reliability.
- Availability.
- Accuracy.
- Response time.
- Service completion.

Validation records can identify the validator, agent ID, request hash, response, evidence reference, response hash, and timestamp.

Reputation scores and validation responses are evidence inputs, not guarantees of objective correctness. Sybil attacks and feedback manipulation remain possible.

## 7.4 Cryptographic research attestations

Completed research workflows can generate cryptographic receipts.

The purpose is to make research artifacts tamper-evident and independently checkable.

The attestation process is:

1. Complete agent research.
2. Collect source evidence.
3. Perform numerical verification.
4. Complete risk review.
5. Compile the final artifact.
6. Convert it into canonical JSON.
7. Generate a cryptographic hash.
8. Submit the commitment through an authorized wallet.
9. Record the transaction on Base.
10. Read back and verify the onchain record.

## 7.5 Research receipt

A research receipt can contain:

```
interface ResearchReceipt {
  receiptId: string;

  taskIdHash: string;
  agentId: string;

  outputHash: string;
  evidenceRoot: string;
  datasetSnapshotHash: string;

  sourceMode: string;

  chainId: number;
  contractAddress: string;

  transactionHash: string;
  blockNumber: string;

  verificationStatus:
    | "pending"
    | "verified"
    | "invalid";
}
```

The receipt preserves references to the research artifact, agent, dataset, evidence, and blockchain transaction.

## 7.6 Canonical hashing

The hashing service must use deterministic canonicalization.

It should consistently handle:

- Field ordering.
- Numeric precision.
- Timestamp format.
- String encoding.
- Schema version.
- Evidence references.

Keccak-256 can be used for EVM-oriented commitments.

Hashing is not encryption. Sensitive account data should not be published or committed in a way that creates avoidable privacy or correlation risks. Opaque references or random salts may be appropriate.

## 7.7 Merkle tree verification

Merkle trees allow multiple research artifacts to be represented by one root hash.

```
              MERKLE ROOT
              /         \
          HASH AB      HASH CD
           /  \         /  \
         H(A) H(B)    H(C) H(D)
          |    |       |    |
        REPORT REPORT REPORT REPORT
```

The system can:

1. Generate a canonical hash for each artifact.
2. Build a Merkle tree.
3. Calculate the root.
4. Anchor the root on Base.
5. Store the batch reference.
6. Generate inclusion proofs.
7. Verify an individual artifact against the anchored root.

This makes batch verification more efficient than submitting a separate onchain commitment for every research artifact.

Important distinction: A valid hash proves that an artifact matches a committed value. It does not prove that the analysis, source data, or conclusions are correct.

# PAGE 8 — X402 AGENT ECONOMY AND USDC ESCROW

## 8.1 Autonomous agent economy

Coinbase Intelligence extends beyond internal financial analysis.

It can discover external agents that provide specialized services, such as:

- Market research.
- Blockchain analytics.
- Data processing.
- Quantitative modeling.
- Independent validation.
- Security analysis.

External agents can advertise their identity, capabilities, wallet references, service endpoints, and payment support.

## 8.2 x402 payment infrastructure

x402 enables HTTP-native payments for protected services.

The platform can use Coinbase's CDP x402 tooling to support payment-enabled agent workflows.

A typical workflow:

```
         REQUEST SERVICE
                |
                v
         DISCOVER RESOURCE
                |
                v
         RECEIVE PAYMENT
           REQUIREMENT
                |
                v
         CHECK SPEND POLICY
                |
                v
         AUTHORIZE PAYMENT
                |
                v
         SUBMIT PAYMENT
                |
                v
         VERIFY PAYMENT
                |
                v
         ACCESS SERVICE
                |
                v
         RECEIVE DELIVERABLE
                |
                v
         VALIDATE RESULT
```

Relevant components include:

- `CdpX402Client`
- `createX402Server`
- `createCdpFacilitatorClient`
- CDP account signer adapters.
- CDP Bazaar service discovery.
- Explicit spend controls.

## 8.3 Payment controls

The platform should configure spending restrictions such as:

- Per-payment limits.
- Cumulative spending limits.
- Approved networks.
- Approved assets.
- Payee allowlists.

These controls must be explicitly configured. Environment variables alone do not enforce spending limits.

The Procurement Agent can recommend or coordinate a service purchase, but financial authorization remains outside the LLM.

## 8.4 Agent marketplace

The marketplace allows buyers to discover services, evaluate agent information, request work, and arrange payment.

The discovery-to-payment workflow is:

1. Identify the required capability.
2. Discover registered agents.
3. Inspect identity and service metadata.
4. Evaluate available reputation and validation records.
5. Check endpoint safety.
6. Compare service terms and costs.
7. Select a provider.
8. Authorize payment or create an escrow job.
9. Receive the deliverable.
10. Validate the result.

## 8.5 Immediate payment versus escrow

Immediate x402 payment is appropriate for eligible services where payment and access can occur within a simple request-response workflow.

USDC escrow is more suitable for larger jobs requiring milestones, deliverable checks, deadlines, disputes, or refunds.

These are different payment mechanisms and should not be treated as interchangeable.

## 8.6 AgentJobEscrow

The escrow contract manages:

- Buyer and provider addresses.
- Agent identity references.
- Approved payment token.
- Total funded amount.
- Milestone amounts.
- Deadlines.
- Deliverable hashes.
- Dispute status.
- Released payments.
- Refunds.

## 8.7 Milestone lifecycle

```
        JOB CREATED
             |
             v
        JOB FUNDED
             |
             v
       PROVIDER WORKS
             |
             v
      DELIVERABLE SUBMITTED
             |
             v
       BUYER REVIEWS WORK
             |
       +-----+------+
       |            |
       v            v
    ACCEPTED      DISPUTED
       |            |
       v            v
   RELEASE       RESOLUTION
    FUNDS            |
       |        +----+----+
       |        |         |
       |        v         v
       |     RELEASE    REFUND
       |        |         |
       +--------+---------+
                |
                v
            JOB CLOSED
```

## 8.8 Escrow security

The contract must enforce strict accounting rules:

- Accepted milestone amounts cannot exceed funded liabilities.
- A milestone cannot settle twice.
- Refunds cannot exceed refundable funds.
- Dispute allocations must equal the milestone amount.
- Unknown tokens must be rejected.
- Arbitrary recipients must not be able to withdraw funds.

# PAGE 9 — BACKEND, DATA, SECURITY AND OBSERVABILITY

## 9.1 Application architecture

The application uses a modular backend with separate services for financial connectivity, agent orchestration, research, risk, wallets, blockchain, and payments.

Suggested technologies:

- TypeScript and Node.js for application services.
- Python for quantitative analytics.
- PostgreSQL for persistent application data.
- Viem for EVM interactions.
- CDP SDK for Coinbase infrastructure.
- Solidity and Foundry for smart contracts.
- OpenTelemetry-compatible instrumentation for observability.

## 9.2 Core data entities

The backend should maintain structured records for:

Users and permissions: Authentication, account access, and authorization.

Agent profiles: Agent IDs, roles, capabilities, endpoints, and identity references.

Agent tasks: Task status, inputs, outputs, timestamps, and execution history.

Research artifacts: Reports, output hashes, evidence roots, dataset references, and source modes.

Portfolio snapshots: Authorized account data and timestamped valuations.

Market snapshots: Product identifiers, prices, timestamps, and provenance.

Backtests: Strategy versions, datasets, assumptions, metrics, and results.

Wallet records: Account addresses, chain IDs, and permission metadata.

Transactions: UserOperation hashes, transaction hashes, receipts, and execution status.

Escrow jobs: Buyers, providers, milestones, payment amounts, and settlement history.

## 9.3 API architecture

Example API categories:

| Endpoint                  | Purpose                          |
| ------------------------- | -------------------------------- |
| `/api/overview`           | Main dashboard                   |
| `/api/coinbase/status`    | Coinbase integration health      |
| `/api/coinbase/portfolio` | Authorized portfolio information |
| `/api/markets`            | Market data                      |
| `/api/agents`             | Agent information                |
| `/api/agents/investigate` | Research orchestration           |
| `/api/agents/tasks`       | Task history                     |
| `/api/quant/backtests`    | Strategy research                |
| `/api/risk/evaluate`      | Risk evaluation                  |
| `/api/cdp/wallets`        | Wallet metadata                  |
| `/api/cdp/policies`       | Policy management                |
| `/api/chain/network`      | Base network status              |
| `/api/chain/transactions` | Transaction history              |
| `/api/erc8004/agents`     | Agent identity                   |
| `/api/erc8004/reputation` | Reputation information           |
| `/api/erc8004/validation` | Validation requests              |
| `/api/attestations`       | Research receipts                |
| `/api/merkle/batches`     | Merkle batches                   |
| `/api/x402/resources`     | Paid resource discovery          |
| `/api/marketplace/agents` | Agent service discovery          |
| `/api/escrow/jobs`        | Escrow jobs                      |
| `/api/escrow/disputes`    | Dispute management               |

Every route must use authenticated access and validated request schemas.

CDP signing credentials and administrative secrets must never be exposed to browser code.

## 9.4 Security architecture

The fundamental security principle is to separate AI reasoning from financial authorization.

The LLM produces structured intents. Independent application services validate them. Coinbase policy controls and wallet permissions enforce restrictions. The user approves applicable operations. CDP handles authorized signing.

## 9.5 Threat model

The platform should defend against:

- Prompt injection.
- Malicious MCP resources.
- Malicious A2A endpoints.
- Untrusted agent registration metadata.
- Tool poisoning.
- Unauthorized transaction requests.
- Replayed approvals.
- Duplicate payments.
- Fake transaction receipts.
- Invalid agent identities.
- Sybil reputation attacks.
- Malicious token contracts.
- Smart Account permission abuse.
- Reentrancy.
- Webhook forgery.
- Blockchain reorganizations.
- Data poisoning.

External agent output must always be treated as untrusted.

External agents must not be allowed to modify wallet permissions, spending budgets, contract allowlists, user approvals, or signing credentials.

## 9.6 Transaction verification

Important blockchain operations should be verified through:

1. Expected chain ID.
2. Contract address.
3. Transaction hash.
4. Transaction receipt.
5. Block number.
6. Event logs.
7. Contract state readback.

A transaction hash existing does not automatically mean the operation succeeded.

The indexer should process events idempotently and retain block and transaction provenance.

## 9.7 Testing and observability

Application tests should cover authentication, API validation, orchestration, financial calculations, data provenance, and error handling.

Coinbase integration tests should cover MCP connectivity, capability discovery, Advanced Trade connectivity, CDP wallet initialization, policy validation, and x402 spend controls.

Smart-contract tests should cover identity, attestations, Merkle proofs, escrow funding, milestone release, disputes, and refunds.

Adversarial tests should cover prompt injection, replay transactions, invalid proofs, duplicate webhooks, unauthorized spending, and malicious contract calls.

Observability should track:

- Agent executions.
- LLM requests.
- Tool calls.
- Coinbase API latency.
- MCP failures.
- CDP wallet operations.
- Policy rejections.
- Blockchain confirmations.
- UserOperations.
- x402 settlements.
- Escrow events.
- Merkle verification.
- Validation outcomes.

An append-only audit ledger should record actors, agent IDs, task IDs, source references, authorization decisions, transaction intents, final transactions, outcomes, and timestamps.

# PAGE 10 — IMPLEMENTATION, DEPLOYMENT AND PROJECT ROADMAP

## 10.1 Development prerequisites

Suggested development environment:

- Node.js 22 or a version compatible with the installed CDP SDK.
- pnpm.
- Git.
- TypeScript.
- PostgreSQL.
- Python 3.11 or later for analytical services.
- Foundry.
- Coinbase Developer Platform account.
- Base Sepolia RPC access.
- Authorized testnet wallet configuration.

Use the versions pinned in the project's lockfiles.

## 10.2 Installation

Clone the repository:

```
git clone https://github.com/OWNER/coinbase-intelligence.git

cd coinbase-intelligence
```

Replace `OWNER` with the actual GitHub organization or username.

Install dependencies:

```
pnpm install
```

Build the application:

```
pnpm build
```

Start the development server:

```
pnpm dev
```

Create a local environment file:

```
cp .env.example .env.local
```

Populate only the configuration required for the integrations being enabled.

Never commit `.env.local` or expose private credentials in frontend code.

## 10.3 Coinbase configuration

The developer should:

1. Create or access a Coinbase Developer Platform project.
2. Configure supported API authentication.
3. Create the required wallet configuration.
4. Configure server-side API credentials.
5. Configure the appropriate network.
6. Set up the required Policy Engine restrictions.
7. Configure webhooks if enabled.
8. Validate connectivity.
9. Test supported account and market capabilities.

Developer portal: [https://portal.cdp.coinbase.com/](https://portal.cdp.coinbase.com/?utm_source=chatgpt.com)

## 10.4 Base contract development

Move into the contract directory:

```
cd contracts
```

Compile:

```
forge build
```

Run tests:

```
forge test
```

Before deploying to Base Sepolia, verify the chain ID:

```
cast chain-id --rpc-url "$BASE_SEPOLIA_RPC_URL"
```

Expected chain ID:

```
84532
```

Before broadcasting a deployment, verify:

- Contract constructor parameters.
- Token allowlists.
- Owner addresses.
- Authorized roles.
- Network identity.
- Deployment bytecode.
- Reviewed deployment scripts.

Never automatically deploy to Base Mainnet.

## 10.5 Application validation

Run the available application checks:

```
pnpm typecheck
pnpm lint
pnpm test
pnpm build
```

Run contract validation:

```
cd contracts

forge build
forge test
```

Only use commands that are actually defined by the repository and its installed dependencies.

## 10.6 Deployment modes

| Mode                  | Description                                  | Financial and blockchain writes |
| --------------------- | -------------------------------------------- | ------------------------------- |
| Demo                  | Synthetic portfolios and simulated workflows | Simulated only                  |
| Testnet               | CDP integrations and Base Sepolia            | Authorized testnet operations   |
| Production read-only  | Configured live data integrations            | Disabled by default             |
| Production authorized | Separately reviewed capabilities             | Explicitly authorized only      |

Demo mode can include:

- Synthetic Coinbase portfolios.
- Sample trading pairs.
- Historical candle fixtures.
- Agent investigations.
- Quantitative backtests.
- Risk scenarios.
- Example ERC-8004 identities.
- Simulated research attestations.
- Demonstration Merkle batches.
- Simulated x402 procurement.
- Escrow job examples.
- Simulated transaction lifecycles.

Every synthetic record must be clearly labeled as demonstration data.

## 10.7 Recommended implementation phases

Phase 1 — Core application

Build the dashboard, backend, authentication, database, configuration system, and application monitoring.

Phase 2 — Coinbase integration

Connect supported Coinbase account and market capabilities. Implement data normalization, source provenance, and portfolio analysis.

Phase 3 — Multi-agent intelligence

Implement the Chief Orchestrator, specialist agents, task state management, structured outputs, and independent verification.

Phase 4 — Quantitative research and risk

Implement financial indicators, historical backtesting, stress testing, portfolio exposure analysis, and transaction risk checks.

Phase 5 — CDP wallets and Base

Configure Smart Accounts, policy restrictions, network verification, contract deployment, transaction monitoring, and audit records.

Phase 6 — Agent identity and research verification

Implement ERC-8004 integration, reputation analysis, research attestations, canonical hashing, and Merkle batches.

Phase 7 — Agent economy

Implement service discovery, x402 payments, procurement controls, USDC escrow, milestone accounting, and dispute handling.

Phase 8 — Production hardening

Complete security testing, independent contract review, operational monitoring, recovery procedures, and deployment verification.

## 10.8 Deployment verification

For every deployed contract, preserve:

- Chain ID.
- Contract address.
- Deployment transaction hash.
- Block number.
- Compiler version.
- Deployment owner.
- ABI reference.
- Verified source link, where applicable.

Never use sample addresses or illustrative configuration values in production.

## 10.9 Project limitations and important distinctions

Coinbase Intelligence is an architecture and implementation blueprint. A capability described in this blueprint should not be treated as already deployed, operational, or independently audited without evidence.

Important limitations include:

- Blockchain verification establishes data integrity, not the factual correctness of AI conclusions.
- ERC-8004 reputation can be manipulated or affected by Sybil attacks.
- External agent registration does not guarantee endpoint safety.
- Backtests do not guarantee future trading performance.
- Smart contracts require independent security review.
- Coinbase product access depends on supported functionality, account eligibility, and configuration.
- x402 spend controls must be explicitly configured.
- Live financial execution requires properly scoped permissions and user authorization.
- Hashing does not encrypt sensitive financial information.

## 10.10 Final engineering principles

Coinbase Intelligence should remain:

- Coinbase-integrated.
- Modular.
- Type-safe.
- Evidence-driven.
- Blockchain-aware.
- Auditable.
- Secure by default.
- Explicit about data provenance.
- Restrictive about financial permissions.
- Transparent about uncertainty and limitations.

The central goal is to create a financial intelligence platform in which specialist AI agents can research, collaborate, verify findings, discover external services, and participate in controlled economic transactions—while financial authority remains protected by explicit policies, wallet permissions, and user approval.

END — COINBASE INTELLIGENCE | CONDENSED 10-PAGE PROJECT BLUEPRINT
