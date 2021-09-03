# Compliance Check
Various tests for standards compliance in Lando Drupal projects.

## Prerequisites
- lando: See https://docs.lando.dev/basics/installation.html.
- composer: See https://getcomposer.org/download/.
- cgr: See https://github.com/consolidation/cgr.
- drush: See https://www.drush.org/latest/install/.

_Note: These prerequisites are only necessary if you plan on running from your host and not in your project container._

## Installation
```bash
$ git clone https://github.com/uberhacker/compliance-check.git
$ cd compliance-check
$ sudo cp compliance-check /usr/local/bin
$ cp .lando.local.yml /path/to/drupal/project/root
```
_Note: The last step is only needed if you plan on running in your project container and not on the host._
_If you already have it your project, you may want to edit .lando.local.yml manually for the additional lines._
_See https://docs.lando.dev/config/lando.html#override-file for more information._

## Usage
```bash
$ cd /path/to/drupal/project/root
$ compliance-check
```
