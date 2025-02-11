---
title: TrueCommand 2.1 Release Notes
weight: 5
aliases:
  - /releasenotes/truecommand/2.1.1/
  - /releasenotes/truecommand/2.1/
---

{{< toc >}}

## Software Lifecycle

{{< include file="/static/includes/General/LifecycleTable.html.part" html="true" >}}

## TrueCommand Schedule

{{< include file="/content/_includes/ReleaseScheduleWarning.md" type="page" >}}

| Version | Checkpoint | Scheduled Date |
|---------|------------|----------------|
| 2.2.0-RC.1 | Internal Testing Sprints | 30 May > 03 June 2022 |
| 2.2.0 | Code-freeze | 08 June 2022 |
| 2.2.0 | Internal Testing Sprints | 09 June 2022 > 22 July 2022 |
| 2.2.0 | Tag | 25 July 2022 |
| 2.2.0 | Release | 26 July 2022 |

## 2.1.1

**March 29, 2022**

The TrueCommand team is pleased to announce [TrueCommand 2.1.1](https://www.truenas.com/docs/truecommand/) is now available. 

### 2.1.1 Changelog

#### Improvement

<ul>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1924'>TC-1924</a>] -         Adjust log rotation to use max size
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1968'>TC-1968</a>] -         Add build/deploy github workflow to release/2.1
</li>
</ul>

#### Bug Fixes

<ul>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1913'>TC-1913</a>] -         TrueCommand does not start when pointed to a custom certificate
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1921'>TC-1921</a>] -         Imported Certificates Are Not Showing In The WebUI
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1934'>TC-1934</a>] -         Mailserver Test Button Lacks Meaningful Output
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1937'>TC-1937</a>] -         Docker Does Not Start Again After Import Certificates
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1941'>TC-1941</a>] -         Unable to open TrueNAS proxy interface on cloud
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1948'>TC-1948</a>] -         Removal of team in edit-user page is not working
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1966'>TC-1966</a>] -         Removing Cluster Volume Hangs
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1967'>TC-1967</a>] -         Deleting Certificate Authorities not working 
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1982'>TC-1982</a>] -         Cluster Volume not showing in UI
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1983'>TC-1983</a>] -         Middleware API crash when I try verify email of my profile in truecommand docker version 
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1985'>TC-1985</a>] -         Handle instance where filewatcher util can fail on initialization
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1988'>TC-1988</a>] -         Do not fail deployment if Influx already setup
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1990'>TC-1990</a>] -         Trouble With Deleting Alerts
</li>
</ul>

## 2.1

{{< expand "2.1" >}}

**January 4, 2022**

The TrueCommand team is pleased to announce [TrueCommand 2.1](https://www.truenas.com/docs/truecommand/) is now available. 

TrueCommand 2.1 is the single pane of glass for:

* **TrueNAS CORE**: Manage systems on standard servers, Minis, or even AWS.
* **TrueNAS Enterprise**: Manage X-Series and M-Series systems with High Availability.
* **TrueNAS SCALE**: Manage a group of systems running a TrueNAS SCALE cluster. 

### 2.1 Changelog

#### New Feature

<ul>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1184'>TC-1184</a>] -         Add two-factor authentication support
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1581'>TC-1581</a>] -         Have TC auto-generate and use an auth token after initial NAS connect
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1711'>TC-1711</a>] -         NAS user management
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1757'>TC-1757</a>] -         Add SAML SSO support
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1774'>TC-1774</a>] -         Add ability to manage NAS users/groups for shares.
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1823'>TC-1823</a>] -         Add ability to reset user passwords from login page
</li>
</ul>

#### Improvement

<ul>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1468'>TC-1468</a>] -         EULA needs to identify GPL components
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1489'>TC-1489</a>] -         Question about the Dashboard System Options Menu
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1603'>TC-1603</a>] -         Update selenium tests
</li>
  <li>[<a href='https://jira.ixsystems.com/browse/TC-1655'>TC-1655</a>] -       Include <b>Group</b> or <b>All</b> option for system selection for reports
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1663'>TC-1663</a>] -         Add email verification to user email
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1772'>TC-1772</a>] -         Multiple time formats in use
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1789'>TC-1789</a>] -         Alerts for failed/suspicious login activity on a NAS
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1806'>TC-1806</a>] -         Remove PostgreSQL and migration routine.
</li>
  <li>[<a href='https://jira.ixsystems.com/browse/TC-1811'>TC-1811</a>] -       Add <b>Test</b> button for LDAP settings
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1813'>TC-1813</a>] -         Rewrite shell scripts to go binaries
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1816'>TC-1816</a>] -         Unique name for the TC instance when it registers a token on the NAS
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1820'>TC-1820</a>] -         Unix permissions widget
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1821'>TC-1821</a>] -         Remove ng2-validation dependency
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1834'>TC-1834</a>] -         Add verbose logging and log level config
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1835'>TC-1835</a>] -         Update SMR disk model scanning
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1844'>TC-1844</a>] -         Prune dead code
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1850'>TC-1850</a>] -         Add warning to Cluster feature
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1857'>TC-1857</a>] -         Delete Dataset shouldn't be an option for datasets with children
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1865'>TC-1865</a>] -         Bugclerk for TrueCommand team
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1869'>TC-1869</a>] -         Add a Confirmation screen when the cluster is successfully deleted
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1876'>TC-1876</a>] -         Disable adding/replacing/removing peers/bricks
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1878'>TC-1878</a>] -         Add Experimental flags to Users/Groups+SAML
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1884'>TC-1884</a>] -         Safety belt for Clustering feature
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1893'>TC-1893</a>] -         Add memory health check
</li>
</ul>

#### Epic

<ul>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1800'>TC-1800</a>] -         Enhanced Authentication Support
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1815'>TC-1815</a>] -         SMB User Management
</li>
</ul>

#### Bug Fixes

<ul>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1761'>TC-1761</a>] -         Used space on system tiles reported as a whole number
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1768'>TC-1768</a>] -         Storage Navigator and Datasets card issues
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1783'>TC-1783</a>] -         SMR Alerts: Disk/Model desync from NAS?
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1784'>TC-1784</a>] -         Share Count Numbers always 0
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1812'>TC-1812</a>] -         DNS lookup failure
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1826'>TC-1826</a>] -         Alert rules not staying paused
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1829'>TC-1829</a>] -         Network speed reporting issues
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1833'>TC-1833</a>] -         Clumsy resolving long alert messages
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1839'>TC-1839</a>] -         NAS API Error - Can't view Storage
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1851'>TC-1851</a>] -         Include the User's name and UID in the logs
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1856'>TC-1856</a>] -         Cluster creation - API error
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1908'>TC-1908</a>] -         Not deleting or reusing TSP
</li>
<li>[<a href='https://jira.ixsystems.com/browse/TC-1911'>TC-1911</a>] -         Mismatch between ignore_alerts in MW and UI
</li>
</ul>

{{< /expand >}}

## To Download this Release

Login to the [TrueCommand Account Portal](https://portal.ixsystems.com) for downloads, documentation links, and licensing options.
For storage clusters with more than 50 disks, the account portal also offers a *free 60-day trial license with unlimited disks*.

#### Minimum Supported TrueNAS Versions

Due to the changes in integrating with the TrueNAS middleware, the minimum version for full-support of functionality has changed with TrueCommand 2.1:

* FreeNAS/TrueNAS 11.3 series - No longer supported. Does not provide realtime statistics or storage information, but you can still connect to them and use TrueCommand to initiate updates.
* TrueNAS 12 CORE/Enterprise - Supported after 12.0-U3. 12.0-U2.1 and older are missing some key metrics in the realtime stats (disk/network usage metrics in particular), but work otherwise.
* TrueNAS SCALE 21.03+ - Fully Supported (SCALE-20.12+ is supported excluding cluster functionality)
 
## To Update to this Release

{{< hint info >}}
**Prior To Updating**
 
As a best practice, TrueCommand admins should backup their instance's data directory before deploying TrueCommand updates. If issues arise after updating, admins can simply pull the previous TC docker image and redeploy with their previous data directory. 
{{< /hint >}}

{{< hint warning >}}
**Important Note for Upgrading from v1.3**
 
Updating from TrueCommand v1.3 to v2.0 or higher involves a database migration process. This preserves all configuration data, but does not preserve old performance statistics.
Additionally, it is not possible to roll back to TrueCommand v1.3 from v2.1. Please use caution when upgrading production TrueCommand systems. If necessary, run TrueCommand 1.3 and TrueCommand 2.1 in parallel for a transition period. Simply use the "ixsystems/truecommand:1.3.2" docker image to continue using that specific version of TrueCommand.
{{< /hint >}}
 
**Docker:** Re-run `docker pull ixsystems/truecommand` to fetch the latest version of TrueCommand, and then restart your docker instance.

**VM Image:** Either reboot the VM or run `systemctl restart truecommand.service`.
This will automatically fetch and start the latest Docker image of TrueCommand within your VM.

## Known Issues

| Seen In | Key | Summary | Workaround | Resolved In |
|---------|-----|---------|------------|-------------|
| | | | | |

