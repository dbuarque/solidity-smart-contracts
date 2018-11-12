---
id: other_CredVert_CredentialFactoryOrg_CredentialOrgFactory
title: CredentialOrgFactory
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> CredentialOrgFactory</h2><p class="base-contracts"><span>is</span> <a href="other_CredVert_Pausable.html">Pausable</a></p><div class="source">Source: <a href="https://github.com/FriendlyUser/solidity-smart-contracts//blob/v0.1.0/contracts/other/CredVert/CredentialFactoryOrg.sol" target="_blank">other/CredVert/CredentialFactoryOrg.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="other_CredVert_CredentialFactoryOrg_CredentialOrgFactory.html#CredentialOrgEvent">CredentialOrgEvent</a></li><li><a href="other_CredVert_CredentialFactoryOrg_CredentialOrgFactory.html#createCredentialOrg">createCredentialOrg</a></li><li><a href="other_CredVert_CredentialFactoryOrg_CredentialOrgFactory.html#">fallback</a></li><li><a href="other_CredVert_CredentialFactoryOrg_CredentialOrgFactory.html#getOwner">getOwner</a></li><li><a href="other_CredVert_CredentialFactoryOrg_CredentialOrgFactory.html#isCredentialOrg">isCredentialOrg</a></li><li><a href="other_CredVert_CredentialFactoryOrg_CredentialOrgFactory.html#selectCredentialOrgByAddress">selectCredentialOrgByAddress</a></li><li><a href="other_CredVert_CredentialFactoryOrg_CredentialOrgFactory.html#selectCredentialOrgByPosition">selectCredentialOrgByPosition</a></li><li><a href="other_CredVert_CredentialFactoryOrg_CredentialOrgFactory.html#selectOrgCount">selectOrgCount</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="events"><h3>Events</h3><ul><li><div class="item event"><span id="CredentialOrgEvent" class="anchor-marker"></span><h4 class="name">CredentialOrgEvent</h4><div class="body"><code class="signature">event <strong>CredentialOrgEvent</strong><span>(address schoolAddress, string detail) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>schoolAddress</code> - address</div><div><code>detail</code> - string</div></dd></dl></div></div></li></ul></div><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="createCredentialOrg" class="anchor-marker"></span><h4 class="name">createCredentialOrg</h4><div class="body"><code class="signature">function <strong>createCredentialOrg</strong><span>(string _shortName, string _officialSchoolName, address _schoolAddress) </span><span>public </span><span>returns  (bool) </span></code><hr/><div class="description"><p>Allows owner to create new credentialing orgs.</p></div><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd><a href="other_CredVert_Ownable.html#onlyOwner">onlyOwner </a><a href="other_CredVert_Pausable.html#whenNotPaused">whenNotPaused </a></dd><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_shortName</code> - shortName of Credentialing orgs</div><div><code>_officialSchoolName</code> - official School Name</div><div><code>_schoolAddress</code> - address of credential org.</div></dd><dt><span class="label-return">Returns:</span></dt><dd>createStatus bool noting creation status success or failure</dd></dl></div></div></li><li><div class="item function"><span id="fallback" class="anchor-marker"></span><h4 class="name">fallback</h4><div class="body"><code class="signature">function <strong></strong><span>() </span><span>public </span></code><hr/><div class="description"><p>Class constructor.</p></div></div></div></li><li><div class="item function"><span id="getOwner" class="anchor-marker"></span><h4 class="name">getOwner</h4><div class="body"><code class="signature">function <strong>getOwner</strong><span>() </span><span>public </span><span>view </span><span>returns  (address) </span></code><hr/><div class="description"><p>Gets owners address.</p></div><dl><dt><span class="label-return">Returns:</span></dt><dd>returns contractOwners Address</dd></dl></div></div></li><li><div class="item function"><span id="isCredentialOrg" class="anchor-marker"></span><h4 class="name">isCredentialOrg</h4><div class="body"><code class="signature">function <strong>isCredentialOrg</strong><span>(address _credentialOrgAddress) </span><span>public </span><span>view </span><span>returns  (bool) </span></code><hr/><div class="description"><p>Allows checking if credentialOrg exists.</p></div><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_credentialOrgAddress</code> - function returns bool if an address is a credentialingOrg</div></dd><dt><span class="label-return">Returns:</span></dt><dd>isAddress returns true if address is Credentialing Org, false if not.</dd></dl></div></div></li><li><div class="item function"><span id="selectCredentialOrgByAddress" class="anchor-marker"></span><h4 class="name">selectCredentialOrgByAddress</h4><div class="body"><code class="signature">function <strong>selectCredentialOrgByAddress</strong><span>(address _credentialOrgAddress) </span><span>public </span><span>view </span><span>returns  (string, string, address) </span></code><hr/><div class="description"><p>Allows selection of a credentialingOrg by address.</p></div><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_credentialOrgAddress</code> - allows selection of credentialing orgs details.</div></dd><dt><span class="label-return">Returns:</span></dt><dd>school -the schools ethereum address</dd></dl></div></div></li><li><div class="item function"><span id="selectCredentialOrgByPosition" class="anchor-marker"></span><h4 class="name">selectCredentialOrgByPosition</h4><div class="body"><code class="signature">function <strong>selectCredentialOrgByPosition</strong><span>(uint32 _credentialOrgPosition) </span><span>public </span><span>view </span><span>returns  (string, string, address) </span></code><hr/><div class="description"><p>Allows selection of a credentialingOrg by position.</p></div><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_credentialOrgPosition</code> - allows selection of credentialing orgs details.</div></dd><dt><span class="label-return">Returns:</span></dt><dd>school -the schools ethereum address</dd></dl></div></div></li><li><div class="item function"><span id="selectOrgCount" class="anchor-marker"></span><h4 class="name">selectOrgCount</h4><div class="body"><code class="signature">function <strong>selectOrgCount</strong><span>() </span><span>public </span><span>view </span><span>returns  (uint32) </span></code><hr/><div class="description"><p>Returns the credentialOrgCount.</p></div><dl><dt><span class="label-return">Returns:</span></dt><dd>returnOrgCount - returns the total credential orgs count</dd></dl></div></div></li></ul></div></div></div>