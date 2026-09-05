
## 2026-08-27 05:06:25 UTC


## 2026-08-27 07:20:28 UTC


## 2026-08-27 07:41:11 UTC


## 2026-08-27 14:18:03 UTC


## 2026-08-27 15:20:15 UTC


## 2026-08-27 15:34:21 UTC


## 2026-08-28 00:40:10 UTC
https://hub.docker.com/v2/repositories/library/hello-world/tags?page_size=5 -> 200 len=? type=application/json
https://hub.docker.com/v2/repositories/<owned-private-namespace>/<private-repo>/tags -> HTTP 400
https://hub.docker.com/v2/repositories/<victim-namespace>/<guessed-private-repo>/tags -> HTTP 400
https://www.autotrader.com/rest/search/vehicle?vehicleId=123456789 -> 200 len=3760 type=text/html
https://www.autotrader.com/api/vehicles/123456 -> 200 len=3760 type=text/html
https://www.vinsolutions.com/api/leads?user_id=1001 -> HTTP 404
https://duocircle.com/api/health -> HTTP 404
https://duocircle.com/swagger.json -> HTTP 404
https://duocircle.com/.well-known/openapi.json -> HTTP 404
https://duocircle.com/api/openapi.json -> HTTP 404
https://tenantmigration.com/api/migrate -> HTTP 404
https://mailflowmonitoring.com/api/check?domain=http://169.254.169.254/ -> HTTP 404

## 2026-08-28 12:15:11 UTC
https://hub.docker.com/v2/ -> HTTP 404
https://hub.docker.com/v2/repositories/library/hello-world/tags?page_size=5 -> 200 len=? type=application/json
https://hub.docker.com/v2/repositories/<victim-namespace>/<private-repo>/tags -> HTTP 400
https://registry-1.docker.io/v2/ -> HTTP 401
https://www.autotrader.com/rest/search/vehicle?vehicleId=123456789 -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=1,2,3 -> 200 len=3761 type=text/html
https://www.autotrader.com/api/vehicles/123456 -> 200 len=3761 type=text/html
https://api.posit.co/v1/applications?app_id=1 -> ERR <urlopen error [Errno -2] Name or service not know
https://shinyapps.io/api/v1/applications/1 -> HTTP 404
https://connect.cloud/__api__/applications -> HTTP 404

## 2026-08-28 22:20:53 UTC
https://registry-1.docker.io/v2/ -> HTTP 401
https://auth.docker.io/token?service=registry.docker.io&scope=repository:library/hello-world:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/library/hello-world/manifests/latest -> HTTP 401
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://hub.docker.com/v2/repositories/library/hello-world/tags?page_size=5 -> 200 len=? type=application/json
https://hub.docker.com/v2/repositories/<owned-private-ns>/<private-repo>/tags -> HTTP 400
https://hub.docker.com/v2/repositories/<victim-ns>/<guessed>/tags -> HTTP 400
https://www.autotrader.com/rest/search/vehicle?vehicleId=123456789 -> 200 len=3760 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=1 -> 200 len=3761 type=text/html
https://www.vinsolutions.com/api/leads?user_id=1001 -> HTTP 404

## 2026-08-29 03:54:44 UTC
https://hub.docker.com/v2/repositories/library/hello-world/tags?page_size=5 -> 200 len=? type=application/json
https://hub.docker.com/v2/repositories/<owned-private-namespace>/<private-repo>/tags -> HTTP 400
https://hub.docker.com/v2/repositories/<victim-namespace>/<guessed-not-exist-xyz123>/tags -> HTTP 400
https://registry-1.docker.io/v2/ -> HTTP 401
https://auth.docker.io/token?service=registry.docker.io&scope=repository:library/hello-world:pull -> 200 len=? type=application/json
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://www.autotrader.com/rest/search/vehicle?vehicleId=1 -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=123456789 -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/1 -> 200 len=3762 type=text/html

## 2026-08-29 11:04:48 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:library/hello-world:pull -> 200 len=? type=application/json
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://registry-1.docker.io/v2/ -> HTTP 401
https://registry-1.docker.io/v2/<owned-private-ns>/<private-repo>/manifests/latest -> HTTP 404
https://registry-1.docker.io/v2/<victim-ns>/notexistXYZ123/manifests/latest -> HTTP 404
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3761 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3761 type=text/html

