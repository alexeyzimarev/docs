---
title: "DomainDkim"
---

<!-- WARNING: this file was generated by the Pulumi Terraform Bridge (tfgen) Tool. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

<style>
  table td p { margin-top: 0; margin-bottom: 0; }
</style>

Provides an SES domain DKIM generation resource.

Domain ownership needs to be confirmed first using [ses_domain_identity Resource](https://www.terraform.io/docs/providers/aws/r/ses_domain_identity.html)

> This content is derived from https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/ses_domain_dkim.html.markdown.


## Create a DomainDkim Resource

{{< langchoose csharp >}}

<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new</span> <span class="nx"><a href=/docs/reference/pkg/nodejs/pulumi/aws/s3/#DomainDkim>DomainDkim</a></span><span class="p">(</span><span class="nx">name</span>: <span class="kt"><a href=https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String>string</a></span><span class="p">,</span> <span class="nx">args</span>: <span class="kt"><a href=/docs/reference/pkg/nodejs/pulumi/aws/s3/#DomainDkimArgs>DomainDkimArgs</a></span><span class="p">,</span> <span class="nx">opts?</span>: <span class="kt"><a href=/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions>pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>

```python
def __init__(__self__, resource_name, opts=None, domain=None, __props__=None)
```

```go
func NewDomainDkim(ctx *pulumi.Context, name string, args *DomainDkimArgs, opts ...pulumi.ResourceOption) (*DomainDkim, error)

```

```csharp
public DomainDkim(string name, DomainDkimArgs args, CustomResourceOptions? options = null)

```

Creates a DomainDkim resource with the given unique name, arguments, and options.

{{% lang nodejs %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>args</strong> &ndash; (Required) The arguments to use to populate this resource's properties.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

{{% lang go %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>args</strong> &ndash; (Required) The arguments to use to populate this resource's properties.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

{{% lang csharp %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>args</strong> &ndash; (Required) The arguments to use to populate this resource's properties.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

The following arguments are supported:

<table class="ml-6">
    <thead>
        <tr>
            <th>Argument</th>
            <th>Type</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="align-top">domain</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Required) Verified domain name to generate DKIM tokens for.

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## DomainDkim Output Properties

The following output properties are available:

<table class="ml-6">
    <thead>
        <tr>
            <th>Argument</th>
            <th>Type</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="align-top">dkim<wbr>Tokens</td>
            <td class="align-top"><code>Array&lt;<wbr>string<wbr>&gt;</code></td>
            <td class="align-top">{{% md %}}
DKIM tokens generated by SES.
These tokens should be used to create CNAME records used to verify SES Easy DKIM.
See below for an example of how this might be achieved
when the domain is hosted in Route 53 and managed by this provider.
Find out more about verifying domains in Amazon SES
in the [AWS SES docs](http://docs.aws.amazon.com/ses/latest/DeveloperGuide/easy-dkim-dns-records.html).

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">domain</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
Verified domain name to generate DKIM tokens for.

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## Look up an Existing DomainDkim Resource

{{< langchoose csharp >}}

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: DomainDkimState, opts?: pulumi.CustomResourceOptions): DomainDkim;
```

```python
def get(resource_name, id, opts=None, acceleration_status=None, acl=None, arn=None, bucket=None, bucket_domain_name=None, bucket_prefix=None, bucket_regional_domain_name=None, cors_rules=None, force_destroy=None, hosted_zone_id=None, lifecycle_rules=None, loggings=None, object_lock_configuration=None, policy=None, region=None, replication_configuration=None, request_payer=None, server_side_encryption_configuration=None, tags=None, versioning=None, website=None, website_domain=None, website_endpoint=None)
```

```go
func GetBucket(ctx *pulumi.Context, name string, id pulumi.IDInput, state *BucketState, opts ...pulumi.ResourceOption) (*Bucket, error)
```

```csharp
public static Bucket Get(string name, Input<string> id, BucketState? state = null, CustomResourceOptions? options = null);
```

Get an existing DomainDkim resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

{{% lang nodejs %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>id</strong> &ndash; (Required) The _unique_ provider ID of the resource to lookup.</li>
    <li><strong>state</strong> &ndash; (Optional) Any extra arguments used during the lookup.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

{{% lang go %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>id</strong> &ndash; (Required) The _unique_ provider ID of the resource to lookup.</li>
    <li><strong>state</strong> &ndash; (Optional) Any extra arguments used during the lookup.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

{{% lang csharp %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>id</strong> &ndash; (Required) The _unique_ provider ID of the resource to lookup.</li>
    <li><strong>state</strong> &ndash; (Optional) Any extra arguments used during the lookup.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

The following state arguments are supported:

<table class="ml-6">
    <thead>
        <tr>
            <th>Argument</th>
            <th>Type</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="align-top">dkim<wbr>Tokens</td>
            <td class="align-top"><code>Array&lt;<wbr>string<wbr>&gt;</code></td>
            <td class="align-top">{{% md %}}
(Optional) DKIM tokens generated by SES.
These tokens should be used to create CNAME records used to verify SES Easy DKIM.
See below for an example of how this might be achieved
when the domain is hosted in Route 53 and managed by this provider.
Find out more about verifying domains in Amazon SES
in the [AWS SES docs](http://docs.aws.amazon.com/ses/latest/DeveloperGuide/easy-dkim-dns-records.html).

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">domain</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) Verified domain name to generate DKIM tokens for.

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## Import an Existing DomainDkim Resource

TODO

## Support Types
