# haskell-reflex-example

**An example client-side web application written in Haskell using the Functional Reactive Programming (FRP) Reflex framework**

## Requirements

* Docker (Engine and Compose)

## Setup

```
./bin/make
```

## Development

After the frontend container is created, the `try-reflex` command is run, which takes a few minutes to finish. You can watch the docker logs to see when it finishes. Head to `localhost:8000` when it's done.

To play with relfex-frp, edit the `hello.hs` file in the `src/frontend` directory.

Questions or comments? Head over to [https://www.civiclabs.com](https://www.civiclabs.com) to get in touch with us. Original inspiration taken from [here](https://github.com/gelisam/frp-zoo/tree/master/reflex-example).
