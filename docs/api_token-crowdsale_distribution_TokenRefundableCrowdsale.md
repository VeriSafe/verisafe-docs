---
id: token-crowdsale_distribution_TokenRefundableCrowdsale
title: TokenRefundableCrowdsale
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> TokenRefundableCrowdsale</h2><p class="base-contracts"><span>is</span> <a href="token-crowdsale_distribution_TokenFinalizableCrowdsale.html">TokenFinalizableCrowdsale</a></p><p class="description">Extension of Crowdsale contract that adds a funding goal, and the possibility of users getting a refund if goal is not met.</p><div class="source">Source: <a href="https://github.com/Cpollo/Ethereum/blob/v0.0.3/contracts/token-crowdsale/distribution/TokenRefundableCrowdsale.sol" target="_blank">token-crowdsale/distribution/TokenRefundableCrowdsale.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="token-crowdsale_distribution_TokenRefundableCrowdsale.html#_finalization">_finalization</a></li><li><a href="token-crowdsale_distribution_TokenRefundableCrowdsale.html#_forwardTokenFunds">_forwardTokenFunds</a></li><li><a href="token-crowdsale_distribution_TokenRefundableCrowdsale.html#claimRefund">claimRefund</a></li><li><a href="token-crowdsale_distribution_TokenRefundableCrowdsale.html#escrow">escrow</a></li><li><a href="token-crowdsale_distribution_TokenRefundableCrowdsale.html#">fallback</a></li><li><a href="token-crowdsale_distribution_TokenRefundableCrowdsale.html#goal">goal</a></li><li><a href="token-crowdsale_distribution_TokenRefundableCrowdsale.html#goalReached">goalReached</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="_finalization" class="anchor-marker"></span><h4 class="name">_finalization</h4><div class="body"><code class="signature">function <strong>_finalization</strong><span>() </span><span>internal </span></code><hr/><div class="description"><p>Escrow finalization task, called when finalize() is called.</p></div></div></div></li><li><div class="item function"><span id="_forwardTokenFunds" class="anchor-marker"></span><h4 class="name">_forwardTokenFunds</h4><div class="body"><code class="signature">function <strong>_forwardTokenFunds</strong><span>(address beneficiary, uint256 amount) </span><span>internal </span></code><hr/><div class="description"><p>Overrides Crowdsale fund forwarding, sending funds to escrow.</p></div><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>beneficiary</code> - address</div><div><code>amount</code> - uint256</div></dd></dl></div></div></li><li><div class="item function"><span id="claimRefund" class="anchor-marker"></span><h4 class="name">claimRefund</h4><div class="body"><code class="signature">function <strong>claimRefund</strong><span>(address beneficiary) </span><span>public </span></code><hr/><div class="description"><p>Investors can claim refunds here if crowdsale is unsuccessful.</p></div><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>beneficiary</code> - Whose refund will be claimed.</div></dd></dl></div></div></li><li><div class="item function"><span id="escrow" class="anchor-marker"></span><h4 class="name">escrow</h4><div class="body"><code class="signature">function <strong>escrow</strong><span>() </span><span>public </span><span>view </span><span>returns  (address) </span></code><hr/><dl><dt><span class="label-return">Returns:</span></dt><dd>minimum amount of funds to be raised in wei.</dd></dl></div></div></li><li><div class="item function"><span id="fallback" class="anchor-marker"></span><h4 class="name">fallback</h4><div class="body"><code class="signature">function <strong></strong><span>(uint256 goal) </span><span>public </span></code><hr/><div class="description"><p>Constructor, creates RefundEscrow.</p></div><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>goal</code> - Funding goal</div></dd></dl></div></div></li><li><div class="item function"><span id="goal" class="anchor-marker"></span><h4 class="name">goal</h4><div class="body"><code class="signature">function <strong>goal</strong><span>() </span><span>public </span><span>view </span><span>returns  (uint256) </span></code><hr/><dl><dt><span class="label-return">Returns:</span></dt><dd>minimum amount of funds to be raised in wei.</dd></dl></div></div></li><li><div class="item function"><span id="goalReached" class="anchor-marker"></span><h4 class="name">goalReached</h4><div class="body"><code class="signature">function <strong>goalReached</strong><span>() </span><span>public </span><span>view </span><span>returns  (bool) </span></code><hr/><div class="description"><p>Checks whether funding goal was reached.</p></div><dl><dt><span class="label-return">Returns:</span></dt><dd>Whether funding goal was reached</dd></dl></div></div></li></ul></div></div></div>