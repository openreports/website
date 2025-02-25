---
title: "OpenReports"
linkTitle: "OpenReports"
---

{{< blocks/cover title="" image_anchor="top" height="full" color="dark" >}}

<img src="/images/OpenReports-Horizontal.png" alt="OpenReports" style="max-width: 800px; width: 100%; height: auto;">

<br/>
<br/>
<H1>Standardized Reporting For Kubernetes</H1>

<div class="mt-5 mx-auto">
	<a class="btn btn-lg btn-primary mr-3 mb-4" href="#about">
		Learn More <i class="fa fa-chalkboard-teacher ml-2"></i>
	</a>

  <a class="btn btn-link text-info" href="#about" aria-label="Read more"><i class="fa fa-chevron-circle-down" style="font-size: 400%"></i></a>
</div>

{{< /blocks/cover >}}


{{% blocks/lead color="light" %}}

# About { class="text-center" }
<br/>
<br/>

<h2>
OpenReports provides an API and tools for managing reports in Kubernetes.
</h2>
<br/>

<p style="line-height:1.5">
 OpenReports allows any Kubernetes controller, policy engine, or scanner to produce reports as a Kubernetes custom resource. Reports can then be consumed via kubectl, the OpenReports dashboard, or any other Kubernetes client. For high performance in large clusters, reports can be offloaded from etcd to a reporting database.
</p>

<br/>
{{% /blocks/lead %}}

{{% blocks/section color="dark" type="row" %}}

{{% blocks/feature icon="fas fa-code" title="Reports API" url="docs/api/" %}}
{{% /blocks/feature %}}

{{% blocks/feature icon="fas fa-arrow-right" title="Report Producers" url="docs/producers/" %}}
{{% /blocks/feature %}}

{{% blocks/feature icon="fas fa-arrow-left" title="Report Consumers" url="docs/consumers/" %}}
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/section color="light" type="row" %}}

# Community { class="text-center" }
<br/>
<br/>

<H3>
The reports API was originally developed by the <a href="https://github.com/kubernetes/community/blob/master/wg-policy/README.md" target="_blank">Kubernetes Policy Working Group</a> to enable standardized reporting across policy engines. Join the community to get the latest news, ask questions, and contribute to the project.
</H3>

<br/>
<br/>

{{% /blocks/section %}}

{{% blocks/section color="white" type="row" %}}

<br/>
<h2 class="text-center">
From leaders in the cloud native ecosystem
</h2>

<br/>
<br/>
<br/>
<br/>

<div style="display: flex; justify-content: center; width: 100%; margin: 0 auto;">
{{% cardpane %}}

{{% card header="" title="" subtitle="" footer="<a href='https://www.fairwinds.com' target='_blank'>Fairwinds</a>" %}}
<div style="height: 150px; display: flex; align-items: center; justify-content: center; min-width: 200px;">
    <img src="/images/fairwinds.svg" alt="Fairwinds" style="max-height: 100%; max-width: 100%; object-fit: contain;">
</div>
{{% /card %}}

{{% card header="" title="" subtitle="" footer="<a href='https://github.com/kubernetes/community/blob/master/wg-policy/README.md' target='_blank'>K8s Policy WG</a>" %}}
<div style="height: 150px; display: flex; align-items: center; justify-content: center; min-width: 200px;">
    <img src="/images/kubernetes.svg" alt="Policy WG" style="max-height: 100%; max-width: 100%; object-fit: contain;">
</div>
{{% /card %}}

{{% card header="" title="" subtitle="" footer="<a href='https://kubewarden.io' target='_blank'>Kubewarden</a>" %}}
<div style="height: 150px; display: flex; align-items: center; justify-content: center; min-width: 200px;">
    <img src="/images/kubewarden.svg" alt="Kubewarden" style="max-height: 100%; max-width: 100%; object-fit: contain;">
</div>
{{% /card %}}

{{% /cardpane %}}
</div>


<div style="display: flex; justify-content: center; width: 100%; margin: 0 auto;">
{{% cardpane %}}

{{% card header="" title="" subtitle="" footer="<a href='https://kyverno.io' target='_blank'>Kyverno</a>" %}}
<div style="height: 150px; display: flex; align-items: center; justify-content: center; min-width: 200px;">
    <img src="/images/kyverno.svg" alt="Kyverno" style="max-height: 100%; max-width: 100%; object-fit: contain;">
</div>
{{% /card %}}

{{% card header="" title="" subtitle="" footer="<a href='https://www.nirmata.com' target='_blank'>Nirmata</a>" %}}
<div style="height: 150px; display: flex; align-items: center; justify-content: center; min-width: 200px;">
    <img src="/images/nirmata.png" alt="Nirmata" style="max-height: 100%; max-width: 100%; object-fit: contain;">
</div>
{{% /card %}}

{{% card header="" title="" subtitle="" footer="<a href='https://www.suse.com' target='_blank'>SUSE</a>" %}}
<div style="height: 150px; display: flex; align-items: center; justify-content: center; min-width: 200px;">
    <img src="/images/suse.svg" alt="SUSE" style="max-height: 100%; max-width: 100%; object-fit: contain;">
</div>
{{% /card %}}

{{% /cardpane %}}
</div>


{{% /blocks/section %}}
