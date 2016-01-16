There is a lot of controversy around SSL decryption (as understood).  In order to mitigate some of the concerns i created a list of sites to bypass.

If you are doing SSL decryption / TLS decryption in your environment then you may want to add this to your list.

Note: This is not a comprehensive and exhaustive list.  But should be a good addition to an exisiting list you may have or if you are just starting off.

There are two lists. The first is domain equals exactly. The second is domain ends with.

If you are adding you own additions with domain ends with then always include the period in the beginning.

example:

correct= ".google.com"

incorrect= "google.com"

As an advisory would be able to registry badgoogle[.]com and that would be bypassed.


The list contains some of the following types of domains
* ones that are only used for logins (ie: accounts.google.com) so as not to grab users passwords
* banks
* insurance
* bill paying (ie: paypal, some power companies or water)
