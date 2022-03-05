# SmartConDetect: Highly Accurate Smart Contract Code Vulnerability Detection Mechanism using BERT

### Sowon Jeon, Gilhee Lee, Hyoungshick Kim and Simon S.Woo. _"Design and Evaluation of Highly AccurateSmart Contract Code Vulnerability Detection Framework"_. Data Mining and Knowledge Disovery. 2022



SmartConDetect is a detection mechanism of smart contract code vulnerability.
In this repository, we provide the code gadget of SmartConDataset, extracted function from 10,000 smart contract codes with the 23 vulnerability labels. 

## Overview of Training Process
![Training- SmartConDetect](https://user-images.githubusercontent.com/20153350/156878806-7eaf66b9-303a-4102-9348-dfff1b02eaf5.png)

## Details of Dataset Collection

- We collected 10,000 Solidity files from Etherscan. 
- We have crawled the Solidity files using BeautifulSoup{~\cite{Beautifulsoup}} from April 2021 to May 2021. 
- We have labeled the 23 different vulnerability classes, leveraging the outputs from SmartCheck as the ground truth. 
