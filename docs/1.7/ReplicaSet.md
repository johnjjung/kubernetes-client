# ReplicaSet

* [read operations](#read)
* [write operations](#write)

## read

### apis.extensions.v1beta1.namespaces(namespace).replicasets(name).status.get

read status of the specified ReplicaSet

#### Path

| Parameter | Description |
| --------- | ----------- |
| `name` | name of the ReplicaSet |
| `namespace` | object name and auth scope, such as for teams and projects |

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |

### apis.extensions.v1beta1.namespaces(namespace).replicasets(name).get

read the specified ReplicaSet

#### Path

| Parameter | Description |
| --------- | ----------- |
| `name` | name of the ReplicaSet |
| `namespace` | object name and auth scope, such as for teams and projects |

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.exact` | Should the export be exact.  Exact export maintains cluster-specific fields like &#39;Namespace&#39;. |
| `qs.export` | Should this value be exported.  Export strips fields that a user can not specify. |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |

### apis.extensions.v1beta1.namespaces(namespace).replicasets.get

list or watch objects of kind ReplicaSet

#### Path

| Parameter | Description |
| --------- | ----------- |
| `namespace` | object name and auth scope, such as for teams and projects |

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.fieldSelector` | A selector to restrict the list of returned objects by their fields. Defaults to everything. |
| `qs.includeUninitialized` | If true, partially initialized resources are included in the response. |
| `qs.labelSelector` | A selector to restrict the list of returned objects by their labels. Defaults to everything. |
| `qs.resourceVersion` | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. |
| `qs.timeoutSeconds` | Timeout for the list&#x2F;watch call. |
| `qs.watch` | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |

### apis.extensions.v1beta1.watch.namespaces(namespace).replicasets(name).get

watch changes to an object of kind ReplicaSet

#### Path

| Parameter | Description |
| --------- | ----------- |
| `name` | name of the ReplicaSet |
| `namespace` | object name and auth scope, such as for teams and projects |

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.fieldSelector` | A selector to restrict the list of returned objects by their fields. Defaults to everything. |
| `qs.includeUninitialized` | If true, partially initialized resources are included in the response. |
| `qs.labelSelector` | A selector to restrict the list of returned objects by their labels. Defaults to everything. |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |
| `qs.resourceVersion` | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. |
| `qs.timeoutSeconds` | Timeout for the list&#x2F;watch call. |
| `qs.watch` | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. |

### apis.extensions.v1beta1.watch.namespaces(namespace).replicasets.get

watch individual changes to a list of ReplicaSet

#### Path

| Parameter | Description |
| --------- | ----------- |
| `namespace` | object name and auth scope, such as for teams and projects |

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.fieldSelector` | A selector to restrict the list of returned objects by their fields. Defaults to everything. |
| `qs.includeUninitialized` | If true, partially initialized resources are included in the response. |
| `qs.labelSelector` | A selector to restrict the list of returned objects by their labels. Defaults to everything. |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |
| `qs.resourceVersion` | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. |
| `qs.timeoutSeconds` | Timeout for the list&#x2F;watch call. |
| `qs.watch` | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. |

### apis.extensions.v1beta1.watch.replicasets.get

watch individual changes to a list of ReplicaSet

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.fieldSelector` | A selector to restrict the list of returned objects by their fields. Defaults to everything. |
| `qs.includeUninitialized` | If true, partially initialized resources are included in the response. |
| `qs.labelSelector` | A selector to restrict the list of returned objects by their labels. Defaults to everything. |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |
| `qs.resourceVersion` | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. |
| `qs.timeoutSeconds` | Timeout for the list&#x2F;watch call. |
| `qs.watch` | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. |

### apis.extensions.v1beta1.replicasets.get

list or watch objects of kind ReplicaSet

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.fieldSelector` | A selector to restrict the list of returned objects by their fields. Defaults to everything. |
| `qs.includeUninitialized` | If true, partially initialized resources are included in the response. |
| `qs.labelSelector` | A selector to restrict the list of returned objects by their labels. Defaults to everything. |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |
| `qs.resourceVersion` | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. |
| `qs.timeoutSeconds` | Timeout for the list&#x2F;watch call. |
| `qs.watch` | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. |

## write

### apis.extensions.v1beta1.namespaces(namespace).replicasets(name).status.patch

partially update status of the specified ReplicaSet

#### Path

| Parameter | Description |
| --------- | ----------- |
| `name` | name of the ReplicaSet |
| `namespace` | object name and auth scope, such as for teams and projects |

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |

#### Body

| Parameter | Description |
| --------- | ----------- |
| `body` | #&#x2F;definitions&#x2F;io.k8s.apimachinery.pkg.apis.meta.v1.Patch |

### apis.extensions.v1beta1.namespaces(namespace).replicasets(name).status.put

replace status of the specified ReplicaSet

#### Path

| Parameter | Description |
| --------- | ----------- |
| `name` | name of the ReplicaSet |
| `namespace` | object name and auth scope, such as for teams and projects |

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |

#### Body

| Parameter | Description |
| --------- | ----------- |
| `body` | #&#x2F;definitions&#x2F;io.k8s.kubernetes.pkg.apis.extensions.v1beta1.ReplicaSet |

### apis.extensions.v1beta1.namespaces(namespace).replicasets(name).delete

delete a ReplicaSet

#### Path

| Parameter | Description |
| --------- | ----------- |
| `name` | name of the ReplicaSet |
| `namespace` | object name and auth scope, such as for teams and projects |

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.gracePeriodSeconds` | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. |
| `qs.orphanDependents` | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true&#x2F;false, the &quot;orphan&quot; finalizer will be added to&#x2F;removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. |
| `qs.propagationPolicy` | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |

#### Body

| Parameter | Description |
| --------- | ----------- |
| `body` | #&#x2F;definitions&#x2F;io.k8s.apimachinery.pkg.apis.meta.v1.DeleteOptions |

### apis.extensions.v1beta1.namespaces(namespace).replicasets(name).patch

partially update the specified ReplicaSet

#### Path

| Parameter | Description |
| --------- | ----------- |
| `name` | name of the ReplicaSet |
| `namespace` | object name and auth scope, such as for teams and projects |

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |

#### Body

| Parameter | Description |
| --------- | ----------- |
| `body` | #&#x2F;definitions&#x2F;io.k8s.apimachinery.pkg.apis.meta.v1.Patch |

### apis.extensions.v1beta1.namespaces(namespace).replicasets(name).put

replace the specified ReplicaSet

#### Path

| Parameter | Description |
| --------- | ----------- |
| `name` | name of the ReplicaSet |
| `namespace` | object name and auth scope, such as for teams and projects |

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |

#### Body

| Parameter | Description |
| --------- | ----------- |
| `body` | #&#x2F;definitions&#x2F;io.k8s.kubernetes.pkg.apis.extensions.v1beta1.ReplicaSet |

### apis.extensions.v1beta1.namespaces(namespace).replicasets.delete

delete collection of ReplicaSet

#### Path

| Parameter | Description |
| --------- | ----------- |
| `namespace` | object name and auth scope, such as for teams and projects |

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.fieldSelector` | A selector to restrict the list of returned objects by their fields. Defaults to everything. |
| `qs.includeUninitialized` | If true, partially initialized resources are included in the response. |
| `qs.labelSelector` | A selector to restrict the list of returned objects by their labels. Defaults to everything. |
| `qs.resourceVersion` | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. |
| `qs.timeoutSeconds` | Timeout for the list&#x2F;watch call. |
| `qs.watch` | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |

### apis.extensions.v1beta1.namespaces(namespace).replicasets.post

create a ReplicaSet

#### Path

| Parameter | Description |
| --------- | ----------- |
| `namespace` | object name and auth scope, such as for teams and projects |

#### Query

| Parameter | Description |
| --------- | ----------- |
| `qs` | Querystring object |
| `qs.pretty` | If &#39;true&#39;, then the output is pretty printed. |

#### Body

| Parameter | Description |
| --------- | ----------- |
| `body` | #&#x2F;definitions&#x2F;io.k8s.kubernetes.pkg.apis.extensions.v1beta1.ReplicaSet |

