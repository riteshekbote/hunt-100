
## RANKED HYPOTHESES 2026-08-27 05:06:25 UTC
- (no NEW hypotheses this cycle — all deduped)

## RANKED HYPOTHESES 2026-08-27 07:20:16 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): SCAN: Passive CT + light probe to populate inventory — 1) crt.sh/CT for duocircle.com, *.docker.com, *.docker.io, posit.cloud, shinyapps.io, autotrader.com 2) r
- LEARN: NONE — no class proven dead/alive this cycle (no passive evidence). Retain prior REJECTED list empty.

## RANKED HYPOTHESES 2026-08-27 07:41:02 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): SCAN: Passive CT + light probe to populate inventory — 1) crt.sh/CT for duocircle.com, *.docker.com, *.docker.io, posit.cloud, shinyapps.io, autotrader.com, kbb
- LEARN: NONE — no class proven dead/alive this cycle (no passive evidence). Retain prior REJECTED list empty.

## RANKED HYPOTHESES 2026-08-27 14:17:52 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): SCAN: Passive CT + light probe to populate inventory — 1) crt.sh/CT for duocircle.com, *.docker.com, *.docker.io, posit.cloud, shinyapps.io, autotrader.com, kbb
- LEARN: NONE — no class proven dead/alive this cycle (no passive evidence). Retain prior REJECTED list empty.

## RANKED HYPOTHESES 2026-08-27 15:20:06 UTC
- (no NEW hypotheses this cycle — all deduped)
- LEARN: NONE — no class proven dead/alive this cycle (no status/param evidence)

## RANKED HYPOTHESES 2026-08-27 15:34:11 UTC
- (no NEW hypotheses this cycle — all deduped)
- LEARN: NONE — no class proven dead/alive this cycle (no status/param evidence) @ inventory

## RANKED HYPOTHESES 2026-08-28 00:39:55 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://hub.docker.com/v2/ — list catalog endpoint + GET https://hub.docker.com/v2/repositories/library/docker/tags?page_size=5 (anon, Accept: applic
- LEARN: NONE — no class proven dead/alive this cycle (no status/param evidence yet). Retain prior REJECTED list empty.

## RANKED HYPOTHESES 2026-08-28 12:14:58 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://hub.docker.com/v2/repositories/library/hello-world/tags?page_size=5 -H "Accept: application/json" ; GET https://hub.docker.com/v2/repositorie
- LEARN: NONE — no class proven dead/alive this cycle (delta is status-code anomaly only, need token-gated probe to confirm). Retain prior REJECTED list empty.

## RANKED HYPOTHESES 2026-08-28 22:20:39 UTC
- (no NEW hypotheses this cycle — all deduped)
- LEARN: NONE - no class proven dead/alive this cycle (status deltas only, need token-gated 200 vs 401 confirmation) Retain prior REJECTED list empty

## RANKED HYPOTHESES 2026-08-29 03:54:31 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://hub.docker.com/v2/repositories/<owned-private-namespace>/<private-repo>/tags -H "Accept: application/json" anon then with Authorization: Bear
- LEARN: NONE — no class proven dead/alive this cycle (status deltas only, need token-gated 200 vs 401 confirmation) Retain prior REJECTED list empty

## RANKED HYPOTHESES 2026-08-29 11:04:35 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-private-ns>/<private-repo>:pull anon then GET https://registry-1.dock
- LEARN: NONE — no class proven dead/alive this cycle (status deltas only, need token-gated 200 vs 401 confirmation) Retain prior REJECTED list empty

## RANKED HYPOTHESES 2026-08-29 15:39:19 UTC
- (no NEW hypotheses this cycle — all deduped)
- LEARN: NONE — no class proven dead/alive this cycle (status deltas only, need token-gated 200 vs 401 confirmation) Retain prior REJECTED list empty

## RANKED HYPOTHESES 2026-08-29 18:54:57 UTC
- [78] *.docker.com: posit-connect-cloud-api-bola (from reports/hypotheses-lead_muse-spark.txt.txt)
- [78] *.docker.com: coxautomotive-autotrader-bola-vehicleId (from reports/hypotheses-lead_muse-spark.txt.txt)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull then GET https://registry-1.docker.io/v2/<vi
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401 confirmation still needed) Retain prior REJECTED list empty

