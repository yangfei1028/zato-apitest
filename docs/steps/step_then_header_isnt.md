
Then header "{header}" isn't "{value}"
=============================================================================================================

Usage example
-------------

```
Feature: zato-apitest docs

Scenario: Then header "{header}" isn't "{value}"

    Given address "http://apitest-demo.zato.io"
    Given URL path "/demo/json"

    When the URL is invoked

    Then header "Content-Type" isn't "text/csv"
```

Discussion
----------

(None)