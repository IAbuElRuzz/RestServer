# RestServer.php
[![Stories in Ready](https://badge.waffle.io/jk/restserver.png?label=ready&title=Ready)](http://waffle.io/jk/restserver)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/jk/RestServer/badges/quality-score.png?s=f73d03bf31d39ae6d8e6717e59fb37ee9f070a2e)](https://scrutinizer-ci.com/g/jk/RestServer/)
[![Code Coverage](https://scrutinizer-ci.com/g/jk/RestServer/badges/coverage.png?s=04bcecf088febc189f3e7f876802def3bd7a5e16)](https://scrutinizer-ci.com/g/jk/RestServer/)
[![Latest Stable Version](https://poser.pugx.org/jk/restserver/v/stable.svg)](https://packagist.org/packages/jk/restserver)
[![License](https://poser.pugx.org/jk/restserver/license.svg)](https://packagist.org/packages/jk/restserver)
[![Total Downloads](https://poser.pugx.org/jk/restserver/downloads.svg)](https://packagist.org/packages/jk/restserver)
[![Latest Unstable Version](https://poser.pugx.org/jk/restserver/v/unstable.svg)](https://packagist.org/packages/jk/restserver)
[![Dependency Status](https://www.versioneye.com/php/jk:restserver/badge.svg)](https://www.versioneye.com/php/jk:restserver/)

| Master branch | Develop branch |
| :---: | :---: |
[![Master Build Status](https://travis-ci.org/jk/RestServer.svg?branch=master)](https://travis-ci.org/jk/RestServer)|[![Develop Build Status](https://travis-ci.org/jk/RestServer.svg?branch=develop)](https://travis-ci.org/jk/RestServer)

A PHP REST server for providing a very light-weight REST API. Very easy to set up and get going. Independent from other libraries and frameworks. Supports HTTP authentication. Supports AMF data if the Zend Framework is present for Flash clients.

As of [Classification of HTTP-based APIs](http://www.nordsc.com/ext/classification_of_http_based_apis.html) this implementation should be considered as an HTTP based type II type of an API. So it is not an academic version of a real RESTful API, but this is by intention, so it's easy to understand and install.