
---
title: "Alarm"
block_external_search_index: true
---






## Create a Alarm Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/cms/#Alarm">Alarm</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/cms/#AlarmArgs">AlarmArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">Alarm</span><span class="p">(resource_name, opts=None, </span>contact_groups=None<span class="p">, </span>dimensions=None<span class="p">, </span>effective_interval=None<span class="p">, </span>enabled=None<span class="p">, </span>end_time=None<span class="p">, </span>metric=None<span class="p">, </span>name=None<span class="p">, </span>operator=None<span class="p">, </span>period=None<span class="p">, </span>project=None<span class="p">, </span>silence_time=None<span class="p">, </span>start_time=None<span class="p">, </span>statistics=None<span class="p">, </span>threshold=None<span class="p">, </span>triggered_count=None<span class="p">, </span>webhook=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewAlarm<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/cms?tab=doc#AlarmArgs">AlarmArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/cms?tab=doc#Alarm">Alarm</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Cms.Alarm.html">Alarm</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Cms.AlarmArgs.html">AlarmArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
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

    <dt class="property-required"
            title="Required">
        <span>Contact<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}List contact groups of the alarm rule, which must have been created on the console.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, object></span>
    </dt>
    <dd>{{% md %}}Map of the resources associated with the alarm rule, such as "instanceId", "device" and "port". Each key's value is a string and it uses comma to split multiple items. For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Effective<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The interval of effecting alarm rule. It foramt as "hh:mm-hh:mm", like "0:00-4:00". Default to "00:00-23:59".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to enable alarm rule. Default to true.
* `webhook`- (Optional, Available in 1.46.0+) The webhook that should be called when the alarm is triggered. Currently, only http protocol is supported. Default is empty string.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>End<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;end_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-required"
            title="Required">
        <span>Metric</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of the monitoring metrics corresponding to a project, such as "CPUUtilization" and "networkin_rate". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The alarm rule name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Alarm comparison operator. Valid values: ["<=", "<", ">", ">=", "==", "!="]. Default to "==".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Index query cycle, which must be consistent with that defined for metrics. Default to 300, in seconds.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Monitor project name, such as "acs_ecs_dashboard" and "acs_rds_dashboard". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Silence<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Notification silence period in the alarm state, in seconds. Valid value range: [300, 86400]. Default to 86400
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;start_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Statistics</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Statistical method. It must be consistent with that defined for metrics. Valid values: ["Average", "Minimum", "Maximum"]. Default to "Average".
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Alarm threshold value, which must be a numeric value currently.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Triggered<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Number of consecutive times it has been detected that the values exceed the threshold. Default to 3.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Webhook</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Contact<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List contact groups of the alarm rule, which must have been created on the console.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}Map of the resources associated with the alarm rule, such as "instanceId", "device" and "port". Each key's value is a string and it uses comma to split multiple items. For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Effective<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The interval of effecting alarm rule. It foramt as "hh:mm-hh:mm", like "0:00-4:00". Default to "00:00-23:59".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to enable alarm rule. Default to true.
* `webhook`- (Optional, Available in 1.46.0+) The webhook that should be called when the alarm is triggered. Currently, only http protocol is supported. Default is empty string.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>End<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;end_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-required"
            title="Required">
        <span>Metric</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of the monitoring metrics corresponding to a project, such as "CPUUtilization" and "networkin_rate". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The alarm rule name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Alarm comparison operator. Valid values: ["<=", "<", ">", ">=", "==", "!="]. Default to "==".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Index query cycle, which must be consistent with that defined for metrics. Default to 300, in seconds.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Monitor project name, such as "acs_ecs_dashboard" and "acs_rds_dashboard". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Silence<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Notification silence period in the alarm state, in seconds. Valid value range: [300, 86400]. Default to 86400
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;start_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Statistics</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Statistical method. It must be consistent with that defined for metrics. Valid values: ["Average", "Minimum", "Maximum"]. Default to "Average".
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Alarm threshold value, which must be a numeric value currently.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Triggered<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Number of consecutive times it has been detected that the values exceed the threshold. Default to 3.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Webhook</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>contact<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}List contact groups of the alarm rule, which must have been created on the console.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}</span>
    </dt>
    <dd>{{% md %}}Map of the resources associated with the alarm rule, such as "instanceId", "device" and "port". Each key's value is a string and it uses comma to split multiple items. For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>effective<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The interval of effecting alarm rule. It foramt as "hh:mm-hh:mm", like "0:00-4:00". Default to "00:00-23:59".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to enable alarm rule. Default to true.
