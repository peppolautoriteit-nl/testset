
# SI-UBL test documents

These are test documents for SI-UBL, to use with a validation
package.

Generally, the tests are placed in a directory with the name of the
SI-UBL version they are meant to test. There are a few tests in the
general/ directory that are for any version.

The filenames have the form SI-UBL-\<version\>-\<status\>-\<rule\>
where:
* version is the SI-UBL version this test tests
* status is whether the document should be ok, give a warning, or give
  an error
* rule the rule the document violates, or a description of the test if
  it does not violate any rules


For instance, the test file
    SI-UBL-2.0/SI-UBL-2.0_BR-NL-12_error.xml
is a test that violates BR-NL-12 from the validation artefacts within SI-UBL 2.0.
    SI-UBL-2.0/SI-UBL-2.0_ok_minimal.xml
is a minimal document that should validate under the rules of
SI-UBL 2.0.

If you find any faults in these documents, please contact
SimplerInvoicing.
