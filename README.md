# Repo

**Reasoning**

In the course of my research, I came across four different clusters, which I will describe in more detail below. I have categorized the wallets into different groups based on their on-chain similarities.

**Cluster 1**

The wallets from groups 1 and 2 are all Sybil wallets operated by the same entity and together form Sybil cluster 1, which consists of a total of 93 wallets. The wallets have almost identical ages, transaction counts, and activity patterns, and all interact directly or indirectly with each other. Some of the addresses that are part of this cluster are included in the initial list from LayerZero.

**Funding Pattern**

GRAPHIC 1

Graphic 1 shows that wallet address 0x1070298571B9156c9497827e116a75d1E383Cb6c (the last address in group 2) creates several wallets and then funds them. These wallets, in turn, create new wallets that exhibit almost the same transaction patterns as the parent wallet. The funding pattern of the wallets listed above thus forms a classic tree structure with wallet 0x1070298571B9156c9497827e116a75d1E383Cb6c as the root. Due to this cluster, there are numerous transactions between the individual wallets: Each listed wallet has interacted directly with at least one other wallet on the list. Each wallet, with few exceptions, receives its first deposit from another wallet on the list. It becomes immediately clear that this is a Sybil attacker when examining the transaction activities of the wallets for similarities in the context of this cluster structure.

**Transaction Patterns**

Almost all of the listed wallets share the following transaction pattern on Linea:
GRAPHIC 2
The accounts, as shown here with wallet 0xABd724f2C82314cBE894B9f1d5d5A45909D68730 from group 2 as an example, conduct the following transactions:
1. Interaction with zAce Chip
2. Minting a Micro3 NFT
3. Minting an Alien Linea Citizen Pass NFT
4. Minting a Comic Book NFT
5. Minting an NFT from Smart-Contract 0xcD1
6. Minting an NFT from Smart-Contract 0xb99

The transaction history of the wallets on the Ethereum network is also very similar. The wallets interact with the same counterparties at the same intervals using similar amounts. Consider the following example:

GRAPHIC 3

GRAPHIC 4

Graphic 3 shows wallet 0x1693112ab1925d23977717Fc25137d233920288F, and Graphic 4 shows wallet 0x5B87F55cDF6C26081c328B06a22E730eD2E5f5A1, two randomly selected wallet addresses. Note the red-marked areas: Both wallets interact consecutively with the projects zkSync, Polygon, Linea, Altlayer, Polyhydra Network, Omni Network, and Scroll at almost identical time intervals and with almost the same amounts. Subsequently, they receive Ether from Okx. In the interactions with Polygon and zkSync, the amounts for both wallets are even identical!

Moreover, each of the listed wallets follows the following transaction pattern:

GRAPHIC 5

Without exception, every single wallet, such as the randomly selected wallet 0xD052A00932a8B3D805F359bfA4C79bdA5E3574f7 from group 2 (Graphic 5), received an amount in the range of 0.05-0.055 Eth on the Arbitrum network from the Okx Hot Wallet about a week ago and then immediately transferred the received Ether back to a separate Okx deposit address.

The wallets also perform the following activities with variations in the order and the network used:

GRAPHIC 6

GRAPHIC 7

The accounts first mint a Merkly Hyperlane NFT, which they immediately burn. They then mint and burn a GetMint NFT. These two activities are sometimes carried out on different networks. Then the wallets mint a Layer 3 Cube NFT and execute the aforementioned OKX transactions on Arbitrum. 
Graphics 6 and 7 show the randomly selected wallets 0xb781ba845aDB5BF9FF2154e5C8F126F56ae7b616 from group 1 and 0xEc8719b439B745D5ff9D189550400B60AbE2087F, which is on LayerZero's initial list. Both follow this pattern: While the first wallet mints and burns the two NFTs on Arbitrum, the second wallet performs these transactions on the Base network. Both accounts then mint the Layer 3 Cube NFT and interact with OKX.

