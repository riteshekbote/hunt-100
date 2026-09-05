
## 2026-08-27 07:20:16 UTC

## 2026-08-27 07:41:02 UTC

## 2026-08-27 14:17:52 UTC

## 2026-08-27 15:20:06 UTC

## 2026-08-27 15:34:11 UTC

## 2026-08-28 00:39:55 UTC

## 2026-08-28 12:14:58 UTC
- NEW www.autotrader.com/rest/search/vehicle?vehicleId=123456789 -> 200 len=3760 text/html (same len as /api/vehicles/123456)
- NEW www.autotrader.com/api/vehicles/123456 -> 200 len=3760 text/html
- NEW www.vinsolutions.com/api/leads?user_id=1001 -> 404 (coxautomotive api exists but param filtered)

## 2026-08-28 22:20:39 UTC

## 2026-08-29 03:54:31 UTC
- CHANGED www.autotrader.com/rest/search/vehicle?vehicleId=1 -> 200 text/html len=3761 (static HTML for all IDs, WAF/cache masking)

## 2026-08-29 11:04:35 UTC
- NEW www.autotrader.com/rest/search/vehicle?vehicleId= param variation 1 vs 123456789 -> both 200 len~3762 html (param ignored, no 4xx)

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

## 2026-09-03 19:52:02 UTC

## 2026-09-03 22:34:55 UTC

## 2026-09-04 00:31:53 UTC

## 2026-09-04 05:08:31 UTC

## 2026-09-04 09:37:47 UTC

## 2026-09-04 13:48:26 UTC

## 2026-09-04 17:37:24 UTC

## 2026-09-04 19:52:43 UTC

## 2026-09-04 22:23:27 UTC

## 2026-09-05 00:25:47 UTC

## 2026-09-05 04:58:14 UTC

## 2026-09-05 09:03:42 UTC

## 2026-09-05 12:42:42 UTC
- NEW NO_DELTA — inventory truncated at api.axon.com, no new hosts vs prior cycle; probe surface unchanged (registry-1.docker.io, posit.cloud, www.autotrader.com remain top)

## 2026-09-05 15:34:53 UTC
