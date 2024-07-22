A fork of [tryzxcvbn](https://github.com/lowe/tryzxcvbn) based on [zxcvbn](https://github.com/dropbox/zxcvbn).

Primary updates:

* Change log10 entropy calculations to log2, since most password entropy is calculated this way.
* Remove the "online" attack scenarios, sicne these aren't realistic for most current-day situations


Check out [StrongPhrase.net](http://strongphrase.net) for a passphrase generator.