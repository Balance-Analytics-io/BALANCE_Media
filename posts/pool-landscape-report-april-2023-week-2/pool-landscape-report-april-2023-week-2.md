---
title: Pool Landscape Report - April 2023 Week 2
description: Cardano Stake Pool Landscape Update Report on Group Edits and Events
slug: pool-landscape-report-april-2023-week-2
published: 2023-4-16
category: pool_landscape
series: true
---

# Pool Landscape Report - April 2023 Week 2

## Table of Contents

------------

## Introduction
Welcome to BALANCE's Pool Landscape Update Report, a series that provides insights into the Cardano Stake Pool ecosystem, covering notable changes and events. Our focus will be on pool groups and decentralization, but we will also include any significant events to keep the Cardano community informed with the best pool and chain intelligence.

We strive to remain unbiased and present only the facts. However, we will also remain vigilant watchdogs and will call out any actions that can improve network security.

This is the first report of many, and we hope you find it informative. You can use the Table of Contents hotlinks to navigate through the report and find the information you need.

## Big Picture Coverage of Epoch 370 to 406 (10/17/22-04/16/22)
To provide a comprehensive view of the stake pool landscape, it's important to cover the significant activity and movement that has taken place over the last few months. This surge appears to have been triggered by the SEC's crackdown on exchanges and staking services - off-chain attacks if you will. In order to understand the context, we present a brief timeline of significant events below:

