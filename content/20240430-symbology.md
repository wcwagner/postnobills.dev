+++
title = "Financial symbology à la carte"
date = 2024-04-24
draft = true
[taxonomies]
tags = ["symbology", "finance", "rust"]
+++

Identifying a financial security, known as Symbology, seems trivial on the friendly UIs common to [retail](https://www.investopedia.com/terms/r/retailinvestor.asp) investing platforms that support trading standardized assets— [equities](<https://en.wikipedia.org/wiki/Equity_(finance)>), [ETFs](https://en.wikipedia.org/wiki/Exchange-traded_fund), and [options](https://en.wikipedia.org/wiki/Option_contract)—in highly developed public markets. In contrast, symbology becomes immensely more complex for [institutional](https://www.investopedia.com/terms/i/institutionalinvestor.asp) platforms that support trading more sophisticated—[futures](https://en.wikipedia.org/wiki/Futures_contract), [swaps](<https://en.wikipedia.org/wiki/Swap_(finance)>), [currencies](https://en.wikipedia.org/wiki/Foreign_exchange_market), [money-markets](https://en.wikipedia.org/wiki/Money_market), [loans](https://en.wikipedia.org/wiki/Loan), and [bonds](<https://en.wikipedia.org/wiki/Bond_(finance)>)—in both emerging markets and private bi-lateral trading (i.e., trading directly between two parties without an intermediary).

Regardless of the platform, symbology sits at the core, spanning the entire investment lifecycle of trading, risk, and settlement. This post will delve into symbology's complexities, dispelling common myths, defining the most common identifiers, and highlighting the various use-cases for symbology. In doing so, we aim to provide a solid foundation for more technical follow-up posts in our *Oxisidsing the Markets* series.
