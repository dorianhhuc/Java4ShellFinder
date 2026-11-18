# Java4ShellFinder

## Introduction

This playbook contains one role:
- **java4shellfinder**
    - Checks if CPU flags exist for Java4Shell exploitation
    - Lists running Java processes on vulnerable machines
    - Ensures reports directory exists locally
    - Writes Java4Shell reports per individual inventory host to reports directory

## Usage

Run the following command:

`ansible-playbook -v -i environment/production/inventory --timeout=1 playbook.yml`

