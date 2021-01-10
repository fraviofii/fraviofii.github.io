---
layout: post
title:  "C++ build project for NuttX using cmake"
author: flavio
categories: [ c++, nuttx, tutorial ]
tags: [red, yellow]
description: "Description on how to build a C++ project for NuttX using CMake"
featured: true
hidden: true
rating: 4.5
---

## Introduction

This article has the objective to describe a cmake-base project used to build a NuttX based application using C++ language.

## Requirements

* A NuttX based library with the correct endpoint set for the application
* Toolchain configured
* JLink tools

## Result

The following link shows an application example: https://github.com/Phi-Innovations/nuttx-apps/tree/main/hellocpp

## References

* [Build NuttX on STM32F4Discovery](https://cwiki.apache.org/confluence/display/NUTTX/STM32F4DISCOVERY+Unix)
* [Install C++ library on Nuttx](https://bitbucket.org/nuttx/uclibc/src/master)
* [Instructions to build Nuttx as library](https://acassis.wordpress.com/2020/06/28/using-nuttx-as-library-once-again)
