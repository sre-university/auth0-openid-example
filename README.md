# openid-examples: collection of examples for openid crate

By default all examples work with [Google OpenID Connect](https://developers.google.com/identity/protocols/oauth2/openid-connect).

You need to define two environment variables `CLIENT_ID` and `CLIENT_SECRET`.

If you want to try another OpenID provider - additionally define `ISSUER` environment variable.

## Legal

Dual-licensed under `MIT` or the [UNLICENSE](http://unlicense.org/).

## Examples

- [warp](examples/warp.rs)

```bash
export CLIENT_ID=<your google client id here>
export CLIENT_SECRET=<your google client secret>
cargo run --example=warp
```

