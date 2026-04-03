│   1 # 🩺 Organ Donation Platform (Blockchain-Powered dApp)                                                                                           │
│   2                                                                                                                                                  │
│   3 [![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)](https://soliditylang.org/)  │
│   4 [![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white)](https://ethereum.org/)             │
│   5 [![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)                  │
│   6 [![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)      │
│   7                                                                                                                                                  │
│   8 A decentralized, transparent, and secure platform built on the **Ethereum Blockchain** to connect organ donors and recipients. This project      │
│     eliminates the inefficiencies and lack of trust in traditional organ donation systems by using immutable smart contracts.                        │
│   9                                                                                                                                                  │
│  10 ---                                                                                                                                              │
│  11                                                                                                                                                  │
│  12 ## 🌟 Key Features                                                                                                                               │
│  13                                                                                                                                                  │
│  14 - **🔗 Blockchain Transparency:** All donor, patient, and pledge records are stored on the Ethereum blockchain via Smart Contracts, ensuring     │
│     they are tamper-proof and auditable.                                                                                                             │
│  15 - **🛡️ Secure Matching:** Integrated algorithm to match donors with recipients based on blood type and organ compatibility.                      │
│  16 - **🤖 ML Success Predictor:** Uses a **Machine Learning (Logistic Regression)** model to estimate the success probability of a transplant based │
│     on donor/recipient health metrics.                                                                                                               │
│  17 - **🌍 Multi-Language Support:** Fully localized in **English** and **Hindi** to increase accessibility.                                         │
│  18 - **🌓 Dark & Light Mode:** A modern, user-friendly interface with a premium **Glassmorphism** design.                                           │
│  19 - **💬 Integrated Chatbot:** A helpful assistant to guide users through the donation process and answer FAQs.                                    │
│  20 - **📊 Impact Dashboard:** Real-time statistics on organ availability, donor growth, and platform impact.                                        │
│  21                                                                                                                                                  │
│  22 ---                                                                                                                                              │
│  23                                                                                                                                                  │
│  24 ## 🛠️ Technology Stack                                                                                                                           │
│  25                                                                                                                                                  │
│  26 | Layer | Technologies |                                                                                                                         │
│  27 |---|---|                                                                                                                                        │
│  28 | **Blockchain** | Ethereum, Solidity (Smart Contracts) |                                                                                        │
│  29 | **Development** | Truffle Suite, Ganache (Local Blockchain) |                                                                                  │
│  30 | **Frontend** | HTML5, CSS3 (Bootstrap 5, Glassmorphism), JavaScript (Web3.js) |                                                                │
│  31 | **Backend** | Node.js |                                                                                                                        │
│  32 | **Machine Learning** | Logistic Regression (Success Prediction) |                                                                              │
│  33 | **Localization** | Custom I18n JavaScript implementation |                                                                                     │
│  34                                                                                                                                                  │
│  35 ---                                                                                                                                              │
│  36                                                                                                                                                  │
│  37 ## 🚀 Getting Started                                                                                                                            │
│  38                                                                                                                                                  │
│  39 ### Prerequisites                                                                                                                                │
│  40                                                                                                                                                  │
│  41 Ensure you have the following installed:                                                                                                         │
│  42 - [Node.js](https://nodejs.org/) (LTS Version)                                                                                                   │
│  43 - [Truffle](https://www.trufflesuite.com/truffle) (`npm install -g truffle`)                                                                     │
│  44 - [Ganache](https://www.trufflesuite.com/ganache) (Desktop application)                                                                          │
│  45 - [MetaMask](https://metamask.io/) (Browser extension)                                                                                           │
│  46                                                                                                                                                  │
│  47 ### Installation & Setup                                                                                                                         │
│  48                                                                                                                                                  │
│  49 1. **Clone the repository:**                                                                                                                     │
│  50    ```bash                                                                                                                                       │
│  51    git clone https://github.com/your-username/organ-donation-platform.git                                                                        │
│  52    cd organ-donation-platform                                                                                                                    │
│  53    ```                                                                                                                                           │
│  54                                                                                                                                                  │
│  55 2. **Install Dependencies:**                                                                                                                     │
│  56    ```bash                                                                                                                                       │
│  57    cd app                                                                                                                                        │
│  58    npm install                                                                                                                                   │
│  59    ```                                                                                                                                           │
│  60                                                                                                                                                  │
│  61 3. **Configure Ganache:**                                                                                                                        │
│  62    - Open Ganache and select "New Workspace".                                                                                                    │
│  63    - Add the `truffle-config.js` file from the root directory to the workspace.                                                                  │
│  64    - Click "Save Workspace".                                                                                                                     │
│  65                                                                                                                                                  │
│  66 4. **Deploy Smart Contracts:**                                                                                                                   │
│  67    - In your terminal (root directory), run:                                                                                                     │
│  68    ```bash                                                                                                                                       │
│  69    truffle compile                                                                                                                               │
│  70    truffle migrate                                                                                                                               │
│  71    ```                                                                                                                                           │
│  72                                                                                                                                                  │
│  73 5. **Start the Development Server:**                                                                                                             │
│  74    ```bash                                                                                                                                       │
│  75    cd app                                                                                                                                        │
│  76    npm run dev                                                                                                                                   │
│  77    ```                                                                                                                                           │
│  78                                                                                                                                                  │
│  79 6. **Access the App:**                                                                                                                           │
│  80    Open your browser and navigate to `http://localhost:8080`.                                                                                    │
│  81                                                                                                                                                  │
│  82 ---                                                                                                                                              │
│  83                                                                                                                                                  │
│  84 ## 📸 Screenshots                                                                                                                                │
│  85                                                                                                                                                  │
│  86 ### 🏠 Homepage (Glassmorphism Design)                                                                                                           │
│  87 The redesigned landing page with clear CTA and multi-language support.                                                                           │
│  88                                                                                                                                                  │
│  89 ### 📊 Dashboard                                                                                                                                 │
│  90 Centralized access to donor registration, patient registration, and matching features.                                                           │
│  91                                                                                                                                                  │
│  92 ### 🧠 ML Prediction                                                                                                                             │
│  93 Transplant success probability estimation using donor and recipient compatibility data.                                                          │
│  94                                                                                                                                                  │
│  95 ---                                                                                                                                              │
│  96                                                                                                                                                  │
│  97 ## 📜 Smart Contract Overview                                                                                                                    │
│  98                                                                                                                                                  │
│  99 The project uses `DonorContract.sol` which handles:                                                                                              │
│ 100 - **Pledge Management:** Allowing individuals to pledge their organs.                                                                            │
│ 101 - **Registration:** Securely registering donors and patients.                                                                                    │
│ 102 - **Matching Logic:** Mapping donors to patients based on medical criteria.                                                                      │
│ 103 - **Verification:** Administrative verification of pledges.                                                                                      │
│ 104                                                                                                                                                  │
│ 105 ---                                                                                                                                              │
│ 106                                                                                                                                                  │
│ 107 ## 🤝 Contributing                                                                                                                               │
│ 108                                                                                                                                                  │
│ 109 Contributions are welcome! Please feel free to submit a Pull Request.                                                                            │
│ 110                                                                                                                                                  │
│ 111 1. Fork the Project                                                                                                                              │
│ 112 2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)                                                                         │
│ 113 3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)                                                                               │
│ 114 4. Push to the Branch (`git push origin feature/AmazingFeature`)                                                                                 │
│ 115 5. Open a Pull Request                                                                                                                           │
│ 116                                                                                                                                                  │
│ 117 ---                                                                                                                                              │
│ 118                                                                                                                                                  │
│ 119 ## ⚖️ License                                                                                                                                    │
│ 120                                                                                                                                                  │
│ 121 Distributed under the MIT License. See `LICENSE` for more information.                                                                           │
│ 122                                                                                                                                                  │
│ 123 ---                                                                                                                                              │
│ 124                                                                                                                                                  │
│ 125 <p align="center">Made with ❤️ for a Better Future</p>   
