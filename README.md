# openlibrary

Unsplash access key is set in Pantheon secrets


```
 ------ -----------------------------------------------------------------------------------------------------------------------------------------
  Line   openlibrary/openlibrary.module
 ------ -----------------------------------------------------------------------------------------------------------------------------------------
  99     Function secrets not found.
         💡 Learn more at https://phpstan.org/user-guide/discovering-symbols
  132    Relying on entity queries to check access by default is deprecated in drupal:9.2.0 and an error will be thrown from drupal:10.0.0. Call
         \Drupal\Core\Entity\Query\QueryInterface::accessCheck() with TRUE or FALSE to specify whether access should be checked.
         💡 See https://www.drupal.org/node/3201242
 ------ -----------------------------------------------------------------------------------------------------------------------------------------
 ```