## 2026-08-29 15:39:30 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:library/hello-world:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/library/hello-world/manifests/latest -> HTTP 401
https://mailflowmonitoring.com/api/check?domain=http://169.254.169.254/latest/meta-data/ -> HTTP 404
https://mailflowmonitoring.com/api/v1/check?url=http://169.254.169.254/ -> HTTP 404
https://tenantmigration.com/api/migrate?domain=http://169.254.169.254/ -> HTTP 404
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<owned -> HTTP 404
https://www.autotrader.com/api/vehicles/<owned -> 200 len=3762 type=text/html

## 2026-08-29 18:55:09 UTC
https://hub.docker.com/v2/repositories/library/hello-world/tags?page_size=5 -> 200 len=? type=application/json
https://hub.docker.com/v2/repositories/<victim-ns>/<private-repo>/tags -> HTTP 400
https://auth.docker.io/token?service=registry.docker.io&scope=repository:library/hello-world:pull -> 200 len=? type=application/json
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=1 -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<other-id -> 200 len=1823 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<other-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html

## 2026-08-29 21:45:28 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:library/hello-world:pull -> 200 len=? type=application/json
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-private-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<owned-private-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3761 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<other-id -> 200 len=3762 type=text/html

## 2026-08-29 23:40:32 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-private-ns>/<repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<owned-private-ns>/<repo>/manifests/latest -> HTTP 404
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<owned -> HTTP 404
https://mailflowmonitoring.com/api/v1/check?url=http://169.254.169.254/latest/meta-data/ -> HTTP 404
https://mailflowmonitoring.com/api/v1/check?url=http://example.com -> HTTP 404
https://mailflowmonitoring.com/api/check -> HTTP 404

## 2026-08-30 01:41:36 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:library/hello-world:pull -> 200 len=? type=application/json
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<other-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<owned -> HTTP 404
https://mailflowmonitoring.com/.well-known/openapi.json -> HTTP 404
https://mailflowmonitoring.com/api/v1/check -> HTTP 404
https://tenantmigration.com/api/migrate -> HTTP 404

## 2026-08-30 07:26:58 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:library/hello-world:pull -> 200 len=? type=application/json
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<other-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<other-id -> 200 len=3762 type=text/html
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<other-id -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=1 -> 200 len=1823 type=text/html

## 2026-08-30 13:18:38 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html

## 2026-08-30 17:48:16 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<other-id -> 200 len=1823 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<other-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<other-id -> HTTP 404

## 2026-08-30 21:04:51 UTC


## 2026-08-30 23:30:28 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:library/hello-world:pull -> 200 len=? type=application/json
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://www.autotrader.com/api/vehicles/<owned-vehicleId -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<other-vehicleId -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<other-vehicleId -> 200 len=3762 type=text/html
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<other-id -> 200 len=1823 type=text/html

## 2026-08-31 01:39:52 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<other-id -> 200 len=1823 type=text/html
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<owned -> HTTP 404

## 2026-08-31 07:44:41 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<other-id -> 200 len=1823 type=text/html
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html

## 2026-08-31 15:28:39 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<victim-id -> 200 len=1823 type=text/html
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<victim-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html

## 2026-08-31 21:07:11 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<victim-id -> 200 len=1823 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<victim-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3761 type=text/html

## 2026-09-01 00:39:09 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<victim-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<victim-id -> 200 len=1823 type=text/html

## 2026-09-01 05:41:48 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<owned-ns>/<private-repo>/manifests/latest -> HTTP 404
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<victim-id -> 200 len=1823 type=text/html
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-vehicleId -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-vehicleId -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<owned -> HTTP 404

## 2026-09-01 10:28:53 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<owned -> HTTP 404

## 2026-09-01 15:13:39 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<owned-ns>/<private-repo>/manifests/latest -> HTTP 404
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<victim-id -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<victim-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<victim-id -> HTTP 404

## 2026-09-01 18:30:52 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<victim-id -> HTTP 404
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html

## 2026-09-01 21:21:55 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://hub.docker.com/v2/repositories/<owned-ns>/ -> HTTP 400
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html

## 2026-09-01 23:35:37 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://hub.docker.com/v2/users/login -> HTTP 415
https://hub.docker.com/v2/repositories/<owned-ns>/ -> HTTP 400

## 2026-09-02 01:26:05 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<owned-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<owned-vehicleId -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-vehicleId -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<owned -> HTTP 404

## 2026-09-02 06:27:25 UTC


## 2026-09-02 11:45:30 UTC


## 2026-09-02 15:20:45 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<owned-ns>/<private-repo>/tags/list -> HTTP 404
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<victim-id -> HTTP 404

