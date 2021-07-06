## CHAPTER 1 Introduction to Cryptography and Cryptocurrencies [page...1]

#### 1.1. CRYPTOGRAPHIC HASH FUNCTIONS [page...34]

- Property 1: Collision Resistance
- Property 2: Hiding
- Property 3: Puzzle Friendliness
- SHA-256

#### 1.2. HASH POINTERS AND DATA STRUCTURES [page...45]

- Block Chain
- Merkle Trees
- Proof of Membership
- Proof of Nonmembership

#### 1.3. DIGITAL SIGNATURES [page...50]

- Practical Concerns
- ECDSA

#### 1.4. PUBLIC KEYS AS IDENTITIES [page...55]

- Decentralized Identity Management

#### 1.5. TWO SIMPLE CRYPTOCURRENCIES [page...58]

- Goofycoin
- Scroogecoin

#### 1.6.  FURTHER READING [page...64]

## CHAPTER 2 How Bitcoin Achieves Decentralization [page...27]

#### 2.1. CENTRALIZATION VERSUS DECENTRALIZATION [page...66]

#### 2.2. DISTRIBUTED CONSENSUS [page...68]

- Impossibility Results
- Breaking Traditional Assumptions

#### 2.3. CONSENSUS WITHOUT IDENTITY USING A BLOCK CHAIN [page...72]

- Implicit Consensus

#### 2.4. INCENTIVES AND PROOF OF WORK [page...24]

- Block Reward
- Transaction Fees
- Mining and Proof of Work
- Difficult to Compute
- Parameterizable Cost
- Trivial to Verify

#### 2.5. PUTTING IT ALL TOGETHER [page...88]

- Cost of Mining
- Getting a Cryptocurrency off the Ground
- The 51 Percent Attack

#### 2.6. FURTHER READING [page...95]

## CHAPTER 3 Mechanics of Bitcoin [page...51]

#### 3.1. BITCOIN TRANSACTIONS [page...96]

#### 3.2. BITCOIN SCRIPTS [page...101]

- Bitcoin Scripting Language
- Executing a Script
- What's Used in Practice
- Proof of Burn
- Pay-to-Script-Hash

#### 3.3. APPLICATIONS OF BITCOIN SCRIPTS [page...108]

- Escrow Transactions
- Green Addresses
- Efficient Micropayments
- Lock Time
- Smart Contracts

#### 3.4. BITCOIN BLOCKS [page...113]

#### 3.5. THE BITCOIN NETWORK [page...116]

- Size of the Network
- Storage Requirements
- Lightweight Nodes

#### 3.6. LIMITATIONS AND IMPROVEMENTS [page...122]

- Changing the Protocol

#### 3.7. FURTHER READING [page...127]

## CHAPTER 4 How to Store and Use Bitcoins [page...76]

#### 4.1. SIMPLE LOCAL STORAGE [page...128]

- Wallets
- Encoding Keys: Base 58 and QR Codes
- Vanity Addresses

#### 4.2. HOT AND COLD STORAGE [page...132]

- Hierarchical Deterministic Wallets
- Brain Wallet
- Paper Wallet
- Tamper-Resistant Device

#### 4.3. SPLITTING AND SHARING KEYS [page...138]

- Threshold Cryptography
- Multisignatures

#### 4.4. ONLINE WALLETS AND EXCHANGES [page...143]

- Online Wallets
- Bitcoin Exchanges
- Three Types of Risks
- Bank Regulation
- Proof of Reserve
- Proof of Liabilities

#### 4.5. PAYMENT SERVICES [page...151]

#### 4.6. TRANSACTION FEES [page...156]

#### 4.7. CURRENCY EXCHANGE MARKETS [page...158]

- Supply and Demand
- A Simple Model of Market Behavior

#### 4.8. FURTHER READING [page...163]

## CHAPTER 5 Bitcoin Mining [page...104]

#### 5.1. THE TASK OF BITCOIN MINERS [page...165]

- Finding a Valid Block
- Determining the Difficulty

#### 5.2. MINING HARDWARE [page...172]

- A Closer Look at SHA-256
- CPU Mining
- GPU Mining
- Disadvantages of GPU Mining
- Mining with Field-Programmable Gate Arrays
- Mining with Application-Specific Integrated Circuits
- Professional Mining Today
- Similarities to Gold Mining
- The Future
- The Cycle Repeats Itself

