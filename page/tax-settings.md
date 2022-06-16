*Setting up taxes and tax rates is one of the first tasks you want to perform when setting up a store. Taxes can be a complex matter, but BECommerce aims to make the setup as straightforward as possible.*

#### 1. Enable the Tax 

Go to **SYSTEM SETTINGS &gt; TAX SETTINGS &gt; Enable tax rates and calculations**

- **Calculate tax based on:** Customer shipping address/Customer billing address
- **Prices entered with tax:** Yes, I will enter prices inclusive of tax/No, I will enter prices inclusive of tax
 
![](/assets/images/tax-settings/b56ad9e06a905f4d70218b68263c4c9f.png)

#### 2. Tax Rate:

In the tax rates table, you can define tax rates (one per row). Click "Add item" to get started.

- **Tax Name** – Name your tax, e.g. VAT Priority – Choose a priority for this tax rate. Only 1 matching rate per priority will be used. To define multiple tax rates for a single area you need to specify a different priority per rate.
- **Country Code** – 2 digit country code for the rate. Use ISO 3166-1 alpha-2 codes. Leave blank (\*) to apply to all countries.
- **State Code** – 2 digit state code for the rate. See i18n/states/COUNTRYCODE.php for supported states. For the US, use a 2 digit abbreviation e.g. AL. Leave blank (\*) to apply to all states.
- **ZIP/Postcode** – Enter postcodes for the rate. You may separate multiple values with a semi-colon (;), use wildcards to match several postcodes (e.g. PE\* would match all postcodes starting with PE), and use numeric ranges (e.g. 2000…3000). Leave blank (\*) to apply to all postcodes.
- **City** – Semi-colon separated list of cities for the rate. Leave blank (\*) to apply to all cities.
- **Rate %** – Enter the tax rate, for example, 20.000 for a tax rate of 20%.
 
![](/assets/images/tax-settings/9e0d950b66a33292055708a6d8717957.png)