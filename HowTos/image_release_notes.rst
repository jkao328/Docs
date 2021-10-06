=======================================
Image Release Notes
=======================================

****Next Controller image is scheduled for November 2021****

****Next Gateway image is scheduled for November 2021****

Security Note for AWS Images
============================


`CVE-2018-16869 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-16869>`_


 
The Aviatrix Product Security team recommends you upgrade to the following AWS images to address known issues. The new images address multiple vulnerabilities ranked from low to high severity. None of the vulnerabilities are considered remotely exploitable in the normal usage of Aviatrix virtual appliances.

- Aviatrix Secure Networking Platform – BYOL, Version 122520 https://aws.amazon.com/marketplace/pp/prodview-nsys2ingy6m3w?sr=0-1&ref_=beagle&applicationId=AWS-Marketplace-Console.
- Copilot & 24x7 Support Aviatrix Secure Networking Platform Metered - Copilot & 24x7 Support, Version - 122520 https://aws.amazon.com/marketplace/pp/prodview-leh6ufnwbl6eo?sr=0-1&ref_=beagle&applicationId=AWS-Marketplace-Console.
- Aviatrix Secure Networking Platform - Enterprise Subscription, Version 122520 https://aws.amazon.com/marketplace/pp/prodview-35vvm63xuwsrw?sr=0-1&ref_=beagle&applicationId=AWSMPContessa.

Please replace your current AWS images during your next maintenance window. To replace your AWS images, follow the `upgrade migration process <https://docs.aviatrix.com/HowTos/image_release_notes.html#existing-customers-controller-image-upgrade-migration>`_. 
   
Detailed list of the affected packages included with the Aviatrix images:

- libzstd (`CVE-2021-24031 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-24031>`_, `CVE-2021-24032 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-24032>`_)
- Apport (`CVE-2021-32547 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32547>`_, `CVE-2021-32548 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32548>`_, `CVE-2021-32549 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32549>`_, `CVE-2021-32550 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32550>`_,
  `CVE-2021-32551 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32551>`_, `CVE-2021-32552 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32552>`_, `CVE-2021-32553 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32553>`_, `CVE-2021-32554 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32554>`_,
  `CVE-2021-32555 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32555>`_, `CVE-2021-32556 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32556>`_, `CVE-2021-32557 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32557>`_)
- Nettle (`CVE-2018-16869 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-16869>`_, `CVE-2021-3580 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-3580>`_, `CVE-2021-20305 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-20305>`_)
- systemd (`CVE-2020-13529 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-13529>`_, `CVE-2021-33910 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-33910>`_)
- PHP (`CVE-2020-7068, <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-7068>`_, `CVE-2021-21704 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-21704>`_, `CVE-2021-21705 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-21705>`_, `CVE-2020-7071 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-7071>`_, `CVE-2020-7072 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-7072>`_)
- OpenJDK (`CVE-2021-2163 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-2163>`_)
- curl (`CVE-2021-22898 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-22898>`_, `CVE-2021-22890 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-22890>`_, `CVE-2021-22924 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-22924>`_, `CVE-2021-22876 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-22876>`_, `CVE-2021-22925 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-22925>`_)
- DHCP (`CVE-2021-25217 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-25217>`_)
- Perl DBI (`CVE-2014-10402 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2014-10402>`_, `CVE-2020-14393 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-14393>`_)
- Pillow (`CVE-2021-25292 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-25292>`_, `CVE-2021-28675 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-28675>`_, `CVE-2021-28678 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-28678>`_, `CVE-2021-25290 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-25290>`_, 
  `CVE-2021-25291 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-25291>`_, `CVE-2021-25293 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-25293>`_, `CVE-2021-25291 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-25291>`_, `CVE-2021-27922 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-27922>`_,
  `CVE-2021-27923 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-27923>`_, `CVE-2021-28676 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-28676>`_, `CVE-2021-28677 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-28677>`_, `CVE-2021-25287 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-25287>`_, `CVE-2021-25288 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-25288>`_,
  `CVE-2021-25289 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-25289>`_)
- lxml (`CVE-2021-28957 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-28957>`_)
- libxml2 (`CVE-2021-3537 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3537>`_, `CVE-2021-3541 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3541>`_, `CVE-2019-20388 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-20388>`_, `CVE-2017-8872 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-8872>`_,
  `CVE-2020-24977 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-24977>`_, `CVE-2021-3516 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3516>`_, `CVE-2021-3517 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3517>`_, `CVE-2021-3518 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3518>`_)