#### 5.3. ENERGY CONSUMPTION AND ECOLOGY [page...184]

- Thermodynamic Limits
- Mining at Scale
- Estimating Energy Usage
- Is Bitcoin Mining Wasteful?
- Repurposing Energy
- Turning Electricity into Cash

#### 5.4. MINING POOLS [page...190]

- High Variance
- Mining Pools
- Mining Shares
- Pay per Share
- Proportional
- Pool Hopping
- History and Standardization
- 51 Percent Mining Pools
- Are Mining Pools Beneficial?

#### 5.5. MINING INCENTIVES AND STRATEGIES [page...199]

- Forking Attack
- Forking Attack via Bribery
- Forking Attack via Bribery
- Blacklisting and Punitive Forking
- Blacklisting and Punitive Forking
- Open Problems

#### 5.6.  URTHER READING [page...206]

## CHAPTER 6 Bitcoin and Anonymity [page...138]

#### 6.1. ANONYMITY BASICS [page...208]

- Defining Anonymity
- Side Channels
- Unlinkability
- Anonymity Set
- Taint Analysis
- Why Anonymity Is Needed
- Ethics of Anonymity
- Anonymization versus Decentralization

#### 6.2. HOW TO DEANONYMIZE BITCOIN [page...215]

- Linking
- Idioms of Use
- Attaching Real-World Identities to Clusters
- Tagging by Transacting
- Identifying Individuals
- Network-Layer Deanonymization

#### 6.3. MIXING [page...225]

- Online Wallets as Mixes
- Dedicated Mixing Services
- Guidelines for Mixing
- Mixing in Practice

#### 6.4. DECENTRALIZED MIXING [page...231]

- CoinJoin
- High-Level Flows

#### 6.5. ZEROCOIN AND ZEROCASH [page...235]

- Zerocoin
- Zero-Knowledge Proofs
- Minting Zerocoins
- Trusted Setup
- Zerocash
- Setting Up Zerocash
- Putting It All Together

#### 6.6.  FURTHER READING [page...244]

## CHAPTER 7 Community, Politics, and Regulation [page...168]

#### 7.1. CONSENSUS IN BITCOIN [page...247]

#### 7.2. BITCOIN CORE SOFTWARE [page...249]

- Bitcoin Improvement Proposals
- Bitcoin Core Developers
- Forks in the Rules

#### 7.3. STAKEHOLDERS: WHO'S IN CHARGE? [page...253]

#### 7.4. ROOTS OF BITCOIN [page...256]

- Cypherpunk and Digital Cash
- Satoshi Nakamoto
- Growth

#### 7.5. GOVERNMENTS NOTICE BITCOIN [page...259]

- Capital Controls
- Crime
- Silk Road
- Lessons from Silk Road

#### 7.6. ANTI-MONEY LAUNDERING [page...264]

- Know Your Customer
- Mandatory Reporting

#### 7.7. REGULATION [page...266]

- Lemons Market
- Fixing a Lemons Market
- Regulatory Fixes
- Collusion and Antitrust Law

#### 7.8. NEW YORK'S BITLICENSE [page...270]

- Who's Covered
- Requirements

#### 7.9.  FURTHER READING [page...273]

## CHAPTER 8 Alternative Mining Puzzles [page...190]

#### 8.1. ESSENTIAL PUZZLE REQUIREMENTS [page...275]

#### 8.2. ASIC-RESISTANT PUZZLES [page...277]

- What Does ASIC Resistance Mean?
- Memory-Hard Puzzles
- Scrypt
- Time-Memory Trade-Offs
- Verification Cost
- Scrypt in Practice
- Other Approaches to ASIC Resistance
- The ASIC Honeymoon
- Arguments against ASIC Resistance

#### 8.3. PROOF OF USEFUL WORK [page...285]

- Previous Distributed Computing Projects
- Primecoin
- Permacoin and Proof of Storage
- Long-Term Challenges and Economics

#### 8.4. NONOUTSOURCEABLE PUZZLES [page...292]

- Technical Requirements for Pools
- Block-Discarding Attacks
- Rewarding Sabotage
- Pros and Cons of Nonoutsourceable Mining

