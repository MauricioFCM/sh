---
title: getUploadUrl
permalink: /backend-integration/healthstack-adapter/healthstack.backend.integration.adapter/-health-stack-backend-a-p-i/get-upload-url.html

sidebar: dev_doc_sidebar
---
//[healthstack-adapter](../../../index.html)/[healthstack.backend.integration.adapter](../index.html)/[HealthStackBackendAPI](index.html)/[getUploadUrl](get-upload-url.html)



# getUploadUrl



[androidJvm]\




@GET(value = &quot;/cloud-storage/projects/{projectId}/participants/upload-url&quot;)



abstract suspend fun [getUploadUrl](get-upload-url.html)(@Header(value = &quot;id-token&quot;)idToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), @Path(value = &quot;projectId&quot;)projectId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), @Query(value = &quot;object_name&quot;)objectName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)




