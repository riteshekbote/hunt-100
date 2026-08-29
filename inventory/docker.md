
## 2026-08-27 07:20:16 UTC

## 2026-08-27 07:41:02 UTC

## 2026-08-27 14:17:52 UTC

## 2026-08-27 15:20:06 UTC

## 2026-08-27 15:34:11 UTC

## 2026-08-28 00:39:55 UTC

## 2026-08-28 12:14:58 UTC
- NEW hub.docker.com/v2/repositories/library/hello-world/tags?page_size=5 -> 200 application/json (public tag listing anon)
- NEW hub.docker.com/v2/repositories/<private-namespace>/<private-repo>/tags -> 400 (diff from public 200, not 401/404)

## 2026-08-28 22:20:39 UTC

## 2026-08-29 03:54:31 UTC
- NEW hub.docker.com/v2/repositories/library/hello-world/tags?page_size=5 -> 200 application/json (public anon tag listing)
- NEW registry-1.docker.io/v2/ -> 401 (auth required, registry alive)
- NEW auth.docker.io/token?service=registry.docker.io&scope=repository:library/hello-world:pull -> 200 (token endpoint alive)

## 2026-08-29 11:04:35 UTC
- NEW auth.docker.io/token scope=repository:<victim-ns>/<private-repo>:pull -> 200 2026-08-29 vs prior 401 expectation for private scope
- NEW registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> 404 vs base registry-1.docker.io/v2/ -> 401 (differential oracle)
- NEW hub.docker.com/v2/repositories/<owned-private-ns>/<private-repo>/tags and <victim-ns>/guessed -> both 400 (no 404 differentiation, potential IDOR oracle suppressed)

## 2026-08-29 15:39:19 UTC
