---
id: games_PowerEther_PowerEther_PowerFour
title: PowerFour
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> PowerFour</h2><p class="base-contracts"><span>is</span> <a href="games_PowerEther_PowerEther_PowerTwo.html">PowerTwo</a></p><div class="source">Source: <a href="https://github.com/FriendlyUser/solidity-smart-contracts//blob/v0.2.0/contracts/games/PowerEther/PowerEther.sol" target="_blank">games/PowerEther/PowerEther.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="games_PowerEther_PowerEther_PowerFour.html#_powerFour">_powerFour</a></li><li><a href="games_PowerEther_PowerEther_PowerFour.html#makePowerFourBid">makePowerFourBid</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="_powerFour" class="anchor-marker"></span><h4 class="name">_powerFour</h4><div class="body"><code class="signature">function <strong>_powerFour</strong><span>(string result, uint256 pnOne, uint256 pnTwo, uint256 pnThree, uint256 pnFour, address playerAddress) </span><span>internal </span></code><hr/><div class="description"><p>Internal core logic of the PowerFour game.</p></div><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>result</code> - string</div><div><code>pnOne</code> - uint256</div><div><code>pnTwo</code> - uint256</div><div><code>pnThree</code> - uint256</div><div><code>pnFour</code> - uint256</div><div><code>playerAddress</code> - address</div></dd></dl></div></div></li><li><div class="item function"><span id="makePowerFourBid" class="anchor-marker"></span><h4 class="name">makePowerFourBid</h4><div class="body"><code class="signature">function <strong>makePowerFourBid</strong><span>(uint256 numberOne, uint256 numberTwo, uint256 numberThree, uint256 numberFour) </span><span>public </span><span>payable </span></code><hr/><div class="description"><p>Makes the bid to the PowerFour game.</p></div><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd><a href="games_PowerEther_PowerEther_PowerEtherBase.html#isHuman">isHuman </a><a href="games_PowerEther_PowerEther_PowerEtherBase.html#isActivated">isActivated </a></dd><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>numberOne</code> - uint256</div><div><code>numberTwo</code> - uint256</div><div><code>numberThree</code> - uint256</div><div><code>numberFour</code> - uint256</div></dd></dl></div></div></li></ul></div></div></div>