# ![LOGO](logo.png) Times Newswire **flow**ground Connector

## Description

A generated **flow**ground connector for the Times Newswire API (version 3.0.0).

Generated from: https://api.apis.guru/v2/specs/nytimes.com/timeswire/3.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:21+03:00

## API Description

With the Times Newswire API, you can get links and metadata for Times articles and blog posts as soon as they are published on NYTimes.com. The Times Newswire API provides an up-to-the-minute stream of published items.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### get_content_json

#### Input Parameters
* `url` - _required_ - The complete URL of a specific news item, URL-encoded or backslash-escaped

### get_content__source___section__json

#### Input Parameters
* `source` - _required_ - Limits the set of items by originating source

all = items from both The New York Times and The International New York Times
nyt = New York Times items only
iht = International New York Times items only

    Possible values: all, nyt, iht.
* `section` - _required_ - Limits the set of items by one or more sections
all | One or more section names, separated by semicolons

 To get all sections, specify all. To get a particular section or sections, use the section names returned by this request:
 http://api.nytimes.com/svc/news/v3/content/section-list.json

* `limit` - _optional_ - Limits the number of results, between 1 and 20
* `offset` - _optional_ - Sets the starting point of the result set

### get_content__source___section___time_period__json

#### Input Parameters
* `source` - _required_ - Limits the set of items by originating source

all = items from both The New York Times and The International New York Times
nyt = New York Times items only
iht = International New York Times items only

    Possible values: all, nyt, iht.
* `section` - _required_ - Limits the set of items by one or more sections
all | One or more section names, separated by semicolons

 To get all sections, specify all. To get a particular section or sections, use the section names returned by this request:
 http://api.nytimes.com/svc/news/v3/content/section-list.json

* `time-period` - _required_ - Limits the set of items by time published, integer in number of hours
* `limit` - _optional_ - Limits the number of results, between 1 and 20
* `offset` - _optional_ - Sets the starting point of the result set

## License

**flow**ground :- Telekom iPaaS / nytimes-com-timeswire-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
