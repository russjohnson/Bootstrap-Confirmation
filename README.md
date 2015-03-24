# Bootstrap-Confirmation

[![Bower version](https://badge.fury.io/bo/bootstrap-confirmation2.svg)](http://badge.fury.io/bo/bootstrap-confirmation2)

Bootstrap plugin for on-place confirm boxes using Popover.

## UPDATE

Other forks of this plugin did not support RESTful routes due to not having support for adding data-method to the confirmation buttons. This fork supports Rails RESTful routes by adding the data-method attribute to the confirmation button if the data-method attribute is included on the original link.


## Documentation

http://mistic100.github.io/Bootstrap-Confirmation


## Changes from original one

- Now supports Rails RESTful routes
- Bootstrap 3 compatible
- Fix double event fires
- Automatic handle of links (without need of custom callback)
