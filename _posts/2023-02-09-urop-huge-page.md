---
date: 2023-02-09 10:17:40
layout: post
title: Performance Analysis of Memory-intensive Workloads with Huge Page in Container Environment
subtitle: Essay for 2022 UROP program / SSLAB
description: Essay for 2022 UROP program / SSLAB
image: https://res.cloudinary.com/drgsu4lyo/image/upload/v1676907017/%ED%99%94%EB%A9%B4_%EC%BA%A1%EC%B2%98_2023-02-21_002959_d8zm5f.jpg
optimized_image: https://res.cloudinary.com/drgsu4lyo/image/upload/v1676907017/%ED%99%94%EB%A9%B4_%EC%BA%A1%EC%B2%98_2023-02-21_002959_d8zm5f.jpg
category: research
tags:
  - SSLAB
  - HugePage
  - Docker
author: Sujin
paginate: true
---

<h1>Details</h1>
Please check out what I did.<br/>

[Paper](https://drive.google.com/file/d/1kCkqcnq2VnPor6jq3iVEsQ6kCWkevPew/view?usp=sharing) //
[Notion page for research](https://waterjin.notion.site/Cold-Start-3a28c5ad12194b6b9f8e28a55a3138dd)

<h1>Abstract</h1>
The HugePage is a page whose unit size is larger than that of the NormalPage (4KB). <br/> The use of HugePage increases TLB hit ratio by reducing the number of pages required to represent the same amount of memory, thus speeding up data access. <br/>For this reason, HugePage is known to be efficient especially in memory-intensive workloads. <br/>In this paper, our aim is to evaluate the effect of HugePage in a container environment.<br/>To do so, we run the containerized memory-intensive workloads in a Linux server and compare the performance results of the workloads with and without Huge Page. <br/>Our experimental results show that the HugePage has a significant impact on the performance of memory-intensive workloads even in a container environment. 

<h1>Keywords</h1>
Huge Page, Memory intensive workloads, Container <br/>