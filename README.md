# empty-front-end

An empty React/Typescript project that is meant to be used to kickstart new projects without spending too much time on all the initial configurations.

## Additional packages / tech choices

* Jest - Testing library used

* Prettier - Used to auto format code

* styled-components - CSS styling for component front end architecture

* Parcel - Used as a bundler instead of webpack. The primary reason is that it doesn't require any configuration and it is just as effective for simple projects. The idea is that if you wish to leverage webpack later on you can do so once the project grows to a significant size.

## Building and running on localhost

First install dependencies:

```sh
npm install
```

To run in hot module reloading mode:

```sh
npm start
```

To create a production build:

```sh
npm run build-prod
```

## Running

Go to localhost:1234 after running npm start

## Testing

To run unit tests:

```sh
npm test
```

## Credits

Used [createapp.dev](https://createapp.dev/) to configure build

