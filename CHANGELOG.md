Change Log
=========

Version 0.2.1 *(2015-07-14)*
----------------------------

 * Fix: Add support for backpressure.


Version 0.2.0 *(2015-06-30)*
----------------------------

 * An `Observable<Query>` can now be created from wrapping a `ContentResolver` in order to observe
   queries from another app's content provider.
 * `SqlBrite` class is now a factory for both a `BriteDatabase` (the `SQLiteOpenHelper` wrapper)
   and `BriteContentResolver` (the `ContentResolver` wrapper).


Version 0.1.0 *(2015-02-21)*
----------------------------

Initial release.