## RANKED HYPOTHESES 2026-08-29 21:45:18 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-private-ns>/<private-repo>:pull -H "Authorization: Bearer <owned-jwt>
- LEARN: NONE — no class proven dead/alive this cycle (status 200 vs 401 deltas only, token-gated 200 vs 401 confirmation still needed) Retain prior REJECTED list empty

## RANKED HYPOTHESES 2026-08-29 23:40:21 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-private-ns>/<private-repo>:pull H: Accept: application/json with owne
- LEARN: NONE — no class proven dead/alive this cycle (status 200 vs 401/404 deltas only, need token-gated 200 vs 401 confirmation) Retain prior REJECTED list empty

## RANKED HYPOTHESES 2026-08-30 01:41:22 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-private-ns>/<private-repo>:pull -H "Authorization: Bearer <owned-jwt>
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401 confirmation still needed) Retain prior REJECTED list empty

## RANKED HYPOTHESES 2026-08-30 07:26:44 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-private-ns>/<private-repo>:pull -H "Authorization: Bearer <owned-jwt>
- LEARN: NONE — no class proven dead/alive this cycle (status 200 vs 401/404 deltas only, token-gated 200 vs 401 confirmation still needed) Retain prior REJECTED list em

## RANKED HYPOTHESES 2026-08-30 13:18:25 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Authorization: Bearer <owned-JWT>" -H "A
- LEARN: NONE — no class proven dead/alive this cycle (status 200 vs 401/404 deltas only, token-gated 200 vs 401 confirmation still needed) Retain prior REJECTED list em

## RANKED HYPOTHESES 2026-08-30 17:48:07 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Authorization: Bearer <owned-JWT>" -H "A
- LEARN: NONE — no class proven dead/alive this cycle (status 200 html vs 404 deltas only, token-gated 200 vs 401/403 confirmation still needed) Retain prior REJECTED li

## RANKED HYPOTHESES 2026-08-30 21:04:40 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Authorization: Bearer <owned-JWT>" -H "A
- LEARN: NONE — no class proven dead/alive this cycle (status 200 html vs 404 deltas only, token-gated 200 vs 401/403 confirmation still needed) Retain prior REJECTED li

## RANKED HYPOTHESES 2026-08-30 23:30:18 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Authorization: Bearer <owned-JWT>" -H "A
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/404 deltas only, need JWT-authenticated JSON differentiation to confirm BOLA) Retain prior 

## RANKED HYPOTHESES 2026-08-31 01:39:38 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://posit.cloud/api/v1/applications?app_id=<owned-id> -H "Accept: application/json" -H "Authorization: Bearer <owned-jwt>" and GET https://posit.
- LEARN: NONE — no class proven dead/alive this cycle (status 200 html vs 404 deltas only, need JWT-authenticated JSON differentiation to confirm BOLA) Retain prior REJE

## RANKED HYPOTHESES 2026-08-31 07:44:30 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Accept: application/json" -H "Authorizat
- LEARN: NONE — no class proven dead/alive this cycle (status 200 html vs 404 deltas only, need JWT-authenticated JSON differentiation to confirm BOLA) Retain prior REJE

## RANKED HYPOTHESES 2026-08-31 15:28:26 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -H "Accept: application/vnd.docker.distribution.manifest.v2+json" -H "Aut
- LEARN: NONE — no class proven dead/alive this cycle (status 200 html vs 404 deltas only, need JWT-authenticated JSON differentiation to confirm BOLA) Retain prior REJE

## RANKED HYPOTHESES 2026-08-31 21:06:58 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -H "Accept: application/vnd.docker.distribution.manifest.v2+json" -H "Aut
- LEARN: NONE — no class proven dead/alive this cycle (status 200 html vs 404 deltas only, need JWT-authenticated JSON differentiation to confirm BOLA) Retain prior REJE

## RANKED HYPOTHESES 2026-09-01 00:38:57 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Accept: application/json" -H "Authorizat
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed for BOLA/IDOR; HTML fallback vs JSON ambiguity remain

