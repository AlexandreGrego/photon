# Summary

## Photon OS 1.0 and 2.0

----

- [Introduction](README.md)
- [Getting Started Guides](getting-started-guides.md)
    - [Downloading Photon OS](Downloading-Photon-OS.md)
    -  [Quick Start](photon-admin-guide.md#getting-started-with-photon-os-20)
    -   [Upgrading to Photon OS 2.0](Upgrading-to-Photon-OS-2.0.md)
    -   [What is New in Photon OS 2.0](What-is-New-in-Photon-OS-2.0.md)
    -   [Running Photon OS on vSphere](Running-Photon-OS-on-vSphere.md)
    -   [Running Photon OS on Fusion](Running-Project-Photon-on-Fusion.md)
    -   [Running Photon OS on Workstation](Running-Photon-OS-on-Workstation.md)
    -   [Running Photon OS on AWS EC2](Running-Photon-OS-on-Amazon-Elastic-Cloud-Compute.md)
    -   [Running Photon OS on Microsoft Azure](Running-Photon-OS-on-Microsoft-Azure.md)
    -   [Running Photon OS on Google Compute Engine](Running-Photon-OS-on-Google-Compute-Engine.md)
        -  [Photon OS on GCE](gce.md)
    - [Running Project Photon on vCloud Air](Running-Project-Photon-on-vCloud-Air.md)        
- [Administration Guides](admin-guides.md)
    - [Photon OS Administration Guide](photon-admin-guide.md)
         - [Photon Management Daemon Command-line Interface (pmd-cli)](pmd-cli.md)
         - [Network Configuration Manager - C API](netmgr.c.md)
         - [Photon Network Manager Command-line Interface (netmgr)](netmgr-cli.md)
         - [Network Configuration Manager - Python API](netmgr.python.md)
         - [How to use Photon Management Daemon](pmd-cli.md)
         - [Managing Packages in Photon OS with tdnf](tdnf.md)
    - [Photon RPM OSTree](Photon-RPM-OSTree-a-simple-guide.md)
        1. [Introduction](Photon-RPM-OSTree-1-Introduction.md)  
            1. [What is OSTree? How about   RPM-OSTree?](Photon-RPM-OSTree-1-Introduction.md#11-what-is-ostree-how-about-rpm-ostree)
            1. [Why use RPM-OSTree in Photon?](Photon-RPM-OSTree-1-Introduction.md#12-why-use-rpm-ostree-in-photon)
            1. [Photon with RPM-OSTree installation profiles](Photon-RPM-OSTree-1-Introduction.md#13-photon-with-rpm-ostree-installation-profiles)
            1. [Terminology](Photon-RPM-OSTree-1-Introduction.md#14-terminology)
            1. [Sample code](Photon-RPM-OSTree-1-Introduction.md#15-sample-code)
            1. [How to read this book](Photon-RPM-OSTree:-1-Introduction#16-how-to-read-this-book)
            1. [RPM-OSTree in Photon OS 2.0](Photon-RPM-OSTree:-1-Introduction#17-rpm-ostree-in-photon-os-20)
        2. [Installing a Photon RPM-OSTree host against default server repository](Photon-RPM-OSTree-2-Installing-a-host-against-default-server-repository.md)  
            1. [Who is this for?](Photon-RPM-OSTree-2-Installing-a-host-against-default-server-repository.md#21-who-is-this-for)
            1. [Installing the ISO, step by step](Photon-RPM-OSTree-2-Installing-a-host-against-default-server-repository.md#22-installing-the-iso-step-by-step)
        3. [Concepts in action](Photon-RPM-OStree-3-Concepts-in-action.md)  
            1. [Querying the deployed   filetrees](Photon-RPM-OStree-3-Concepts-in-action.md#31-querying-the-deployed-filetrees)
            1. [Bootable filetree version](Photon-RPM-OStree-3-Concepts-in-action.md#32-bootable-filetree-version)
            1. [Commit ID](Photon-RPM-OStree-3-Concepts-in-action.md#33-commit-id)
            1. [OSname](Photon-RPM-OStree-3-Concepts-in-action.md#34-osname)
            1. [Refspec](Photon-RPM-OStree-3-Concepts-in-action.md#35-refspec)
            1. [Deployments](Photon-RPM-OStree-3-Concepts-in-action.md#36-deployments)
        4. [Querying for commit, file and package metadata](Photon-RPM-OSTree-4-Querying-for-commit-file-and-package-metadata.md)  
            1. [Commit history](Photon-RPM-OSTree-4-Querying-for-commit-file-and-package-metadata.md#41-commit-history)
            1. [Listing file mappings](Photon-RPM-OSTree-4-Querying-for-commit-file-and-package-metadata.md#42-listing-file-mappings)
            1. [Listing configuration changes](Photon-RPM-OSTree-4-Querying-for-commit-file-and-package-metadata.md#43-listing-configuration-changes)
            1. [Listing packages](Photon-RPM-OSTree-4-Querying-for-commit-file-and-package-metadata.md#44-listing-packages)
            1. [Querying for package details](Photon-RPM-OSTree-4-Querying-for-commit-file-and-package-metadata.md#45-querying-for-package-details)
            1. [Why am I unable to install, update or delete packages?](Photon-RPM-OSTree-4-Querying-for-commit-file-and-package-metadata.md#46-why-am-i-unable-to-install-update-or-delete-packages)
        5. [Host updating operations](Photon-RPM-OSTree-5-Host-updating-operations.md)  
            1. [Is it an update or an upgrade?](Photon-RPM-OSTree-5-Host-updating-operations.md#51-is-it-an-update-or-an-upgrade)
            1. [Incremental upgrade](Photon-RPM-OSTree-5-Host-updating-operations.md#52-incremental-upgrade)
            1. [Listing file differences](Photon-RPM-OSTree-5-Host-updating-operations.md#52-listing-file-differences)
            1. [Listing package differences](Photon-RPM-OSTree-5-Host-updating-operations.md#52-listing-package-differences)
            1. [Rollback](Photon-RPM-OSTree-5-Host-updating-operations.md#55-rollback)
            1. [Deleting a deployed filetree](Photon-RPM-OSTree-5-Host-updating-operations.md#56-deleting-a-deployed-filetree)
            1. [Version skipping upgrade](Photon-RPM-OSTree-5-Host-updating-operations.md#57-version-skipping-upgrade)
            1. [Tracking parent commits](Photon-RPM-OSTree-5-Host-updating-operations.md#58-tracking-parent-commits)
            1. [Resetting a branch to a previous commit](Photon-RPM-OSTree-5-Host-updating-operations.md#59-resetting-a-branch-to-a-previous-commit)
        6. [Installing a Photon RPM-OSTree server](Photon-RPM-OSTree-6-Installing-a-server.md)  
        7. [Installing a Photon RPM-OStree host against a custom server repository](Photon-RPM-OSTree-7-Installing-a-host-against-a-custom-server-repository.md)  
            1. [Manual install of a custom host](Photon-RPM-OSTree-7-Installing-a-host-against-a-custom-server-repository.md#71-manual-install-of-a-custom-host)
            1. [Automated install of a custom host via kickstart](Photon-RPM-OSTree-7-Installing-a-host-against-a-custom-server-repository.md#72-automated-install-of-a-custom-host-via-kickstart)
        8. [File oriented server operations](Photon-RPM-OStree-8-File-oriented-server-operations.md)
            1. [Starting a fresh OSTree repo](Photon-RPM-OStree-8-File-oriented-server-operations.md#81-starting-a-fresh-ostree-repo)
            1. [Checking out a filetree](Photon-RPM-OStree-8-File-oriented-server-operations.md#82-checking-out-a-filetree)
            1. [Committing changes to a filetree](Photon-RPM-OStree-8-File-oriented-server-operations.md#83-committing-changes-to-a-filetree)
            1. [Downloading the changes at the host](Photon-RPM-OStree-8-File-oriented-server-operations.md#84-downloading-the-changes-at-the-host)
            1. [Creating summary metadata](Photon-RPM-OStree-8-File-oriented-server-operations.md#85-creating-summary-metadata)
        9. [Package oriented server operations](Photon-RPM-OSTree-9-Package-oriented-server-operations.md)  
            1. [JSON configuration file](Photon-RPM-OSTree-9-Package-oriented-server-operations.md#91-json-configuration-file)
            1. [Package addition, removal, upgrade](Photon-RPM-OSTree-9-Package-oriented-server-operations.md#92-package-addition-removal-upgrade)
            1. [RPMS repository](Photon-RPM-OSTree-9-Package-oriented-server-operations.md#93-rpms-repository)
            1. [Composing a tree](Photon-RPM-OSTree-9-Package-oriented-server-operations.md#94-composing-a-tree)
            1. [Automatic version prefix](Photon-RPM-OSTree-9-Package-oriented-server-operations.md#95-automatic-version-prefix)
            1. [Installing package updates](Photon-RPM-OSTree-9-Package-oriented-server-operations.md#96-installing-package-updates)
            1. [Creating server metadata](Photon-RPM-OSTree-9-Package-oriented-server-operations.md#97-creating-server-metadata)
            1. [Starting a fresh OSTree repo](Photon-RPM-OSTree-9-Package-oriented-server-operations.md#98-starting-a-fresh-ostree-repo)
        10. [Remotes](Photon-RPM-OSTree-10-Remotes.md)  
            1. [Listing remotes](Photon-RPM-OSTree-10-Remotes.md#101-listing-remotes)
            1. [GPG signature verification](Photon-RPM-OSTree-10-Remotes.md#102-gpg-signature-verification)
            1. [Switching repositories](Photon-RPM-OSTree-10-Remotes.md#103-switching-repositories)
            1. [Adding and removing remotes](Photon-RPM-OSTree-10-Remotes.md#104-adding-and-removing-remotes)
            1. [List available branches](Photon-RPM-OSTree-10-Remotes.md#105-list-available-branches)
        11. [Running container applications between bootable images](Photon-RPM-OSTree-11-Running-container-applications-between-bootable-images.md)  
            1. [Downloading a docker container appliance](Photon-RPM-OSTree-11-Running-container-applications-between-bootable-images.md#111-downloading-a-docker-container-appliance)
            1. [Rebooting into an existing image](Photon-RPM-OSTree-11-Running-container-applications-between-bootable-images.md#112-rebooting-into-an-existing-image)
            1. [Reboot into a newly created image](Photon-RPM-OSTree-11-Running-container-applications-between-bootable-images.md#113-reboot-into-a-newly-created-image)
        12. [Install or rebase to Photon OS 2.0](Photon-RPM-OSTree-Install-or-rebase-to-Photon-OS-2.0.md)  
            1. [Installing an RPM-OSTree server](Photon-RPM-OSTree-Install-or-rebase-to-Photon-OS-2.0.md#121-installing-an-rpm-ostree-server)
            1. [Installing an RPM-OSTree host](Photon-RPM-OSTree-Install-or-rebase-to-Photon-OS-2.0.md#122-installing-an-rpm-ostree-host)
            1. [Rebasing a host from Photon 1.0 to 2.0](Photon-RPM-OSTree-Install-or-rebase-to-Photon-OS-2.0.md#123-rebasing-a-host-from-photon-10-to-20)
            1. [Creating a host raw image](Photon-RPM-OSTree-Install-or-rebase-to-Photon-OS-2.0.md#124-creating-a-host-raw-image)
    
            [Appendix A: Known issues](Photon-RPM-OSTree-Appendix-A-Known-issues.md)  
- [How-To Guides](how-to-guides.md)
    - [Setting Up a Swarm Cluster with DNS](Install-and-Configure-a-Swarm-Cluster-with-DNS-Service-on-PhotonOS.md)
    - [Setting Up a Mesos Cluster](Install-and-Configure-a-Production-Ready-Mesos-Cluster-on-Photon-OS.md)
    - [Setting Up Marathon for a Mesos Cluster](Install-and-Configure-Marathon-for-Mesos-Cluster-on-PhotonOS.md)
    - [Setting Up DCOS CLI for Mesos](Install-and-Configure-DCOS-CLI-for-Mesos.md)
    - [Setting Up Mesos DNS on a Mesos Cluster](Install-and-Configure-Mesos-DNS-on-a-Mesos-Cluster.md)
    - [Setting Up a Network PXE Boot Server](PXE-boot.md)
    - [Working with Kickstart](kickstart.md)
    - [Running Kubernetes](kubernetes.md)
    - [Mounting Remote File Systems](nfs-utils.md)
    - [Building Photon OS from the Source Code](build-photon.md)
    - [Installing and Using Lightwave on Photon OS](Installing-and-Using-Lightwave-on-Photon-OS.md)
        - [Installing the Lightwave Server and Configuring It as a Domain Controller on a Photon Image](Installing-Lightwave-Server-and-Setting-Up-a-Domain.md) 
        - [Installing the Lightwave Client on a Photon Image and Joining the Client to a Domain](Installing-Lightwave-Client-and-Joining-a-Domain.md)
        - [Installing the Photon Management Daemon on a Lightwave Client](Installing-the-Photon-Management-Daemon-on-a-Lightwave-Client.md)
        - [Remotely Upgrade a Single Photon OS Machine With Lightwave Client and Photon Management Daemon Installed](Remotely-Upgrade-a-Photon-OS-Machine-With-Lightwave-Client-and-Photon-Management-Daemon-Installed.md)
        - [Remotely Upgrade Multiple Photon OS Machines With Lightwave Client and Photon Management Daemon Installed](Remotely-Upgrade-Photon-OS-Machine-With-Lightwave-Client-and-Photon-Management-Daemon-Installed.md)
- [Troubleshooting](photon-os-troubleshooting-guide.md)
- [Frequently Asked Questions](Frequently-Asked-Questions.md)
* [Security Advisories](https://github.com/vmware/photon/wiki/Security-Advisories)