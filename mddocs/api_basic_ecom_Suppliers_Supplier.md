---
id: basic_ecom_Suppliers_Supplier
title: Supplier
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> Supplier</h2><div class="source">Source: <a href="https://github.com/FriendlyUser/solidity-smart-contracts//blob/v0.1.0/contracts/basic/ecom/Suppliers.sol" target="_blank">basic/ecom/Suppliers.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="basic_ecom_Suppliers_Supplier.html#ItemAdded">ItemAdded</a></li><li><a href="basic_ecom_Suppliers_Supplier.html#ProcessAnOrder">ProcessAnOrder</a></li><li><a href="basic_ecom_Suppliers_Supplier.html#addItem">addItem</a></li><li><a href="basic_ecom_Suppliers_Supplier.html#getItem">getItem</a></li><li><a href="basic_ecom_Suppliers_Supplier.html#getStatus">getStatus</a></li><li><a href="basic_ecom_Suppliers_Supplier.html#getTotalNumberOfAvailableItems">getTotalNumberOfAvailableItems</a></li><li><a href="basic_ecom_Suppliers_Supplier.html#getTotalNumberOfOrdersProcessed">getTotalNumberOfOrdersProcessed</a></li><li><a href="basic_ecom_Suppliers_Supplier.html#processOrder">processOrder</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="events"><h3>Events</h3><ul><li><div class="item event"><span id="ItemAdded" class="anchor-marker"></span><h4 class="name">ItemAdded</h4><div class="body"><code class="signature">event <strong>ItemAdded</strong><span>(uint idItem) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>idItem</code> - uint</div></dd></dl></div></div></li><li><div class="item event"><span id="ProcessAnOrder" class="anchor-marker"></span><h4 class="name">ProcessAnOrder</h4><div class="body"><code class="signature">event <strong>ProcessAnOrder</strong><span>(uint idOfCustomer, uint idOrder, bool status) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>idOfCustomer</code> - uint</div><div><code>idOrder</code> - uint</div><div><code>status</code> - bool</div></dd></dl></div></div></li></ul></div><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="addItem" class="anchor-marker"></span><h4 class="name">addItem</h4><div class="body"><code class="signature">function <strong>addItem</strong><span>(bytes32 itemName, uint price) </span><span>public </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>itemName</code> - bytes32</div><div><code>price</code> - uint</div></dd></dl></div></div></li><li><div class="item function"><span id="getItem" class="anchor-marker"></span><h4 class="name">getItem</h4><div class="body"><code class="signature">function <strong>getItem</strong><span>(uint idItem) </span><span>public </span><span>view </span><span>returns  (bytes32, uint) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>idItem</code> - uint</div></dd><dt><span class="label-return">Returns:</span></dt><dd>bytes32</dd><dd>uint</dd></dl></div></div></li><li><div class="item function"><span id="getStatus" class="anchor-marker"></span><h4 class="name">getStatus</h4><div class="body"><code class="signature">function <strong>getStatus</strong><span>(uint idOrder) </span><span>public </span><span>view </span><span>returns  (bool) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>idOrder</code> - uint</div></dd><dt><span class="label-return">Returns:</span></dt><dd>bool</dd></dl></div></div></li><li><div class="item function"><span id="getTotalNumberOfAvailableItems" class="anchor-marker"></span><h4 class="name">getTotalNumberOfAvailableItems</h4><div class="body"><code class="signature">function <strong>getTotalNumberOfAvailableItems</strong><span>() </span><span>public </span><span>view </span><span>returns  (uint) </span></code><hr/><dl><dt><span class="label-return">Returns:</span></dt><dd>uint</dd></dl></div></div></li><li><div class="item function"><span id="getTotalNumberOfOrdersProcessed" class="anchor-marker"></span><h4 class="name">getTotalNumberOfOrdersProcessed</h4><div class="body"><code class="signature">function <strong>getTotalNumberOfOrdersProcessed</strong><span>() </span><span>public </span><span>view </span><span>returns  (uint) </span></code><hr/><dl><dt><span class="label-return">Returns:</span></dt><dd>uint</dd></dl></div></div></li><li><div class="item function"><span id="processOrder" class="anchor-marker"></span><h4 class="name">processOrder</h4><div class="body"><code class="signature">function <strong>processOrder</strong><span>(uint idOrder, uint idCustomer) </span><span>public </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>idOrder</code> - uint</div><div><code>idCustomer</code> - uint</div></dd></dl></div></div></li></ul></div></div></div>