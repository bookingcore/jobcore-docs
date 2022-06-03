<p>&nbsp;</p>
<p><em>Setting up taxes and tax rates is one of the first tasks you want to perform when setting up a store. Taxes can be a complex matter, but BECommerce aims to make the setup as straightforward as possible.</em></p>
<h4>1. Enable the Tax&nbsp;</h4>
<p>Go to <strong>SYSTEM SETTINGS &gt; TAX SETTINGS &gt; Enable tax rates and calculations</strong></p>
<ul>
<li><strong>Calculate tax based on:</strong>&nbsp;Customer shipping address/Customer billing address</li>
<li><strong>Prices entered with tax: </strong>Yes, I will enter prices inclusive of tax/No, I will enter prices inclusive of tax</li>
</ul>
<p><img src="/assets/images/tax-settings/b56ad9e06a905f4d70218b68263c4c9f.png" alt="" width="1048" height="875" /></p>
<p>&nbsp;</p>
<h4>2. Tax Rate:</h4>
<p>In the tax rates table, you can define tax rates (one per row). Click "Add item"&nbsp;to get started.</p>
<ul>
<li><strong>Tax Name</strong> &ndash; Name your tax, e.g. VAT Priority &ndash; Choose a priority for this tax rate. Only 1 matching rate per priority will be used. To define multiple tax rates for a single area you need to specify a different priority per rate.</li>
<li><strong>Country Code</strong> &ndash; 2 digit country code for the rate. Use ISO 3166-1 alpha-2 codes. Leave blank (*) to apply to all countries.</li>
<li><strong>State Code</strong> &ndash; 2 digit state code for the rate. See i18n/states/COUNTRYCODE.php for supported states. For the US, use a 2 digit abbreviation e.g. AL. Leave blank (*) to apply to all states.</li>
<li><strong>ZIP/Postcode</strong> &ndash; Enter postcodes for the rate. You may separate multiple values with a semi-colon (;), use wildcards to match several postcodes (e.g. PE* would match all postcodes starting with PE), and use numeric ranges (e.g. 2000&hellip;3000). Leave blank (*) to apply to all postcodes.</li>
<li><strong> City</strong> &ndash; Semi-colon separated list of cities for the rate. Leave blank (*) to apply to all cities.</li>
<li><strong>Rate %</strong> &ndash; Enter the tax rate, for example, 20.000 for a tax rate of 20%.</li>
</ul>
<p>&nbsp;</p>
<p><img src="/assets/images/tax-settings/9e0d950b66a33292055708a6d8717957.png" alt="" width="664" height="619" /></p>