* `webhook`- (Optional, Available in 1.46.0+) The webhook that should be called when the alarm is triggered. Currently, only http protocol is supported. Default is empty string.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>end<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;end_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-required"
            title="Required">
        <span>metric</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of the monitoring metrics corresponding to a project, such as "CPUUtilization" and "networkin_rate". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The alarm rule name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Alarm comparison operator. Valid values: ["<=", "<", ">", ">=", "==", "!="]. Default to "==".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Index query cycle, which must be consistent with that defined for metrics. Default to 300, in seconds.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Monitor project name, such as "acs_ecs_dashboard" and "acs_rds_dashboard". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>silence<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Notification silence period in the alarm state, in seconds. Valid value range: [300, 86400]. Default to 86400
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;start_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>statistics</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Statistical method. It must be consistent with that defined for metrics. Valid values: ["Average", "Minimum", "Maximum"]. Default to "Average".
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Alarm threshold value, which must be a numeric value currently.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>triggered<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Number of consecutive times it has been detected that the values exceed the threshold. Default to 3.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>webhook</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>contact_<wbr>groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}List contact groups of the alarm rule, which must have been created on the console.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}Map of the resources associated with the alarm rule, such as "instanceId", "device" and "port". Each key's value is a string and it uses comma to split multiple items. For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>effective_<wbr>interval</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The interval of effecting alarm rule. It foramt as "hh:mm-hh:mm", like "0:00-4:00". Default to "00:00-23:59".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to enable alarm rule. Default to true.
* `webhook`- (Optional, Available in 1.46.0+) The webhook that should be called when the alarm is triggered. Currently, only http protocol is supported. Default is empty string.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>end_<wbr>time</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;end_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-required"
            title="Required">
        <span>metric</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Name of the monitoring metrics corresponding to a project, such as "CPUUtilization" and "networkin_rate". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The alarm rule name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Alarm comparison operator. Valid values: ["<=", "<", ">", ">=", "==", "!="]. Default to "==".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Index query cycle, which must be consistent with that defined for metrics. Default to 300, in seconds.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>project</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Monitor project name, such as "acs_ecs_dashboard" and "acs_rds_dashboard". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>silence_<wbr>time</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Notification silence period in the alarm state, in seconds. Valid value range: [300, 86400]. Default to 86400
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>start_<wbr>time</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;start_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>statistics</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Statistical method. It must be consistent with that defined for metrics. Valid values: ["Average", "Minimum", "Maximum"]. Default to "Average".
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Alarm threshold value, which must be a numeric value currently.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>triggered_<wbr>count</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Number of consecutive times it has been detected that the values exceed the threshold. Default to 3.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>webhook</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## Alarm Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Contact<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}List contact groups of the alarm rule, which must have been created on the console.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, object></span>
    </dt>
    <dd>{{% md %}}Map of the resources associated with the alarm rule, such as "instanceId", "device" and "port". Each key's value is a string and it uses comma to split multiple items. For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Effective<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The interval of effecting alarm rule. It foramt as "hh:mm-hh:mm", like "0:00-4:00". Default to "00:00-23:59".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to enable alarm rule. Default to true.
