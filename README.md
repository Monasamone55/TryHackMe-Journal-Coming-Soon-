Linux Notes 
Its an Open source Operating System

The name "Linux" is actually an umbrella term for multiple OS's that are based on UNIX (another operating system). Thanks to Linux being open-source, variants of Linux come in all shapes and sizes - suited best for what the system is being used for.

For example, Ubuntu & Debian are some of the more commonplace distributions of Linux because it is so extensible. I.e. you can run Ubuntu as a server (such as websites & web applications) or as a fully-fledged desktop. 
For this series, we're going to be using Ubuntu.

Linux is considerably much more lightweight and you'd be surprised to know that there's a good chance you've used Linux in some form or another every day! Linux powers things such as:

Websites that you visit
Car entertainment/control panels
Point of Sale (PoS) systems such as checkout tills and registers in shops
Critical infrastructures such as traffic light controllers or industrial sensors
Log Notes 

Logs serve as invaluable records of past events, providing essential insights to address these questions. By preserving an archive of historical activities, we can bolster our security posture and protect our digital assets more effectively.

Log analysis tools and methods empower individuals to interpret historical events and establish a reliable source of historical evidence, streamlining the processing and scrutiny of log data. This efficiency facilitates prompt detection and response to potential incidents or significant events.

Both embody a fundamental principle of growth over time and serve as living records in their respective domains – physical and digital.

Specific log types can offer a unique perspective on a system's operation, performance, and security. While there are various log types, we will focus on the most common ones that cover approximately 80% of the typical use cases.

Application Logs: Messages about specific applications, including status, errors, warnings, etc.
Audit Logs: Activities related to operational procedures crucial for regulatory compliance.
Security Logs: Security events such as logins, permissions changes, firewall activity, etc.
Server Logs: Various logs a server generates, including system, event, error, and access logs.
System Logs: Kernel activities, system errors, boot sequences, and hardware status.
Network Logs: Network traffic, connections, and other network-related events.
Database Logs: Activities within a database system, such as queries and updates.
Web Server Logs: Requests processed by a web server, including URLs, response codes, etc.

A log format defines the structure and organization of data within a log file. It specifies how the data is encoded, how each entry is delimited, and what fields are included in each row. These formats can vary widely and may fall into three main categories: Semi-structured, Structured, and Unstructured. We'll explore these categories and illustrate their usage with examples.

Semi-structured Logs: These logs may contain structured and unstructured data, with predictable components accommodating free-form text. Examples include:

Syslog Message Format: A widely adopted logging protocol for system and network logs.
