# 🌩️ CORA - Cloud Operations and Resource Assistant

![CORA Banner](https://via.placeholder.com/1000x300.png?text=CORA+Cloud+Operations+and+Resource+Assistant)

## 🚀 Overview

Welcome to **CORA** - your GEN-AI powered assistant for managing cloud operations effortlessly! 🌟 With CORA, you can interact with your cloud resources through simple and intuitive natural language commands. Whether it's **AWS**, **Azure**, or **GCP**, CORA has got you covered! 🔥

---

## 💡 What Can CORA Do?

CORA is designed to make cloud management a breeze by understanding your requests and executing commands in real time. Here's what CORA can help you with:

### 🖥️ **Resource Management**
- 🕵️‍♂️ **"How many servers are running in Mumbai?"**
- 💻 **"Start two new EC2 instances in us-east-1."**
- 📦 **"List all available S3 buckets."**

### 📈 **Monitoring & Logs**
- 📄 **"Tail the logs from my CloudWatch group."**
- 📊 **"Show me the CPU utilization of my Azure VMs."**

### 💸 **Cost Management**
- 💰 **"How much did I spend on AWS this month?"**
- 🏷️ **"List my top 5 most expensive services."**

### 🔐 **Security & Compliance**
- 🛡️ **"Are there any open security groups in my AWS environment?"**
- 🔒 **"What are the IAM roles attached to my EC2 instance?"**

---

## 🤖 How It Works

Just ask CORA a question, and she’ll take care of the rest! 💫  
CORA uses **Microsoft Autogen**, a multi-agent conversation framework, to understand and process your cloud-related queries. CORA relies on pre-defined scripts and **Terraform templates** to fetch real-time data and provide accurate responses from your cloud environments. Whether it's AWS, Azure, or GCP, CORA speaks your cloud language! 🌍

---

## 🌍 Supported Cloud Platforms
- **AWS** (Amazon Web Services) ☁️
- **Azure** (Microsoft Azure) 🔵
- **Google Cloud** (GCP) 🌤️

---

## ✨ Features

- **Multi-cloud support**: Seamlessly query resources across AWS, Azure, and GCP.
- **Natural language queries**: Talk to CORA like you would to a human assistant.
- **Real-time responses**: Get instant updates on your cloud resources.
- **Cost efficiency**: Stay on top of your cloud spending with detailed cost breakdowns.
- **Secure operations**: Keep track of your security policies with ease.

## ⚠️ Security & Prompt Jacking Protection

To ensure the security of your cloud accounts and avoid **prompt jacking**, CORA is restricted to **GET/READ** requests only. This means that CORA **cannot create, modify, or delete resources**, protecting your infrastructure from unintended actions. However, if desired, it is possible to provide CORA with the ability to perform **write** operations, but we highly recommend keeping the default read-only permissions for maximum safety.

---

