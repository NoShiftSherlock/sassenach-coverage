# The Sassenach: instant delivery and retail coverage (private sales page)

**Private sales page.** Prepared by AccelPay for a conversation with Sassenach Spirits. It uses
the brand's name and marks, which belong to their owner. Not affiliated with or endorsed by
Sassenach Spirits. Please keep it unlisted.

Live: https://noshiftsherlock.github.io/sassenach-coverage/

Built with the `alcohol-coverage` skill (`cpg-coverage-cli map` plus the retailer-network layer),
then patched: live Gopuff numbers, Esri basemap tiles, sources note.

Sources, all 2026-10-24:
- Gopuff: live brand check across 193 spirits-licensed Gopuff locations; 185 passed a control
  check; The Sassenach showed at 49, all in California. 15 of the 49 have no published city or
  delivery ZIPs, so reach and metros are a floor. Geo and ZIPs from the 2026-06-17 BigQuery snapshot.
- Retailer network: AccelPay/LiquidCommerce retailer catalog, synced 2026-10-24, cross-checked
  against the retailer inventory sheets. A store counts as in stock only if it shows stock on hand
  (141 stores); 210 list at least one Sassenach product.
- DoorDash was not measured.

Three retailers are excluded from all counts on purpose (Josh, 2026-10-24).
