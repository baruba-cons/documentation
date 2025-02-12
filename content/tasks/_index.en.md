+++
title = "Scheduled Tasks"
pre = "<i class='fas fa-fw fa-stopwatch'></i> "
weight = 32
layout = "man"
tags = ["scheduled tasks"]
+++

Web apps or services sometimes need to periodically run tasks, commands or call up URLs with no user interaction. To manage this point you should save a scheduled task.

Our platform is based on [Debian](https://www.debian.org/) and its [crontab](https://en.wikipedia.org/wiki/Cron) but allows them to be directly managed from our [administration interface](https://admin.alwaysdata.com) - menu **Advanced > Scheduled tasks** - making their use easier.

Several kinds of information need to be provided:

- the one or more commands that you wish to run or the URLs you wish to request,
- the SSH environment,
- the task frequency: you can specify a fixed time or an interval.

{{% notice tip %}}
Email addresses can also be filled in to receive error reports (separated by a space). They do not replace the execution logs already given in the `$HOME/admin/logs/jobs` directory.
{{% /notice %}}

{{< fig "admin-panel_create-task.en.png" "Administration interface: create a scheduled task" >}}

{{% notice note %}}
If your script needs to allow some IPs, allow these [IP adresses ranges]({{< ref "security/ip-ranges" >}}).
{{% /notice %}}

---
- [Use scheduled tasks]({{< ref "tasks/use-scheduled-tasks" >}})
- [API reference](https://api.alwaysdata.com/v1/job/doc/)