### SEC Rumors and Crackdown Timeline
- Feb 8, 2023 [Epoch 392], [Brian Armstrong Tweet on SEC Rumors](https://twitter.com/brian_armstrong/status/1623459203150131201?s=20)
    > "1/ We're hearing rumors that the SEC would like to get rid of crypto staking in the U.S. for retail customers. I hope that's not the case as I believe it would be a terrible path for the U.S. if that was allowed to happen."
- Feb 9, 2023 [Epoch 393], [Kraken to end on-chain staking services for U.S. clients](https://blog.kraken.com/post/17619/settlement/)
    > "Kraken has agreed to end its on-chain staking services for U.S. clients. Starting today, Kraken will automatically unstake all U.S. client assets enrolled in the on-chain staking program."
- Feb 17, 2023 [Epoch 394], [Bloomberg Report: Binance Considers Pulling Back From US Partners as Crypto Crackdown Escalates](https://www.bloomberg.com/news/articles/2023-02-17/binance-holdings-explores-retreat-from-the-us-as-crypto-crackdown-escalates?leadSource=uverify%20wall)
    > ""We pulled back on some potential investments, or bids on bankrupt companies in the U.S. for now. Seek permission first,” Zhao said in another tweet."
- March 22, 2023 [Epoch 401], [Coinbase Blog: We asked the SEC for reasonable crypto rules for Americans. We got legal threats instead.](https://www.coinbase.com/blog/we-asked-the-sec-for-reasonable-crypto-rules-for-americans-we-got-legal)
    > "Today, we are disappointed to share that the SEC gave us a “Wells notice” regarding an unspecified portion of our listed digital assets, **our staking service Coinbase Earn**, Coinbase Prime, and Coinbase Wallet after a cursory investigation. A Wells notice is the way that SEC staff tells a company that they are recommending that the SEC take enforcement action for possible violations of securities laws. It is not a formal charge or lawsuit, but it can lead to one. Rest assured, Coinbase products and services continue to **operate as usual** - today’s news does not require any changes to our current products or services." (bold text added by BALANCE)

### Big Pool Movements
During the same time period, we saw the following big pool changes.

- **Binance**: Stake decreased by a whooping -27% for 782MAda
- **Coinbase**: Stake decreased by -9% for 217MAda
- **SWIM Pool Group?**: New pool group with a 1,678% increase for 557MAda. Maybe Binance moved funds?
- **WHO KNOWS**: Was far top left, is now far right (high leverage). Significant change too.

### MAV Increase
So, has the SEC crack-down been helping improve the infamous Nakamoto Coefficient, or Minimum Attack Vector (MAV) of 51% of chain stake ownership (and thus control)?

It's hard to say and prove. However, there has been a significant downsizing and reorganization on the big pools, and a sharp rate of increase in MAV! 

{% img src="mav_epoch_406.png" alt="mav_epoch_406" %}

MAV has increased by 32% from 19 to 25. K-effective has increased by 27% from 34 to 43. The rate of increase has sharply turned positive. These numbers are nothing to sneeze at. One could probably argue the SEC attack has had a correlated effect.

## Other Noteworthy Significant Events in March-April
- 11 new pools
    - [EMURG6](https://pool.pm/34d37dabdf2c17056c07a002a685e4bba8673e6bf30c6ef6bd394534) new Emurgo pool
    - New [SWIM] SwimmingPools for the summer heat
- 1 multi-pool update, [CNODE](https://pool.pm/0775f0139af22e1ebf2c3278598816946e750029b70eace3c5135c3e) (4 pools under [Cardanode](https://www.cardanode.io/))
- [4/7/23] [FAX](https://pool.pm/7c342689b39e269c29ef74fe12e66dee78df69955544d9f0662f6167) pool ISPO, 5 Epochs and Saturated! Look out hot stuff at [Orcfax](https://orcfax.io/#ispo)
- [ARM1], nice pledge increase to 800kA
- [BD%](https://pool.pm/5eb362978a68a4780f4fd701b8f04f5aeb990eb80b1cb025d99e82a1) Blockdaemon Pool Group, updating margin from 3.00 to 8.00%.
    - Who are these guys anyway? The short answer is VC Money. We might do a deep dive on them for you.

### [AWP2] Not Meeting 1k Pledge

[4/11/23] [AWP2](https://pool.pm/ae66e56ab11ccb39e882669f220a37956c683e4ce84fefd910012d7a) pool of [Atomic Wallet](https://atomicwallet.io/) is a low pledge pool group that keeps messing up their stake pledge. Get out of that pool people if you want rewards. How hard is a 1kAda pledge to keep for a 25MAda pool!

{% img src="awp2_pledge_not_met.png" alt="awp2_pledge_not_met" %}

We sent out a warning tweet to the community, as did [OYSTR Pool](https://twitter.com/OystrPool) (Good looks).

<blockquote class="twitter-tweet tw-align-center"><p lang="en" dir="ltr">Imagine not meeting a 1kAda pledge...<br><br>AWP Pool Group has 3 pools, combined 3kAda Pledge, and 125MAda Stake, giving them a 40,000x Leverage Factor.<br><br>AWP has 2 tweets on Cardano in 3 years.<br><br>Between OYSTR and AWP, there&#39;s a clear choice what&#39;s better for the <a href="https://twitter.com/hashtag/CardanoCommunity?src=hash&amp;ref_src=twsrc%5Etfw">#CardanoCommunity</a>. <a href="https://t.co/fa6etdzYfd">https://t.co/fa6etdzYfd</a></p>&mdash; BALANCE (@BalanceData22) <a href="https://twitter.com/BalanceData22/status/1645752437523857408?ref_src=twsrc%5Etfw">April 11, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### [NUFI0] Whale Over-Saturation Attack?

Was [NUFI0] Pool subject to a Whale Over-Saturation Attack (OSA)?? An OSA is when a whale entity delegates a massive amount of stake to super saturate the pool (stake well over the saturation limit of ~80MAda) and thereby tank the pool's reward returns.

[NuFi](https://nu.fi/) is a non-custodial web3 crypto wallet service powered by parent company [VacuumLabs](https://vacuumlabs.com/adalite/). The now NUFI% pools can be found under the ADALITE Pool Group, their former wallet and branding. They use to be a super low pledge, high leverage pool group on the far right of the chart, but have since added significant pledge and stake, as shown below. Well done.

{% img src="adalite_stake_v_lev.png" alt="adalite_stake_v_lev" %}

{% img src="adalite_pledge_stake.png" alt="adalite_pledge_stake" %}

So during Epoch 402, a multi-wallet whale entity moved six sets of 50MAda and one 13MAda stake into NUFI0 pool on April 11 2023. That's a total of 313MAda! A pool's saturation is about 80MAda. That's a huge whale herd!

{% img src="nufi0_incoming.png" alt="nufi0_incoming" %}

[NUFI0](https://pool.pm/a0fc643d831b144e1dd289f5acf4274aedc331b6a0e4257ef5376520) quickly found itself insanely over-saturated and losing significant staking rewards.

{% img src="nufi0_over_sat.png" alt="nufi0_over_sat" %}

We and other Single Pools raised the warning flag:

<blockquote class="twitter-tweet tw-align-center"><p lang="en" dir="ltr">Err...you do know there&#39;s other pools right NUFI0? 👀<br><br>ADALITE pool group has added significant pledge and stake since epoch 370, look for yourself:<a href="https://t.co/MCxNeN5sJO">https://t.co/MCxNeN5sJO</a> <a href="https://t.co/r9vHUsNRhH">pic.twitter.com/r9vHUsNRhH</a></p>&mdash; BALANCE (@BalanceData22) <a href="https://twitter.com/BalanceData22/status/1645954409250328577?ref_src=twsrc%5Etfw">April 12, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

NuFi on twitter also [stated](https://twitter.com/NuFi_Official/status/1646093009719525376?s=20) they will work to address the issue, thanks also to [BBHMM]'s tweet:

<blockquote class="twitter-tweet tw-align-center"><p lang="en" dir="ltr">🚨Attention NUFI0 delegates you will lose your rewards delegated there.<br>🐳Please swim over to some <a href="https://twitter.com/CardanoSPA?ref_src=twsrc%5Etfw">@CardanoSPA</a> pools.<br>🛡️Let&#39;s decentralize cardano even more.<br>☔️ Registered pools get&#39;s drops at <a href="https://twitter.com/TosiDrop?ref_src=twsrc%5Etfw">@TosiDrop</a> <a href="https://t.co/kKrWqnjq8y">https://t.co/kKrWqnjq8y</a><br>✅Check us out and spread the ADA love❤️ <a href="https://t.co/UG4zWC4UhC">pic.twitter.com/UG4zWC4UhC</a></p>&mdash; BBHMM | ☔️ | SSPO | TOSI | FLZ (@BBHMM_Stake) <a href="https://twitter.com/BBHMM_Stake/status/1646005515909050368?ref_src=twsrc%5Etfw">April 12, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Two days later, the whale entity migrated to other NuFi pools to spread out the stake.

{% img src="nufi0_outgoing.png" alt="nufi0_outgoing" %}

The whale herd is likely NuFi or VC friendly wallets, not an intentional OSA to tank the pool.  In reality, it was a lack of due diligence and a bone head move.  That would have been an interesting saga to watch.


## What We're Watching Now
In other news, here's what we are keeping an eye on.

### Exodus Launches Cardano Web3 Browser Wallet - Watch EVE Pool Group
On March 31st Exodus Wallet, a self-custody multi-chain wallet, [announced](https://www.exodus.com/web3-wallet/) they are launching a Cardano Web3 Browser Extension wallet. This is great news as they have a large user base. 

<blockquote class="twitter-tweet tw-align-center"><p lang="en" dir="ltr">We are proud to announce that <a href="https://twitter.com/hashtag/Cardano?src=hash&amp;ref_src=twsrc%5Etfw">#Cardano</a> is LIVE in the Exodus <a href="https://twitter.com/hashtag/Web3?src=hash&amp;ref_src=twsrc%5Etfw">#Web3</a> Wallet!<br><br>✅ Connect to <a href="https://twitter.com/hashtag/NFT?src=hash&amp;ref_src=twsrc%5Etfw">#NFT</a> &amp; <a href="https://twitter.com/hashtag/DeFi?src=hash&amp;ref_src=twsrc%5Etfw">#DeFi</a> dApps!<br>✅ Manage <a href="https://twitter.com/search?q=%24ADA&amp;src=ctag&amp;ref_src=twsrc%5Etfw">$ADA</a> Native Tokens &amp; CNFTs!<br>✅ Cross-chain swaps!<br>✅ Easy access to our 24/7 support team!<br><br>Download Exodus for Chrome &amp; Brave today! 👇<a href="https://t.co/vAnNTBqHgE">https://t.co/vAnNTBqHgE</a> <a href="https://t.co/Z7ZLreEeDT">pic.twitter.com/Z7ZLreEeDT</a></p>&mdash; Exodus - Crypto Wallet (@exodus_io) <a href="https://twitter.com/exodus_io/status/1641900795879649280?ref_src=twsrc%5Etfw">March 31, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

What you may not be fully aware of though is that they utilize a 3rd party staking service [Everstake](https://everstake.one/cardano) who runs the pool group [EVE](https://cexplorer.io/groups/eve). Do a "ctrl+f" word search for "everstake" in [Exodus' support article on Cardano staking](https://www.exodus.com/support/article/1498-cardano-staking-faq).

In our [tweet](https://twitter.com/BalanceData22/status/1643038391498428416?s=20) we made aware that Exodus & Everstake [EVE] Pool Group have supported Cardano Staking since Sept 2021, early epoch 200s.

However, EVE runs 11 low pledge high leverage pools, combined for 11k pledge, ~500MAda, at about 45,000x leverage factor. So far there have been no significant stake changes since the announcement.

An option to choose your own stake pool would be great for advanced users in the Exodus web3 wallet, maybe we can mass request this feature.

### Luganodes [LGNS1] Potential to Multi-Pool
We have been watching these guys [Luganodes](https://www.luganodes.com/) who are another staking service provider based in the Swiss: "Secure staking by leading blockchain infrastructure provider". 

They currently run just one pool [LGNS1] with a pledge of 10 Ada, but let's see if they form a multi-pool operation soon. Their whole business is about running staking as a service so we wouldn’t be surprised if we see them spin up more when the market picks back up.

So far though they have a decent Cardano awareness and pretty decent [Cardano tweets](https://twitter.com/search?q=from%3Aluganodes%20cardano&src=recent_search_click), so they aren't completely out of touch with the community.

The pool [LGNS1](https://pool.pm/0338d4f1c5e8ebee0689e22148c1483d411c5587d0ab986b8e824428/stake) looks like it has one huge wallet of 41MAda (MAda for Million Ada) with 86% majority stake that arrived in epoch 370. This is a new stake address, with [only previous delegation](https://cexplorer.io/stake/stake1u87mn7454dmezggnq6fy3j0fclh0e6zhsd7x5r6t0x4u3fc86730l/delegation#data) to [FKAI](https://cexplorer.io/pool/pool1mmrh2l3t5r7w5l7e82ven0e595vhgvu0hyf4ttrgcyejq8gwqcm) pool, who has a whooping 1.53 Ada met pledge (sarcasim alert). 

FKAI looks like it is currently inactive with 0% saturation now.  You can probably assume this 41MAda is VC or Big Business money getting "professional" third party staking service. 

It makes you wonder, what is the driver to use these third party services and not community delegation?

## BALANCE Updates

### New BALANCE Pool Group API Link - now with Single Pool Group!
We have made updates to the BALANCE Pool Group Data API, which now includes a **"SINGLEPOOL"** group!  This should be a very interesting and useful new detail.  Please find the dataset here:

https://www.balanceanalytics.io/api/groupdata.json

### BALNC Pool Pledge Increase
We are happy to announce our pledge has increased by 100,000 Ada, and now includes the co-owners wallet! Christophe now officially has skin-in-the-game. Welcome to the club rookie.

<blockquote class="twitter-tweet" data-dnt="true" align="center"><p lang="en" dir="ltr">Pledge increase alert.<br><br>We now have 22x the pledge of ADALITE (<a href="https://twitter.com/NuFi_Official?ref_src=twsrc%5Etfw">@NuFi_Official</a>) group of 18 pools. 🤷‍♂️ <a href="https://twitter.com/hashtag/CardanoADA?src=hash&amp;ref_src=twsrc%5Etfw">#CardanoADA</a> <a href="https://twitter.com/hashtag/Cardano?src=hash&amp;ref_src=twsrc%5Etfw">#Cardano</a> <a href="https://twitter.com/hashtag/CardanoCommunity?src=hash&amp;ref_src=twsrc%5Etfw">#CardanoCommunity</a> <a href="https://twitter.com/Cardano_CF?ref_src=twsrc%5Etfw">@Cardano_CF</a> <a href="https://twitter.com/Cardano?ref_src=twsrc%5Etfw">@Cardano</a> <a href="https://twitter.com/CardanoSPA?ref_src=twsrc%5Etfw">@CardanoSPA</a> <a href="https://t.co/hzBsOmeWOy">pic.twitter.com/hzBsOmeWOy</a></p>&mdash; BALANCE (@BalanceData22) <a href="https://twitter.com/BalanceData22/status/1646981987062763529?ref_src=twsrc%5Etfw">April 14, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

{% img src="balnc_pledge_increase.png" alt="balnc_pledge_increase" %}

As always, be sure to give us feedback and hope you enjoyed the article! Until next time.

Cheers,

The BALANCE Team

