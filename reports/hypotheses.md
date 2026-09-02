
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