The following 25 addresses are part of this Sybil cluster but were already filtered out in LayerZero's initial filtering process:
0x811204Add9F52500A2622e1f6c935D9fDA3D05E0  
0x052A9b611CbaF24d352c7dcc52300E99c94371D8  
0xA14bbFc56F4Cd3b5c868683540F916321adEF6fC  
0xF9C8841625F42d90B364a302Ec9Ee0f04CF2a4F3  
0x3c0B6e29f2e1Fb3Ec1B147a261B1f3c58191D8fb  
0xEd700CcbaFB63dA65b49c559585Fa0BDe7EFc9A8  
0x5C57Ae3eD96aF96Be71E84cB89F071F249C0833B  
0x7846BCc384E9015c5638Ce34F778365274b1Cd25  
0x0AdE448bEc348C6255ce70d31f61b8A921fBeC7e  
0x6814B9e477186472Ab822AE4663298000c84480D  
0xd50667FC5F68326C832755C7Fa2516470b65bc5C  
0x67aC343E9C85FE25008E12C53892957Fb042fEbf  
0x86F0DB2fC5a4F6FF5fd85FD10365B97447Bc1b72  
0x3763DD6330Cc1E66A76F704Dfc78092Bd78B0a01  
0x0cc1C40e874C41Ea906d2a8c8B786547903397Df  
0xc388652c5B60279D70557D8F52688caC46c7A630  
0x25Dd427f7CCa3a5483143a344563CeE86212DabE  
0xEc8719b439B745D5ff9D189550400B60AbE2087F  
0x248A9EaC8e73aEf17bE6BdA84C5809F211BD3b53  
0x726d8111046452C29E48f8FBc69567D0ACbB9b96  
0x0f5467E864aE9e30Fb597956449021B7D75aB657  
0x1dDBaF5358ffF7985504f74384D7dBE45bb63800  
0xdC7673394f6f947CaFFF3EF82FF0166C59E93B7f  
0x1AF80DdDd65bf01f0a50b1D7c52a55Dbd12bF2bd  
0xAcAD709De5e569427084c8c1A6551a3d1c612ae1  

**Cluster 2**

**Funding Pattern**

All wallets from group 3 have been funded by the address 0x521205abF224Dcb7eB5FF363E975C1D3a05192ba (the first wallet in group 3) with the ENS name elonmusk1971625.eth and form the second cluster in this report. All listed wallets have deposited funds into the same OKX deposit address (0xef9f8e6c1979b7E9196956244CC5Cc4A252DD80c).
GRAPHIC 8
In Graphic 8, I have entered all wallets from group 3 into the Arkham Tracer. Besides the transactions with elonmusk1971625.eth and the same OKX deposit address, the wallets also interact directly with each other at times.

**Transactions on Ethereum**

At first glance, it is clear that the wallets have no economic purpose and were created solely for airdrop farming. All wallets, except the last one on the list, follow the following pattern on Ethereum:
GRAPHIC 9
On March 25, 2023, the wallets transferred Ether to zkSync, and on March 26, 2023, they all received 0.04 Ether. Subsequently, on the same day, the wallets bridged an amount of about 0.036 Ether to zkSync and transferred Gitcoin tokens on June 15, 2023, or June 16, 2023. There are also common transaction patterns on other networks like Linea and Polygon.

The following wallets, which I also identified as part of this Sybil group during my research, were filtered out in LayerZero's initial filtering process:

0xdB5CCfE91652A8c694c024BcFbAD5c262968A635  
0xB3ed852a7f49fc32D95006ace69CD42982978395  
0x9508592B1792792B53ceD167b33DF77C184d724a  
0xB4B2CF10Cff7cc006284eb692a42d5F461C2dd0a  
0x9e5aD65Ef42770f611A512Bcf57253f0F21d650f  
0x13300a91744f3122A535c2C556D1d02720b6B406  
0x9A8dd4c13Df89023eBb93d1ca29EE3cff1f21D3A  
0x9E8d20e6eA25C3cdB3377cB81032bd143b5b87bC  
0xbC3134D7026a9fAe4B0F810aa79AA4324685DdC4  
0x7294d6522d9d17E2342ACcDF1331E8117429663A  
0x6fA2175FB6087EDde86C19cB33Afd5D48767DD49  
0x555766F1DA6b9C4faAF58418F902408416C9a1f7  
0xd9187060F07c9573d579883343De5Eb9123fcbd5  
0xeE616c52311c695Ff48c2AD93881aD43A2e1bf15  
0xC83aD4e9B58E6f922dC285D9a35dBf67996f21B5  
0xed8243b35Ec91bB27c1C95F2Df50c6Fb21DFA3f2  
0x1678C2e2ae0DAB80c609dFACafA95dACF51F1dCb  
0xa12cF769aA2dBc61080459bA673cB7dDe45B8265  
0x0cd97C0a904641b73c886EA51819b5e73af50b22  
0x25cB1bc802F8C2c2e5F16f9Eff78a25660789373  
0x10a8C32F7e46e575a7d63B7E7c1e0dE2524C87d3  
0xAe8df4d5864eAB0735aCc2a74dD9A83ff89B7D31  
0x31863332a6D34d767fdd9cdDEE2e02d558BbF550  
0xD08DcEDf87Eb2ff031dCbf8dba28B53AfcD1b0cd  
0x56006268D4a8A48645c85D8f5f6725e54E3feeD1  
0xf3b79AAeDd3C280C2BE1765da4D1884A1DBBFffa  
0xe897a460CF9AB052b144755dB27c71D811a9718D  
0x791E4c1F5552D1b7f82f2e4F47f567Aa077F4afC  
0x887cFc63645c855C55758D433661Ff245C9C6e80  
0x9E294aED1E93615Cf2770dB82dF5E71AFa898cD6
0x040b61D7fB10E4D389dCeF2503eA0Eed74fAdb40
0x71501Df1eb6cec9AafDd2DdAD13De2548106a22A
0x2e250C002c7d4425839fC3761549bd75bC391D98
0xcb50a48d820AA7F67Cca08F528b9a489AaD68644

