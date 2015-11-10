# Features

All these features are exposed through the web client, XO-Web, which is using a [responsive design](https://xen-orchestra.com/blog/xen-orchestra-responsive-design/).

## XenServer administration

This part is about everyday XenServer administration tasks.

### Infrastructure overview

The original motivation of XO was to provide a view to understand the whole infrastructure in a single page. In short, to answer the question: "where is my VM?".

![](https://xen-orchestra.com/blog/content/images/2014/Aug/main_view.png)

[Read more about it](https://xen-orchestra.com/blog/introducing-new-interface/#horizontalhierarchy).

### Live filter search

If you infrastructure starts to be big, it could be useful to find exactly what you need. It could be an IP address, a VM name, or a storage name: any object!

![](https://xen-orchestra.com/blog/content/images/2014/Aug/flat_view_filtered.png)

[Read more about this](https://xen-orchestra.com/blog/introducing-new-interface/#flatviewwithpowerfulsearchengine).

### Easy VM creation

Creating a VM should be trivial! That's why we are constantly improving our interface to display only what's necessary, but also allow the user to access advanced stuff when needed.

### VM import and export

You can import or export a VM directly on your computer, through your web browser.

![](https://xen-orchestra.com/blog/content/images/2014/Sep/import1bis.png)

[Read more about it](https://xen-orchestra.com/blog/import-and-export-vm-in-xo/).

### Snapshots management

![](https://xen-orchestra.com/blog/content/images/2014/Nov/snap2.png)

[Read more about it](https://xen-orchestra.com/blog/snapshot-export-with-xen-orchestra/).

### Statistics

Live statistics are showing the last 10 minutes of VM/host/SR usage.

![](https://xen-orchestra.com/blog/content/images/2015/04/statsI.png)

[Read more about this](https://xen-orchestra.com/blog/vm-live-metrics-in-xenserver-with-xen-orchestra/).

### Auto patching

Patching a host manually could be time consuming (and boring). That's why we provide a high level feature downloading and applying patches automatically.

![](https://xen-orchestra.com/blog/content/images/2015/10/patch_all.png)

[Read more about this](https://xen-orchestra.com/blog/xen-orchestra-4-8/#fullyautomatedpatching).

### Batch operations

You can make simultaneous operations on many objects: like migrate a bunch of VM, or start them at the same time.

### Drag'n drop live migration

You can live migrate a VM just by drag'n drop!

![](https://xen-orchestra.com/blog/content/images/2015/06/dragndrop.png)

[Read more about it](https://xen-orchestra.com/blog/vm-live-migration-with-xenserver-and-xen-orchestra/).

### VDI live migration

Thanks to Xen Storage Motion, it's easy to move a VM disk from a storage to another, while the VM is on!

![](https://xen-orchestra.com/blog/content/images/2015/01/vdi3.png)

[Read more about this](https://xen-orchestra.com/blog/moving-vdi-in-live/).

### Adjusting resources

You can edit your VM RAM or CPUs in live.

## Backups and Disaster Recovery

This section is dedicated to any existing means to rollback or backup your VM in Xen Orchestra.

### Full backups

You can schedule full backups of your VMs, by exporting them in the local XOA file-system, or directly in a NFS share. "Depth" parameter allow to modify the retention (removing the oldest one).

![](https://xen-orchestra.com/blog/content/images/2015/07/backupexample.png)

[Read more here](https://xen-orchestra.com/blog/backup-your-xenserver-vms-with-xen-orchestra/).

### Scheduled snapshots

This feature is close to Backups, but it creates a snapshot when planned to do so. It also handles the retention (to remove the oldest snapshot).

[Read more about it](https://xen-orchestra.com/blog/xen-orchestra-4-2/#schedulerollingsnapshots).

### Disaster recovery

## VM (and resources) delegation

### ACLs

### LDAP

### SSO

## Visualizations

### Dashboard

### Heatmap

### Sunbrust

### Health

## Scheduler

## Load balancing