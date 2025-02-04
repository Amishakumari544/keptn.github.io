---
title: Keptn 0.9.1
weight: 87
---


This is a bug fix release for Keptn 0.9.0, containing fixes for the Bridge and Keptn core services; especially, lighthouse-service and shipyard-controller.

---

## Improvements and Fixes

<details><summary>Platform Support / Installer</summary>
<p>

- *Fixes:*
  * mongodb and mongodb-datastore killed because of OOM [#5196](https://github.com/keptn/keptn/issues/5196)

</p>
</details>


</p>
</details>

<details><summary>Keptn Core</summary>
<p>

- *Fixes:*
  * *lighthouse-service*: Print logs if configure monitoring fails [#5088](https://github.com/keptn/keptn/issues/5088)
  * *lighthouse-service*: No error message when SLO parsing failed [#5130](https://github.com/keptn/keptn/issues/5130)
  * *lighthouse-service*: Error events from the lighthouse-service are shown even though "status": "succeeded" [#5170](https://github.com/keptn/keptn/issues/5170)
  * *shipyard-controller*: Returns a 500 error if a triggered event is not found [#5132](https://github.com/keptn/keptn/issues/5132)
  * *shipyard-controller*: Every 10 seconds an error is produced with "could not load queued sequences" [#5138](https://github.com/keptn/keptn/issues/5138)
  * *configuration-service*: deleting a file on a specific stage or for specific service not possible [#5136](https://github.com/keptn/keptn/issues/5136)
  * Providing an invalid git token disables the access to the repository [#5064](https://github.com/keptn/keptn/issues/5064)
  * Unable to (re)register to Keptn [#4791](https://github.com/keptn/keptn/issues/4791)


</p>
</details>

<details><summary>Bridge</summary>
<p>

- *Fixes:*
  * Bridge not grouping paused sequences correctly [#5154](https://github.com/keptn/keptn/issues/5154)
  * Sequence screen does not get updated on project change if no sequence was triggered for a project [#5085](https://github.com/keptn/keptn/issues/5085)
  * A failed sequence is shown as it would be running and cannot be aborted [#5137](https://github.com/keptn/keptn/issues/5137)
  * Bridge runs into some errors if a sequence for a service could not be found [#5172](https://github.com/keptn/keptn/issues/5172)
  * Project delete dialog is not closed [#5091](https://github.com/keptn/keptn/issues/5091)
  * Polling of a project does not stop [#5094](https://github.com/keptn/keptn/issues/5094)
  * Unread error event indicator for integrations is shown even if there aren't any [#5118](https://github.com/keptn/keptn/issues/5118)
  * Dashboard: Redirect after click on a service or a sequence does not work [#5126](https://github.com/keptn/keptn/issues/5126)
  * If 401 for API token request is returned, endless redirect loop occurs [#5086](https://github.com/keptn/keptn/issues/5086)
  * Sequence is not displayed correctly if more than 100 events exist [#5056](https://github.com/keptn/keptn/issues/5056)

</p>
</details>

## Upgrade to 0.9.1

- The upgrade from 0.9.0 to 0.9.1 is supported by the `keptn upgrade` command. Find the documentation here: [Upgrade from Keptn 0.9.0 to 0.9.1](https://keptn.sh/docs/0.9.x/operate/upgrade/#upgrade-from-keptn-0-9-0-to-0-9-1).
