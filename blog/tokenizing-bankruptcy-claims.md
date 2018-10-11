---
description: >-
  Proposal: Use Digital Assets to Track Ownership of Bankruptcy Claims (e.g.,
  ERC20 token)
---

# Tokenizing Bankruptcy Claims

One of the biggest headaches I can recall as a junior associate was managing ‘ownership’ schedules for bankruptcy claims. Complex cases can drag on for years and creditors often sell off pieces of their ‘claims’ to get immediate satisfaction. This often leaves a ‘family tree’ of transfers down the line of various sub-creditors and much work for junior associates, with little room for error.

For example, you might see a $9 billion claim held by a major creditor \(e.g., Pension Benefit Guaranty Corporation\) get whittled down to hundreds of minor claims over time and spread across various counter-parties and geographies, resulting in complex paperwork and diligence review whenever these splinters change hands. But this has been a necessary frustration: without a careful record of these ‘downstream’ transfers between the initial creditor and various sub-creditors, a court might not allow repayment and there’s plenty of room for dispute — hardly ideal for claiming large sums against a dwindling estate.

The end result: transactions involving bankruptcy claims often require arduous review \(open to error\) to ensure these claims are properly ‘accounted for’ when they cross into court.

Proposal: Use Digital Assets to Track Ownership of Bankruptcy Claims \(e.g., ERC20 token\):

\(i\) Creditor \(“Bob”\) creates ERC20 token to represent claim\(s\) against Debtor \(total amount of tokens = 100% ownership of claim\(s\)\) \(“Bnkrpt01”\);

\(ii\) Bob files typical Proof of Claim \(“PoC”\) with Bankruptcy Court that references Bnkrpt01 contract;

Bob now has a digital asset tied to his PoC. Huzzah. While there could be numerous digital assets referencing Bob’s PoC and court docket \(not sure why?\), only Bob’s PoC should reference this digital asset, providing a unique link. By ‘tokenizing’ his PoC, he can also provide a transparent and tamper-proof record of its ownership without involving third-parties. This seems a fair step towards “Tokenizing Bankruptcy Claims.”

Next? Convince bankruptcy courts to recognize ownership of Bnkrpt01 tokens as ownership of the underlying PoC or ‘real-world bankruptcy claim.’ Though holding a private key that controls 20% of Bnkrpt01 should reasonably reflect a similar right over the original PoC, it is not clear how this will proceed in practice. Converting bankruptcy claims into easily-traded-and-tracked digital assets seems too promising to punt, though.

Short of that \(and perhaps the next best step\), transfer agreements should reference a Bnkrpt01 token contract to establish the record of ownership over underlying claims. Schedules detailing past transfers really shouldn’t be necessary — Bob or any of his sub-creditors can only transfer the amount of Bnkrpt01 tokens that they actually control \(nevertheless, a simple etherscan.io page for the Bankrpt01 token contract can tell a complex story\).

For now, it’s safe to assume most sub-creditors would want more than mere Bnkrpt01 tokens before pressing their claims at court. However, the above exercise should provide a ready way to track ownership and accustom the bankruptcy process to these tools. The prospect of automating ‘Notices of Transfer’ and related filings on court dockets directly following Bnkrpt01 transfers seems more than promising. Going further, Bnkrpt01 tokens could plug into other markets and exchange against a multitude of ERC20 digital assets \(e.g., ETH, GNT, and all the fun stuff waiting to get tokenized, such as customer loyalty points, game items, fractional real estate, etc.\)

I will try and revisit this proposal in the coming weeks, as I think there is much more to chew on…. until then.

// July 30, 2018 via [https://bit.ly/2IQPNSE](https://bit.ly/2IQPNSE)

