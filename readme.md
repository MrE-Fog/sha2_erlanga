#sha2_erlang

Erlang NIF wrappers for OpenSSL's SHA224, SHA256, SHA384 and SHA512 digest and HMAC functions. On pre-R14 systems or where the NIF is otherwise unavailable functions fallback to standard Erlang implementations. [Stephen B. Vinoski](http://steve.vinoski.net/)'s BSD licensed [sha2 implementation](http://steve.vinoski.net/code/sha2.erl) is bundled (as sha2_erl.erl) to faciliate this.

Prerequisites:

- Erlang/OTP R14
- OpenSSL
