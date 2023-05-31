---
title: "Regional banks, how you doin'?"
date: 2023-05-26T15:59:56-07:00
draft: false
---

## Summary

Since 2022, regional banks have been having a hard time. The introduction of the Bank Term Funding Program (BTFP) has tied banking sector stress tighter with overall market liquidity. In this article, we revisit several key metrics we've been watching since SVB failure to gauge the current stress level within the banking system. We also explore the various channels through which bank stress can affect market liquidity. Through analyzing past weeks' data, we try to project a path forward for regional banks, as well as market liquidity, for the coming months.

---

## Bank stress

77 days have passed since the SVB collapse, we have witnessed three relatively large banks failing (SVB, Signature Bank, First Republic Bank). It's probably an understatement to say that the regional bank sector is under stress. SVB and Signature suffered rapid bank runs, while First Republic was on life support for two months before slowly bleeding to death.

The underlying reason for such stress is largely due to the banks' exposure to interest rate risk. Having bought in large amount of low-interest long-duration assets during the 2021-2022 Fed-induced fixed income bubble, banks suffered a large loss on their hold-to-maturity (HTM) portfolio.

![Fig1](https://raw.githubusercontent.com/zyw229/zyw229.github.io/main/contents/macro003/image001.png)

> Almost all banks suffered a few percentage point capital ratio loss due to duration exposure. SVB was one of the more severely impacted banks. As this data was reported in Q4 2022, further rapid rise in interest rates in Feb 2023 likely finally pushed SVB into underwater territory.

Some banks were more exposed to interest rate risk than others. SVB had a particularly large exposure to long-dated Treasury and Agency MBS, which saw rapid decline in value as interest rate rose rapidly in 2022, and had a concentration problem of deposits from venture capital. First Republic had a particularly low yielding loan book, as it subsidized many rich Californian homeowners with their 2% 30-year fixed mortgage (ridiculous!) in 2021.

Those were stupidity on their side, but there will always be outliers in any system. The fact that all failing banks are outliers, does not mean the system is "safe and sound". Instead, if it were "safe and sound" we wouldn't have needed programs like BTFP.

### Fed emergency bank lending facilities

To mitigate the immediate crisis, the Fed, working in conjunction with the Treasury and FDIC, has a few important tools to provide emergency liquidity to the banking system:

- **Discount Window** has been the primary lending facility before the SVB crisis, which is a standing facility that allows banks to borrow from the Fed at a penalty rate. This usage shows up in the Fed balance sheet under **"Primary credit"**;
- **Bank Term Funding Program** (BTFP) is the new facility that was introduced in the wake of the regional bank crisis. It allows banks to use long-term treasury & MBS to borrow from fed at a penalty rate, but in the amount of **par value** of those assets. This is intended to completely negate the impact of interest-rate loss on banks. This usage shows up in the Fed balance sheet under **"Bank Term Funding Program"**;
- **Loans to FDIC** happens when a bank is shut down and goes into FDIC receivership. Fed extend temporary loans to those banks to allow FDIC to pay out depositors, with guarantee that FDIC will eventually pay back these loans. This usage shows up in the Fed balance sheet under **"Other credit extensions"**.

![Fig2](https://raw.githubusercontent.com/zyw229/zyw229.github.io/main/contents/macro003/image002.png)

> Above-mentioned facilities shows up as reserve balance entries in the Fed balance sheet.

As discussed in my [previous article](https://zyw229.github.io/posts/macro001/), although not technically QE, the above-mentioned facilities positively impact overall market liquidity. An increase in usage of those facilities should have a marginal equivalent effect of QE, as it marginally pushes investors into riskier assets.

### Liquidity push and pull

The introduction of BTFP created an interesting dynamic. The tighter financial condition is, the more usage of BTFP it encourages, therefore effectively negating some of the effects of tight financial condition.

If financial condition is so tight to the extent that it causes more banks to fail, the tightening effect caused by money being destroyed will also be partially negated by liquidity injection through FDIC loans.

![Fig4](https://raw.githubusercontent.com/zyw229/zyw229.github.io/main/contents/macro003/image004.png)

> Since April, BTFP usage change has had a somewhat weak correlation with 10-year yield (higher 10-year yield -> tighter financial condition -> more BTFP usage). As 10-year yield getting closer to its February levels, BTFP usage should continue to increase in the coming weeks.

### How heavily are those facilities used?

Quantitatively, how much liquidity has these facilities contributed to overall market liquidity? Here, we look at the individual usage of these facilities since the start of March, right before the SVB failure.

![Fig3](https://raw.githubusercontent.com/zyw229/zyw229.github.io/main/contents/macro003/image003.png)

> The aggregate usage of BTFP, Discount window & FDIC loans over the last 12 weeks.

Let's interpret the above figure:

* In the week of 3/15, we saw a large spike in FDIC loans as SVB & Signature bank went into FDIC receivership. There is also a large spike in Discount Window usage reflecting the shock in the regional bank sector;
* In the week of 3/22, total amount of injected liquidity peaked. Since then, banks have been gradually shifting their Discount Window loans into BTFP, all the way until the week of 4/5;
* In the week of 5/3, First Republic Bank went into FDIC receivership. The Discount Window loans they were using were transferred to FDIC loans. To my surprise, this event did not increase the overall liquidity;
* Since then until 5/24, there has been a steady increase in the usage of BTFP. However, that was not enough to offset FDIC loan repayment. Overall level of injected liquidity continued to steadily decrease.

## How would liquidity situation evolve?

As indicated above, the usage of such facilities has been generally trending down since 3/22. As FDIC loans gets repaid fairly quickly, we should generally see the green bars continue to shrink.

On the other hand, as the inflation / soft-landing narrative takes center stage again, we are seeing treasury yield continue to climb back closer to its February level, causing more stress in the banking sector. This should result in more usage of BTFP, thus partially offsetting the liquidity shrink caused by FDIC loan repayment.

Assuming no more bank failures, the ongoing QT and the upcoming TGA refill (to be discussed in a separate article, assuming debt ceiling gets resolved), should outweigh the net positive effects of these facilities (if any).

### Bank walk & controlled demolition

Banks have other assets that are not BTFP-eligible (e.g. commercial real estate loans). If anything, those will probably be the main reason if more banks were to fail later in the year. However, after the initial SVB shock that caught regional banks off guard, a lot of banks have significantly improved their asset allocation to be more resilient to future interest rate shocks. One notable example is one struggling bank: PacWest, who [proactively offloaded some portion of its bad loans](https://finance.yahoo.com/news/struggling-pacwest-offloads-real-estate-151928827.html). All regional banks, barring a few outliers, should be well positioned to survive another few months.

Although banks can do whatever they need to improve its asset allocation, it cannot solve the fundamental problem that deposits are slowly leaving the system. This deposit loss is not necessarily due to panic, but rather due to much better alternative (even the RRP is at 5%!) compared to the deposit rates those banks are offering.

![Fig5](https://raw.githubusercontent.com/zyw229/zyw229.github.io/main/contents/macro003/image005.png)

> Deposit level shows modest outflow (not seasonally adjusted) for both large & small US banks since SVB failure.

First Republic has shown us a slow bank run can cause a bank to fail. As this "bank walk" continues across the board, and with no massive monetary policy relief in sight, it's only a matter of time until more regional banks collapse under pressure. After a relatively stable period, in a few months time, we may start to see another wave of bank failures as the pressure builds up again. And this controlled demolition of regional banks goes on...

## Liquidity outlook

In the short term, relative stability in the regional banks is bad news for market liquidity, since it sets up a period of liquidity drain.

With the Treasury replenishing the TGA in the second half of year, financial condition is likely to further worsen on top of that, causing interest rates to rise in the near term, and more bank stress. Although BTFP usage can negate part of this financial condition tightening, my expectation is that it won't be of the same magnitude as QT + TGA combined.

Until more bank fails, there is probably no liquidity relief in sight. Investors will have to get through the next few months and, ironically, pray for the next batch of banks to fail. And, maybe if enough of them fail, the Fed will go back to buying stuff again in the second half of the year :)