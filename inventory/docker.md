
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

## 2026-08-29 18:54:57 UTC

## 2026-08-29 21:45:18 UTC

## 2026-08-29 23:40:21 UTC

## 2026-08-30 01:41:22 UTC

## 2026-08-30 07:26:44 UTC

## 2026-08-30 13:18:25 UTC

## 2026-08-30 17:48:07 UTC

## 2026-08-30 21:04:40 UTC

## 2026-08-30 23:30:18 UTC
- CHANGED NO_DELTA - status pattern stable: posit.cloud 200 text/html len 1823 for any app_id ; www.autotrader.com 200 text/html len 3762 for any vehicleId ; auth.docker.io 200 json + registry-1.docker.io 404 f

## 2026-08-31 01:39:38 UTC

## 2026-08-31 07:44:30 UTC

## 2026-08-31 15:28:26 UTC

## 2026-08-31 21:06:58 UTC

## 2026-09-01 00:38:57 UTC

## 2026-09-01 05:41:34 UTC

## 2026-09-01 10:28:41 UTC

## 2026-09-01 15:13:30 UTC

## 2026-09-01 18:30:39 UTC

## 2026-09-01 21:21:42 UTC

## 2026-09-01 23:35:28 UTC

## 2026-09-02 01:25:50 UTC

## 2026-09-02 06:27:14 UTC

## 2026-09-02 11:45:18 UTC

## 2026-09-02 15:20:32 UTC

## 2026-09-02 18:59:21 UTC

## 2026-09-02 21:50:03 UTC

## 2026-09-03 00:14:41 UTC

## 2026-09-03 04:23:13 UTC

## 2026-09-03 09:13:03 UTC

## 2026-09-03 13:35:41 UTC

## 2026-09-03 17:15:09 UTC
- NEW NO_DELTA — inventory stable vs 2026-09-03 probes; live hosts repeat (auth.docker.io 200 json, registry-1.docker.io 404, posit.cloud 1823 html, autotrader 3762 html) no new host/param observed this cyc

## 2026-09-03 19:52:02 UTC

## 2026-09-03 22:34:55 UTC

## 2026-09-04 00:31:53 UTC

## 2026-09-04 05:08:31 UTC

## 2026-09-04 09:37:47 UTC
- NEW NO_DELTA — inventory vs 2026-09-04 05:08 probes shows same HTML fallback 1823/3762 vs 404 pattern, no new hosts beyond wildcard *.docker.com/*.docker.io already in probe_allow

## 2026-09-04 13:48:26 UTC

## 2026-09-04 17:37:24 UTC

## 2026-09-04 19:52:43 UTC

## 2026-09-04 22:23:27 UTC
