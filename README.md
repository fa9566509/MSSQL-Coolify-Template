# Coolify MSSQL Template

This repository provides a well-structured template for running Microsoft SQL Server (MSSQL) on Coolify with built-in support for automated backups to S3.

## Features

- **MSSQL Server** running inside a container.
- **Backup Automation**: Automated backups using SQL Server `BACKUP` command.
- **S3 Integration**: Uploads backups directly to an S3-compatible bucket.
- **Customizable**: Supports custom database names and schedules.

## Requirements

- [Coolify](https://coollabs.io) installed.
- An S3-compatible storage (AWS S3, DigitalOcean Spaces, etc.).
- Docker and Docker Compose.

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/coolify-mssql-template.git
   cd coolify-mssql-template
