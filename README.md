# Part 1 - Blockchain Intuition

<aside>
📢 In this part you will learn :

- Build up a solid Blockchain Intuition
- Learn how to create a general Blockchain from scratch
- What is Blockchain ?
- Understanding SHA256 Hash
- Immutable Ledger
- Distributed P2P Network
- How Mining Works (Part 1 : The Nonce )
- How Mining Works ( Part 2 : The cryptographic puzzle)
- Byzante Fault Tolerance
- Consensus Protocol ( Part 1 : Defence against attackers )
- Consesus Protocol ( Part 2 : Competing chains )
- Blockchain Demo
</aside>

# 01. What is BlockChain

Wikipedia ⇒ It is a continuously growing list of records, called blocks, which are linked and secured using cryptography.

Block: 

- Data ⇒ "Hello World"
- Prev. Hash ⇒ 034DFA357
- Hash ⇒ 4D56E1F95

These are materials what each block has except 'Genesis Block'

What is Genesis Block : 

It is the first block in the chain. It does not have any previous hash. But it has its own hash. 

After genesis block another block comes next and it linked with previous hash number which is genesis blocks hash. So;

!! This means blocks are cryptographically linked together. !!

With BlockChain , there are many kinds of works. Like :

- Hash Cryptography
- Mining
- Consesus Protocol
- Distrubuted P2P Network
- Immutable Ledger

# 02. Understanding SHA 256 - Hash

  The name is Shatara 256. It is 64 characters long. It includes letters because it is Hexadecimal Hash !!

- So it means each character in the resulting hash takes up 4 bits 4^2 = 16 and 4 times 64 = 256
- This hash algorithm does not work just for words, documents. It works for any digital material. ( Video , Image .. )

[https://tools.superdatascience.com/blockchain/hash](https://tools.superdatascience.com/blockchain/hash) ⇒ For testing SHA 256 Hash and other blockchain 

5 requirements for Hash algorithms :

- It has to be One-WAY : You can not go backwards reverse and restore.
- Deterministic: If we run exactly same document we have to see the same as we saw previously.
- Fast Computation :   Dealing with 64 characters should be fast
- The Avalanche(Çığ) Effect:  Even if we change a tiny variable in document. The Hash should will be absolutely different. The idea is that one change triggers a few changes and they in turn trigger more changes and more.
- Must withstand collisions :  It is rare situation that different documment shows same hash number. But is like 60 millions of people who have same fingerprint situation.
    
    [https://webspace.science.uu.nl/~tel00101/liter/Books/CrypCont.pdf](https://webspace.science.uu.nl/~tel00101/liter/Books/CrypCont.pdf) ⇒ Document for creating Shatara Hash Algorithm
    

# 03. Immutable Ledger

temper ⇒ ☠️

Example : Property Ledger is great example for this.

The main idea of immutable ledger is containing kind of deeds in properties. But making these deeds more privately. For instance if somebody wants to change any deed it has to change next to it. Because all deeds are connecting to each other and their hash's are unique. 

# 04. Distributed P2P Network
