# Resetting the cache of your Amazon Lightsail distribution<a name="amazon-lightsail-resetting-distribution-cache"></a>

 *Last updated: July 23, 2020* 

The cache lifespan \(time to live\) setting controls the amount of time your content stays in your Amazon Lightsail distribution's cache\. You can also manually reset the cache on your distribution if you need to clear it before the cache lifespan interval\. After you clear the cache, the next time a user requests content, your distribution pulls the latest version of your content from your origin and caches it\. In this guide, we show you how to manually reset the cache on your distribution\. For more information about distributions, see [Content delivery network distributions in Amazon Lightsail](amazon-lightsail-content-delivery-network-distributions.md)\.

## Reset the cache of your distribution<a name="reset-distribution-cache"></a>

Complete the following procedure to reset the cache of your distribution\.

1. Sign in to the [Lightsail console](https://lightsail.aws.amazon.com/)\.

1. On the Lightsail home page, choose the **Networking** tab\.

1. Choose the name of the distribution for which you want to reset the cache\.

1. Choose the **Cache** tab on your distribution's management page\.

1. Scroll to the **Reset cache** section of the page, and choose **Reset cache**\.

1. At the confirmation prompt, choose **Yes, reset** to confirm that you want to reset your distribution's cache\. Or choose **No, cancel** to not reset your distribution's cache\.

## Additional information<a name="resetting-distribution-cache-additional-information"></a>

Here are some articles to help you manage distributions in Lightsail:
+ [Content delivery network distributions in Amazon Lightsail](amazon-lightsail-content-delivery-network-distributions.md)
+ [Creating Amazon Lightsail distributions](amazon-lightsail-creating-content-delivery-network-distribution.md)
+ [Understanding request and response behaviors of an Amazon Lightsail distribution](amazon-lightsail-distribution-request-and-response.md)
+ [Configuring your WordPress instance to work with your Amazon Lightsail distribution](amazon-lightsail-editing-wp-config-for-distribution.md)
+ [Testing your Amazon Lightsail distribution](amazon-lightsail-testing-distribution.md)
+ [Changing the origin of your Amazon Lightsail distribution](amazon-lightsail-changing-distribution-origin.md)
+ [Changing the caching behavior of your Amazon Lightsail distribution](amazon-lightsail-changing-default-cache-behavior.md)
+ [Resetting the cache of your Amazon Lightsail distribution](#amazon-lightsail-resetting-distribution-cache)
+ [Changing the plan of your Amazon Lightsail distribution](amazon-lighstail-changing-distribution-plan.md)
+ [Enabling custom domains for your Amazon Lightsail distributions](amazon-lightsail-enabling-distribution-custom-domains.md)
+ [Pointing your domains to your Amazon Lightsail distributions](amazon-lightsail-point-domain-to-distribution.md)
+ [Changing custom domains for your Amazon Lightsail distribution](amazon-lightsail-changing-distribution-custom-domains.md)
+ [Disabling custom domains for your Amazon Lightsail distributions](amazon-lightsail-disabling-distribution-custom-domains.md)
+ [Viewing distribution metrics in Amazon Lightsail](amazon-lightsail-viewing-distribution-health-metrics.md)
+ [Deleting your Amazon Lightsail distribution](amazon-lightsail-deleting-distribution.md)
+ [SSL/TLS certificates in Amazon Lightsail](understanding-tls-ssl-certificates-in-lightsail-https.md)
+ [Creating SSL/TLS certificates for your Amazon Lightsail distribution](amazon-lightsail-create-a-distribution-certificate.md)
+ [Validating SSL/TLS certificates for your Amazon Lightsail distribution](amazon-lightsail-validating-a-distribution-certificate.md)
+ [Viewing SSL/TLS certificates for your Amazon Lightsail distribution](amazon-lightsail-viewing-distribution-certificates.md)
+ [Deleting SSL/TLS certificates for your Amazon Lightsail distribution](amazon-lightsail-deleting-distribution-certificates.md)