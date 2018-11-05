---
id: wallet_TokenWallet
title: TokenWallet
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> TokenWallet</h2><p class="base-contracts"><span>is</span> <a href="wallet_CpolloWallet.html">CpolloWallet</a></p><p class="description">Wallet contract that holds token funds for a specific role. Only Wallet managers can transfer funds. .</p><div class="source">Source: <a href="https://github.com/Cpollo/Ethereum/blob/v0.0.3/contracts/wallet/TokenWallet.sol" target="_blank">wallet/TokenWallet.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="wallet_TokenWallet.html#_transfer">_transfer</a></li><li><a href="wallet_TokenWallet.html#_transferFundsScam">_transferFundsScam</a></li><li><a href="wallet_TokenWallet.html#">fallback</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="_transfer" class="anchor-marker"></span><h4 class="name">_transfer</h4><div class="body"><code class="signature">function <strong>_transfer</strong><span>(address payee, uint256 amount) </span><span>internal </span></code><hr/><div class="description"><p>Transfer tokens to destination payed.</p></div><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>payee</code> - The destination address of the funds.</div><div><code>amount</code> - uint256</div></dd></dl></div></div></li><li><div class="item function"><span id="_transferFundsScam" class="anchor-marker"></span><h4 class="name">_transferFundsScam</h4><div class="body"><code class="signature">function <strong>_transferFundsScam</strong><span>() </span><span>internal </span></code><hr/><div class="description"><p>Transfer tokens funds back to team wallet when scam happens.</p></div></div></div></li><li><div class="item function"><span id="fallback" class="anchor-marker"></span><h4 class="name">fallback</h4><div class="body"><code class="signature">function <strong></strong><span>(IERC20 token) </span><span>public </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>token</code> - Address of the token</div></dd></dl></div></div></li></ul></div></div></div>