# SAOIRSE
## Servizi di Assistenza Online per Informazioni Riservate sulla Salute ed Educazione 
(Online Assistance Services for Private Health and Education Information)

## Your data, your choice

Saoirse is a decentralized privacy-first platform for monetizing your health data. 

## Users

### Seller

Sellers join the platform to securely monetise sensitive information. There are also community elements that allow private peer-to-peer connections on issues that are often stigmatised. 

### Buyer

Buyers include healthcare insitutions, resaerch DAOs and other entities. These organisations can access large pools of data after purchasing a decryption key.

## Flow

- Seller logs in with their wallet
- They use ZKPass to generate that the healthcare data they want to reveal is accurate
- The 'public' data of these proofs is encrypted and posted onto IPFS
- The seller address is then added to a contract to be able to receive a share of funds each time a buyer purchases the data
- A buyer will deposit into a smart contract a fixed amount (right now) to access all encrypted data
- They will be added to smart contract storage as verified buyers and can receive a decryption key for all the data

## Tech stack

- ZKPass for generating proofs on healthcare data (eg Strava)
- Noir for generating email proofs (not sure if possible wtih ZKPass)
- Solidity smart contracts for marketplace and verifiers

## ZKPass schemas

Check [here](./zkpass/README.md) for schema documentation.