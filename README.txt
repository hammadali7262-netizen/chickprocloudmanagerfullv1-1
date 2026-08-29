ChickPro Production Fixed v2

Based on the user's uploaded ChickPro Manager HTML. Fixes included:
- Added a dedicated Chicken Waste / Wastage entry screen.
- Waste records support date, product, category, quantity, unit, remarks, edit and delete.
- Added complete purchase listing with edit/delete and supplier/product selectors.
- Sales register shows Date, Item, Qty, Unit, Rate (Rs), Total (Rs), Payment Mode, Customer Name, Phone Number, Remarks, Edit/Delete.
- Sale edit updates both sale header and sale item.
- Processing batches and distribution support edit/delete.
- Admin permissions expanded to all operational modules: wastage, waste sales, daily prices, day close, import/export, staff.
- Admin permission matrix is explicitly visible and editable.
- Audit triggers added for wastage, returns, waste sales, daily prices, day close, and permission changes.
- RLS policies added for wastage, returns, waste sales, daily prices, and day close so authenticated users can use them.
- Date period selectors remain: Today, Yesterday, This Week, Last Week, This Month, Last Month, Custom.
- Day Close has edit/delete.
- Inventory formula continues to use purchase + processing distribution + returns - sales - wastage.

Important: this is still a single-file browser app using the Supabase publishable key. Deploy this index.html to the existing Vercel project. Do not expose any Supabase secret/service-role key.
