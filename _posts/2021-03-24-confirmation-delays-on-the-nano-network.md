# Confirmation delays on the Nano network

The problem of long confirmation times after the spam attack on the Nano network caused Kuyumcu to be temporarily closed. Here are some details.

### Long story short
Confirmations of some transactions on the Nano network can now take longer than usual, which is why Kuyumcu is not running now and many exchanges temporarily closed their deposits and withdrawals for Nano. There's no ETA, we can't estimate when the network conditions will be normal again. We're following [nanoticker.info](https://nanoticker.info/ "nanoticker.info") to check the amount of checked and confirmed blocks. When they're equal to each other, it means the network is confirming blocks instantly, and we can reopen Kuyumcu - we're looking forward to that day!

### - Nano network
Nano is a cryptocurrency. It is open for everyone, there are no transaction fees for sending and receiving it. To prevent someone to spam the Nano network, or at least to make it costly to do so, each block (transaction) needs a [Proof of Work (POW)](https://docs.nano.org/glossary/?h=principal#proof-of-work-pow "Proof of Work (POW)") to be published to the Nano network. Work generation can take a few seconds or maybe more, depending on the hardware and the [difficulty](https://docs.nano.org/commands/rpc-protocol/?h=active_#active_difficulty "difficulty") level of POW.

### - Confirmations on the Nano network
When a block is published to the Nano network, it needs to reach a [quorum](https://docs.nano.org/glossary/?h=principal#quorum "quorum") to be [confirmed](https://docs.nano.org/glossary/?h=principal#confirmation "confirmed"). Elections for the [active transactions](https://docs.nano.org/glossary/?h=principal#active-transaction "active transactions") are being done on the network and the [Principal Representatives (PR)](https://docs.nano.org/glossary/?h=principal#principal-representative "Principal Representatives (PR)") votes for them.

### - Ongoing spam attack
Every valid block was getting confirmed instantly before the spam attack and no one was "waiting" for a confirmation, since it was taking less than a second. The [Transactions Per Second (TPS)](https://docs.nano.org/glossary/?h=cps#transactions-per-second-tps "Transactions Per Second (TPS)") was equal to [Confirmations Per Second (CPS)](https://docs.nano.org/glossary/?h=cps#confirmations-per-second-cps "Confirmations Per Second (CPS)"). With the ongoing spam attack, some transactions did not receive an instant confirmation. They will eventually get confirmed, but it can take up to 2-3 days or even more.

![Source: nanoticker.info](https://i.imgur.com/xvnQWAY.png "Source: nanoticker.info")
*Checked and confirmed blocks were separated at that point. Source: [nanoticker.info](https://nanoticker.info "nanoticker.info")*

The difference between checked blocks and confirmed blocks, which started on March 11, 2020, still continues. As of now, there are nearly 113 million checked and 97 million confirmed blocks.

### - What's next?
With the new update of Nano node (V21.3), "several cases where the synchronization process would be restarted or prevented from being restarted were fixed" according to [this article](https://medium.com/nanocurrency/recent-dos-nano-network-attack-and-v21-3-fixes-97b9b7297f9 "this article"). There are still valid and unconfirmed transactions, so the problem persists. We hope to see all the valid transactions on Nano network to get confirmed instantly as on normal days.

[nano.trade](http://nano.trade "Go to nano.trade")