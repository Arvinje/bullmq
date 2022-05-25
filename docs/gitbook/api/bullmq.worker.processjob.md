<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [Worker](./bullmq.worker.md) &gt; [processJob](./bullmq.worker.processjob.md)

## Worker.processJob() method

<b>Signature:</b>

```typescript
processJob(job: Job<DataType, ResultType, NameType>, token: string): Promise<void | Job<DataType, ResultType, NameType>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  job | [Job](./bullmq.job.md)<!-- -->&lt;DataType, ResultType, NameType&gt; |  |
|  token | string |  |

<b>Returns:</b>

Promise&lt;void \| [Job](./bullmq.job.md)<!-- -->&lt;DataType, ResultType, NameType&gt;&gt;
