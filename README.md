An api is only as good as its documentation. An untestable api documentation is
only as good as untestable code.

[Apiblueprint](https://apiblueprint.org/) provides a stanrdised format for writing API docs.
This formar is easyto write, but at the same time easy for machines to parse.

Being a machine parsable format, it is possible to assert that your API behaves as documented.

### Goals

Given an APIblueprint compatible document , generate [Django rest framework](http://www.django-rest-framework.org/) stubs and tests.

### Design

Apiblueprint -> transformed AST -> DRF stubs + tests

