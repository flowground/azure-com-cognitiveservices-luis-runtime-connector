# ![LOGO](logo.png) Language Understanding Intelligent Service (LUIS) Endpoint API for running predictions and extracting user intentions and entities from utterances. **flow**ground Connector

## Description

A generated **flow**ground connector for the Language Understanding Intelligent Service (LUIS) Endpoint API for running predictions and extracting user intentions and entities from utterances. API (version v2.0 preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/cognitiveservices-LUIS-Runtime/v2.0 preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:47+03:00

## API Description



## Authorization

Supported authorization schemes:
- API Key
## Actions

### Gets predictions for a given utterance, in the form of intents and entities. The current maximum query size is 500 characters.

#### Input Parameters
* `appId` - _required_ - The LUIS application ID (guid).
* `q` - _required_ - The utterance to predict.
* `timezoneOffset` - _optional_ - The timezone offset for the location of the request.
* `verbose` - _optional_ - If true, return all intents instead of just the top scoring intent.
* `staging` - _optional_ - Use the staging endpoint slot.
* `spellCheck` - _optional_ - Enable spell checking.
* `bing-spell-check-subscription-key` - _optional_ - The subscription key to use when enabling bing spell check
* `log` - _optional_ - Log query (default is true)

### Gets predictions for a given utterance, in the form of intents and entities. The current maximum query size is 500 characters.

#### Input Parameters
* `appId` - _required_ - The LUIS application ID (Guid).
* `timezoneOffset` - _optional_ - The timezone offset for the location of the request.
* `verbose` - _optional_ - If true, return all intents instead of just the top scoring intent.
* `staging` - _optional_ - Use the staging endpoint slot.
* `spellCheck` - _optional_ - Enable spell checking.
* `bing-spell-check-subscription-key` - _optional_ - The subscription key to use when enabling bing spell check
* `log` - _optional_ - Log query (default is true)

## License

**flow**ground :- Telekom iPaaS / azure-com-cognitiveservices-luis-runtime-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