#### 8.5. PROOF OF STAKE AND VIRTUAL MINING [page...296]

- Closing the Loop on Mining
- Advantages of Virtual Mining
- Implementing Virtual Mining: Peercoin
- Alternate Forms of Stake
- The Nothing-at-Stake Problem
- Other Drawbacks of Virtual Mining
- Can Virtual Mining Actually Work?

#### 8.6.  FURTHER READING [page...302]

## CHAPTER 9 Bitcoin as a Platform [page...213]

#### 9.1. BITCOIN AS AN APPEND-ONLY LOG [page...304]

- Secure Timestamping
- Applications of Timestamping
- Attacks on Proofs of 'Clairvoyance'
- Secure Timestamping the Old-Fashioned Way
- Secure Timestamping in Bitcoin
- Unspendable Outputs
- Illicit Content
- Overlay Currencies

#### 9.2. BITCOINS AS 'SMART PROPERTY' [page...312]

- Smart Property
- Colored Coins
- OpenAssets
- Uses of Colored Coins and Smart Property

#### 9.3. SECURE MULTIPARTY LOTTERIES IN BITCOIN [page...318]

- Coin Flipping Online
- Fairness

#### 9.4. BITCOIN AS A PUBLIC RANDOMNESS SOURCE [page...322]

- NBA Draft Lottery
- U.S. Military Draft Lottery
- Cryptographic Beacons
- National Institute of Standards and Technology Beacon
- Other Potential Ways to Build a Beacon: Natural Phenomena
- Financial Data
- Using Bitcoin as a Beacon
- Evaluating the Security of a Bitcoin Beacon
- Scripting Support for Beacons

#### 9.5. PREDICTION MARKETS AND REAL-WORLD DATA FEEDS [page...331]

- Decentralized Prediction Markets
- Payment and Settlement
- Prediction Market Arbitration
- Data Feeds
- Order Books

#### 9.6. FURTHER READING [page...340]

## CHAPTER 10 Altcoins and the Cryptocurrency Ecosystem [page...342]

#### 10.1. ALTCOINS: HISTORY AND MOTIVATION [page...342]
- Reasons for Launching Altcoins
- How to Launch an Altcoin
- Pump-and-Dump Scams
- Initial Allocation

#### 10.2. A FEW ALTCOINS IN DETAIL [page...348]

- Namecoin
- Litecoin
- Dogecoin

#### 10.3. RELATIONSHIP BETWEEN BITCOIN AND ALTCOINS [page...352]

- Comparing Altcoins
- Economic View of Bitcoin-Altcoin Interactions

#### 10.4. ALTCOIN INFANTICIDE AND MERGE MINING [page...355]

- Altcoin Infanticide
- Merge Mining
- Merge Mining and Security

#### 10.5. ATOMIC CROSS-CHAIN SWAPS [page...361]

#### 10.6. SIDECHAINS: BITCOIN-BACKED ALTCOINS [page...364]

- The SPV Trick
- Contesting a Transfer
- Compact SPV Proofs via Proof-of-Work Samples

#### 10.7. ETHEREUM AND SMART CONTRACTS [page...368]

- Smart Contract Programming Model
- A Simple Example: Namecoin in Ethereum
- Gas, Incentives, and Security
- A Second Example: Chess in Ethereum
- Other Applications
- Ethereum Project

#### 10.8. FURTHER READING [page...378]

## CHAPTER 11 Decentralized Institutions: The Future of Bitcoin? [page...272]

#### 11.1. THE BLOCK CHAIN AS A VEHICLE FOR DECENTRALIZATION [page...380]

- Motivating Example
- Get Smart
- Secure Exchange

#### 11.2. ROUTES TO BLOCK CHAIN INTEGRATION [page...383]

- Route 1: Directly on Bitcoin
- Route 2: Alternative Block Chains

#### 11.3. TEMPLATE FOR DECENTRALIZATION [page...388]

- Levels of Decentralization
- How Security Is Achieved
- The Framework

#### 11.4. WHEN IS DECENTRALIZATION A GOOD IDEA? [page...393]

- The Challenge of Real-World Security
- Pros and Cons of Smart Property
- Crypto, the State, and the Big Opportunity

## CONCLUSION [page...286]

## ACKNOWLEDGMENTS [page...287]

## ABOUT THE AUTHORS [page...289]
