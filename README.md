# Awesome Minio [![Build Status](https://api.travis-ci.org/minio/awesome-minio.svg?branch=master)](https://travis-ci.org/minio/awesome-minio) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack](https://slack.minio.io/slack?type=svg)](https://slack.minio.io)

A curated list of Minio community projects inspired by [awesome-go](https://github.com/avelino/awesome-go).

## Contribution Guidelines
* Add entries alphabetically, under the appropriate category.
* To add, remove, or change things on the list: Submit a pull request.
* Description should contain a link with the name of the package/project/website.
* Do not exceed more than a paragraph.

### Cloud - PaaS
* [Cloudron](https://cloudron.io) - Cloudron is an open source platform that makes it easy to run web apps on your server and keep them up-to-date. The Cloudron also supports storing it's backups on Minio, you can read more [here](https://cloudron.io/blog/2016-12-13-minio-support.html). Minio itself has been packaged as a Cloudron App - you can try it from the [Cloudron App Store](https://cloudron.io/store/io.minio.cloudronapp.html) - [Source](https://git.cloudron.io/dswd/minio-app).
* [Jelastic](https://jelastic.com/) - Jelastic is a multi-cloud PaaS and CaaS for business. It uses Minio as an S3 compatible object storage server in Docker containers.
* [minio-dist-boshrelease](https://github.com/shinji62/minio-dist-boshrelease) - Cloud Foundry [BOSH](https://bosh.io) is an open source tool chain for release engineering, deployment and lifecycle management of large scale distributed services. minio-dist-boshrelease will help easily install the [distributed version of Minio](https://docs.minio.io/docs/distributed-minio-quickstart-guide).
* [minio-dokku](https://github.com/slypix/minio-dokku) - Dockerfile to run Minio on [Dokku](http://dokku.viewdocs.io/dokku/) PaaS.
* [sloppy.io](https://sloppy.io/) - sloppy.io is the fastest way to deploy your docker container online. We provide the infrastructure and workflow to run container applications and micro services. Access our platform over the web, via CLI or our own API. Check out [Deploying Minio to sloppy.io](https://sloppy.io/deploying-minio-to-sloppy-io/) for further info! 


### Cloud - IaaS
* [Deis Workflow](https://deis.com/workflow/) - an open source Platform-as-a-Service for [Kubernetes](https://kubernetes.io/). Workflow uses Minio by default to store all internal application metadata and database backups.
* [Digital Ocean](https://www.digitalocean.com) - Deploy an SSD cloud server in 55 seconds.
* [Eucalyptus](http://www.dxc.technology/cloud/offerings/140041/140149-eucalyptus_software_support_services) - Eucalyptus is an open solution to build private and hybrid clouds that are compatible with Amazon Web Services. Minio can be [used](https://mdshaonimran.wordpress.com/category/cloud-computing/eucalyptus/) as an object storage backend for Eucalyptus.
* [Ha-Minio](https://github.com/bryanl/ha-minio) - Configures Minio, as a S3 compatible cloud storage server for DigitalOcean in a highly available fashion.
* [Onlinetech](http://www.onlinetech.com) - Secure, compliant enterprise cloud.
* [OVH](https://www.ovh.com/us/) - Build your own infrastructure with OVH public cloud..
* [Packet](https://www.packet.net) - Packet is a baremetal cloud provider.
* [Plumbery](http://plumbery.readthedocs.io/en/latest/tutorial.minio.html) -  Plumbery is an open source project that was initiated by Dimension Data to accelerate digital transformation. It recommends using Minio as a standalone object storage.
* [s3-tus-store](https://github.com/blockai/s3-tus-store) - Minio is the supported storage backend for [https://tus.io/](https://tus.io/). Tus is an open protocol for resumable file uploads.
* [ScaleWay](https://www.scaleway.com) - Scalable and affordable cloud and bare-metal servers (European DC).
* [SSD Nodes](https://www.ssdnodes.com/) - Simple, high performance cloud provider with truly personalized support.

### DevOps - CI/CD
* [drone.io](https://github.com/drone/drone) - drone.io is continuous integration for Github and Bitbucket, that monitors your code for bugs. It uses Minio as an AWS S3 cloud storage alternative.
* [Gorbachev IO](https://www.dragonfly.co.nz/) - Gorbachev is a continuous integration platform, used to manage reproducible research at Dragonfly Data Science. Minio tools are awesome, and the community is supportive and responsive.
* [mkrepo](https://github.com/tarantool/mkrepo) - maintains an RPM or DEB repository in S3, and periodically regenerates metadata. You can use Minio as a convenient and inexpensive storage for your CI.
* [s3-resource-simple](https://github.com/making/s3-resource-simple) - s3-resource-simple is [Concourse CI's](https://concourse.ci/) resource for uploading files to S3. It supports Minio as an object storage backend.
* [puppet-minio](https://github.com/kogitoapp/puppet-minio) - Puppet module to manage Minio installations. Uses the binary, does not (yet) support Docker based installation. (Requires Puppet version 4+)

### Cloud/SaaS Applications
* [Appknox](https://www.appknox.com/) - Appknox detects & addresses vulnerabilities in mobile apps within minutes. Managing storage was a nightmare for us before Minio came along. We use Minio to store all our ipa/apk files and pdf reports that gets auto-nenerated. We are an enterprise startup and we offer on-premise and private-cloud installations of our cloud-based scanner. We have deployed our code base on AWS, Google, Azure, multiple on-premise installations and private cloud. Before Mino came along - we had to write and maintain Python libraries for each platform and maintain them. Some of the changes that we make cannot be even tested - because it is deployed on-premise which we dont have access to. Thankfully, we came across Minio. Now we just install minio everywhere and forget about storage. Minio Rocks!
* [Blockai](https://blockai.com/) - Blockai helps artists claim their copyrights and protects them, for free. It uses Minio for all internal development and testing as an AWS S3 compatible object storage service.
* [CODECASTS](https://codecasts.com.br/lesson) - A Brazilian e-learning platform for developers, uses Minio to serve and scale its video traffic.
* [Cosmic App](https://cosmicapp.co.uk/login) - Cosmic App uses Minio for storing client files and quote information for commercial brokers. Files are packaged up for lenders including high street banks to access securely.
* [Crisp](https://crisp.im/en/) - Crisp is a Customer Intelligence Platform. It helps teams know, understand and communicate with their customers, from multiple channels (chat, email). Minio is used to securely store user file uploads. Files are uploaded from the chatbox, operator dashboard and email attachments. Minio completely replaces S3 and brings more control to user data safety.
* [dapploy](https://dapploy.io/) - dapploy is a solution to create private app stores to deploy iOS and Android applications to your team, company or organization. Minio is easily integrated with dapploy's architecture and docker environment. Minio is used to store application packages - ipas, apks, icons and images. Minio's great feature among others is the ability to have presigned urls while downloading resources. We use that a lot. Thanks for your good documentation and community.
* [DBHub.io](https://dbhub.io) - Online storage, visualisation, and collaboration for SQLite databases.  Uses Minio as the primary object store for holding them.
* [GitLab](https://gitlab.com/users/sign_in) - GitLab is an open source software to collaborate on code.  It uses Minio to store objects in their caching server.
* [Mattermost](https://about.mattermost.com/) - Mattermost is an open source, self-hosted Slack alternative. It uses minio-go fully to handle S3 API requests.
* [Pathio](https://www.pathio.com) - Pathio is a version control system for Excel. It uses Minio as an on-premise storage backend for workbooks and json blobs.
* [QuezX](https://quezx.com/) - QuezX is a recruitment aggregator for connecting employers to recruitment agencies. It uses Minio to store and manage CV's and other documents on their platform.
* [Trustvox](http://site.trustvox.com.br) - Trustvox is an integrator of ecommerce platforms, ensures 100% valid product reviews, allowing only real buyers to post reviews along with a continuous audit process. The platform team chose Minio to create its own S3 service to avoid infrastructure vendor lock-in, obtaining transparent compatibility with Google Cloud Storage and previous Amazon S3 infrastructures. We tested other options before, and only Minio showed the stable and enterprise-grade results we were looking for.
* [www.houbank.com](https://www.houbank.com/home/) - Houbank uses Minio as a simple, reliable and compatible self-host AWS S3 alternative. Houbank uses Minio to upload user files and exchange documents in internal applications/jobs.
* [Rocket.Chat](https://rocket.chat/) - Rocket.Chat is a completely FOSS alternative to Slack. In Rocket.Chat Minio can be used for file uploads — this applies to channels, groups and privately between one user and another.

### Content Management System
* [Simple Simple Ads](https://simplesimple.ca) - uses Minio as a compatible object storage server replacement in our development environment. Multiple developers share a local repository of files transparently without having to change any site configuration. This makes developing with [Drupal](https://www.drupal.org/) and the [s3fs](https://www.drupal.org/project/s3fs) modules very easy. File changes are staged locally and then migrated to Amazon S3 after approval using the mc client utility.

### Application Development Services
* [C0D1UM](http://www.codium.co) - C0D1UM is a software development firm doing projects on demand and offering operating system infrastructure support. We use `minio` to secure all confidential data in private network. It was a first choice because major functions are compatible with AWS S3 standard functions.
* [Collaborne](https://github.com/Collaborne) - Collaborne uses Minio docker containers in development environments to simulate a full AWS S3 environment.
* [nxsol](http://nxsol.com/) - nxsol specializes in the development of desktop and web-based businesses and personal applications. It uses minio-java client library for Amazon S3 related applications.
* [ToolsLib](https://toolslib.net) - ToolsLib provides project management services including software hosting for millions of users. Minio fits perfectly in the current infrastructure: its ability to easily scale is a crucial point for ToolsLib services.

### Cloud Backup / Versioning
* [Arq](https://www.arqbackup.com) - Arq is a storage backend agnostic backup tool for Mac and Windows. Backend services include Amazon Cloud Drive, Google Drive, Dropbox, One Drive, Amazon S3 and more. It also supports 'Other S3-Compatible Services' which means that you can use Minio to build your own backend.
* [BackupHive](https://www.backuphive.nl) - Providing online backup services from The Netherlands with Minio as an S3 compatible back-end server to store and retrieve files. Minio is very scalable, uses almost no resources itself and is easy to maintain. The awesome team has a strong combined knowledge of use-cases, ranging from the smallest personal project to large scale cross-datacenter setups, all available within a comfortable community.
* [CloudBerry Backup](https://www.cloudberrylab.com/backup/windows-server.aspx) - CloudBerry Backup is used to store files, folders and system images to cloud storage providers. CloudBerry uses Minio for standalone, online and managed backup service.
* [Duplicati](https://www.duplicati.com) - Duplicati is free, open source, backup software that implements full encryption, compression, and de-duplication that fully obscures backup contents from data hosting providers. It supports S3-compatible services, allowing Minio to server as the backend storage.
* [rclone](https://rclone.org/) - "rsync for cloud storage".  Rclone is a command line application to sync files to and from cloud storage systems and it works well with Minio. Check out [rclone's s3 docs](https://rclone.org/s3/) for more information.
* [restic](https://restic.github.io) - restic is a backup program that is fast, efficient and secure. Check [the documentation](http://restic.readthedocs.io/en/latest/manual.html#minio-server) for instructions on how to backup to a Minio server using restic.
* [s3git](https://github.com/s3git/s3git) - git for cloud storage. s3git provides distributed version control for data. Create decentralized and versioned repos that scale infinitely to 100s of millions of files. Clone huge PB-scale repos on your local SSD to make changes, commit and push back. Check out [s3git docs](https://github.com/s3git/s3git/blob/master/README.md#integration-with-minio) for more information.

### Cloud Storage Clients
* [Cloud Explorer](https://github.com/rusher81572/cloudExplorer) - Cloud Explorer is an open source client written in Java and runs on any OS. It has many unique features such as a a text editor, performance testor, image viewer, search, bucket migrations, music player, IRC client, and much more.
* [Cyberduck](https://cyberduck.io/) - Cyberduck is an open source client for FTP and SFTP, WebDAV, OpenStack Swift, and Amazon S3, available on Mac OS X and Windows. It supports Minio as an AWS S3 compatible storage.
* [Mountain Duck](https://mountainduck.io/) - Mountain Duck lets you mount a server and cloud storage as a local disk within the Finder app on Mac and the File Explorer app on Windows. It supports Minio as an AWS S3 compatible storage.

### Web Application Framework
* [Django-Minio](https://github.com/maddevsio/django_minio) - Django is a popular Python web framework. Django-Minio plugin enables use of Minio as an AWS S3 replacement.
* [Minio-Play-Rest-API](https://github.com/s4kibs4mi/minio-play-rest-api) - Rest API for Minio ( AWS S3 compatible object storage server ) based on Java Play Framework 2.

### Minio as Managed Service
* [Apcera](https://docs.apcera.com/services/types/service-minio/) - Apcera offers a Minio service gateway to their users. Minio enables Apcera users to spin up a persistent, S3 compatible datastore on any infrastructure with just a single command. Minio provides an open source  AWS S3 alternative for Apcera users.

### Compatible Hardware
* [Cisco UCS C240 M4 Rack Server](http://www.cisco.com/c/en/us/products/servers-unified-computing/ucs-c240-m4-rack-server/index.html) - Cisco 2U DP E5-2600v3 platform with 12x 3.5” drive bays
* [Intel® Server System R2312WTTYSR](http://ark.intel.com/products/88286) - Intel 2U DP E5-2600v3 platform with 12x 3.5” drive bays
* [Quanta Grid D51B-2U (OCP Compliant) ](https://www.hyperscalers.com/quanta-qct-server-1u-quantagrid-d51b-2u-buy-quantagridd51b2u-distribution-buy-usa-aus) - Quanta 2U DP E5-2600v3 platform with 12x 3.5” drive bays
* [SMC 5018A-AR12L (Intel Atom)](http://www.supermicro.com/products/system/1U/5018/SSG-5018A-AR12L.cfm?parts=SHOW) - SMC 1U SoC Atom C2750 platform with 12x 3.5” drive bays
