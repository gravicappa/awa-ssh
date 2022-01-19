## v0.1.0 (2022-01-19)

* mirage: add server implementation, and ssh subsystem (#35, @palainp)
* client: accept channel extended data (stderr) (@art-w, #43)
* cram test for awa_gen_key and what a user provides (@dinosaure, #44)

## v0.0.5 (2021-12-14)

* use `eqaf` and hash to test the password (@dinosaure, @hannesm, #41)
* fix isomorphism between `of_seed`/`of_string` and `awa_gen_key` tool (@dinosaure, @hannesm, #40)
* provide `Keys.of_string` (@dinosaure, @hannesm, #37)
* conflict `awa` with `result < 1.5` (@hannesm, 1c3d2eb)

## v0.0.4 (2021-10-28)

* support rsa-sha2 and ed25519 in server code (#29 #30 @palainp)
* awa_test_client: add --key argument (#28 @hannesm, suggested in #27 by
  @dgjustice @palainp)
* Avoid deprecated Cstruct.len, avoid astring (@hannesm)
* Drop rresult dependency (#34 @hannesm)

## v0.0.3 (2021-04-22)

* Adapt to mirage-crypto-ec 0.10.0 API changes (#26 @hannesm)

## v0.0.2 (2021-04-14)

* Use mirage-crypto-ec instead of hack_x25519 (#24 @hannesm)
* Support X.509 >= 0.12.0 (#24 @hannesm)

## v0.0.1 (2021-01-07)

* Initial public release
