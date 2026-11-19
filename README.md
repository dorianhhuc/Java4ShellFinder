# Java4ShellFinder

## Introduction

This playbook contains one role:
- **java4shellfinder**
    - Check if CPU flags exist for Java4Shell exploitation
    - List running Java versions (if executable is host-resolvable) and processes on vulnerable machines
    - Check if Docker is installed
    - List all Docker containers and their Java versions and processes on vulnerable machines
    - Summarize findings (no Docker)
    - Summarize findings (with Docker)
    - Ensure reports directory exists locally
    - Save output locally to reports directory, per inventory hostname (no Docker)
    - Save output locally to reports directory, per inventory hostname (with Docker)

## Usage

Run the following command:

`ansible-playbook -v -i environment/production/inventory --timeout=1 playbook.yml`