## RANKED HYPOTHESES 2026-09-01 05:41:34 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -H "Accept: application/vnd.docker.distribution.manifest.v2+json" -H "Aut
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed for BOLA/IDOR; HTML fallback vs JSON ambiguity remain

## RANKED HYPOTHESES 2026-09-01 10:28:41 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -H "Accept: application/vnd.docker.distribution.manifest.v2+json" -H "Aut
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed for BOLA/IDOR; HTML fallback vs JSON ambiguity remain

## RANKED HYPOTHESES 2026-09-01 15:13:30 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -H "Accept: application/vnd.docker.distribution.manifest.v2+json" -H "Aut
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed for BOLA/IDOR; HTML fallback vs JSON ambiguity remain

## RANKED HYPOTHESES 2026-09-01 18:30:39 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Accept: application/json" -H "Authorizat
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed for BOLA/IDOR; HTML fallback vs JSON ambiguity remain

## RANKED HYPOTHESES 2026-09-01 21:21:42 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: POST https://hub.docker.com/v2/users/login -H "Content-Type: application/json" -d '{"username":"invalid_test_user_123","password":"invalid_test_123"}' th
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed for BOLA/IDOR; HTML fallback vs JSON ambiguity remain

## RANKED HYPOTHESES 2026-09-01 23:35:28 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Accept: application/json" -H "Authorizat
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed for BOLA/IDOR; HTML fallback vs JSON ambiguity remain

## RANKED HYPOTHESES 2026-09-02 01:25:50 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Accept: application/json" -H "Authorizat
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation to confirm BOLA/IDOR; HTML fallback vs 404 ambigu

## RANKED HYPOTHESES 2026-09-02 06:27:14 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Accept: application/json" -H "Authorization: Bearer <JWT-from-auth.docker.io
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation to confirm BOLA/IDOR; HTML fallback vs 404 ambigu

## RANKED HYPOTHESES 2026-09-02 11:45:18 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Accept: application/json" -H "Authorization: Bearer <JWT-from-GET-https://au
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation to confirm BOLA/IDOR; HTML fallback vs 404 ambigu

## RANKED HYPOTHESES 2026-09-02 15:20:32 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Accept: application/json" -H "Authorization: Bearer <JWT-from-GET-https://au
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation to confirm BOLA/IDOR; HTML fallback vs 404 ambigu

## RANKED HYPOTHESES 2026-09-02 18:59:21 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://posit.cloud/__api__/v1/content/<owned-guid> -H "Accept: application/json" -H "Authorization: Bearer <owned-JWT>" vs GET https://posit.cloud/_
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation to confirm BOLA/IDOR; HTML fallback 1823/3762 vs 

## RANKED HYPOTHESES 2026-09-02 21:50:03 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull Authorization: Bearer <owned-JWT-from-hub.do
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation to confirm BOLA/IDOR; HTML fallback 1823/3762 vs 

## RANKED HYPOTHESES 2026-09-03 00:14:41 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Accept: application/json" -H "Authorization: Bearer <JWT-from-GET https://au
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed for BOLA/IDOR; HTML fallback 1823/3762 vs 404 ambigui

## RANKED HYPOTHESES 2026-09-03 04:23:13 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Accept: application/json" -H "Authorization: Bearer <JWT-from-GET-https://au
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed; current evidence is HTML fallback 1823/3762 vs 404 i

## RANKED HYPOTHESES 2026-09-03 09:13:03 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Accept: application/json" -H "Authorization: Bearer <JWT-from-GET https://au
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed for BOLA/IDOR; current evidence is HTML fallback 1823

## RANKED HYPOTHESES 2026-09-03 13:35:41 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Authorization: Bearer <hub-JWT-owned>" t
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed; current HTML fallback 1823/3762 vs 404 identical for

## RANKED HYPOTHESES 2026-09-03 17:15:09 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Authorization: Bearer <hub-JWT-owned>" t
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed; HTML fallback 1823/3762 vs 404 identical for owned/v

## RANKED HYPOTHESES 2026-09-03 19:52:02 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Authorization: Bearer <hub-JWT-owned-fro
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed for BOLA/IDOR; current evidence HTML fallback 1823/37

