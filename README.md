[README_Bell_Ringing_System.md](https://github.com/user-attachments/files/24973629/README_Bell_Ringing_System.md)
# Automated School Bell Ringing System

## Overview

This project is an ESP-based automated school bell ringing system
designed to ring a buzzer at the start and end of lessons, tea breaks,
and lunch breaks based on a configurable timetable. The system uses
Wi‑Fi and a built-in web server to allow teachers or administrators to
manage schedules through a browser.

## Features

-   Automated bell ringing based on real-time clock (NTP)
-   Web-based interactive timetable dashboard
-   Lesson, tea break, and lunch break support
-   Color‑coded timetable (Lessons vs Breaks)
-   Manual override for testing and emergency assemblies
-   Reliable and accurate time management

## Hardware Requirements

-   ESP‑12E (ESP8266)
-   Active buzzer
-   Power supply (5V / USB)
-   Connecting wires

## Software Requirements

-   Arduino IDE (v2.3.4 or later)
-   ESP8266 Board Package
-   Required libraries:
    -   ESP8266WiFi
    -   ESP8266WebServer
    -   WiFiUdp
    -   NTPClient

## How It Works

1.  ESP connects to Wi‑Fi and synchronizes time using NTP.
2.  A web server runs on the ESP.
3.  Teachers access the dashboard via a browser.
4.  Lesson and break times are added or updated.
5.  When the current time matches a scheduled event, the buzzer rings
    automatically.

## Applications

-   Schools and colleges
-   Training institutions
-   Automated time management systems

## Advantages

-   Eliminates manual bell operation
-   Accurate and consistent ringing
-   Easy schedule updates
-   Low cost and scalable

## Author

Bell Ringing Automation Project
