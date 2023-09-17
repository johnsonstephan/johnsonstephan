# Hi there, I'm Stephan.

- Solidity smart contract auditor and researcher
- Currently bug hunting and conducting research
- Completed the [Secureum Bootcamp](https://www.secureum.xyz/bootcamp/)
- Completed my [MSc in Blockchain and Digital Currency](https://www.unic.ac.cy/blockchain/msc-digital-currency/) at the University of Nicosia as a [Coinbase Scholar](https://www.unic.ac.cy/unic-and-coinbase-announce-awardees-of-their-scholarship-programme-for-minority-professionals/#:~:text=I%20chose%20to%20apply%20to%20the,accessibility%20of%20financial%20services)
- Previously a Vice President at Goldman Sachs, leading business development and strategic partnerships

Here's a bit more about [my story](https://stephanjohnson.substack.com/p/rebooted-dreams).

This is a public profile of my adventure as an auditor and researcher. Some of my projects and contributions are shared below.

[![Twitter: StephanJohnson_](https://img.shields.io/twitter/follow/StephanJohnson_?style=social)](https://twitter.com/stephanjohnson_)

## Table of Contents

1. [Smart Contracts](https://github.com/johnsonstephan#smart-contracts)
2. [Vulnerabilities and Safeguards](https://github.com/johnsonstephan#vulnerabilities-and-safeguards)
3. [Wargames](https://github.com/johnsonstephan#wargames)
4. [My Toolkit](https://github.com/johnsonstephan#my-toolkit)
5. [Community Contributions](https://github.com/johnsonstephan#community-contributions)

### Smart Contracts

[Here](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/smart-contracts) are various smart contracts I've developed, including:

- [NFT Marketplace: OpenWave](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/smart-contracts/erc721/custom-erc721-marketplace)
- [Custom NFT ERC721 Token](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/smart-contracts/erc721/custom-nft-erc721-token)
- [Custom ERC20 Token](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/smart-contracts/erc20/custom-erc20-token)
- [Token Depository and Receipt Token](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/smart-contracts/erc20/token-depository-and-receipt-token)

### Vulnerabilities and Safeguards

[Here](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/vulnerabilities-and-safeguards) is a compilation of projects that underline common vulnerabilities and exhibit how they can be exploited. For some, improved contracts are included, showcasing best practices to fortify the contract's security. Highlights include:

- [Formal Verification Overflow](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/vulnerabilities-and-safeguards/arithmetic-wraparounds/formal-verification-overflow)
- [CryptoBank Reentrancy](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/vulnerabilities-and-safeguards/reentrancy/cryptobank-reentrancy)
- [TX Origin Phishing](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/vulnerabilities-and-safeguards/phishing/tx-origin-phishing)
- [Token Minting Underflow](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/vulnerabilities-and-safeguards/arithmetic-wraparounds/token-minting-underflow)
- [ICO Overflow](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/vulnerabilities-and-safeguards/arithmetic-wraparounds/ico-overflow)
- [Beyond The Limit Overflow](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/vulnerabilities-and-safeguards/arithmetic-wraparounds/beyond-the-limit-overflow)
- [Timed Vault Overflow](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/vulnerabilities-and-safeguards/arithmetic-wraparounds/timed-vault-overflow)
- [Insecure Blockhash](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/vulnerabilities-and-safeguards/insecure-randomness/randomness-blockhash)
- [Guessing Random Numbers](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/vulnerabilities-and-safeguards/insecure-randomness/randomness-guessing)

### Wargames

[Here](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/wargames) are my solutions to blockchain security wargames, challenges, and capture the flag (CTF) competitions.

- [Ethernaut](https://github.com/johnsonstephan/smart-contract-security-researcher-portfolio/tree/main/wargames/ethernaut)

### My Toolkit

#### Security Tools

1. [Mythril](https://github.com/Consensys/mythril): I appreciate its extensibility, enabling me to script custom modules to detect specific vulnerabilities. For example, it can help in identifying a flawed external call that leads to a reentrancy attack.
2. [Slither](https://github.com/crytic/slither): I find it invaluable during preliminary code assessments, when I can run a static analysis to identify vulnerabilities without executing the code. For instance, it can highlight an uninitialized state variable (intended to hold the contract owner's address) to flag risk for a potential ownership takeover.
3. [Echidna](https://github.com/crytic/echidna): I value its holistic property-based testing approach which expands my toolkit beyond traditional unit testing to testing properties. One practical example is verifying that a transfer function consistently maintains the integrity of the total token supply.
4. [Manticore](https://github.com/trailofbits/manticore): I like to think of Manticore as my personal army of testers, leveraging symbolic execution to traverse all conceivable paths within a contract. For example, it can detect a multi-sig vulnerability that permits unauthorized fund withdrawals despite insufficient signature counts.
5. [Foundry](https://github.com/foundry-rs/foundry): Ultimately, I believe manual testing is the most powerful tool and Foundry enables me to generate POCs with simulated real-world contract interactions. It is useful for creating reports that go beyond outlining a theoretical weakness and requires the generation of tangible evidence for an exploit.

Others: [Surya](https://github.com/Consensys/surya), [Ethlint](https://github.com/duaraghav8/Ethlint)

#### Research Environment

- Linux Distribution: [ZIION](https://www.ziion.org). I enjoy using ZIION because it is tailored for smart contract security and minimizes the usual environment setup woes. It has dozens of pre-installed tools (ranging from decompilers to vulnerability scanners) that I enjoy using and it supports Solidity/EVM + Rust-based blockchains.
- IDE: [VS Code](https://code.visualstudio.com/). I appreciate the suites of great blockchain extensions. A few of my favorites include the [Solidity extension](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) to enable syntax highlighting and the [Solidity Visual Auditor](https://marketplace.visualstudio.com/items?itemName=tintinweb.solidity-visual-auditor) to visualize control flow graphs. For quick code review and testing I enjoy using [Remix](https://remix.ethereum.org) as well.

### Community Contributions

I value contributing back to the smart contract security community. Highlights include:

- [Awesome Uniswap v4 Hooks](https://github.com/johnsonstephan/awesome-uniswap-v4-hooks): I am the original creator of a comprehensive list of Uniswap v4 hooks and resources, which aimed to serve both seasoned researchers and emerging developers. Given the wealth of knowledge presented, a fellow community member updated their own similar resource with my contributions; I was credited as a contributor in a [pull request](https://github.com/fewwwww/awesome-uniswap-hooks/pull/11/files) where they deprecated [their previous awesome list](https://github.com/fewwwww/awesome-uniswap-hooks/tree/e20d477bd8f6c121e8a6edeb562a064c0038e705). The resource has been adopted by UniSwap and is included in their [v4 documentation](https://docs.uniswapfoundation.org/hooks/dev-resources).
- [Awesome-Smart-Contract-Security](https://github.com/saeidshirazi/Awesome-Smart-Contract-Security): I contributed to this list of resources for smart contract security via an audit of the repository's links - leading to the discovery and subsequent correction of non-functioning links.

## Contact Info

- Twitter - [@StephanJohnson\_](https://twitter.com/StephanJohnson_)
- Telegram - [StephanJohnson](https://t.me/StephanJohnson)
- Discord - [Stephan#0861](http://discordapp.com/users/809417928234762272)
- LinkedIn - [Stephan Johnson](https://www.linkedin.com/in/stephancjohnson/)
