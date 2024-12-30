---
author: Swastik G N
pubDatetime: 2024-12-28
title: An Introduction to Redis
slug: an-intro-to-redis
featured: true
draft: false
tags:
  - redis

description:
  A short introduction to Redis
---

## Table of contents 


## Introduction
Redis stands for REmote Dictionary Server.
It is an in-memory data structure store that can be used as a primary database,cache, or queue.
While Redis' primary use case is caching, it can also serve as a database and message broker.
Redis is very fast because it stores data in memory, reducing the need for slower disk-based retrieval.
Redis supports various data structures, including strings,sets, lists, and more.

## Setup  
We will use docker to run redis server and python library redis-py to connect to the server.
 
1. start the server
```bash
docker run -p 6379:6379 -it redis/redis-stack:latest
```
2. create a virtual environment 
```bash
python3 venv -m venv 
```
3. activate the virtual environment
```bash
source venv/bin/activate
```
4. install redis-py
```bash
pip install redis
```
5. create a file and open it in your favourite editor
```bash 
touch main.py
```
 