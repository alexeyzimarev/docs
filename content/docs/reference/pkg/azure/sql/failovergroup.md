
---
title: "FailoverGroup"
block_external_search_index: true
---

Create a failover group of databases on a collection of Azure SQL servers.

> This content is derived from https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/sql_failover_group.html.markdown.



## Create a FailoverGroup Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/sql/#FailoverGroup">FailoverGroup</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/sql/#FailoverGroupArgs">FailoverGroupArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">FailoverGroup</span><span class="p">(resource_name, opts=None, </span>databases=None<span class="p">, </span>name=None<span class="p">, </span>partner_servers=None<span class="p">, </span>read_write_endpoint_failover_policy=None<span class="p">, </span>readonly_endpoint_failover_policy=None<span class="p">, </span>resource_group_name=None<span class="p">, </span>server_name=None<span class="p">, </span>tags=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewFailoverGroup<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/sql?tab=doc#FailoverGroupArgs">FailoverGroupArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/sql?tab=doc#FailoverGroup">FailoverGroup</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Sql.FailoverGroup.html">FailoverGroup</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Sql.Inputs.FailoverGroupArgs.html">FailoverGroupArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">Pulumi.CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

#### Resource Arguments




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Databases</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}A list of database ids to add to the failover group
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the failover group. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Partner<wbr>Servers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergrouppartnerserver">List&lt;Failover<wbr>Group<wbr>Partner<wbr>Server<wbr>Args&gt;</a></span>
    </dt>
    <dd>{{% md %}}A list of secondary servers as documented below
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadwriteendpointfailoverpolicy">Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A read/write policy as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadonlyendpointfailoverpolicy">Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}a read-only policy as documented below
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the SQL server
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Server<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the primary SQL server. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Databases</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of database ids to add to the failover group
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the failover group. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Partner<wbr>Servers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergrouppartnerserver">[]Failover<wbr>Group<wbr>Partner<wbr>Server</a></span>
    </dt>
    <dd>{{% md %}}A list of secondary servers as documented below
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadwriteendpointfailoverpolicy">Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}A read/write policy as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadonlyendpointfailoverpolicy">*Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}a read-only policy as documented below
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the SQL server
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Server<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the primary SQL server. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>databases</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}A list of database ids to add to the failover group
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the failover group. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>partner<wbr>Servers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergrouppartnerserver">Failover<wbr>Group<wbr>Partner<wbr>Server[]</a></span>
    </dt>
    <dd>{{% md %}}A list of secondary servers as documented below
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadwriteendpointfailoverpolicy">Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}A read/write policy as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadonlyendpointfailoverpolicy">Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy?</a></span>
    </dt>
    <dd>{{% md %}}a read-only policy as documented below
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the SQL server
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>server<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the primary SQL server. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>databases</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of database ids to add to the failover group
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the failover group. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>partner_<wbr>servers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergrouppartnerserver">List[Failover<wbr>Group<wbr>Partner<wbr>Server]</a></span>
    </dt>
    <dd>{{% md %}}A list of secondary servers as documented below
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>read_<wbr>write_<wbr>endpoint_<wbr>failover_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadwriteendpointfailoverpolicy">Dict[Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}A read/write policy as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>readonly_<wbr>endpoint_<wbr>failover_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadonlyendpointfailoverpolicy">Dict[Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}a read-only policy as documented below
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the SQL server
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>server_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the primary SQL server. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## FailoverGroup Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Databases</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}A list of database ids to add to the failover group
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}the location of the failover group.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the failover group. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Partner<wbr>Servers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergrouppartnerserver">List&lt;Failover<wbr>Group<wbr>Partner<wbr>Server&gt;</a></span>
    </dt>
    <dd>{{% md %}}A list of secondary servers as documented below
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadwriteendpointfailoverpolicy">Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}A read/write policy as documented below
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadonlyendpointfailoverpolicy">Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}a read-only policy as documented below
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the SQL server
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Role</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}local replication role of the failover group instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Server<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the primary SQL server. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Databases</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of database ids to add to the failover group
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}the location of the failover group.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the failover group. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Partner<wbr>Servers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergrouppartnerserver">[]Failover<wbr>Group<wbr>Partner<wbr>Server</a></span>
    </dt>
    <dd>{{% md %}}A list of secondary servers as documented below
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadwriteendpointfailoverpolicy">Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}A read/write policy as documented below
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadonlyendpointfailoverpolicy">Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}a read-only policy as documented below
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the SQL server
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Role</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}local replication role of the failover group instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Server<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the primary SQL server. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>databases</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}A list of database ids to add to the failover group
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}the location of the failover group.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the failover group. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>partner<wbr>Servers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergrouppartnerserver">Failover<wbr>Group<wbr>Partner<wbr>Server[]</a></span>
    </dt>
    <dd>{{% md %}}A list of secondary servers as documented below
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadwriteendpointfailoverpolicy">Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}A read/write policy as documented below
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadonlyendpointfailoverpolicy">Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}a read-only policy as documented below
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the SQL server
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>role</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}local replication role of the failover group instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>server<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the primary SQL server. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>databases</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of database ids to add to the failover group
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}the location of the failover group.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the failover group. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>partner_<wbr>servers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergrouppartnerserver">List[Failover<wbr>Group<wbr>Partner<wbr>Server]</a></span>
    </dt>
    <dd>{{% md %}}A list of secondary servers as documented below
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>read_<wbr>write_<wbr>endpoint_<wbr>failover_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadwriteendpointfailoverpolicy">Dict[Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}A read/write policy as documented below
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>readonly_<wbr>endpoint_<wbr>failover_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadonlyendpointfailoverpolicy">Dict[Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}a read-only policy as documented below
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the SQL server
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>role</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}local replication role of the failover group instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>server_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the primary SQL server. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing FailoverGroup Resource

