# Subject heading list
At Northwestern University Libraries, we wanted to know what additional subject headings are used on records that have the LCSH (Library of Congress Subject Heading) "Anti-racism." This was used to search Gobi for new books.

## Methodology

1. in Alma analytics, search for "Anti-racism" in the subject. Include the MMSID from the bibliographic record.
2. Export the list of MMSIDs. Use this list to create a set in Alma.
3. Export this set using the Export Bibliographic Records job in Alma.
4. In MARCedit: search for all 650 \0s. Copy to Clipboard.
5. In OpenRefine: create a new project from the Clipboard.
6. Clean up the 650s. Remove all subfields except subfield $a; remove the tags, indicators, and punctuation.
7. In Excel: create a pivot table and sort in descending order.

## Questions

For any questions: https://libguides.northwestern.edu/metadata
