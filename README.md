# GRAND CHICKEN SHOP — Android starter project

This is a starter Android Studio project for an offline-first shop-management prototype.

## Included
- English / Tamil language toggle
- Shop contact and address shown in the app
- Demo role selector (Owner, Billing Staff, Delivery)
- Basic chicken billing for whole/cut chicken
- Local device preferences for sales, expenses and stock
- Simple report screen

## Important limitations
This is a prototype, not a production-ready POS system. It does not yet include secure user accounts, role-based permissions, supplier/purchase ledger, customer order management, tax-compliant invoices, receipt printing, encrypted database, cloud sync, or tested backup/restore. The current local storage is simple Android preferences and should be replaced with Room/SQLite before real shop use. The role selector is only a demo and is not authentication.

## Build
1. Install Android Studio on a computer.
2. Open this folder in Android Studio.
3. Let Gradle sync complete (internet is needed for the first dependency download).
4. Connect an Android phone with USB debugging enabled, or create an APK using Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Test thoroughly with sample data before using it for real transactions.

Minimum Android version: Android 6.0 (API 23). Compile/target SDK: 35.
