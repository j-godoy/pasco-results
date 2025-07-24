# pasco-results
This repository contains the generated abstractions produced by the tool PASCo. The folders are structured based on the parameters used during the generation process.

## Folder Structure

- **k_n**: Indicates the `k_bound` parameter used to set up PASCo.
- **t_600**: Indicates the timeout used in seconds.

## File Types

Each generated abstraction contains the following files:
- `.epa` or `.states`: The abstraction in EPA mode or states (for enum).
- `.csv`: The query times for that abstraction.
- `.txt`: Extra information.

## Summary
Final abstraction build times were measured on a system equipped with an Intel Core i7-4790 processor (4 cores), 16GB of RAM, running Windows 10.


| Subject                                  | Mode   | Time     |
|------------------------------------------|--------|----------|
| AssetTransfer                            | states | 0:08:44  |
| BasicProvenance                          | states | 0:00:13  |
| DefectiveComponentCounter                | states | 0:00:05  |
| DigitalLocker                            | states | 0:03:09  |
| FrequentFlyerRewardsCalculator           | states | 0:00:05  |
| HelloBlockchain                          | states | 0:00:07  |
| RefrigeratedTransportation               | states | 0:00:28  |
| RoomThermostat                           | states | 0:00:09  |
| SimpleMarketplace                        | states | 0:00:16  |
| AssetTransferFixed                       | states | 0:08:47  |
| BasicProvenanceFixed                     | states | 0:00:13  |
| DefectiveComponentCounterFixed           | states | 0:00:06  |
| DigitalLockerFixed                       | states | 0:03:03  |
| HelloBlockchainFixed                     | states | 0:00:07  |
| RefrigeratedTransportationFixed          | states | 0:00:27  |
| SimpleMarketplaceFixed                   | states | 0:00:16  |
| RefundEscrow                             | states | 0:00:31  |
| RefundEscrow                             | epa    | 0:00:30  |
| RefundEscrowWithdraw                     | epa    | 0:01:04  |
| EscrowVault                              | states | 0:01:09  |
| EscrowVault                              | epa    | 0:00:40  |
| EPXCrowdsale                             | states | 0:07:22  |
| EPXCrowdsale                             | epa    | 0:01:49  |
| EPXCrowdsaleIsCrowdsaleClosed            | epa    | 0:02:54  |
| ValidatorAuction                         | states | 0:01:45  |
| ValidatorAuction                         | epa    | 0:01:37  |
| ValidatorAuction_withdraw                | epa    | 0:03:18  |
| SimpleAuction                            | epa    | 0:01:02  |
| SimpleAuctionTime                        | epa    | 0:01:32  |
| SimpleAuctionEnded                       | epa    | 0:01:06  |
| SimpleAuctionHB                          | states | 0:01:22  |
| Auction                                  | epa    | 0:00:18  |
| AuctionEnded                             | epa    | 0:00:23  |
| AuctionWithdraw                          | epa    | 0:00:41  |
| RockPaperScissors                        | states | 0:00:56  |
| RockPaperScissors                        | epa    | 0:00:19  |
| CrowdfundingTime_Base                    | epa    | 0:00:24  |
| CrowdfundingTime_BaseBalance             | epa    | 0:01:14  |
| CrowdfundingTime_BaseBalanceFix          | epa    | 0:00:59  |
| EtherstoreOriginalReentrancy             | epa    | 0:05:40  |
| ReentranceOriginalReentrancy             | epa    | 0:10:16  |
| Reentrancy_daoOriginalReentrancy         | epa    | 0:03:26  |
| Reentrancy_simpleOriginalReentrancy      | epa    | 0:04:37  |
| Simple_daoOriginalReentrancy             | epa    | 0:10:13  |
| EtherstoreReentrancy                     | epa    | 0:12:51  |
| ReentranceReentrancy                     | epa    | 0:12:16  |
| Reentrancy_daoReentrancy                 | epa    | 0:20:57  |
| Reentrancy_simpleReentrancy              | epa    | 0:20:54  |
| Simple_daoReentrancy                     | epa    | 0:12:16  |
| EtherstoreReentrancyFixed                | epa    | 0:32:05  |
| ReentranceReentrancyFixed                | epa    | 0:31:40  |
| Reentrancy_daoReentrancyFixed            | epa    | 0:20:13  |
| Reentrancy_simpleReentrancyFixed         | epa    | 0:31:31  |
| Simple_daoReentrancyFixed                | epa    | 0:31:41  |

