# clarofixes
Drupal 9+ CSS injection, to bring the Claro admin Theme from "Mobile Only" to "Also usable on desktop"

## Installation

Add this to the `composer.json` of your project:
```json
{
  // ...
  
  "repositories": {
    
    
    "clarofixes": {
      "type": "git",
      "url": "https://github.com/flowconcept/clarofixes.git"
    },
    
    "drupal": {
      "type": "composer",
      "url": "https://packages.drupal.org/8"
    },
    // ...
  }
}
```

And then:

```
composer require flowconcept/clarofixes && drush en clarofixes 
```
