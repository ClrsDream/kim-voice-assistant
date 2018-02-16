# 介绍 

Kim Voice Assistant是一款开源智能语音助理（智能音箱），灵感来自外国友人的开源项目 [jasper-client](http://jasperproject.github.io/)。Kim在安装、本土化、控制方式等方面提出了不少改进方案，使得项目更容易安装，可玩性也有不少提升。

[![Build Status](https://travis-ci.org/Chyroc/kim-voice-assistant-iot-client.svg?branch=master)](https://github.com/Chyroc/WechatSogou)
[![PyPI version](https://badge.fury.io/py/kim-voice-assistant-iot-client.svg)](https://github.com/Chyroc/WechatSogou)
[![PyPI](https://img.shields.io/pypi/wheel/kim-voice-assistant-iot-client.svg)](https://github.com/Chyroc/WechatSogou)
[![py27,py35,py36](https://img.shields.io/pypi/pyversions/kim-voice-assistant-iot-client.svg)](https://github.com/Chyroc/WechatSogou)
[![PyPI](https://img.shields.io/pypi/l/kim-voice-assistant-iot-client.svg)](https://github.com/Chyroc/WechatSogou)

## 特性

1. 基于Alibaba Cloud Services构建
1. 通过Docker管理运行环境，支持快速安装部署
1. 优化中文语义仲裁算法，更加精准的理解中文语义
2. 可选安装Web和OpenAPI控制方案，提供丰富的设备的控制方式
2. 支持树莓派（或其他物联网硬件）、macOS、PC，跨平台安装运行

## 组成

| 名称 | 描述 | 链接 |
|----|----|----|
| Kim Voice Assistant Dock | Kim服务运行Docker构建项目（设备端和服务端）  | [Dock](https://github.com/tenstone/kim-voice-assistant-dock) |
| Kim Voice Assistant Iot Client | Kim设备端项目 | [Client](https://github.com/tenstone/kim-voice-assistant-iot-client) |
| Kim Voice Assistant Server | Kim服务器端项目 | [Server](https://github.com/tenstone/kim-voice-assistant-server) |

# 安装

通过Dockerfile构建镜像







