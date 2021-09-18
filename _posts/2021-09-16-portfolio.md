---
layout: post
topmost: true
title: My Portfolio
categories: FullStackWebsite MobileApplication MedicalSoftware UsefulTool
description: 通过 XXL-JOB 的分片广播机制，实现灵活控制的并发数控制。
keywords: Portfolio
---

some statements

## Full Stack Websites

现在一张数据表里有大量数据需要某个服务端应用来处理，要求：

1. 能够并行处理；
2. 能够较灵活地控制并行任务数量。
3. 压力较均衡地分散到不同的服务器节点；

## Mobile Applications

因为需要并行处理同一张数据表里的数据，所以比较自然地想到了分片查询数据，可以利用对 id 取模的方法进行分片，避免同一条数据被重复处理。

根据第 1、2 点要求，本来想通过对线程池的动态配置来实现，但结合第 3 点来考虑，服务器节点数量有可能会变化，节点之间相互无感知无通信，自己在应用内实现一套调度机制可能会很复杂。

如果有现成的独立于这些服务器节点之外的调度器就好了——顺着这个思路，就想到了已经接入的分布式任务调度平台 XXL-JOB，而在阅读其 [官方文档][1] 后发现「分片广播 & 动态分片」很贴合这种场景。

![](/images/posts/java/mobile-applications.png)

## Medical Softwares

## Useful Tools

## What's Next?