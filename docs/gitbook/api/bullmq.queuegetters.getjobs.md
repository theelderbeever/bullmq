<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [QueueGetters](./bullmq.queuegetters.md) &gt; [getJobs](./bullmq.queuegetters.getjobs.md)

## QueueGetters.getJobs() method

<b>Signature:</b>

```typescript
getJobs(types: string[] | string, start?: number, end?: number, asc?: boolean): Promise<Job<any, any, string>[]>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  types | string\[\] \| string |  |
|  start | number |  |
|  end | number |  |
|  asc | boolean |  |

<b>Returns:</b>

Promise&lt;[Job](./bullmq.job.md)<!-- -->&lt;any, any, string&gt;\[\]&gt;
