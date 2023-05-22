* BodyStyleSettings.xml<br>
** cleanly separate content from data<br>
** internationalize it<br>
** normalize it<br>
* Save configurations<br>
** allow lookup by either ss or config id<br>
* Records Vault<br>
** Blazer EV - Live in production July 12th<br>
** Hummer EV - Live in production July 18th<br>
** PreOrderMode<br>
*** prod client secret gets 200 against pprod RV<br>
*** respond to email re: azure client secret mismatch<br>
* Consolidated Image List<br>
** might just be a property key
* Limit FullyConfigured by Trim<br>
** ie the Denali / Avenir problem<br>
* Smarter Super Cache<br>
** Make sure baseline fully configured responses from the model matrix are always cached<br>
** Make sure limits on fully configured responses only apply to non-baseline configurations<br>
** Extend caching into the 1st level of the rules engine tree (ie 1 toggle away from baseline)<br>
* Deal with Toggle/Retrieve outliers<br>
** Daily report of heinous Chrome calls (more than 60 seconds for a toggle/retrieve)<br>
** Come up with a plan to mitigate<br>
* Predictive Customer Activity Analysis<br>
** vehicle popularity by zip code<br>
** trim popularity by zip code<br>
** option popularity by zip code<br>
* Java17
* OAuth2 on ADO
* APIM on ADO
* ShoppingLinks - hostnames
* SwaggerConfig
* DataSync Validation<br>
** Set validate back to true as soon as we get DataSyncTest.runtimeCheckout() to support branch name configuration<br>
** There is no need to validate the pprod profile against the stp-prod branch but we still should validate<br>
** the prod profile against stp-prod and pprod profile against the master branch<br>