* `webhook`- (Optional, Available in 1.46.0+) The webhook that should be called when the alarm is triggered. Currently, only http protocol is supported. Default is empty string.
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>End<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;end_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-"
            title="">
        <span>Metric</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of the monitoring metrics corresponding to a project, such as "CPUUtilization" and "networkin_rate". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The alarm rule name.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Alarm comparison operator. Valid values: ["<=", "<", ">", ">=", "==", "!="]. Default to "==".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Index query cycle, which must be consistent with that defined for metrics. Default to 300, in seconds.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Monitor project name, such as "acs_ecs_dashboard" and "acs_rds_dashboard". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Silence<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Notification silence period in the alarm state, in seconds. Valid value range: [300, 86400]. Default to 86400
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>Start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;start_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-"
            title="">
        <span>Statistics</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Statistical method. It must be consistent with that defined for metrics. Valid values: ["Average", "Minimum", "Maximum"]. Default to "Average".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Status</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The current alarm rule status.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Alarm threshold value, which must be a numeric value currently.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Triggered<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Number of consecutive times it has been detected that the values exceed the threshold. Default to 3.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Webhook</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Contact<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List contact groups of the alarm rule, which must have been created on the console.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}Map of the resources associated with the alarm rule, such as "instanceId", "device" and "port". Each key's value is a string and it uses comma to split multiple items. For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Effective<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The interval of effecting alarm rule. It foramt as "hh:mm-hh:mm", like "0:00-4:00". Default to "00:00-23:59".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to enable alarm rule. Default to true.
* `webhook`- (Optional, Available in 1.46.0+) The webhook that should be called when the alarm is triggered. Currently, only http protocol is supported. Default is empty string.
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>End<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;end_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-"
            title="">
        <span>Metric</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of the monitoring metrics corresponding to a project, such as "CPUUtilization" and "networkin_rate". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The alarm rule name.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Alarm comparison operator. Valid values: ["<=", "<", ">", ">=", "==", "!="]. Default to "==".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Index query cycle, which must be consistent with that defined for metrics. Default to 300, in seconds.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Monitor project name, such as "acs_ecs_dashboard" and "acs_rds_dashboard". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Silence<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Notification silence period in the alarm state, in seconds. Valid value range: [300, 86400]. Default to 86400
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>Start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;start_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-"
            title="">
        <span>Statistics</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Statistical method. It must be consistent with that defined for metrics. Valid values: ["Average", "Minimum", "Maximum"]. Default to "Average".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Status</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The current alarm rule status.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Alarm threshold value, which must be a numeric value currently.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Triggered<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Number of consecutive times it has been detected that the values exceed the threshold. Default to 3.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Webhook</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>contact<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}List contact groups of the alarm rule, which must have been created on the console.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}</span>
    </dt>
    <dd>{{% md %}}Map of the resources associated with the alarm rule, such as "instanceId", "device" and "port". Each key's value is a string and it uses comma to split multiple items. For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>effective<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The interval of effecting alarm rule. It foramt as "hh:mm-hh:mm", like "0:00-4:00". Default to "00:00-23:59".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to enable alarm rule. Default to true.
* `webhook`- (Optional, Available in 1.46.0+) The webhook that should be called when the alarm is triggered. Currently, only http protocol is supported. Default is empty string.
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>end<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;end_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-"
            title="">
        <span>metric</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of the monitoring metrics corresponding to a project, such as "CPUUtilization" and "networkin_rate". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The alarm rule name.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Alarm comparison operator. Valid values: ["<=", "<", ">", ">=", "==", "!="]. Default to "==".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Index query cycle, which must be consistent with that defined for metrics. Default to 300, in seconds.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Monitor project name, such as "acs_ecs_dashboard" and "acs_rds_dashboard". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>silence<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Notification silence period in the alarm state, in seconds. Valid value range: [300, 86400]. Default to 86400
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;start_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-"
            title="">
        <span>statistics</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Statistical method. It must be consistent with that defined for metrics. Valid values: ["Average", "Minimum", "Maximum"]. Default to "Average".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>status</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The current alarm rule status.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Alarm threshold value, which must be a numeric value currently.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>triggered<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Number of consecutive times it has been detected that the values exceed the threshold. Default to 3.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>webhook</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>contact_<wbr>groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}List contact groups of the alarm rule, which must have been created on the console.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}Map of the resources associated with the alarm rule, such as "instanceId", "device" and "port". Each key's value is a string and it uses comma to split multiple items. For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>effective_<wbr>interval</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The interval of effecting alarm rule. It foramt as "hh:mm-hh:mm", like "0:00-4:00". Default to "00:00-23:59".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to enable alarm rule. Default to true.
