# ![LOGO](logo.png) Greenwire Public **flow**ground Connector

## Description

A generated **flow**ground connector for the Greenwire Public API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/greenpeace.org/1.0.0/swagger.json<br/>
Generated at: 2019-06-06T16:12:23+03:00

## API Description

Greenpeace Greenwire allows you connect with other volunteers, activists and groups working on environmental campaigns all across the world!

## Authorization

This API does not require authorization.

## Actions

### Return the upcoming events (e.g. start date >= today). Gets an array of `Event` object. Mandatory query param of **domain** determines the site / country the event belongs to.

#### Input Parameters
* `domain` - _required_ - the site the groups belongs to, example: netherlands
* `limit` - _optional_ - the number of desired records

### Get one `Event` object by specifying its UUID in the url path.

#### Input Parameters
* `UUID` - _required_

### Gets an array of `Group` object. Mandatory query param of **domain** determines the site / country the group belongs to.

#### Input Parameters
* `domain` - _required_ - the site the groups belongs to, example: netherlands
* `limit` - _optional_ - the number of desired records

### Get one `Group` object by specifying its UUID in the url path.

#### Input Parameters
* `UUID` - _required_

### Gets an array of `Volunteer` object. Mandatory query param of **domain** determines the site / country the volunteers are from.

#### Input Parameters
* `domain` - _required_ - the site the users are registered on, example: netherlands
* `limit` - _optional_ - the number of desired records. Default is 5.
* `must_have_default_avatar` - _optional_ - 1 or 0. filter on people that have the default avatar or not.

### Get one specific `Volunteer` object by specifying its UUID in the url path.

#### Input Parameters
* `UUID` - _required_

## License

**flow**ground :- Telekom iPaaS / greenpeace-org-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
