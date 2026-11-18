# Java4ShellFinder

## Introduction

This playbook contains one role:
- **java4shellfinder**
    - Checks if CPU flags exist for Java4Shell exploitation
    - Lists running Java processes on vulnerable machines
    - Summarizes findings
    - Ensures reports directory exists locally
    - Saves output locally to reports directory, per inventory hostname

## Usage

Run the following command:

`ansible-playbook -v -i environment/production/inventory --timeout=1 playbook.yml`