* `webhook`- (Optional, Available in 1.46.0+) The webhook that should be called when the alarm is triggered. Currently, only http protocol is supported. Default is empty string.
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>end_<wbr>time</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;end_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-"
            title="">
        <span>metric</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Name of the monitoring metrics corresponding to a project, such as "CPUUtilization" and "networkin_rate". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The alarm rule name.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Alarm comparison operator. Valid values: ["<=", "<", ">", ">=", "==", "!="]. Default to "==".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Index query cycle, which must be consistent with that defined for metrics. Default to 300, in seconds.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>project</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Monitor project name, such as "acs_ecs_dashboard" and "acs_rds_dashboard". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>silence_<wbr>time</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Notification silence period in the alarm state, in seconds. Valid value range: [300, 86400]. Default to 86400
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>start_<wbr>time</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;start_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-"
            title="">
        <span>statistics</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Statistical method. It must be consistent with that defined for metrics. Valid values: ["Average", "Minimum", "Maximum"]. Default to "Average".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>status</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The current alarm rule status.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Alarm threshold value, which must be a numeric value currently.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>triggered_<wbr>count</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Number of consecutive times it has been detected that the values exceed the threshold. Default to 3.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>webhook</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing Alarm Resource

Get an existing Alarm resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">Input&lt;ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/cms/#AlarmState">AlarmState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/cms/#Alarm">Alarm</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>contact_groups=None<span class="p">, </span>dimensions=None<span class="p">, </span>effective_interval=None<span class="p">, </span>enabled=None<span class="p">, </span>end_time=None<span class="p">, </span>metric=None<span class="p">, </span>name=None<span class="p">, </span>operator=None<span class="p">, </span>period=None<span class="p">, </span>project=None<span class="p">, </span>silence_time=None<span class="p">, </span>start_time=None<span class="p">, </span>statistics=None<span class="p">, </span>status=None<span class="p">, </span>threshold=None<span class="p">, </span>triggered_count=None<span class="p">, </span>webhook=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetAlarm<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/cms?tab=doc#AlarmState">AlarmState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/cms?tab=doc#Alarm">Alarm</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Cms.Alarm.html">Alarm</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Cms.AlarmState.html">AlarmState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
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
        <span>Contact<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}List contact groups of the alarm rule, which must have been created on the console.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, object>?</span>
    </dt>
    <dd>{{% md %}}Map of the resources associated with the alarm rule, such as "instanceId", "device" and "port". Each key's value is a string and it uses comma to split multiple items. For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Effective<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The interval of effecting alarm rule. It foramt as "hh:mm-hh:mm", like "0:00-4:00". Default to "00:00-23:59".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to enable alarm rule. Default to true.
* `webhook`- (Optional, Available in 1.46.0+) The webhook that should be called when the alarm is triggered. Currently, only http protocol is supported. Default is empty string.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>End<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;end_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Metric</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Name of the monitoring metrics corresponding to a project, such as "CPUUtilization" and "networkin_rate". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The alarm rule name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Alarm comparison operator. Valid values: ["<=", "<", ">", ">=", "==", "!="]. Default to "==".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Index query cycle, which must be consistent with that defined for metrics. Default to 300, in seconds.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Monitor project name, such as "acs_ecs_dashboard" and "acs_rds_dashboard". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Silence<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Notification silence period in the alarm state, in seconds. Valid value range: [300, 86400]. Default to 86400
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;start_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Statistics</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Statistical method. It must be consistent with that defined for metrics. Valid values: ["Average", "Minimum", "Maximum"]. Default to "Average".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Status</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The current alarm rule status.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Alarm threshold value, which must be a numeric value currently.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Triggered<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Number of consecutive times it has been detected that the values exceed the threshold. Default to 3.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Webhook</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Contact<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List contact groups of the alarm rule, which must have been created on the console.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}Map of the resources associated with the alarm rule, such as "instanceId", "device" and "port". Each key's value is a string and it uses comma to split multiple items. For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Effective<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The interval of effecting alarm rule. It foramt as "hh:mm-hh:mm", like "0:00-4:00". Default to "00:00-23:59".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to enable alarm rule. Default to true.
* `webhook`- (Optional, Available in 1.46.0+) The webhook that should be called when the alarm is triggered. Currently, only http protocol is supported. Default is empty string.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>End<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;end_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Metric</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Name of the monitoring metrics corresponding to a project, such as "CPUUtilization" and "networkin_rate". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The alarm rule name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Alarm comparison operator. Valid values: ["<=", "<", ">", ">=", "==", "!="]. Default to "==".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Index query cycle, which must be consistent with that defined for metrics. Default to 300, in seconds.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Project</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Monitor project name, such as "acs_ecs_dashboard" and "acs_rds_dashboard". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Silence<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Notification silence period in the alarm state, in seconds. Valid value range: [300, 86400]. Default to 86400
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;start_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Statistics</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Statistical method. It must be consistent with that defined for metrics. Valid values: ["Average", "Minimum", "Maximum"]. Default to "Average".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Status</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The current alarm rule status.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Alarm threshold value, which must be a numeric value currently.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Triggered<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Number of consecutive times it has been detected that the values exceed the threshold. Default to 3.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Webhook</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>contact<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}List contact groups of the alarm rule, which must have been created on the console.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}?</span>
    </dt>
    <dd>{{% md %}}Map of the resources associated with the alarm rule, such as "instanceId", "device" and "port". Each key's value is a string and it uses comma to split multiple items. For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>effective<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The interval of effecting alarm rule. It foramt as "hh:mm-hh:mm", like "0:00-4:00". Default to "00:00-23:59".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to enable alarm rule. Default to true.