## RANKED HYPOTHESES 2026-09-03 22:34:55 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Authorization: Bearer <hub-JWT-owned-fro
- LEARN: NONE — no class proven dead/alive this cycle (token-gated 200 vs 401/403 JSON differentiation still needed for BOLA/IDOR; HTML fallback 1823/3762 vs 404 identic

## RANKED HYPOTHESES 2026-09-04 00:31:53 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull H:Authorization: Bearer <JWT-from-POST-hub.d
- LEARN: NONE — no class proven dead/alive this cycle (need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current HTML fallback 1823/3762 vs 404 i

## RANKED HYPOTHESES 2026-09-04 05:08:31 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -H "Authorization: Bearer <JWT-from-POST-htt
- LEARN: NONE — no class proven dead/alive this cycle (need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 1823/3762

## RANKED HYPOTHESES 2026-09-04 09:37:47 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Accept: application/vnd.docker.distribution.manifest.v2+json" -H "Authorizat
- LEARN: NONE — no class proven dead/alive this cycle (need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 1823/3762

## RANKED HYPOTHESES 2026-09-04 13:48:26 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Accept: application/vnd.docker.distribution.manifest.v2+json" -H "Authorizat
- LEARN: NONE — no class proven dead/alive this cycle (need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 1823/3762

## RANKED HYPOTHESES 2026-09-04 17:37:24 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Accept: application/vnd.docker.distribution.manifest.v2+json" -H "Authorizat
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-04 19:52:43 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: POST https://hub.docker.com/v2/users/login -H "Content-Type: application/json" -d '{"username":"<owned-user>","password":"<owned-pass>"}' -> extract toke
- LEARN: NONE — no class proven dead/alive this cycle (need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current HTML fallback 1823/3762 vs 404 i

## RANKED HYPOTHESES 2026-09-04 22:23:27 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: POST https://hub.docker.com/v2/users/login -H "Content-Type: application/json" -d '{"username":"<owned-user>","password":"<owned-pass>"}' -> extract toke
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; HTML fallback 1823/3762 vs 404 ide

## RANKED HYPOTHESES 2026-09-05 00:25:47 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: POST https://hub.docker.com/v2/users/login -H "Content-Type: application/json" -d '{"username":"<owned-user>","password":"<owned-pass>"}' -> extract JWT;
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-05 04:58:14 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: POST https://hub.docker.com/v2/users/login -H "Content-Type: application/json" -d '{"username":"<owned-user>","password":"<owned-pass>"}' -> extract JWT;
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-05 09:03:42 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: POST https://hub.docker.com/v2/users/login -H "Content-Type: application/json" -d '{"username":"<owned-user>","password":"<owned-pass>"}' -> extract toke
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current HTML fallback 1823/3762 vs

## RANKED HYPOTHESES 2026-09-05 12:42:42 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: POST https://hub.docker.com/v2/users/login -H "Content-Type: application/json" -d '{"username":"<owned-user>","password":"<owned-pass>"}' -> extract toke
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-05 15:34:53 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<owned-private>:pull -u "<owned-user>:<owned-pass>" -H "Accept: a
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current HTML fallback 1823/3762 vs

## RANKED HYPOTHESES 2026-09-05 17:40:09 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -u <owned-user>:<owned-pass> -H Accept:appli
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; HTML fallback 1823/3762 vs 404 ide

## RANKED HYPOTHESES 2026-09-05 19:31:30 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -u "<owned-user>:<owned-pass>" -H "Accept: a
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-05 21:46:30 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -u "<owned-user>:<owned-pass>" -H "Accept: a
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-05 23:20:57 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -u "<owned-user>:<owned-pass>" -H "Accept: a
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-06 01:21:47 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<owned-private>:pull -u "<owned-user>:<owned-pass>" -H "Accept: a
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-06 06:32:25 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -u "<owned-user>:<owned-pass>" -H "Accept: a
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-06 11:23:38 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -u "<owned-user>:<owned-pass>" -H "Accept: a
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA; HTML fallback 1823/3762 vs 404/401 iden

## RANKED HYPOTHESES 2026-09-06 14:27:00 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -u "<owned-user>:<owned-pass>" -H "Accept: a
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current HTML fallback 1823/3762 vs

## RANKED HYPOTHESES 2026-09-06 17:22:45 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -u "<owned-user>:<owned-pass>" -H "Accept: a
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current HTML fallback 1823/3762 vs

## RANKED HYPOTHESES 2026-09-06 19:32:52 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Authorization: Bearer <owned-JWT-from-auth.docker.io-victim-scope>" -H "Acce
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-06 21:45:26 UTC
- [73] hub.docker.com: Posit Cloud Content IDOR via GUID enumeration (from reports/hypotheses-lead_muse-spark.txt.txt)
- [73] hub.docker.com: Docker Registry BOLA via token scope confusion (from reports/hypotheses-lead_muse-spark.txt.txt)
- [73] hub.docker.com: CoxAutomotive Vinsolutions Lead IDOR via user_id (from reports/hypotheses-lead_muse-spark.txt.txt)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Authorization: Bearer <owned-JWT-from-auth.docker.io?victim-scope>" -H "Acce
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; HTML fallback 1823/3762 vs 404/401

## RANKED HYPOTHESES 2026-09-06 23:12:32 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Authorization: Bearer <owned-JWT-from-auth.docker.io?service=registry.docker
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-07 01:02:54 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Authorization: Bearer <JWT-from-auth.docker.io?service=registry.docker.io&sc
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-07 06:06:26 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <JWT-from-auth.docker.io?service=registry.docker.io&scop
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-07 12:27:24 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -H "Authorization: Bearer <JWT-from-GET-https://auth.docker.io/token?service=reg
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-07 17:57:15 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <JWT-from-GET-https://auth.docker.io/token?service=regis
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-07 21:31:56 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <JWT-from-GET-https://auth.docker.io/token?service=regis
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current HTML fallback 1823/3760 vs

## RANKED HYPOTHESES 2026-09-07 23:47:43 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <JWT-from-GET-https://auth.docker.io/token?service=regis
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current HTML 1823/3760 vs 401/404/

## RANKED HYPOTHESES 2026-09-08 01:29:15 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull with attacker Authorization (or anonymous if n
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-08 06:34:55 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-base64>" th
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; HTML fallback 1823 vs 401/404/596 

## RANKED HYPOTHESES 2026-09-08 11:47:39 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-base64>" th
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; HTML fallback 1823 vs 401/404/596 

## RANKED HYPOTHESES 2026-09-08 15:22:37 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-base64>" th
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; HTML fallback 1823 vs 401/404/596 

## RANKED HYPOTHESES 2026-09-08 19:00:38 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-base64>" th
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-08 21:52:24 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-base64>" th
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-09 00:14:57 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-base64>" -H
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML 1823 vs 401/

## RANKED HYPOTHESES 2026-09-09 04:41:32 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-base64>" -H
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML 1823 vs 401/

## RANKED HYPOTHESES 2026-09-09 09:14:08 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-base64>" -H
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML 1823 vs 401/

## RANKED HYPOTHESES 2026-09-09 13:44:57 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -H "A
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; HTML fallback 1823 vs 596/401 iden

## RANKED HYPOTHESES 2026-09-09 17:20:45 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -H "A
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; HTML fallback 1823 vs 596/401 iden

## RANKED HYPOTHESES 2026-09-09 20:03:41 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -> ex
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; HTML fallback 1823 vs 596/401 iden

## RANKED HYPOTHESES 2026-09-09 22:34:34 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -> ca
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML 1823 identic

## RANKED HYPOTHESES 2026-09-10 00:37:35 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -H "A
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence HTML fallback 182

## RANKED HYPOTHESES 2026-09-10 05:18:41 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-attacker-Ba
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-10 10:03:39 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-attacker-Ba
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-10 14:27:03 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-attacker-Ba
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-10 17:54:58 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-attacker-Ba
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-10 20:52:25 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-token-service-registry.docker
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; HTML 1823 vs 596/404 identical own

## RANKED HYPOTHESES 2026-09-10 23:11:31 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-attacker-Ba
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-11 01:05:41 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-attacker-Ba
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-11 05:59:21 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -> de
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-11 11:19:01 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -> de
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-11 15:13:16 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -> de
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-11 18:32:52 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -> de
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-11 21:19:31 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Header Authorization: Basic <attacker-b64> -> 
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-11 23:33:13 UTC
- [74] registry-1.docker.io: Posit Cloud Content API IDOR — GUID enumeration returns identical 1823 html fallback (from reports/hypotheses-lead_muse-spark.txt.txt)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -> ca
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-12 01:34:57 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -> ca
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-12 06:31:47 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-attacker-Ba
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-12 11:17:04 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-attacker-Ba
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-12 14:11:36 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-attacker-Ba
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-12 17:09:49 UTC
- (no NEW hypotheses this cycle — all deduped)
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-12 19:19:56 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-attacker-Ba
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-12 21:41:55 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Authorization: Basic <attacker-b64> Accept: ap
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-12 23:23:07 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-attacker-Ba
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-13 01:26:31 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:owned-ns/owned-private:pull -H "Authorization: Basic <attacker-b64>" -H "Acc
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-13 06:48:41 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-attacker-Ba
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-13 12:45:34 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -H "A
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current evidence auth.docker.io 20

## RANKED HYPOTHESES 2026-09-13 16:40:41 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/manifests/latest -H "Authorization: Bearer <token-from-auth.docker.io-victim-scope-with-atta
- LEARN: NONE — no class proven dead/alive this cycle (still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA/IDOR; current HTML 1823 vs 401/404/596 i

## RANKED HYPOTHESES 2026-09-13 19:01:23 UTC
- [75] registry-1.docker.io: Posit Cloud IDOR via __api__ content JSON vs HTML fallback (from reports/hypotheses-lead_muse-spark.txt.txt)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -H "A
- LEARN: NONE @ registry-1.docker.io: still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA; HTML fallback 1823 vs 596/401 identical owned/victim rem
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for BOLA/IDOR; HTML 1823 identical owned/victim
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical owned/victim

## RANKED HYPOTHESES 2026-09-13 21:28:44 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -H "A
- LEARN: NONE @ registry-1.docker.io: still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not yet proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-13 23:33:27 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -H "A
- LEARN: NONE @ registry-1.docker.io: still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-14 01:41:00 UTC
- [75] registry-1.docker.io: Posit Cloud __api__ content IDOR via GUID with Accept header bypass (from reports/hypotheses-lead_muse-spark.txt.txt)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -H "A
- LEARN: NONE @ registry-1.docker.io: still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-14 07:06:29 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://posit.cloud/__api__/v1/content/<victim-guid> -H "Accept: application/json" -H "Authorization: Bearer <attacker-jwt-for-owned-account>" and sa
- LEARN: NONE @ registry-1.docker.io: still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-14 14:03:09 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" then 
- LEARN: NONE @ registry-1.docker.io: still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA; 401 identical not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-14 19:21:22 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" then 
- LEARN: NONE @ registry-1.docker.io: still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA; 401 identical not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-14 22:46:27 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull H: Authorization: Basic <attacker-b64> -> capt
- LEARN: NONE @ registry-1.docker.io: still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-15 00:57:14 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -> ca
- LEARN: NONE @ registry-1.docker.io: still need JWT-authenticated JSON 200 vs 401/403 differentiation for BOLA; 401 identical not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-15 06:10:15 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://posit.cloud/__api__/v1/content/<victim-guid> -H "Accept: application/json" -H "Authorization: Bearer <attacker-jwt-for-owned-account>" and sa
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-15 11:41:26 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://posit.cloud/__api__/v1/content/<victim-guid> H: Accept: application/json H: Authorization: Bearer <attacker-jwt-for-owned-account-sha256> ; A
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-15 15:42:57 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <jwt-from-auth.docker.io-token-for-victim-ns-with-attack
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-15 19:13:35 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -H "Authorization: Basic <attacker-b64>" -> ca
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-15 22:14:19 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list H: Authorization: Bearer <jwt-from-auth.docker.io-token-for-victim-ns-pull-with-at
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-16 00:20:01 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://api.vinsolutions.com/api/v2/leads?user_id=<victim-id> -H "Accept: application/json" -H "Authorization: Bearer <attacker-jwt-for-owned-account
- LEARN: NONE @ hub.docker.com: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-16 05:17:30 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list -H "Authorization: Bearer <jwt-from-auth.docker.io-token-for-victim-ns-pull-with-a
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-16 10:00:49 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://api.vinsolutions.com/api/v2/leads?user_id=<victim-id> H:Accept: application/json H:Authorization: Bearer <attacker-jwt-sha256> ; compare to G
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-16 14:57:56 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list H:Authorization: Bearer <jwt-from-auth.docker.io-token-service=registry.docker.io-
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-16 18:53:49 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list H: Authorization: Bearer <jwt-from-GET-https://auth.docker.io/token?service=regist
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-16 22:09:27 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list Host: registry-1.docker.io Accept: application/json Authorization: Bearer <jwt-fro
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-17 00:28:47 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list H:Host: registry-1.docker.io H:Accept: application/vnd.docker.distribution.manifes
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-17 05:22:55 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list — step1: GET https://auth.docker.io/token?service=registry.docker.io&scope=reposit
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-17 10:26:09 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list H:Host: registry-1.docker.io H:Accept: application/vnd.docker.distribution.manifes
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-17 15:20:12 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list — step1 GET https://auth.docker.io/token?service=registry.docker.io&scope=reposito
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-17 19:16:31 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -> then GET https://registry-1.docker.io/v2/vi
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-17 22:12:11 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull -> extract token, then GET https://registry-1.
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-18 00:15:52 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull (with owned DockerHub session) -> extract toke
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-18 04:46:45 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull with owned DockerHub session -> extract token 
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-18 09:15:43 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:owned-ns/owned-private:pull with owned DockerHub session cookie -> extract t
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-18 13:38:08 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:owned-ns/owned-private:pull with owned DockerHub session cookie -> extract t
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-18 17:13:59 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull with owned DockerHub session cookie -> extract
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-18 19:36:23 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:owned-ns/owned-private:pull with owned DockerHub session cookie -> extract t
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-18 21:52:47 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:owned-ns/owned-private:pull with owned DockerHub session Cookie -> extract t
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-19 00:19:07 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://posit.cloud/__api__/v1/content/<owned-guid> Headers: Accept: application/json, Authorization: Bearer <owned-posit-jwt> and GET https://posit.
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-19 05:04:54 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull with owned DockerHub session Cookie -> extract
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-19 09:29:31 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull with Header Cookie: <owned DockerHub session> 
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-19 13:25:58 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Header Cookie: <owned DockerHub session> -> ex
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-19 16:49:45 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Header Cookie: <owned DockerHub session> -> ex
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + JWT differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-19 19:20:14 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:owned-ns/owned-private:pull Header Cookie: <owned DockerHub session> -> extr
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation for BOLA; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-19 21:46:33 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Header Cookie: <owned-DockerHub-session> -> ex
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-19 23:37:07 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull with Header Cookie: <owned DockerHub session> 
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-20 01:39:37 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Header Cookie: <owned-DockerHub-session> Accep
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-20 07:01:08 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://api.vinsolutions.com/api/v2/leads?user_id=<victim-id> with Header Accept: application/json Authorization: Bearer <owned-cox-jwt> and GET http
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not

## RANKED HYPOTHESES 2026-09-20 12:20:02 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Header Cookie: <owned-DockerHub-session> Accep
- LEARN: NONE @ hub.docker.com: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ www.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation for BOLA; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-20 16:30:14 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Accept: application/json Cookie: <owned-Docker
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof vs 404 on www host remai

## RANKED HYPOTHESES 2026-09-20 19:04:47 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull with Accept: application/json Cookie: <owned-D
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-20 21:32:37 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull with Accept: application/json Cookie: <owned-D
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-20 23:32:33 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list Headers: Accept: application/json Authorization: Bearer <owned-docker-jwt-from-aut
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-21 01:41:49 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list Headers: Accept: application/json Authorization: Bearer <owned-docker-jwt-from-GET
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof vs 404 on www.vinsolutio

## RANKED HYPOTHESES 2026-09-21 07:10:54 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Accept: application/json Cookie: <owned-Docker
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical not proof

## RANKED HYPOTHESES 2026-09-21 14:05:37 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull headers: Accept: application/json Cookie: <own
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim vs 404 on www host remains routing

## RANKED HYPOTHESES 2026-09-21 19:25:48 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list Headers: Accept: application/json Authorization: Bearer <owned-docker-jwt-from-GET
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof

## RANKED HYPOTHESES 2026-09-21 22:50:36 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull header Accept: application/json Cookie: <owned
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof vs 404 on www host remai

## RANKED HYPOTHESES 2026-09-22 01:37:24 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list Headers: Accept: application/json Authorization: Bearer <owned-docker-jwt-from-GET
- LEARN: NONE — no class proven dead/alive this cycle; registry-1 401 identical without Bearer not proof, posit 1823 html identical not proof, vinsolutions 596 identical

## RANKED HYPOTHESES 2026-09-22 06:48:43 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Accept: application/json Cookie: <owned-Docker

## RANKED HYPOTHESES 2026-09-22 12:36:19 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list Headers: Accept: application/json Authorization: Bearer <owned-docker-jwt-from-GET
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof vs 404 on www host remai

## RANKED HYPOTHESES 2026-09-22 17:18:26 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list Headers: Accept: application/json Authorization: Bearer <owned-docker-jwt-from-GET
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim not proof vs 404 on www host remai

## RANKED HYPOTHESES 2026-09-22 20:30:36 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list Headers: Accept: application/json Authorization: Bearer <owned-docker-jwt-from-GET
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical vs 404 on www host remains routing ambiguity no

## RANKED HYPOTHESES 2026-09-22 23:17:34 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list Headers: Accept: application/json Authorization: Bearer <owned-docker-jwt-from-GET
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim vs 404 on www host remains routing

## RANKED HYPOTHESES 2026-09-23 01:48:52 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list Headers: Accept: application/json Authorization: Bearer <owned-docker-jwt-from-GET
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim vs 404 on www remains routing ambi

## RANKED HYPOTHESES 2026-09-23 07:45:54 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Accept: application/json (capture owned-docker
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim vs 404 on www host remains routing

## RANKED HYPOTHESES 2026-09-23 13:03:49 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list Headers: Accept: application/json, Authorization: Bearer <owned-docker-jwt-from-GE
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical vs 404 on www host remains routing ambiguity no

## RANKED HYPOTHESES 2026-09-23 17:52:53 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Headers: Accept: application/json -> capture o
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim vs 404 on www host remains routing

## RANKED HYPOTHESES 2026-09-23 21:29:36 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Headers: Accept: application/json -> capture o
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical vs 404 on www remains routing ambiguity not pro

## RANKED HYPOTHESES 2026-09-23 23:58:48 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Headers: Accept: application/json -> capture o
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical vs 404 on www remains routing ambiguity not pro

## RANKED HYPOTHESES 2026-09-24 04:45:01 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://registry-1.docker.io/v2/victim-ns/victim-private/tags/list Headers: Accept: application/json Authorization: Bearer <owned-docker-jwt-from-GET
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical not proof
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical vs 404 on www remains routing ambiguity not pro

## RANKED HYPOTHESES 2026-09-24 09:34:25 UTC
- (no NEW hypotheses this cycle — all deduped)
- NEXT(hypotheses-lead_muse-spark.txt.txt): PROBE: GET https://auth.docker.io/token?service=registry.docker.io&scope=repository:victim-ns/victim-private:pull Headers: Accept: application/json -> capture o
- LEARN: NONE @ registry-1.docker.io: still need JWT Bearer JSON 200 vs 401/403 differentiation for BOLA; 401 identical owned/victim without Bearer not proof
- LEARN: NONE @ posit.cloud: still need Accept: application/json + Authorization: Bearer <owned-posit-jwt> differentiation for IDOR; HTML 1823 identical owned/victim not
- LEARN: NONE @ api.vinsolutions.com: still need authenticated JSON 200 vs 401/403 differentiation; gateway 596 identical owned/victim vs 404 on www remains routing ambi
