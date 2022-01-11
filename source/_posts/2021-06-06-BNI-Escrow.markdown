---
layout: post
title:  BNI银行Escrow监管账户API接入说明
date:   2021-06-06 18:37:00 +0700
categories: PRD
description: 关于 BNI 银行 Escrow 监管账户 API 接入流程的完整说明
permalink: /prd/files/2021/06/06/BNI-Escrow.html
cover: /assets/img/blue-g75366fb19_1280.jpg
thumbnail: /assets/img/blue-g75366fb19_1280.jpg
tags: 
    - BNI
    - Escrow
    - API
    - 接入流程
---

{% raw %}<div class="post-summary">{% endraw %}

关于 BNI 银行 Escrow 监管账户 API 接入流程的完整说明

{% raw %}</div>{% endraw %}

<!-- more -->

<style type="text/css">
.post-summary { display: none; }
</style>

# 1.配置沙盒测试
The customer performs SIT with a sandbox and creates a credential development API at the address: https://digitalservices.bni.co.id
- with a sandbox endpoint: https://apidev.bni.co.id:8067
- File Attached: {% asset_link How-To-Generate-Credentials-PORTAL-SANDBOX.pdf How To Generate Credentials PORTAL SANDBOX %}
- Video Tutorial: [How to create BNI on Sandbox API credential key](https://youtu.be/JomHszcAhqg)
- Video Tutorial: [How To Generate Token and JWT Signature API BNI On Sandbox](https://youtu.be/RboI7aiwsyk)

接入BNI测试环境需要进入沙盒后台进行接入配置。配置地址为:https://digitalservices.bni.co.id
- 沙盒环境接口地址: https://apidev.bni.co.id:8067
- 沙盒环境配置说明: {% asset_link How-To-Generate-Credentials-PORTAL-SANDBOX.pdf How To Generate Credentials PORTAL SANDBOX %}
- 沙盒环境API Key配置说明: [How to create BNI on Sandbox API credential key](https://youtu.be/JomHszcAhqg)
- 沙盒环境Token及签名说明: [How To Generate Token and JWT Signature API BNI On Sandbox](https://youtu.be/RboI7aiwsyk)

------
# 2.填写沙盒环境测试文档
SIT stage: based on the Technical Document, then fill out the testing document (Sample Result of SIT RDL P2P Lending) and send it via email api.onboarding@bni.co.id
- File Attached: {% asset_link BNI-P2P-Lending-Service-v1.5.pdf BNI P2P Lending Service %}
- File Attached: {% asset_link API-P2PL(RDL)-Testing-Document_Client.docx API P2PL (RDL) Testing Document_Client %}

 SIT阶段：根据技术文档，填写测试文档（Sample Result of SIT RDL P2P Lending）并通过email(onboarding@bni.co.id)向BNI发送结果。
- 接入说明: {% asset_link BNI-P2P-Lending-Service-v1.5.pdf BNI P2P Lending Service %}
- 测试文档: {% asset_link API-P2PL(RDL)-Testing-Document_Client.docx API P2PL (RDL) Testing Document_Client %}

------
# 3.提交白名单IP
The queue enters the UAT Stage, for this we ask for help conveying the IP Address of the PC that accesses the Development environment so that we can process the Whitelist

进入UAT阶段，需要向BNI提交请求IP，BNI需要处理白名单

------
# 4.UAT测试
Stages of UAT: Doing Testing based on Documents that will be sent by the onboarding fire team

UAT阶段：BNI会提交一个测试验收文件，需要根据这个测试验收文件进行测试验收

------
# 5.提交UAT测试文件，获取生产环境配置
Submit the UAT Document to the email address api.onboarding@bni.co.id, the BNI Team will check the UAT document, and if it is appropriate we will send the production credential and promote Production at the url: https://api.bni.co.id

将填写完成的UAT测试验收文件发送到邮箱api.onboarding@bni.co.id，BNI团队会检查UAT文件，如果合格BNI会提供生产环境接入凭证。然后可以使用正式环境接口地址进行访问: https://api.bni.co.id

------
# 6.填写RDL审查文件
Filling PIR Documentation on the production env by trying all the features on RDL for 7 HK after being promoted.

For RDL Callback Notification needs (Technical Document: attached RDL Technical Documentation) please send the following information:

RDL Dev Callback URL Address
RDL Prod Callback URL Address
Email address for sending credential key URL Callback RDL
 
As the underlying in the production stage, please send information 2 Email address for sending Credential key Production (pic email 1 for zip file containing credentials, pic email 2 containing zip password)​

# 其他附件
- {% asset_link API-P2PL(RDL)-Testing-Document_Client.docx API P2PL (RDL) Testing Document_Client %}
- {% asset_link BNI-P2P-Lending-Service-v1.5.pdf BNI P2P Lending Service v1.5 %}
- {% asset_link Contoh-Hasil-SIT-RDL-P2P-Lending.docx Contoh Hasil SIT RDL P2P Lending %}
- {% asset_link How-To-Generate-Credentials-PORTAL-SANDBOX.pdf How To Generate Credentials PORTAL SANDBOX %}
- {% asset_link List-Bank-P2P-Lending.xlsx List Bank P2P Lending %}
- {% asset_link RDL-Technical-Documentation-1.0.2.pdf RDL Technical Documentation 1.0.2 %}