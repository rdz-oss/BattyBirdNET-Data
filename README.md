# BattyBirdNET-Data
Scripts and info on ML data set collection, refinement and use.

This projects targets to collect and publicly provide the best data for machine learning purposes for European bats. Thank you for being part of this data collection effort!
The BattyBirdNET-ML database is made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/. The scripts and code for processing the data are under the Apache 2.0 License.

To reach that aim try to:

- Use your best recordings for each species
- One species in a recording only
- 384kHz or higher recommended, 256kHz minimum
- Low noise levels (environment or recorder noise)
- Oganize your data in form of folders

    - battybirdnet-staging/YOUR_NAME/Latin name_Common name echo
    - battybirdnet-staging/YOUR_NAME/Latin name_Common name social
    - battybirdnet-staging/YOUR_NAME/Latin name_Common name buzz
      
- optional: Metadata in GUANO form embedded in the files

we separate echo location from calls that include social elements (see above convention) or feeding buzzes.
Upload is done via rclone. By adding your data you are ok with

- adding it under the Database Contents License to the BattyBirdNET-ML database under the Open Database License. 
- you made sure that you have the rights to do so, e.g. if you recorded the data yourself or the data is under a license that allows to add it.
- You made sure the calls are very likely made by the species you attribute it too.
- you checked to make sure (to a reasonable level of effort) that no humans were accidentally recorded. The easiest way to achieve this is to use a high-pass on the data only adding sounds over e.g. 10kHz.


Thank you and best regards.

Dr. Richard Zinck

battybirdnet@mailbox.org

https://www.researchgate.net/profile/Richard-Zinck








### Open Data Commons Open Database License (ODbL) Summary

This is a human-readable summary of the ODbL 1.0 license. Please see the disclaimer below.

You are free:

    To share: To copy, distribute and use the database.
    To create: To produce works from the database.
    To adapt: To modify, transform and build upon the database.

As long as you:

    Attribute: You must attribute any public use of the database, or works produced from the database, in the manner specified in the ODbL. For any use or redistribution of the database, or works produced from it, you must make clear to others the license of the database and keep intact any notices on the original database.
    Share-Alike: If you publicly use any adapted version of this database, or works produced from an adapted database, you must also offer that adapted database under the ODbL.
    Keep open: If you redistribute the database, or an adapted version of it, then you may use technological measures that restrict the work (such as DRM) as long as you also redistribute a version without such measures.

Disclaimer

This is not a license. It is simply a handy reference for understanding the ODbL 1.0 — it is a human-readable expression of some of its key terms. This document has no legal value, and its contents do not appear in the actual license. Read the full ODbL 1.0 license text for the exact terms that apply.



### Apache 2.0 License

Text version: https://www.apache.org/licenses/LICENSE-2.0.txt

SPDX short identifier: Apache-2.0

OSI Approved License: https://opensource.org/licenses/Apache-2.0





