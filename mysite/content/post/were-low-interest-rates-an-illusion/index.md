---
title: "Were low interest rates an illusion?"
date: 2026-11-14
share: false
summary: "Do changes in who buys government debt make today's interest rates more informative than those of the 2010s?"
image:
  preview_only: true
---

![Ten-year US Treasury yield from 2008 onward](/media/blog/were-low-interest-rates-an-illusion/yield_10y_2008_present.png)

Interest rates on longer-term government debt have risen a lot recently. It’s hard to say why this is – a lot of things have changed in the economy. Compared with the 2010s, the 2020s have given us higher inflation, higher short-term interest rates, and, arguably, more optimism about future growth. The market for government debt has changed too. Governments are issuing lots of new debt, while they lose a major set of buyers: their own central banks.

One way of interpreting these patterns (laid out well in [this](https://thetwocents.substack.com/p/what-happens-to-yields-in-between) [series](https://thetwocents.substack.com/p/global-bond-markets-marked-to-market) of [posts](https://thetwocents.substack.com/p/are-central-bankers-chasing-their) by Hanno Lustig) is that central banks used quantitative easing (buying long-term bonds) and forward guidance (communicating about the future) to force yields lower for most of the 2010s. Only now, with [profit-seeking private sector buyers](https://www.federalreserve.gov/econres/notes/feds-notes/decomposing-hedge-funds-u-s-treasury-exposures-20260622.html) once again setting prices, are governments being “forced to test the long end of the yield curve.” This means “government debt is being marked to market” – that is, it is no longer artificially overvalued (both quotes from Lustig).

My current PhD research is all about who buys government bonds, but in this post I want to push back on the view that the changing composition of buyers means interest rates now tell us more about the economy than they did in the 2010s.

## What are yields supposed to tell us?

Let’s focus on governments that borrow in their own currencies and assume that credit risk is not important[^1]. This means sidestepping questions about the divergence of yields within the euro area, which may reflect changing odds of default or redenomination (ie repaying debt in francs instead of euros). I’ll use US data below.

From the perspective of a macroeconomist, the simplest way to answer questions about long-term interest rates is to think about how they relate to short-term interest rates, since the government sets short rates directly,[^2] and our field has put a lot of thought into understanding short rates. If we knew future interest rates with certainty, the return to holding a ten-year bond for ten years would be the same as the return to rolling over a three-month bill for ten years. Because we aren’t sure about future rates, we can think of the ten-year yield as being determined by two components: the expected return on rolling over the three-month bill, plus some compensation for the risk that interest rates are not what we expect (the “term premium”)[^3].

## Some data

This framing suggests that to predict the ten-year yield we don’t need to know anything about the supply and demand for ten-year bonds; we just need to know the distribution of future short yields. That’s not entirely true, as I’ll discuss below – we have [plenty](https://www.journals.uchicago.edu/doi/10.1086/729581) of [evidence](https://www.federalreserve.gov/Pubs/feds/2012/201244/201244pap.pdf) the quantity of debt matters – but let’s start by thinking about what determines the short rate. Unlike long rates, we know what literally determines the short rate – the FOMC chooses it. One basis for arguing that the ten-year rate is also all about the FOMC’s choices is Sebastian Hillenbrand’s very cool [observation](https://academic.oup.com/rfs/article-abstract/38/4/981/7979199) that the decline in interest rates since the 1990s has happened entirely on days around FOMC meetings.

![Cumulative changes in the ten-year yield around FOMC, CPI, and PPI announcements](/media/blog/were-low-interest-rates-an-illusion/selected_cumulative_10y_fomc_cpi_ppi.png)

However, just because rates move in these windows doesn’t mean the Fed controls them – in fact, much of the action is happening on the day prior to rate announcements, which could have to do with risk management or trading dynamics, but not new information from the central bank. Furthermore, this doesn’t prove the Fed was all that mattered. If the Fed must respond to inflation, future short rates (and thus current long rates) are out of its control, and should depend on information about future inflation. If we look at the days when the BLS reports current inflation, we see that rates also fell a lot in these windows. This surprises me as much as the pattern around FOMC decisions, since information about future economic conditions is released all the time. It’s just easier to tell a story about Fed decisions, since they occur on a small handful of dates.

If we take a closer look at what’s happening on data release days, it’s not obvious that prices are any more or less sensitive to information than they were before COVID. It does look like the relationship between CPI surprises and rates may have weakened, but if we look at payroll data releases (the most watched releases related to the Fed’s full employment mandate), we see the opposite story. There’s no limit to the context central banks can consider when setting interest rates, so there’s no reason to expect these relationships to be stable.

![Ten-year yield changes versus economic data surprises before and after 2020](/media/blog/were-low-interest-rates-an-illusion/selected_surprise_scatter_10y_pre_post_2020.png)

To me, the size of the forecast errors after COVID is more striking than their relationship with rates. It’s hard to say bond prices are more informative now – there might just be more information to process. Here’s the full series of forecast errors:

![Economic data forecast errors over time](/media/blog/were-low-interest-rates-an-illusion/selected_surprise_bars.png)


## So what changed?

Based on day-to-day movements, I don’t see any reason to think yields were less informative in the 2010s than they are now. What about the bigger picture? Do high yields now mean the low yields we saw before were wrong? I don’t think so. Returning to the split between rate expectations and term premia, the world gave us reason to think rates would be lower for longer in the 2010s. Looking at forecasts one year ahead instead of one day ahead, growth and inflation persistently surprised us to the downside. In the 2020s, they persistently surprised us to the upside, justifying higher rates. This can only be a result of the Fed’s choices if you believe it has, in my opinion, an unrealistic degree of control over the economy.

![One-year-ahead growth and inflation forecasts compared with realized outcomes](/media/blog/were-low-interest-rates-an-illusion/sep_spf_1y_forecasts_vs_realized.png)

Broad economic conditions have also given us reason to think term premia (the compensation for interest rate risk) should rise. In the 2010s, bond prices tended to go up (yields went down) when stocks fell, with this hedging benefit justifying high prices. Since COVID, bonds and stocks have moved in the same direction, meaning it makes sense to pay less for bonds. There are a lot of ways to rationalize [what made this pattern flip](https://campbell.scholars.harvard.edu/sites/g/files/omnuum5881/files/2026-06/CampbellPfluegerViceira_ARFE_20260529.pdf), but the simplest intuition relies on what we know about short rates. If in the 2010s the major risk to most investments was low aggregate demand, the Fed could be relied on to lower interest rates (raising bond prices) when things were bad. If in the 2020s the major risk is constrained supply and high inflation, the Fed has to raise rates when things are bad.

## Does it matter who buys the debt?

I haven’t seen evidence that low yields were irrational, or that we can only explain the recent rise in yields by looking at who’s buying. However, that’s not to say supply and demand don’t matter. One reason quantities matter is that long-term government bonds are risky assets – because of interest rate risk, not credit risk – and more bonds outstanding means more risk to land on someone’s balance sheet. Investors with long-term liabilities, like insurance companies and pension funds, need interest rate risk in their assets to offset the risk embedded in their liabilities. As the supply of government debt increases, though, their demand may be exhausted, meaning term premia must rise to draw in other kinds of buyers. A similar story applies to regulated banks and [foreign central banks](https://www.brookings.edu/articles/whos-buying-u-s-treasury-debt-and-why/) that may be willing to pay more for Treasurys than [investors motivated purely by profit](https://jepayne.github.io/files/LPSS_HistoricalSpreads.pdf). However, unless these effects are very large, most of the rise in yields must be due to higher expected short rates.[^4]

It is possible that the quantity of debt affects not just term premia, but rate expectations. Assuming the central bank only cares about its mandate,[^5] debt must affect prices or employment in order to affect future short rates. I’ve framed the repeated upside surprises to inflation and growth as originating somewhere outside debt markets, but higher government spending and lower taxes create increasing demands on the productive capacity of the economy. Once resources are scarce enough, the government must either bid prices up or raise interest rates to convince others to spend less. It’s coherent to link deficits and inflation[^6], but I don’t see why the link would be highly contingent on who buys the debt, to the point that price signals could be suppressed for a decade.

Studying quantitative easing and term premia is super interesting, but when we talk about huge swings in yields, we need to look at more than just who is buying the debt – we have to explain why higher interest rates are needed to reach target inflation. And with that, I realize I’ve written a defense of r-star[^7].

[^1]: This means assuming printing money to repay debt is preferable to default. In practice, CDS tell us the chance of a US default has not risen enough to drive the change in yields, though who exactly can sell insurance against a US government default is not obvious.

[^2]: The Fed doesn’t literally set the rate on T-bills, but that rate follows the rate on the federal funds rate closely enough to conflate them when discussing large movements.

[^3]: I'm not mentioning the further decomposition into inflation risk and real rate risk. For simplicity, I'll talk about inflation news affecting nominal rate expectations; it only matters more if we start thinking about the full distribution of future inflation.

[^4]: This is consistent with [models separating long rates into expected short rates and term premia](https://www.newyorkfed.org/research/data_indicators/term-premia-tabs#/interactive).

[^5]: You could also imagine the central bank wants to lower government interest payments, but this would mean lowering, not raising, rates.

[^6]: I don’t want to debate the fiscal theory of the price level here. As an aside, I see this as being consistent with the progressive position that “whatever we can afford, we can pay for” – printing money is equivalent to issuing infinitely short-term debt; at the end of the day, competing claims on real resources force interest rates higher.

[^7]: I used to post the NY Fed r-star estimates.
