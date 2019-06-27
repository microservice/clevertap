# _CleverTap_ OMG Microservice

[![Open Microservice Guide](https://img.shields.io/badge/OMG%20Enabled-👍-green.svg?)](https://microservice.guide)

An OMG service to access the CleverTap event and profile APIs.

## Direct usage in [Storyscript](https://storyscript.io/):

##### Push
```coffee
clevertap push event: "Logged In" identity: "john"
clevertap push event: "Logged In" properties: {"Source": "Website"} identity: "john"
clevertap push profile: {"Fruit": "Mango"} identity: "john"
```

Curious to [learn more](https://docs.storyscript.io/)?

✨🍰✨

## Usage with [OMG CLI](https://www.npmjs.com/package/omg)

##### Push
```shell
$ omg run push -a event=<EVENT> -a properties=<MAP_OF_PROPERTIES> -a profile=<MAP_OF_PROFILE> -a identity=<IDENTITY> -e ACCOUNT_ID=<ACCOUNT_ID> -e ACCOUNT_PASSCODE=<ACCOUNT_PASSCODE>
```

**Note**: The OMG CLI requires [Docker](https://docs.docker.com/install/) to be installed.

## License
[MIT License](https://github.com/omg-services/clevertap/blob/master/LICENSE).



