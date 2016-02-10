## v0.2.0 2016-02-05

* Added: Support for updating and deleting customers.
* Added: A `Nonces` module for help testing transactions.
* Changed: Include testing support `Braintree.Testing.CreditCardNumbers` as well as
  `Braintree.Testing.Nonces` in `lib/testing`, making it available in packaged
  releases.
* Fixed: Trying to call `XML.load` on empty strings returns an empty map.
* Removed: The `__using__` macro has been removed from HTTP because the naming
  conflicted with `delete` actions. An equivalent macro will be introduced in
  the future.

## v0.1.0 2016-02-03

* Initial release with support for `Customer.create` and `Transaction.sale`.