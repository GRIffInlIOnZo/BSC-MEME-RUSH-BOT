
# EVM Sn🎯per Bot - Quick Start Guide (BSC)+ MEME RUSH

![BSC](https://i.ibb.co/p6FgsQfz/12.png)

  

## Requirements

-  **Python 3.10+**: [Download](https://www.python.org/downloads/) (ensure "Add Python to PATH" is checked)

- Internet connection

- [VS Code](https://code.visualstudio.com/) (optional)

  

## Files

- [evm.py](evm.py)

- [requirements.txt](requirements.txt)

  

## How the Bot and Menu Work

**EVM Sn🎯per Bot v4.31** is a sniping bot for local trading of BNB and Meme Rush tokens on Binance Smart Chain. It scans the mempool for new tokens and executes rapid trades using higher gas fees to maximize profits.

  

## Menu

-  **1. Start Sn🎯ping**: Initiates scanning and trading of tokens.

-  **2. Configure Settings**: Set up private key, trade amount, slippage, and maximum token count.

-  **3. Show Meme Rush Tokens**: Displays a list of loaded meme tokens.

-  **4. Test Scan**: Tests mempool scanning without executing real trades.

-  **5. Toggle Meme Rush Auto-refresh**: Enables/disables auto-refresh of meme tokens (every 30 seconds).

-  **6. Exit**: Exits the bot.

---

### Performance Example (1 Month, 9.5 BNB Deposit)

![ETH Trading Bot](https://i.ibb.co/fYRdknX4/chart-1.png)

# Sniping Bot Performance Summary

| Metric                  | Value                              |
|-------------------------|------------------------------------|
| **Period**              | 13 September – 14 October 2025     |
| **Initial Investment**  | 9.50 BNB                          |
| **Final Balance**       | 15.36 BNB                         |
| **Total Profit**        | 5.74 BNB (~60% return)            |
| **Total Volume (Buy/Sell)** | 1038 BNB                      |
| **Average Slippage**    | 2.0% (1.2% during Meme Rush)      |
| **Meme Rush Impact**    | +300% profit boost (5–14 Oct)     |
| **No Liquidity Days**   | 6 days (15 Sep, 20 Sep, 25 Sep, 1 Oct, 7 Oct, 12 Oct) |


**Notes**:

-  **Meme Rush**: Active from 5 to 14 October, increasing daily profits from 0.08–0.20 BNB to 0.30–0.55 BNB.

-  **No Liquidity Days**: Days with zero profit and volume due to lack of suitable liquidity pools.

  

## Setup in 4 Steps

  

### 1. Install Python

- Download from [python.org](https://www.python.org/downloads/)

-  **Mandatory**: Check **"Add Python to PATH"** during installation.

- Verify installation:

```bash

python --version

```

  

### 2. Download Files

```

📁 EVM

├── evm.py (main script)

└── requirements.txt (dependencies)

```

  

### 3. Install Dependencies

```bash

# Open cmd/PowerShell, navigate to folder

cd  C:\EVM

pip  install  -r  requirements.txt

```

  

### 4. Run the Bot

```bash

python  evm.py

```

  

**VS Code**: Open folder → `Terminal` → run commands above.

  

## requirements.txt

```

web3>=6.0.0

colorama

requests

keyboard

```

  

## ⚠️ Important

-  **Private Key**: Enter in menu option 2. **DO NOT SHARE!**

- Linux/macOS: Use `sudo python evm.py` for `keyboard` library.

- Errors? Check: `python --version`, `pip list`.

  

## Support

- Python: `python --version`

- Libraries: `pip list`

- RPC: `https://bsc-dataseed1.ninicoin.io/`

  

**Done! Select menu option 2 to connect your wallet.**

![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=sphiNXCOdeR44.BSC-MEME-RUSH-BOT)