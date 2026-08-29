
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
