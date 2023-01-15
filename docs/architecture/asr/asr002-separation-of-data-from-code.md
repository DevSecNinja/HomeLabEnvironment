# #ASR002-separation-of-data-from-code

## Purpose

The purpose of this requirement is to ensure that the data (configurations, settings)
of the system is separate from the code to improve
maintainability, security and scalability.

## Description

The system must have the data (configurations, settings) separate from the code.
This means that the data should be stored in separate files, or in a
configuration management tool such as Ansible, Chef or Puppet. This will improve
maintainability, security and scalability by allowing for easy updates and rollbacks
of the data, and by allowing for different data for different environments,
such as development, staging, and production.

## Acceptance Criteria

- [ ] The data (configurations, settings) of the system is separate from the code
- [ ] Data is stored in separate files, or in a configuration management tool
- [ ] Data is easily updated and rolled back
- [ ] Different data can be used for different environments
- [ ] Data is separated from code for improved maintainability, security, and scalability
