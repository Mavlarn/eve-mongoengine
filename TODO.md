* support DynamicField (there is one test for this, but definetely not enough)
* pagination tests
* save() and update() hooks on mongoengine classes: auto-generate etag and
  value of 'updated' field when performing actions on mongoengine side.
* Documentation: advanced usage, extending and hacking
* Test for subresources: PUT, PATCH, DELETE. Should be working, but tests missing.
* Media operations are not tested
