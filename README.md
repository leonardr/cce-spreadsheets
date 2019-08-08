# Spreadsheets of copyright registration renewal information

These tab-separated files are a simplified version of the output of
the [cce-python](https://github.com/leonardr/cce-spreadsheets)
project. The goal is to provide an easy (if incomplete) answer to this
question:

**Of the books published in the US before 1963, which ones had their
copyright renewed and which ones lapsed into the public domain?**

The [cce-python](https://github.com/leonardr/cce-spreadsheets) dataset
is a lot more detailed and probably better for convincing lawyers, but
these spreadsheets can be used to get a quick overview of the pre-1963
publishing landscape.

* `FINAL-renewed.tsv` - These registrations have at least one
  corresponding renewal, which means they were probably renewed and
  the underlying books are still in copyright. However, many
  registration IDs were reused over the years, and it's possible that
  the registration and renewal are for different books -- in which
  case the unrenewed book might be in the public domain after all.

* `FINAL-not-renewed.tsv` - No renewal was found for these
  registrations, so there's a very good argument that they lapsed into
  the public domain. Making this determination is an important step --
  but not the only step -- towards making digitized editions of this
  these books freely available.

* `FINAL-foreign.tsv` - Books that seem to have been published outside
    the US. Such works had their copyright restored by treaty, so
    they're all still under copyright. It's good to have a list of
    these books, in case you're wondering why a book doesn't show up
    on one of the other lists.
