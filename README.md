# degenics
Decentralized Genetics Project

### This file provides the concept document for the Degenics project.

Organizational repo for the project is at [Degenics](github.com/Degenics).

### Elevator Pitch

Degenics: The Decentralized Genetics Initiative
We are building a decentralized platform for your personal genetics.
Our concept allows synergy between labs of all scales while guaranteeing user anonymity and sovereignty at every step of the genomic data science workflow—
from sample collection, data storage, to report generation.

### Vision

We aim to democratize direct-to-consumer genomics with a privacy-preserving, anonymous-first platform running on a fully decentralized, autonomous infrastructure.

### MVP Vision

Degenics 1.0 (private deployment March 2021) will provide anonymous, decentralised sample collection, payment, data storage, and report distribution. 
TL;DR: a VPN for your DNA.

### Who we are

Degenics is a group of IT consultants, blockchain developers, and biologists who are passionate about privacy, decentralized technologies, and genomic data science.

* [Pandu Sastrowardoyo](github.com/Decentricity) - Initiator
* Gilang Bhagaskara - Tech Lead
* Jean-Daniel Gauthier - Product Lead
* Aaron Ting - Marketing Lead
* Bobby Andika - Dev Lead
* [Muhammad Arif](github.com/marcondol) - Back End and Blockchain
* Aloysius Dedy - Blockchain and Smart Contracts
* Kevin Janada - UI/UX
* Ibnu Gamal Alhadid - Advisor

### The Following Concept Description is licensed via [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/) to Pandu Sastrowardoyo / [Decentricity](github.com/Decentricity)

### Core Mechanism

## Trustless/Fully Decentralized Model

Anonymous Physical-Digital Bridge
Without having to enter KYC, the user activates the dApp and generates her passphrase. This forms the basis of her private key, and is paired with a sharable public key.

The user takes two samples -- a cheek swab to be practical-- and puts them into a sample bottle each. Each sample bottle is put into its own envelope.

dApp creates an envelope label that the user can either rewrite or print on the sample envelopes. This envelope label contains her public key, no personally identifiable information and no return address, but does contain 2 lab addresses to send samples to.

User sends the two envelopes via her local post office box.

## Decentralized Labs, Sovereign Data

The aforementioned labs analyze the sample and produce datasets (VCF file & analysis).

The platform compares datasets from the  two labs and checks the difference between select points in the data.

If there is more than 10% difference, the user is given the option to send in another sample. Sampling instructions are provided again.

If there is less than 10% difference between two output datasets. both are encrypted with the user's public key and put inside the platform (Blockchain + Decentralized Storage).

User is alerted, and can access her data at any time by decrypting via private key.

### Enterprise/Consortium Model
## Semi-Decentralized  Deployment with "Lab Marketplace"

An alternative deployment model would be the private / consortium deployment where labs are directly selected by the users.

This simplifies the workflow while maintaining the anonymity of the users. The labs get access to a commercial market, and the users still get an anonymous physical-to-digital bridge for their genomic data.

Additionally, after the initial on-ramp, the labs are free to up-sell additional analytics products to the users, without resampling.
