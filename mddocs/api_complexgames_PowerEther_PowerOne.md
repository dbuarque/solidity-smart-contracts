---
id: complexgames_PowerEther_PowerOne
title: PowerOne
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> PowerOne</h2><p class="base-contracts"><span>is</span> <a href="complexgames_PowerEther_PowerEtherHelper.html">PowerEtherHelper</a><span>, </span><a href="complexgames_PowerEther_usingOraclize.html">usingOraclize</a></p><div class="source">Source: <a href="https://github.com/FriendlyUser/solidity-smart-contracts//blob/v0.2.0/contracts/complexgames/PowerEther.sol" target="_blank">complexgames/PowerEther.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="complexgames_PowerEther_PowerOne.html#_powerOne">_powerOne</a></li><li><a href="complexgames_PowerEther_PowerOne.html#makePowerOneBid">makePowerOneBid</a></li><li><a href="complexgames_PowerEther_PowerOne.html#onlyOraclize">onlyOraclize</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="modifiers"><h3>Modifiers</h3><ul><li><div class="item modifier"><span id="onlyOraclize" class="anchor-marker"></span><h4 class="name">onlyOraclize</h4><div class="body"><code class="signature">modifier <strong>onlyOraclize</strong><span>() </span></code><hr/><div class="description"><p>Checks only Oraclize address is calling.</p></div></div></div></li></ul></div><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="_powerOne" class="anchor-marker"></span><h4 class="name">_powerOne</h4><div class="body"><code class="signature">function <strong>_powerOne</strong><span>(string result, uint256 pnOne, address playerAddress) </span><span>internal </span></code><hr/><div class="description"><p>Internal core logic of the PowerOne game.</p></div><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>result</code> - string</div><div><code>pnOne</code> - uint256</div><div><code>playerAddress</code> - address</div></dd></dl></div></div></li><li><div class="item function"><span id="makePowerOneBid" class="anchor-marker"></span><h4 class="name">makePowerOneBid</h4><div class="body"><code class="signature">function <strong>makePowerOneBid</strong><span>(uint256 numberOne) </span><span>public </span><span>payable </span></code><hr/><div class="description"><p>Makes the bid to the PowerOne game.</p></div><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd><a href="complexgames_PowerEther_PowerEtherBase.html#isHuman">isHuman </a><a href="complexgames_PowerEther_PowerEtherBase.html#isActivated">isActivated </a></dd><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>numberOne</code> - uint256</div></dd></dl></div></div></li></ul></div></div></div>