Get an existing FailoverGroup resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">pulumi.Input&lt;pulumi.ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/sql/#FailoverGroupState">FailoverGroupState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/sql/#FailoverGroup">FailoverGroup</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>databases=None<span class="p">, </span>location=None<span class="p">, </span>name=None<span class="p">, </span>partner_servers=None<span class="p">, </span>read_write_endpoint_failover_policy=None<span class="p">, </span>readonly_endpoint_failover_policy=None<span class="p">, </span>resource_group_name=None<span class="p">, </span>role=None<span class="p">, </span>server_name=None<span class="p">, </span>tags=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetFailoverGroup<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">pulumi.IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/sql?tab=doc#FailoverGroupState">FailoverGroupState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/sql?tab=doc#FailoverGroup">FailoverGroup</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Sql.FailoverGroup.html">FailoverGroup</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Pulumi.Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Sql.FailoverGroupState.html">FailoverGroupState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">Pulumi.CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>resource_name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Optional">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

The following state arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Databases</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}A list of database ids to add to the failover group
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}the location of the failover group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the failover group. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Partner<wbr>Servers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergrouppartnerserver">List&lt;Failover<wbr>Group<wbr>Partner<wbr>Server<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}A list of secondary servers as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadwriteendpointfailoverpolicy">Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}A read/write policy as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadonlyendpointfailoverpolicy">Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}a read-only policy as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the SQL server
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Role</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}local replication role of the failover group instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Server<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the primary SQL server. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Databases</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of database ids to add to the failover group
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}the location of the failover group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the failover group. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Partner<wbr>Servers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergrouppartnerserver">[]Failover<wbr>Group<wbr>Partner<wbr>Server</a></span>
    </dt>
    <dd>{{% md %}}A list of secondary servers as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadwriteendpointfailoverpolicy">*Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}A read/write policy as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadonlyendpointfailoverpolicy">*Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}a read-only policy as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the SQL server
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Role</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}local replication role of the failover group instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Server<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the primary SQL server. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>databases</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}A list of database ids to add to the failover group
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}the location of the failover group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the failover group. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>partner<wbr>Servers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergrouppartnerserver">Failover<wbr>Group<wbr>Partner<wbr>Server[]?</a></span>
    </dt>
    <dd>{{% md %}}A list of secondary servers as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadwriteendpointfailoverpolicy">Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy?</a></span>
    </dt>
    <dd>{{% md %}}A read/write policy as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadonlyendpointfailoverpolicy">Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy?</a></span>
    </dt>
    <dd>{{% md %}}a read-only policy as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the SQL server
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>role</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}local replication role of the failover group instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>server<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the primary SQL server. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>databases</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of database ids to add to the failover group
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}the location of the failover group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the failover group. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>partner_<wbr>servers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergrouppartnerserver">List[Failover<wbr>Group<wbr>Partner<wbr>Server]</a></span>
    </dt>
    <dd>{{% md %}}A list of secondary servers as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>read_<wbr>write_<wbr>endpoint_<wbr>failover_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadwriteendpointfailoverpolicy">Dict[Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}A read/write policy as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>readonly_<wbr>endpoint_<wbr>failover_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#failovergroupreadonlyendpointfailoverpolicy">Dict[Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}a read-only policy as documented below
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the SQL server
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>role</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}local replication role of the failover group instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>server_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the primary SQL server. Changing this forces a new resource to be created.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assign to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Supporting Types

