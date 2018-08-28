---
id: version-1.10.0-token_ERC20_ERC20
title: ERC20
original_id: token_ERC20_ERC20
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> ERC20</h2><p class="base-contracts"><span>is</span> <a href="token_ERC20_ERC20Basic.html">ERC20Basic</a></p><p class="description">See https://github.com/ethereum/EIPs/issues/20.</p><div class="source">Source: <a href="https://github.com/OpenZeppelin/zeppelin-solidity/blob/v1.10.0/contracts/token/ERC20/ERC20.sol" target="_blank">token/ERC20/ERC20.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="token_ERC20_ERC20.html#Approval">Approval</a></li><li><a href="token_ERC20_ERC20.html#allowance">allowance</a></li><li><a href="token_ERC20_ERC20.html#approve">approve</a></li><li><a href="token_ERC20_ERC20.html#transferFrom">transferFrom</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="events"><h3>Events</h3><ul><li><div class="item event"><span id="Approval" class="anchor-marker"></span><h4 class="name">Approval</h4><div class="body"><code class="signature">event <strong>Approval</strong><span>(address owner, address spender, uint256 value) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>owner</code> - address</div><div><code>spender</code> - address</div><div><code>value</code> - uint256</div></dd></dl></div></div></li></ul></div><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="allowance" class="anchor-marker"></span><h4 class="name">allowance</h4><div class="body"><code class="signature"><span>abstract </span>function <strong>allowance</strong><span>(address owner, address spender) </span><span>public </span><span>view </span><span>returns  (uint256) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>owner</code> - address</div><div><code>spender</code> - address</div></dd><dt><span class="label-return">Returns:</span></dt><dd>uint256</dd></dl></div></div></li><li><div class="item function"><span id="approve" class="anchor-marker"></span><h4 class="name">approve</h4><div class="body"><code class="signature"><span>abstract </span>function <strong>approve</strong><span>(address spender, uint256 value) </span><span>public </span><span>returns  (bool) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>spender</code> - address</div><div><code>value</code> - uint256</div></dd><dt><span class="label-return">Returns:</span></dt><dd>bool</dd></dl></div></div></li><li><div class="item function"><span id="transferFrom" class="anchor-marker"></span><h4 class="name">transferFrom</h4><div class="body"><code class="signature"><span>abstract </span>function <strong>transferFrom</strong><span>(address from, address to, uint256 value) </span><span>public </span><span>returns  (bool) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>from</code> - address</div><div><code>to</code> - address</div><div><code>value</code> - uint256</div></dd><dt><span class="label-return">Returns:</span></dt><dd>bool</dd></dl></div></div></li></ul></div></div></div>