- GD library (CVE-2021-38115 `CVE-2021-38115 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-38115>`_, `CVE-2021-40145 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-40145>`_, `CVE-2017-6363 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-6363>`_)
- Squashfs-Tools (`CVE-2021-41072 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-41072>`_, CVE-2021-40153`CVE-2021-41072 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-41072>`_)
- OpenSSH (`CVE-2016-10708 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-10708>`_, `CVE-2018-15473 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-15473>`_)
- libwebp (`CVE-2020-36332 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-36332>`_, `CVE-2018-25009 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-25009>`_, `CVE-2018-25010 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-25010>`_, `CVE-2018-25012 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-25012>`_, 
  `CVE-2018-25013 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-25013>`_, `CVE-2020-36330 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-36330>`_, `CVE-2020-36331 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-36331>`_, `CVE-2018-25011 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-25011>`_,
  `CVE-2018-25014 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-25014>`_, `CVE-2020-36328 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-36328>`_, `CVE-2020-36329 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-CVE-2020-36329>`_)
- Pygments (`CVE-2021-20270 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-20270>`_, `CVE-2021-27291 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-27291>`_)
- GLib (`CVE-2021-27218 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-27218>`_, `CVE-2021-27219 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-27219>`_, `CVE-2021-28153 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-28153>`_)
- Git (`CVE-2021-40330 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-40330>`_)
- LibTIFF (`CVE-2020-35523 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-35523>`_, `CVE-2020-35524 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-35524>`_)
- libsndfile (`CVE-2021-3246 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3246>`_)
- GNU cpio (`CVE-2021-38185 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-38185>`_)
- Python (`CVE-2020-27619 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-27619>`_, `CVE-2021-3177 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3177>`_)
- nginx (`CVE-2021-23017 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-23017>`_)
- Underscore (`CVE-2021-23358 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-23358>`_)
- GNU Screen (`CVE-2021-26937 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-26937>`_)
- xterm (`CVE-2021-27135 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-27135>`_)
- libx11 (`CVE-2021-31535 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-27135>`_)
- LZ4 (`CVE-2021-3520 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3520>`_)
- Libgcrypt (`CVE-2021-40528 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-40528>`_, `CVE-2021-33560 <https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-33560>`_)





Gateway Images: hvm-cloudx-aws- 022021, hvm-cloudx-aliyun-122520 (5/10/2021) 
====================================================================================================

- R6.4.2499 Software Version is required

- Support new IPSec encryption mechanism

- Update security patches to date 

- Introduced the gateway in AWS China and Ali Cloud

- Fix and pass vulnerabilities scan to Feb/2021


Controller Images: AWS AMI – 050120 (8/17/2020) 
===============================================

- R6.1.1280 Software Version is required

- Update Linux kernel and packages versions 

- Remove packages no longer used by the product 

- Set X-XSS-Protection and X-Content-Type-Options by default 

- Fix all vulnerabilities up to Jun/2020 (mid ref: 15727) 

Gateway Images: hvm-cloudx-aws-102320 (11/10/2020)
==================================================

- R6.2.1837 Software Version is required

- New image fetch mechanism 

- Update security patches to date 

- Linux Kernel update and package upgrade 

- New network drivers 

- Fix and pass vulnerabilities scan to Sep/2020 (mid ref: 18262) 

=======================================
Overview
=======================================

Aviatrix multi-cloud networking platform is delivered via two images, a Controller image and a gateway image,  
both should be maintained with the latest version for managing security 
and support for the product. Aviatrix intends to publish 2 new images per year.

New Customer Installation Procedures 
====================================

- Customer launches the Aviatrix Controller image instance in the AWS, Azure, or respective cloud marketplace.  

- Customer launches new gateways from the Controller. The Controller will automatically pull the latest compatible Gateway version.   

Existing Customers - Controller Image upgrade (Migration) 
=========================================================

- Customer is responsible for migrate their existing Controller to the latest image. See image list below.  

- To implement the **latest Controller image**, perform the following steps: 

  #. Go to your Controller management console 

  #. Go to Settings > Maintenance > Software Upgrade.  Make sure you are on the right software version for the migration. If not, upgrade your software version.  

  #. Go to Settings > Maintenance > Backup & Restore. Make sure you have a backup of your current settings.  

  #. Go to Settings > Maintenance > Migration. Migrate your controller to the latest image.  

  |controller_migration|

Note: Migrating your Controller does not impact your network data plane. Your existing Gateways should continue operating during migration.  

Existing Customers- Gateway Image upgrade 
===========================================

- To implement the **latest Gateway image**, perform the following steps: 

  #. Go to your Controller management console 

  #. Go to Troubleshoot > Diagnostics > Gateway -> Gateway Replace. Select each Gateway and click Replace. (`More info on  Gateway Replace operation <https://docs.aviatrix.com/HowTos/Troubleshoot_Diagnostics.html#gateway-replace>`_)

  |gateway_replace|


.. |controller_migration| image:: image_release_notes_media/controller_migration.png
   :scale: 50%

.. |gateway_replace| image:: image_release_notes_media/gateway_replace.png
   :scale: 50%

.. disqus::
