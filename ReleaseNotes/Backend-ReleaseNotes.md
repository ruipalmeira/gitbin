# Backend ChangeLog `[27/01/2023]`

`[26/01/2023]`

> Introducing moviik actions! 
> 
> Configure custom actions on the backoffice. 
> 
> These can be triggered by an opaque and unique url. 
> 
> Just use the url in any html page, iot/automation device, smart devices, etc. to invoke some action defined in the system.
>
> The url can be revoked, or the corresponding action can be reconfigured, the url can be rate limited to prevent abuse.
> 
> A backend protype is in place in [DEV](https://dev.moviik.com).
>
> Introducing ticket preview - an image url to display a ticket, ideal to share on chats or messaging.
>
> The image is generated server side in around 100 milliseconds. The same technology supports generating a pdf version. 
> 
> A prototype of this is in place in [DEV](https://dev.moviik.com).
> 
> This is required to fix whatsapp integration. 

## Current Version 
  - frontend: [`v2.1.1`] 
  - backend: [`v2.1.0`]

### Added:
     
  [`v2.1.0`] `[26/01/2023]`
    
    - charts: add chart type to dashboard item for readability
    - charts: charts setup default settings
    - fix: return rabbitmq subscriber close function
    - via-guide: add slot end time in notification email
    - charts: remove chart with old naming
    - charts: added tickets-stats-by-branch chart
    - charts: fixed influx by service profile
    - charts: add tickets stats by service profile chart
    - charts: fixed influx by branch
    - charts: added charts and support for settings
    - charts: add setup to dashboards
    - charts: get dashboard by id
    - charts: add table devices as chart
    - charts: add count tickets by terminal chart

  [`v2.0.0`] `[19/01/2023]`

    - runner: add ise call tickets
    - worker: remove notifications command
    - refactor: use notification controller in ticket act
    - commands: drop alerts
    - worker: remove asset processor command
    - worker: drop kpi incidents
    - feat: use `moviik.com` domain in mail from address
    - api: generate just 5 video frames
    - api: fill artifacts url in asset/video job
    - api: use space.settings.s3 in putobject
    - api: use space.settings.s3 in fgetobject
    - api: use space.settings.s3 in fputobject 
    - refactor: pass space to convert video
    - api: add API_SESSION_SECURE
    - viaguide: fill tzl details
    - via-guide: use subject based on ticket lang
    - via-guide: format slot date based on ticket lang
    - via-guide: update template messages
    - tests: skip old dashboard test
    - api: add manager, model & interface for dashboard
    - db: add dashboards table
    - viaguide: fix typo in email
    - charts: remove return from query
    - charts: add influx tickets by branch chart
    - charts: add count tickets by branch chart
    - chart: add influx tickets by service profile chart
    - runner: fix runner query nulls
    - charts: rename chart query count to cnt
    - runner: add retry failed jobs strategy


`Currently backend has no visible tags or versioning attributed to the changes being pushed and made to the system. 
We should think about versioning the backend as well.`