## 2026-09-02 18:59:32 UTC


## 2026-09-02 21:50:16 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html

## 2026-09-03 00:14:55 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://hub.docker.com/v2/users/login -> HTTP 415
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<owned-id -> 200 len=3762 type=text/html
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://posit.cloud/api/v1/applications?app_id=<owned-id -> 200 len=1823 type=text/html

## 2026-09-03 04:23:25 UTC


## 2026-09-03 09:13:13 UTC


## 2026-09-03 13:35:54 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<owned-ns>/<private-repo>/tags/list -> HTTP 404
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/v2/vehicles/<victim-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<victim-id -> HTTP 404

## 2026-09-03 17:15:22 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3761 type=text/html
https://www.vinsolutions.com/api/leads?user_id=<victim-id -> HTTP 404

## 2026-09-03 19:52:14 UTC


## 2026-09-03 22:35:08 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/manifests/latest -> HTTP 404
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/.well-known/openapi.json -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/.well-known/security.txt -> 200 len=3762 type=text/html
https://www.autotrader.com/api/docs -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<victim-id -> 200 len=3762 type=text/html

## 2026-09-04 00:32:03 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/applications/<id -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/v2/leads?user_id=<owned-id -> HTTP 404

## 2026-09-04 05:08:42 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3761 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html

## 2026-09-04 09:38:00 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/login -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html

## 2026-09-04 13:48:40 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/login -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/login -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3761 type=text/html
https://www.autotrader.com/.well-known/security.txt -> 200 len=3761 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3761 type=text/html
https://www.vinsolutions.com/api/v2/leads?user_id=<victim-id -> HTTP 404

## 2026-09-04 17:37:36 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/login -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/applications/<id -> 200 len=1823 type=text/html
https://www.autotrader.com/.well-known/security.txt -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3761 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/v2/leads?user_id=<victim-id -> HTTP 404

## 2026-09-04 19:52:53 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/login -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/applications/<id -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<victim-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/v2/leads?user_id=<victim-id -> HTTP 404

## 2026-09-04 22:23:41 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/login -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.autotrader.com/.well-known/security.txt -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<victim-id -> 200 len=3762 type=text/html

## 2026-09-05 00:25:58 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<owned-private>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/login -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/applications/<id -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<victim-id -> 200 len=3762 type=text/html
https://www.autotrader.com/.well-known/security.txt -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/v2/leads?user_id=<victim-id -> HTTP 404

## 2026-09-05 04:58:25 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/v1/login -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.autotrader.com -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html

## 2026-09-05 09:03:54 UTC


## 2026-09-05 12:42:56 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/login -> 200 len=1823 type=text/html
https://www.autotrader.com/api/vehicles/<owned-id -> 200 len=3762 type=text/html
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html
https://www.autotrader.com/.well-known/security.txt -> 200 len=3762 type=text/html
https://www.autotrader.com/rest/search/vehicle?vehicleId=<victim-id -> 200 len=3762 type=text/html

## 2026-09-05 15:35:04 UTC


## 2026-09-05 17:40:24 UTC
https://hub.docker.com/v2/users/login -> HTTP 415
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.vinsolutions.com/api/v2/leads?user_id=<owned-id -> HTTP 404
https://www.vinsolutions.com/api/v2/leads?user_id=<victim-id -> HTTP 404

## 2026-09-05 19:31:40 UTC
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<owned-ns>/<owned-private>:pull -> 200 len=? type=application/json
https://auth.docker.io/token?service=registry.docker.io&scope=repository:<victim-ns>/<private-repo>:pull -> 200 len=? type=application/json
https://registry-1.docker.io/v2/<victim-ns>/<private-repo>/tags/list -> HTTP 404
https://posit.cloud/__api__/v1/content/<owned-guid -> 200 len=1823 type=text/html
https://posit.cloud/__api__/login -> 200 len=1823 type=text/html
https://posit.cloud/__api__/v1/content/<victim-guid -> 200 len=1823 type=text/html
https://www.vinsolutions.com/api/v2/leads?user_id=<owned -> HTTP 404
https://www.autotrader.com/api/vehicles/<id -> 200 len=3762 type=text/html
https://www.autotrader.com/__api__/login -> 200 len=3762 type=text/html
https://www.vinsolutions.com/api/v2/leads?user_id=<owned-id -> HTTP 404
https://www.vinsolutions.com/api/v2/leads?user_id=<victim-id -> HTTP 404
https://www.autotrader.com/api/vehicles/<victim-id -> 200 len=3762 type=text/html
