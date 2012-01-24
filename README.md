Yale University Library Bagger Profiles
=======================================

This repository contains profiles for use with the [Library of Congress Bagger application](http://sourceforge.net/projects/loc-xferutils/files/loc-bagger/) to create transfer packages of digital objects compliant with the [BagIt specification](http://tools.ietf.org/html/draft-kunze-bagit-06). The elements included in the profiles map to metadata elements to be included in the 
`bag-info.txt` (see section 2.2.2 of the BagIt specification)

All Yale University Library profiles are indicated by beginning with the prefix "YUL". Any other profiles are stock profiles included with Bagger.

* YUL\_DISKIMG\_ACCN\_SIP: 0.2

YUL-Specific Bag Metadata Elements
----------------------------------

These profiles for BagIt packages define additional elements for BagIt packages created by units of the Yale University Library. These additional elements are described below.

### Profile metadata ###

* `YUL-Profile-Identifier`: an internal identifier for the profile used for a given bag.
* `YUL-Profile-Version`: the version number for the profile in use
* `YUL-Profile-Description`: a brief, human-readable description of the profile
* `YUL-Profile-Maintainer`: an e-mail address or netid for the maintainer of a profile

### Source metadata ###

* `YUL-Source-Department`: the department whose content is contained within the bag; should be taken from a controlled list
    * Values currently in use are "Manuscripts and Archives" and "Beinecke Rare Book and Manuscript Library"

### Relationship metadata ###

* `YUL-Accession-Number`: an identifier for an accession associated with a given bag
* `YUL-Forms-Part-Of`: an identifier (e.g. a call number) or a title for a related collection that has been processed or cataloged 
