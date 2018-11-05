---
id: access_LegalRole
title: LegalRole
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> LegalRole</h2><p class="description">LegalRole role is a public registry of all legal members.Legal members can receive funds from legal escrow&#x27;s.  Only Cpollo members can add legals to the public registry.</p><div class="source">Source: <a href="https://github.com/Cpollo/Ethereum/blob/v0.0.3/contracts/access/LegalRole.sol" target="_blank">access/LegalRole.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="access_LegalRole.html#LegalAdded">LegalAdded</a></li><li><a href="access_LegalRole.html#LegalRemoved">LegalRemoved</a></li><li><a href="access_LegalRole.html#_addLegal">_addLegal</a></li><li><a href="access_LegalRole.html#_removeLegal">_removeLegal</a></li><li><a href="access_LegalRole.html#addLegal">addLegal</a></li><li><a href="access_LegalRole.html#">fallback</a></li><li><a href="access_LegalRole.html#isLegal">isLegal</a></li><li><a href="access_LegalRole.html#onlyCpollo">onlyCpollo</a></li><li><a href="access_LegalRole.html#removeLegal">removeLegal</a></li><li><a href="access_LegalRole.html#renounceLegal">renounceLegal</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="events"><h3>Events</h3><ul><li><div class="item event"><span id="LegalAdded" class="anchor-marker"></span><h4 class="name">LegalAdded</h4><div class="body"><code class="signature">event <strong>LegalAdded</strong><span>(address account) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>account</code> - address</div></dd></dl></div></div></li><li><div class="item event"><span id="LegalRemoved" class="anchor-marker"></span><h4 class="name">LegalRemoved</h4><div class="body"><code class="signature">event <strong>LegalRemoved</strong><span>(address account) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>account</code> - address</div></dd></dl></div></div></li></ul></div><div class="modifiers"><h3>Modifiers</h3><ul><li><div class="item modifier"><span id="onlyCpollo" class="anchor-marker"></span><h4 class="name">onlyCpollo</h4><div class="body"><code class="signature">modifier <strong>onlyCpollo</strong><span>() </span></code><hr/></div></div></li></ul></div><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="_addLegal" class="anchor-marker"></span><h4 class="name">_addLegal</h4><div class="body"><code class="signature">function <strong>_addLegal</strong><span>(address account) </span><span>internal </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>account</code> - address</div></dd></dl></div></div></li><li><div class="item function"><span id="_removeLegal" class="anchor-marker"></span><h4 class="name">_removeLegal</h4><div class="body"><code class="signature">function <strong>_removeLegal</strong><span>(address account) </span><span>internal </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>account</code> - address</div></dd></dl></div></div></li><li><div class="item function"><span id="addLegal" class="anchor-marker"></span><h4 class="name">addLegal</h4><div class="body"><code class="signature">function <strong>addLegal</strong><span>(address account) </span><span>public </span></code><hr/><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd><a href="access_LegalRole.html#onlyCpollo">onlyCpollo </a></dd><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>account</code> - address</div></dd></dl></div></div></li><li><div class="item function"><span id="fallback" class="anchor-marker"></span><h4 class="name">fallback</h4><div class="body"><code class="signature">function <strong></strong><span>(ICpolloRoles cpollo) </span><span>public </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>cpollo</code> - ICpolloRoles</div></dd></dl></div></div></li><li><div class="item function"><span id="isLegal" class="anchor-marker"></span><h4 class="name">isLegal</h4><div class="body"><code class="signature">function <strong>isLegal</strong><span>(address account) </span><span>public </span><span>view </span><span>returns  (bool) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>account</code> - address</div></dd><dt><span class="label-return">Returns:</span></dt><dd>bool</dd></dl></div></div></li><li><div class="item function"><span id="removeLegal" class="anchor-marker"></span><h4 class="name">removeLegal</h4><div class="body"><code class="signature">function <strong>removeLegal</strong><span>(address account) </span><span>public </span></code><hr/><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd><a href="access_LegalRole.html#onlyCpollo">onlyCpollo </a></dd><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>account</code> - address</div></dd></dl></div></div></li><li><div class="item function"><span id="renounceLegal" class="anchor-marker"></span><h4 class="name">renounceLegal</h4><div class="body"><code class="signature">function <strong>renounceLegal</strong><span>() </span><span>public </span></code><hr/></div></div></li></ul></div></div></div>