<h4>Failover<wbr>Group<wbr>Partner<wbr>Server</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#FailoverGroupPartnerServer">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#FailoverGroupPartnerServer">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/sql?tab=doc#FailoverGroupPartnerServerArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/sql?tab=doc#FailoverGroupPartnerServerOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}the SQL server ID
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}the location of the failover group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Role</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}local replication role of the failover group instance.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}the SQL server ID
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}the location of the failover group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Role</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}local replication role of the failover group instance.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}the SQL server ID
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}the location of the failover group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>role</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}local replication role of the failover group instance.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}the SQL server ID
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}the location of the failover group.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>role</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}local replication role of the failover group instance.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Failover<wbr>Group<wbr>Read<wbr>Write<wbr>Endpoint<wbr>Failover<wbr>Policy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#FailoverGroupReadWriteEndpointFailoverPolicy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#FailoverGroupReadWriteEndpointFailoverPolicy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/sql?tab=doc#FailoverGroupReadWriteEndpointFailoverPolicyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/sql?tab=doc#FailoverGroupReadWriteEndpointFailoverPolicyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Grace<wbr>Minutes</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Applies only if `mode` is `Automatic`. The grace period in minutes before failover with data loss is attempted
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}the failover mode. Possible values are `Manual`, `Automatic`
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Grace<wbr>Minutes</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Applies only if `mode` is `Automatic`. The grace period in minutes before failover with data loss is attempted
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}the failover mode. Possible values are `Manual`, `Automatic`
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>grace<wbr>Minutes</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Applies only if `mode` is `Automatic`. The grace period in minutes before failover with data loss is attempted
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}the failover mode. Possible values are `Manual`, `Automatic`
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>grace<wbr>Minutes</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Applies only if `mode` is `Automatic`. The grace period in minutes before failover with data loss is attempted
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}the failover mode. Possible values are `Manual`, `Automatic`
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Failover<wbr>Group<wbr>Readonly<wbr>Endpoint<wbr>Failover<wbr>Policy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/input/#FailoverGroupReadonlyEndpointFailoverPolicy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#FailoverGroupReadonlyEndpointFailoverPolicy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/sql?tab=doc#FailoverGroupReadonlyEndpointFailoverPolicyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/sql?tab=doc#FailoverGroupReadonlyEndpointFailoverPolicyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Failover policy for the read-only endpoint. Possible values are `Enabled`, and `Disabled`
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Failover policy for the read-only endpoint. Possible values are `Enabled`, and `Disabled`
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Failover policy for the read-only endpoint. Possible values are `Enabled`, and `Disabled`
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Failover policy for the read-only endpoint. Possible values are `Enabled`, and `Disabled`
{{% /md %}}</dd>

</dl>
{{% /choosable %}}