* `webhook`- (Optional, Available in 1.46.0+) The webhook that should be called when the alarm is triggered. Currently, only http protocol is supported. Default is empty string.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>end<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;end_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>metric</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Name of the monitoring metrics corresponding to a project, such as "CPUUtilization" and "networkin_rate". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The alarm rule name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Alarm comparison operator. Valid values: ["<=", "<", ">", ">=", "==", "!="]. Default to "==".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Index query cycle, which must be consistent with that defined for metrics. Default to 300, in seconds.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Monitor project name, such as "acs_ecs_dashboard" and "acs_rds_dashboard". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>silence<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Notification silence period in the alarm state, in seconds. Valid value range: [300, 86400]. Default to 86400
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;start_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>statistics</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Statistical method. It must be consistent with that defined for metrics. Valid values: ["Average", "Minimum", "Maximum"]. Default to "Average".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>status</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The current alarm rule status.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Alarm threshold value, which must be a numeric value currently.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>triggered<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Number of consecutive times it has been detected that the values exceed the threshold. Default to 3.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>webhook</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>contact_<wbr>groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}List contact groups of the alarm rule, which must have been created on the console.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}Map of the resources associated with the alarm rule, such as "instanceId", "device" and "port". Each key's value is a string and it uses comma to split multiple items. For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>effective_<wbr>interval</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The interval of effecting alarm rule. It foramt as "hh:mm-hh:mm", like "0:00-4:00". Default to "00:00-23:59".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to enable alarm rule. Default to true.
* `webhook`- (Optional, Available in 1.46.0+) The webhook that should be called when the alarm is triggered. Currently, only http protocol is supported. Default is empty string.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>end_<wbr>time</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;end_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>metric</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Name of the monitoring metrics corresponding to a project, such as "CPUUtilization" and "networkin_rate". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The alarm rule name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Alarm comparison operator. Valid values: ["<=", "<", ">", ">=", "==", "!="]. Default to "==".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Index query cycle, which must be consistent with that defined for metrics. Default to 300, in seconds.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>project</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Monitor project name, such as "acs_ecs_dashboard" and "acs_rds_dashboard". For more information, see [Metrics Reference](https://www.alibabacloud.com/help/doc-detail/28619.htm).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>silence_<wbr>time</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Notification silence period in the alarm state, in seconds. Valid value range: [300, 86400]. Default to 86400
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>start_<wbr>time</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}It has been deprecated from provider version 1.50.0 and 'effective_interval' instead.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;start_time&#39; has been deprecated from provider version 1.50.0. New field &#39;effective_interval&#39; instead.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>statistics</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Statistical method. It must be consistent with that defined for metrics. Valid values: ["Average", "Minimum", "Maximum"]. Default to "Average".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>status</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The current alarm rule status.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Alarm threshold value, which must be a numeric value currently.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>triggered_<wbr>count</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Number of consecutive times it has been detected that the values exceed the threshold. Default to 3.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>webhook</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}











<h3>Package Details</h3>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-alicloud">https://github.com/pulumi/pulumi-alicloud</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
    
</dl>
