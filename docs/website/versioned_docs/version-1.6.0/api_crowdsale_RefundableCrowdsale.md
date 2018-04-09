---
id: version-1.6.0-crowdsale_RefundableCrowdsale
title: RefundableCrowdsale
original_id: crowdsale_RefundableCrowdsale
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> RefundableCrowdsale</h2><p class="base-contracts"><span>is</span> <a href="crowdsale_FinalizableCrowdsale.html">FinalizableCrowdsale</a></p><p class="description">Extension of Crowdsale contract that adds a funding goal, and the possibility of users getting a refund if goal is not met. Uses a RefundVault as the crowdsale&#x27;s vault.</p><div class="source">Source: <a href="https://github.com/OpenZeppelin/zeppelin-solidity/blob/v1.6.0/contracts/crowdsale/RefundableCrowdsale.sol" target="_blank">crowdsale/RefundableCrowdsale.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="crowdsale_RefundableCrowdsale.html#RefundableCrowdsale">RefundableCrowdsale</a></li><li><a href="crowdsale_RefundableCrowdsale.html#claimRefund">claimRefund</a></li><li><a href="crowdsale_RefundableCrowdsale.html#finalization">finalization</a></li><li><a href="crowdsale_RefundableCrowdsale.html#forwardFunds">forwardFunds</a></li><li><a href="crowdsale_RefundableCrowdsale.html#goalReached">goalReached</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="RefundableCrowdsale" class="anchor-marker"></span><h4 class="name">RefundableCrowdsale</h4><div class="body"><code class="signature">function <strong>RefundableCrowdsale</strong><span>(uint256 _goal) </span><span>public </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_goal</code> - uint256</div></dd></dl></div></div></li><li><div class="item function"><span id="claimRefund" class="anchor-marker"></span><h4 class="name">claimRefund</h4><div class="body"><code class="signature">function <strong>claimRefund</strong><span>() </span><span>public </span></code><hr/></div></div></li><li><div class="item function"><span id="finalization" class="anchor-marker"></span><h4 class="name">finalization</h4><div class="body"><code class="signature">function <strong>finalization</strong><span>() </span><span>internal </span></code><hr/></div></div></li><li><div class="item function"><span id="forwardFunds" class="anchor-marker"></span><h4 class="name">forwardFunds</h4><div class="body"><code class="signature">function <strong>forwardFunds</strong><span>() </span><span>internal </span></code><hr/></div></div></li><li><div class="item function"><span id="goalReached" class="anchor-marker"></span><h4 class="name">goalReached</h4><div class="body"><code class="signature">function <strong>goalReached</strong><span>() </span><span>public </span><span>view </span><span>returns  (bool) </span></code><hr/><dl><dt><span class="label-return">Returns:</span></dt><dd>bool</dd></dl></div></div></li></ul></div></div></div>