**Cluster 3**

**Funding Pattern**

The wallets in group 4 are all operated by the same person and form the third cluster of my report. These wallets received the exact same amount of Ether in a total of 6 Disperse App transactions. The transactions were conducted by the wallets 0x56a9108A50940F3471fABEC573dCC4D030421D80 and 0x0655F2EE873B08EF81dFB58CfA69d48Add5A5c23, which are listed last in group 4. Additionally, all addresses deposit funds into the same OKX deposit address (0xCfb2a94c453005Dd8F86A618145f549ba29A0723), indicating that all these addresses are operated by the same entity.
GRAPHIC 10
In Graphic 10, I inserted 8 randomly selected wallets into the Arkham Tracer. All deposit into the same OKX address and receive funds via the Disperse App from the addresses 0x56a and 0x065. Unfortunately, Arkham does not show the transfers originating from the Disperse App to the respective wallets in this graphic. The wallets sometimes interact directly with each other and were also funded directly by the wallet 0x065 on Binance Chain.

**Transactions on Ethereum**

The wallets do not follow an economic purpose: they interact with small amounts with protocols like Scroll, zkSync, and Starknet to maximize profit in case of an airdrop.

GRAPHIC 11

As shown in Graphic 11, the Ethereum transaction history of the specified wallets is very sparse. There is no evidence of organic use. The wallets differ in their transaction count, but all interacted with zkSync on 08.09.2023, Starknet on 17.09.2023, and the Swell Network project on 23.09.2023.

**Cluster 4**

**Funding Pattern**

On 04.01.2024, the wallets from group 5, forming cluster 4, were funded three times via Disperse App by the address 0x725DC93AF46673071897D8886BB4b3763869E2f9. In the first transaction (0xbddf8ef52be50f6863b3574177b1ec377ff976aef4bb36459f40adeb10351011), the wallets received different amounts of the AIT token, while in the second (0x1fbfe679ff9aee5945c2f33c4100d744a39922c3d8af37c6d956bec8824094ca) and third (0x7b0a9f3555b70a51ef0a4f5a32242d4978226a93bd0c4a05140548bd0898247b) transactions, Ether was distributed. In the third transaction, each wallet received exactly 0.01 Ether.

GRAPHIC 12

Graphic 12 shows the transaction pattern followed by the wallets in group 5, using the wallet 0x7a1223bE51CB47080FA2561aE9f7Fa0D295D558A as an example. The addresses receive a different number of AIT tokens via Disperse App, which they swap for Ether on Uniswap. The Ether obtained is then transferred to the addresses 0x7555692bF815cc2386E2C5d870aaeae4cBf088E3 and 0x811330fDBF7Cb217a9a340d803641c3Bf1B7aAf5, which subsequently transfer the funds to Binance.

GRAPHIC 13

Graphic 13 shows the Sybil structure. The wallets receive funds via Disperse App and transfer them to wallets 0x755 and 0x811, which in turn transfer the funds to the Binance account of the Sybil attacker. As shown, the wallets also interact with each other or directly deposit into the Binance address.

**Transactions on Ethereum**

GRAPHIC 14

Graphic 14 shows the randomly selected wallet 0x957dEF46f9DA8AbbD9c2e3F0B1C4345989A3B5F3. This address has interacted with only 4 protocols, 2 of which are part of the LayerZero ecosystem. This lack of real usage indicates that the sole purpose of the wallets in group 5 is airdrop farming.

**Methodology**

I discovered Cluster 1 by analyzing the transactions of the smart contract 0x001FE350a8624166E946f0Ba67065a325bdDcc2B, which belongs to Alienswap. I noticed some batch transactions distributing exactly 0.008 Ether to wallets with the same Ethereum history. Upon closer inspection, I realized that all these wallets followed the same transaction pattern. I noted these wallets in group 1 and then analyzed who initially funded these addresses. I identified the wallet 0x1070298571B9156c9497827e116a75d1E383Cb6c as the root of the cluster. The addresses in group 2 are the wallets I found when tracing the cluster from 0x107 using Arkham Tracing. While manually analyzing another Sybil cluster on Etherscan, which often conducted transactions with multiple wallets in the same block, I came across the transaction 0x3d15c613bbed85cee89dacfda5d2e431af84a2c1d176859a50924da312ed5a3b, where the Sybil attacker from cluster 2 funded his wallets via Disperse App. I then started examining Disperse App transactions from that period to find more wallets of the Sybil. This led me to the transactions 0xa367e34b2aa4eaf0df31ea0e04c70f9d2dd8d44c7bcdc62c1aed7f5fa5c3dc09 (cluster 3) and 0x7b0a9f3555b70a51ef0a4f5a32242d4978226a93bd0c4a05140548bd0898247b (cluster 4).
