CHANGE LOG
==========


## V8.4 (26/04/2016)

* Added laravel 5.3 support


## V8.3.6 (27/03/2016)

* Fixed broken logging on lumen


## V8.3.5 (27/03/2016)

* Added missing import


## V8.3.4 (27/03/2016)

* Another fix for lumen


## V8.3.3 (27/03/2016)

* Fixed the lumen exception handler


## V8.3.2 (30/01/2016)

* Improved service provider
* Fixed some typos


## V8.3.1 (21/01/2016)

* Fixed with response exceptions


## V8.3 (21/01/2016)

* Deal with model not found exceptions


## V8.2 (15/01/2016)

* Support both whoops ^1.1 and ^2.0


## V8.1 (07/03/2016)

* Added a transformer for laravel's new auth exception


## V8.0 (05/03/2016)

* Pass through info to the user provided error views
* Fixed some typos including a protected property


## V7.0 (11/12/2015)

* Support exceptions with getResponse methods
* Modfied the filters to be passed the request


## V6.1 (09/12/2015)

* Support more client error codes


## V6.0 (22/11/2015)

* Made whoops optional


## V5.1 (14/11/2015)

* Added laravel 5.2 support
* Improved environment detection
* Improvements to id generation


## V5.0 (06/10/2015)

* Improved lumen support
* Updated interfaces so we can filter by code
* Added view displayer to mimic laravel


## V4.0 (25/07/2015)

* Associated uuids with exceptions
* Added default displayer config
* Resolve all the config earlier
* Made the html displayer responsive
* Added exception levels
* Allowed access to exceptions before transformation


## V3.2 (06/07/2015)

* Added exception transformers


## V3.1 (26/06/2015)

* Official lumen support
* Code cleanup


## V3.0.1 (01/06/2015)

* Make sure we're always creating an illuminate response


## V3.0 (28/05/2015)

* Drop support for laravel 5.0
* Improved the error info class
* Return empty body and no content type if we can't match a displayer
* Conformed to json api standards
* Use laravel's new accepts method


## V2.0.1 (26/05/2015)

* Fixed logger resolution in the exception handler


## V2.0 (21/05/2015)

* Support both laravel 5.0 and 5.1
* Removed dependence on views in the html displayer
* Replaced the info trait with an exception info class
* Made exception displayers really configurable
* Correctly deal with content types by default
* Renamed some displayer classes
* Displayer classes now return responses


## V1.0 (04/02/2015)

* Initial release
