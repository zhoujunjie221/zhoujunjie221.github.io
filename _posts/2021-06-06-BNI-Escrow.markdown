---
layout: post
title:  BNI银行Escrow监管账户API接入说明
date:   2021-06-06 18:37:00 +0700
categories: PRD files
description: 关于 BNI 银行 Escrow 监管账户 API 接入流程的完整说明
keyword: BNI,Escrow,API,接入流程
---

1.The customer performs SIT with a sandbox and creates a credential development API at the address: https://digitalservices.bni.co.id
    - with a sandbox endpoint: https://apidev.bni.co.id:8067
    - File Attached: [How To Generate Credentials PORTAL SANDBOX.pdf](/assets/files/BNI-ESCROW/How-To-Generate-Credentials-PORTAL-SANDBOX.pdf)
    - Video Tutorial: [How to create BNI on Sandbox API credential key](https://youtu.be/JomHszcAhqg)
    - Video Tutorial: [How To Generate Token and JWT Signature API BNI On Sandbox](https://youtu.be/RboI7aiwsyk)

1.接入BNI测试环境需要进入沙盒后台进行接入配置。配置地址为:https://digitalservices.bni.co.id
    - 沙盒环境接口地址: https://apidev.bni.co.id:8067
    - 沙盒环境配置说明: [How To Generate Credentials PORTAL SANDBOX.pdf](/assets/files/BNI-ESCROW/How-To-Generate-Credentials-PORTAL-SANDBOX.pdf)
    - 沙盒环境API Key配置说明: [How to create BNI on Sandbox API credential key](https://youtu.be/JomHszcAhqg)
    - 沙盒环境Token及签名说明: [How To Generate Token and JWT Signature API BNI On Sandbox](https://youtu.be/RboI7aiwsyk)

------

2.SIT stage: based on the Technical Document, then fill out the testing document (Sample Result of SIT RDL P2P Lending) and send it via email api.onboarding@bni.co.id
    - File Attached: [BNI P2P Lending Service](/assets/files/BNI-ESCROW/BNI-P2P-Lending-Service-v1.5.pdf)
    - File Attached: [API P2PL (RDL) Testing Document_Client](/assets/files/BNI-ESCROW/API-P2PL(RDL)-Testing-Document_Client.docx)

2.SIT阶段：根据技术文档，填写测试文档（Sample Result of SIT RDL P2P Lending）并通过email(onboarding@bni.co.id)向BNI发送结果。
    - 接入说明: [BNI P2P Lending Service](/assets/files/BNI-ESCROW/BNI-P2P-Lending-Service-v1.5.pdf)
    - 测试文档: [API P2PL (RDL) Testing Document_Client](/assets/files/BNI-ESCROW/API-P2PL(RDL)-Testing-Document_Client.docx)

------

3.The queue enters the UAT Stage, for this we ask for help conveying the IP Address of the PC that accesses the Development environment so that we can process the Whitelist

3.进入UAT阶段，需要向BNI提交请求IP，BNI需要处理白名单

------

4.Stages of UAT: Doing Testing based on Documents that will be sent by the onboarding fire team

4.UAT阶段：BNI会提交一个测试验收文件，需要根据这个测试验收文件进行测试验收

------

5.Submit the UAT Document to the email address api.onboarding@bni.co.id, the BNI Team will check the UAT document, and if it is appropriate we will send the production credential and promote Production at the url: https://api.bni.co.id

5.将填写完成的UAT测试验收文件发送到邮箱api.onboarding@bni.co.id，BNI团队会检查UAT文件，如果合格BNI会提供生产环境接入凭证。然后可以使用正式环境接口地址进行访问: https://api.bni.co.id

------

6.Filling PIR Documentation on the production env by trying all the features on RDL for 7 HK after being promoted.

For RDL Callback Notification needs (Technical Document: attached RDL Technical Documentation) please send the following information:

RDL Dev Callback URL Address
RDL Prod Callback URL Address
Email address for sending credential key URL Callback RDL
 
As the underlying in the production stage, please send information 2 Email address for sending Credential key Production (pic email 1 for zip file containing credentials, pic email 2 containing zip password)​