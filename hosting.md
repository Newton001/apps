---

copyright:
  years: 2017, 2019
lastupdated: "2019-03-29"

keywords: apps, application, migrating apps, hosting apps, migrating, hosting, migration

subcollection: creating-apps

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Migrating and hosting apps
{: #hosting}

If you have an existing app, you can host it on {{site.data.keyword.cloud}} with all the infrastructure or platform services you need. You can also migrate your app to {{site.data.keyword.cloud_notm}} incrementally instead of shifting your app to the cloud environment all at once.

## Migrating apps
{: #migrating}

If you need your app to access your on-premises data or services, you can use [{{site.data.keyword.SecureGatewayfull}}](/docs/services/SecureGateway?topic=securegateway-getting-started-with-sg#getting-started-with-sg) to establish a secured tunnel between an {{site.data.keyword.cloud_notm}} organization and your enterprise backend network. For details, see [Reaching enterprise backend with {{site.data.keyword.cloud_notm}} Secure Gateway via console](https://developer.ibm.com/bluemix/2015/04/01/reaching-enterprise-backend-bluemix-secure-gateway/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon").

If you need help with your migration, [{{site.data.keyword.cloud_notm}} Migration Services](https://www.ibm.com/cloud/migration-services){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") are available.

## Hosting apps
{: #ht_hostapp}

In the {{site.data.keyword.cloud_notm}} [catalog](https://{DomainName}/catalog/?taxonomyNavigation=apps){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"), you can choose a managed environment like Kubernetes or Cloud Foundry, or can you host your app directly on a bare metal or virtual server.

On a virtual deployment, most of your app's operations are managed by {{site.data.keyword.cloud_notm}}. A [virtual](/docs/vsi?topic=virtual-servers-about-virtual-servers#about-virtual-servers) deployment is best if your workload is spread out across geographic regions and you want to use an {{site.data.keyword.cloud_notm}} hypervisor to manage your deployments. A [bare metal](/docs/bare-metal?topic=bare-metal-bm-getting-started#getting-started) deployment is best if you need direct access to a dedicated physical server for higher performance.

You also have many options for:
* Selecting the type of [storage](https://{DomainName}/catalog/?taxonomyNavigation=apps&category=slstorage){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") that's right for you from block storage, file storage, or Object Storage.
* Selecting the type of [network](https://{DomainName}/catalog/?taxonomyNavigation=apps&category=slnetwork){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon")} you need.
* Selecting a [containerization](https://{DomainName}/catalog/?taxonomyNavigation=apps&category=containers){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") service to take advantage of {{site.data.keyword.cloud_notm}} Kubernetes technology.