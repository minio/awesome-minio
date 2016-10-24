# Awesome Minio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/minio/minio?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A curated list of Minio community projects inspired by [awesome-go](https://github.com/avelino/awesome-go).

## Contribution Guidelines
* To add, remove, or change things on the list: Submit a pull request.
* Latest entries are added to the top, just below the sample text.
* The link should be the name of the package or project or a link to your website.
* Description should not exceed more than two lines.


## Contents

### Awesome Projects
List of projects bundling Minio server in it's stack.
 

### Awesome Use Cases
List of projects using Minio server to store their data.
* [dapploy](https://dapploy.io/) - dapploy is a solution to create private app stores to deploy your iOS and Android applications to your team, company or organization. Minio is easily integrated with our architecture and docker environment. Minio is used to store application packages ipa and apk, icons and images. Minio's great features among others is to have presigned url while downloading resources and we use that a lot. Thanks for your good documentation and community around it.
* [Cosmic App](https://cosmicapp.co.uk) - Cosmic App uses Minio for storing files and quote for commercial brokers about their clients, files are packaged up for lenders including high street banks to access securely.
* [Collaborne](https://github.com/Collaborne) - Collaborne uses Minio docker containers in their development environments to simulate a full AWS S3 environment.
* [GitLab](https://gitlab.com) - GitLab is open source software to collaborate on code.  It uses Minio for storing object for their caching server.
* [drone.io](https://drone.io/) - drone.io is continuous integration for Github and Bitbucket that monitors your code for bugs. It supports  Minio as AWS S3 cloud storage alternative.
* [CloudBerry Backup](http://www.cloudberrylab.com/best-bare-metal-backup-software.aspx) - CloudBerry Backup is used for storing  files, folders and system image to the cloud storage providers. It uses Minio for Standalone, Online and Managed Backup Service. 
* [Plumbery](http://plumbery.readthedocs.io/en/latest/tutorial.minio.html) -  Plumbery is an Open Source project that was initiated by Dimension Data to accelerate the digital transformation. It recommends Minio as Standalone Object Storage.
* [Jelastic](https://jelastic.com/) - Jelastic is a Multi-Cloud PaaS and CaaS for Business. It uses Minio as compatible object storage server in Docker containers.
* [QuezX](https://quezx.com/) - QuezX is a recruitment aggregator for connecting employers to recruitment agencies. It uses Minio to store and manage all the CV's and all other documents of the platform. 
* [nxsol](http://nxsol.com/index.html) - nxsol specializes in the development of desktop and web-based business and personal applications. It uses minio-java client library for Amazon S3 related applications.
* [Blockai](https://blockai.com/) - Blockai  helps artists claim their copyrights and protect them for free. It uses Minio for all internal dev and testing for AWS S3 compatible service.
* [Ramcloud](https://ramcloud.io) - Ramcloud is a hosting service provider. It uses Minio with CDN to host backups, machine images, etc.
* [Deis](https://deis.com) - Deis is an open source Platform as a Service for use with [Kubernetes](http://kubernetes.io/). It uses Minio by default for all internal application metadata storage, as well as the store for database backups.
* [Pathio](https://www.pathio.com) - Pathio is a version control system for Excel, using minio as the on-premise storage backend for workbooks and json blobs. 
* [Gorbachev IO](https://dragonfly.co.nz) - Gorbachev is a continuous integration platform, used for managing reproducible research at Dragonfly Data Science. The minio tools are awesome, and the community is supportive and responsive. 
* [CODECASTS](https://codecasts.com.br) - A Brazilian e-learning platform for developers, using minio to serve and scale it's video traffic.
* [Appknox](https://www.appknox.com/) - Appknox detects & addresses vulnerabilities in mobile apps within minutes. Managing storage was a nightmare for us before Minio came along. We use Minio to store all our ipa/apk files and pdf reports that gets auto-nenerated. We are an Enterprise startups and offer On-Premise and Private-Cloud installations of our cloud-based scanner. We have deployed our code base on AWS, Google, Azure, multiple On-Premise installations and Private Cloud. Before Mino came along - we had to write and maintain Python libraries for each platform and maintain it. Some of the changes that we make cannot be even tested - because its deployed on-premise where we dont have access to. Thankfully, we came across Minio. Now we just install minio everywhere and forget about storage. Minio Rocks!
* [BackupHive](https://www.backuphive.nl) - Providing online backup services from The Netherlands with Minio as a back-end S3 compatible server for storage and retrieval of files. Minio is very scalable, uses almost no resources itself and is easy to maintain. The awesome team has a strong combined knowledge of use-cases, ranging from the smallest personal project to large scale cross-datacenter setups, all available within a comfortable community.
* [mkrepo](https://github.com/tarantool/mkrepo) - maintain an RPM or DEB repository in S3, and periodically regenerate metadata. You can use Minio as a convenient and inexpensive storage for your CI.
* [Trustvox](http://trustvox.com.br) - Trustvox is an integrator to ecommerce platforms that ensure 100% of valid product reviews, allowing only real buyers to post a review along with a continuous audit process. The platform team chooses Minio to create its own S3 service to avoids infrastructure vendor lock-in, obtaining transparent compatibility with Google Cloud Storage and Amazon S3 previous infrastructures. We tested other options before, and only Minio showed stable and enterprise-grade results we was looking for.

### Awesome Tools
List of tools and software supporting Minio with it.
* [s3-tus-store](https://github.com/blockai/s3-tus-store) - Minio is supported storage backend for [https://tus.io/](https://tus.io/)  
* [Cyberduck](https://cyberduck.io/) - Cyberduck is an open source client for FTP and SFTP, WebDAV, OpenStack Swift, and Amazon S3, available for Mac OS X and Windows. It supports Minio as AWS S3 compatible storage.
* [Mountain Duck](https://mountainduck.io/) - Mountain Duck lets you mount server and cloud storage as a local disk in the Finder.app on Mac and the File Explorer on Windows. It supports Minio as AWS S3 compatible storage.
* [restic](https://restic.github.io) - restic is a backup program that is fast, efficient and secure. Check [the documentation](http://restic.readthedocs.io/en/latest/Manual/#create-a-minio-server-repository) for instructions on how to backup to a Minio server.
* [rclone](http://rclone.org) - "rsync for cloud storage".  Rclone is a command application to sync files to and from cloud storage systems and it works well with Minio. Check out [rclone's s3 docs](http://rclone.org/s3/) to see how.
* [s3git](https://github.com/s3git/s3git) - git for Cloud Storage. Distributed Version Control for Data. Create decentralized and versioned repos that scale infinitely to 100s of millions of files. Clone huge PB-scale repos on your local SSD to make changes, commit and push back.s3 docs](http://rclone.org/s3/) to see how.
* [Django-Minio](https://github.com/maddevsio/django_minio) - Django is popular Python web framework, Django-Minio plugin enables use of Minio as AWS S3 replacement.
* [Ha-Minio](https://github.com/bryanl/ha-minio) - Configure Minio, as a S3 compatible Cloud Storage Server for DigitalOcean in a highly available fashion.


### Awesome Cloud
List of public cloud services recommended for Minio deployments.
* [Packet](https://www.packet.net) - Packet is the baremetal cloud provider. 
* [Digital Ocean](https://www.digitalocean.com) - Deploy an SSD cloud server in 55 seconds.
* [SSD Nodes](https://www.ssdnodes.com/) - Simple, high performance cloud provider with truly personalized support.
* [OVH](https://www.ovh.com/us) - Build your own infrastructure with OVH public cloud.. 
* [Onlinetech](http://www.onlinetech.com) - Secure, compliant enterprise cloud.
* [ScaleWay](https://www.scaleway.com) - Scalable and affordable cloud and bare-metal servers (European DC).


### Awesome Hardware
List of compatible hardware platform recommended for Minio deployments.
* [SMC 5018A-AR12L (Intel Atom)](http://www.supermicro.com/products/system/1U/5018/SSG-5018A-AR12L.cfm?parts=SHOW) - SMC 1U SoC Atom C2750 platform with 12x 3.5” drive bays
* [Quanta Grid D51B-2U (OCP Compliant) ](http://www.qct.io/Product/Servers/Rackmount-Servers/2U/QuantaGrid-D51B-2U-p256c77c70c83c118)- Quanta 2U DP E5-2600v3 platform with 12x 3.5” drive bays
* [Cisco UCS C240 M4 Rack Server](http://www.cisco.com/c/en/us/products/servers-unified-computing/ucs-c240-m4-rack-server/index.html) - Cisco 2U DP E5-2600v3 platform with 12x 3.5” drive bays
* [Intel® Server System R2312WTTYSR](http://ark.intel.com/products/88286) - Intel 2U DP E5-2600v3 platform with 12x 3.5” drive bays

