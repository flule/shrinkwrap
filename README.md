Shrink Wrap
===
A full-featured URL shrinking service.

URL Shrinking
-------------
Shrink Wrap's primary purpose is to shrink URLs. There are two mechanisms
provided for wrapping the url:

 * *Automatic* - A unique hash is automatically generated for the URL. For more
   information see *URL Hashing*
 * *Manual* - Manual wrapping allows you to manually define a hash for the URL.
   This gives you the ability to make URLs that are more memorable than the
   automatic method.

URL Hashing
-----------
The hashing algorithm does not care one bit about the contents of the URL. Each
hash is mearly the next auto increment ID from MySQL convereted from base-2 to
base-36. With this method there's no chance of hashes overwriting each other and
a very large upper limit on the number of hashes.

Statistics
----------
Statistics are gathered for every URL entered into the database. For each entry,
you will be able to view:

 * Total Hits
 * Total Previews
 * Total Follow-thrus (hit after preview)
 * Referrer List

Additionaly, you will be able to view statistics for a range of time.

