Modern airports face significant challenges in managing passenger queues due to increasing traveler volumes and highly dynamic movement patterns. Traditional queue management methods rely on manual observation and fixed schedules, making them inefficient and slow to respond.

This project presents an AI-powered multimodal queue management system that integrates Computer Vision and Internet of Things (IoT) technologies to enable real-time, scalable, and intelligent queue monitoring in smart airports. The system leverages edge computing using Raspberry Pi devices to detect, track, and count passengers accurately, even in crowded environments.

Objectives

Enable real-time passenger counting and queue monitoring

Improve airport operational efficiency

Reduce passenger waiting time

Provide data-driven decision support for airport staff

System Architecture

The system combines visual sensors, embedded devices, and wireless communication:

Edge Devices: Raspberry Pi (3 / 4 / 5)

Cameras: Pi Camera or USB Camera

AI Models: Lightweight deep learning models deployed on-device

Communication: MQTT-based wireless messaging

Dashboard: Web-based monitoring using Flask/Django

All video processing and people counting are performed on the edge, reducing latency and bandwidth
