## v3.1.0

### New Features & Improvements

#### Consignee exporting

We now support the ability to export your entire consignee address book. A new `Export Consignees` button is available on the consignees section that will allow you to export your consignees to an Excel spreadsheet.

#### Shipment history

We've added a new `Shipment Account History` tab to our shipments section that allows you to view the entire shipment history of any billing account connected with your login.

#### View shipments connected to a parcel invoice

When viewing your parcel invoices under billing, we now support the ability to view any shipments associated with that invoice directly on our shipping platform.

#### Streamlined package preset selection

Now when selecting a package preset, the preset will automatically be added as a package to your current shipment.

#### Shipping label re-print functionality on tracking

You now have the ability to re-print a shipping label directly from the tracking section for easy reference.

### Fixes & Other Misc Changes

- Closed pickups are no longer shown as an available option when creating a shipment
- Customer ID's are now shown correctly on the label when the 'Display unique ID on waybill' option is enabled
- Certain numeric input fields (e.g., weight and dimensions) now correctly accept decimal values
- Tracking will no longer display out for delivery when a parcel is still in transit
- Fixed an issue that would prevent a rate estimate from being generated if the parcel had DGG
- Fixed an issue that would sometimes prevent registration when an address was typed in manually
- Fixed an issue that would on rare occasion prevent a consignee's address or contacts from being modified
- Signature-related surcharges are now being handled correctly on quick rate
- Reference numbers on the pre-billing tab within the billing section now have hyperlinks to tracking
- Billing reference codes are now displayed in the current locale (e.g., FAC instead of INV)
- Added a missing unit suffix to the weight field for DGG shipments for improved clarity
- The consignee search dropdown now displays the default collect billing account, when applicable
- The pickups section now has a filter to only display active pickups, which is enabled by default
- The unlock full shipment details button has been replaced with a much more prominent and easy-to-use card
- We've added a hyperlink to the useful documents section of our website to the support page
- Fixed a label display issue when a comma was used inside a freight billing reference
- Added instructions as an available column under advanced shipment reports