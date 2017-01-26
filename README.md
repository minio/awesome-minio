# Awesome Minio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/minio/minio?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A curated list of Minio community projects inspired by [awesome-go](https://github.com/avelino/awesome-go).

## Contribution Guidelines
* Add entries alphabetically, under the appropriate category.
* To add, remove, or change things on the list: Submit a pull request.
* Description should contain a link with the name of the package/project/website.
* Do not exceed more than a paragraph.

### Cloud - PaaS
* [minio-dokku](https://github.com/slypix/minio-dokku) - Dockerfile to run Minio on [Dokku](http://dokku.viewdocs.io/dokku/) PaaS.
* [minio-dist-boshrelease](https://github.com/shinji62/minio-dist-boshrelease) - Cloud Foundry [BOSH](https://bosh.io) is an open source tool chain for release engineering, deployment and lifecycle management of large scale distributed services. minio-dist-boshrelease will help easily install the [distributed version of Minio](https://docs.minio.io/docs/distributed-minio-quickstart-guide).
* [Jelastic](https://jelastic.com/) - Jelastic is a multi-cloud PaaS and CaaS for business. It uses Minio as an S3 compatible object storage server in Docker containers.

### Cloud - IaaS
* [Digital Ocean](https://www.digitalocean.com) - Deploy an SSD cloud server in 55 seconds.
* [Deis Workflow](https://deis.com/workflow/) - an open source Platform-as-a-Service for [Kubernetes](http://kubernetes.io/). Workflow uses Minio by default to store all internal application metadata and database backups.
* [Eucalyptus](http://www.eucalyptus.com) - Eucalyptus is an open solution to build private and hybrid clouds that are compatible with Amazon Web Services. Minio can be used as an object storage backend for Eucalyptus.
* [Ha-Minio](https://github.com/bryanl/ha-minio) - Configures Minio, as a S3 compatible cloud storage server for DigitalOcean in a highly available fashion.
* [Packet](https://www.packet.net) - Packet is a baremetal cloud provider.
* [Plumbery](http://plumbery.readthedocs.io/en/latest/tutorial.minio.html) -  Plumbery is an open source project that was initiated by Dimension Data to accelerate digital transformation. It recommends using Minio as a standalone object storage.
* [Ramcloud](https://ramcloud.io) - Ramcloud is a hosting service provider. It uses Minio with a CDN to host backups, machine images, etc.
* [SSD Nodes](https://www.ssdnodes.com/) - Simple, high performance cloud provider with truly personalized support.
* [s3-tus-store](https://github.com/blockai/s3-tus-store) - Minio is the supported storage backend for [https://tus.io/](https://tus.io/). Tus is an open protocol for resumable file uploads.
* [ScaleWay](https://www.scaleway.com) - Scalable and affordable cloud and bare-metal servers (European DC).
* [OVH](https://www.ovh.com/us) - Build your own infrastructure with OVH public cloud..
* [Onlinetech](http://www.onlinetech.com) - Secure, compliant enterprise cloud.

### DevOps - CI/CD
* [drone.io](https://drone.io/) - drone.io is continuous integration for Github and Bitbucket, that monitors your code for bugs. It uses Minio as an AWS S3 cloud storage alternative.
* [Gorbachev IO](https://dragonfly.co.nz) - Gorbachev is a continuous integration platform, used to manage reproducible research at Dragonfly Data Science. Minio tools are awesome, and the community is supportive and responsive.
* [mkrepo](https://github.com/tarantool/mkrepo) - maintains an RPM or DEB repository in S3, and periodically regenerates metadata. You can use Minio as a convenient and inexpensive storage for your CI.
* [s3-resource-simple](https://github.com/making/s3-resource-simple) - s3-resource-simple is [Concourse CI's](https://concourse.ci/) resource for uploading files to S3. It supports Minio as an object storage backend.

### Cloud/SaaS Applications
* [Appknox](https://www.appknox.com/) - Appknox detects & addresses vulnerabilities in mobile apps within minutes. Managing storage was a nightmare for us before Minio came along. We use Minio to store all our ipa/apk files and pdf reports that gets auto-nenerated. We are an enterprise startup and we offer on-premise and private-cloud installations of our cloud-based scanner. We have deployed our code base on AWS, Google, Azure, multiple on-premise installations and private cloud. Before Mino came along - we had to write and maintain Python libraries for each platform and maintain them. Some of the changes that we make cannot be even tested - because it is deployed on-premise which we dont have access to. Thankfully, we came across Minio. Now we just install minio everywhere and forget about storage. Minio Rocks!
* [Blockai](https://blockai.com/) - Blockai helps artists claim their copyrights and protects them, for free. It uses Minio for all internal development and testing as an AWS S3 compatible object storage service.
* [Cosmic App](https://cosmicapp.co.uk) - Cosmic App uses Minio for storing client files and quote information for commercial brokers. Files are packaged up for lenders including high street banks to access securely.
* [Crisp](https://crisp.im/) - Crisp is a Customer Intelligence Platform. It helps teams know, understand and communicate with their customers, from multiple channels (chat, email). Minio is used to securely store user file uploads. Files are uploaded from the chatbox, operator dashboard and email attachments. Minio completely replaces S3 and brings more control to user data safety.
* [CODECASTS](https://codecasts.com.br) - A Brazilian e-learning platform for developers, uses Minio to serve and scale its video traffic.
* [dapploy](https://dapploy.io/) - dapploy is a solution to create private app stores to deploy iOS and Android applications to your team, company or organization. Minio is easily integrated with dapploy's architecture and docker environment. Minio is used to store application packages - ipas, apks, icons and images. Minio's great feature among others is the ability to have presigned urls while downloading resources. We use that a lot. Thanks for your good documentation and community.
* [DBHub.io](https://dbhub.io) - Online storage, visualisation, and collaboration for SQLite databases.  Uses Minio as the primary object store for holding them.
* [GitLab](https://gitlab.com) - GitLab is an open source software to collaborate on code.  It uses Minio to store objects in their caching server.
* [www.houbank.com](https://www.houbank.com) - Houbank uses Minio as a simple, reliable and compatible self-host AWS S3 alternative. Houbank uses Minio to upload user files and exchange documents in internal applications/jobs.
* [Pathio](https://www.pathio.com) - Pathio is a version control system for Excel. It uses Minio as an on-premise storage backend for workbooks and json blobs.
* [Mattermost](https://www.mattermost.org/) - Mattermost is an open source, self-hosted Slack alternative. It uses minio-go fully to handle S3 API requests.
* [QuezX](https://quezx.com/) - QuezX is a recruitment aggregator for connecting employers to recruitment agencies. It uses Minio to store and manage CV's and other documents on their platform.
* [Trustvox](http://trustvox.com.br) - Trustvox is an integrator of ecommerce platforms, ensures 100% valid product reviews, allowing only real buyers to post reviews along with a continuous audit process. The platform team chose Minio to create its own S3 service to avoid infrastructure vendor lock-in, obtaining transparent compatibility with Google Cloud Storage and previous Amazon S3 infrastructures. We tested other options before, and only Minio showed the stable and enterprise-grade results we were looking for.

### Content Management System
* [Simple Simple Ads](https://simplesimple.ca) - uses Minio as a compatible object storage server replacement in our development environment. Multiple developers share a local repository of files transparently without having to change any site configuration. This makes developing with [Drupal](https://www.drupal.org/) and the [s3fs](https://www.drupal.org/project/s3fs) modules very easy. File changes are staged locally and then migrated to Amazon S3 after approval using the mc client utility.

### Application Development Services
* [Collaborne](https://github.com/Collaborne) - Collaborne uses Minio docker containers in development environments to simulate a full AWS S3 environment.
* [nxsol](http://nxsol.com/index.html) - nxsol specializes in the development of desktop and web-based businesses and personal applications. It uses minio-java client library for Amazon S3 related applications.
* [C0D1UM] (http://www.codium.co) - C0D1UM is a software development firm doing projects on demand and offering operating system infrastructure support. We use `minio` to secure all confidential data in private network. It was a first choice because major functions are compatible with AWS S3 standard functions.

### Cloud Backup / Versioning
* [BackupHive](https://www.backuphive.nl) - Providing online backup services from The Netherlands with Minio as an S3 compatible back-end server to store and retrieve files. Minio is very scalable, uses almost no resources itself and is easy to maintain. The awesome team has a strong combined knowledge of use-cases, ranging from the smallest personal project to large scale cross-datacenter setups, all available within a comfortable community.
* [CloudBerry Backup](http://www.cloudberrylab.com/best-bare-metal-backup-software.aspx) - CloudBerry Backup is used to store files, folders and system images to cloud storage providers. CloudBerry uses Minio for standalone, online and managed backup service.
* [restic](https://restic.github.io) - restic is a backup program that is fast, efficient and secure. Check [the documentation](http://restic.readthedocs.io/en/latest/Manual/#create-a-minio-server-repository) for instructions on how to backup to a Minio server using restic.
* [rclone](http://rclone.org) - "rsync for cloud storage".  Rclone is a command line application to sync files to and from cloud storage systems and it works well with Minio. Check out [rclone's s3 docs](http://rclone.org/s3/) for more information.
* [s3git](https://github.com/s3git/s3git) - git for cloud storage. s3git provides distributed version control for data. Create decentralized and versioned repos that scale infinitely to 100s of millions of files. Clone huge PB-scale repos on your local SSD to make changes, commit and push back. Check out [s3 docs](http://rclone.org/s3/) for more information.

### Cloud Storage Clients
* [Cyberduck](https://cyberduck.io/) - Cyberduck is an open source client for FTP and SFTP, WebDAV, OpenStack Swift, and Amazon S3, available on Mac OS X and Windows. It supports Minio as an AWS S3 compatible storage.
* [Mountain Duck](https://mountainduck.io/) - Mountain Duck lets you mount a server and cloud storage as a local disk within the Finder app on Mac and the File Explorer app on Windows. It supports Minio as an AWS S3 compatible storage.

### Web Application Framework
* [Django-Minio](https://github.com/maddevsio/django_minio) - Django is a popular Python web framework. Django-Minio plugin enables use of Minio as an AWS S3 replacement.

### Minio as Managed Service
* [Apcera](https://docs.apcera.com/services/types/service-minio/) - Apcera offers a Minio service gateway to their users. Minio enables Apcera users to spin up a persistent, S3 compatible datastore on any infrastructure with just a single command. Minio provides an open source  AWS S3 alternative for Apcera users.

### Compatible Hardware
* [SMC 5018A-AR12L (Intel Atom)](http://www.supermicro.com/products/system/1U/5018/SSG-5018A-AR12L.cfm?parts=SHOW) - SMC 1U SoC Atom C2750 platform with 12x 3.5” drive bays
* [Quanta Grid D51B-2U (OCP Compliant) ](http://www.qct.io/Product/Servers/Rackmount-Servers/2U/QuantaGrid-D51B-2U-p256c77c70c83c118)- Quanta 2U DP E5-2600v3 platform with 12x 3.5” drive bays
* [Cisco UCS C240 M4 Rack Server](http://www.cisco.com/c/en/us/products/servers-unified-computing/ucs-c240-m4-rack-server/index.html) - Cisco 2U DP E5-2600v3 platform with 12x 3.5” drive bays
* [Intel® Server System R2312WTTYSR](http://ark.intel.com/products/88286) - Intel 2U DP E5-2600v3 platform with 12x 3.5” drive bays
