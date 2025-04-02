# Ansible Role: Wintel Readiness

## Description

Provide a concise description of what your role does.  What problem does it solve?  What functionality does it provide?

## Requirements

List any prerequisites or dependencies for the role to function correctly.  This might include specific versions of Ansible, operating systems, or other roles.

## Role Variables

Describe the role variables that can be configured.  Include the following information for each variable:

*   **Name:** [Variable Name]
*   **Type:** [Variable Type (e.g., string, integer, list)]
*   **Default:** [Default Value]
*   **Description:** [A brief description of the variable's purpose and how it affects the role]
*   **Example:** [Provide an example of how to set this variable]

## Dependencies

List any other Ansible roles that this role depends on.

## Usage

Provide instructions on how to use the role in a playbook.  Include examples of how to include the role and set any necessary variables.

## Example Playbook

```yaml
- hosts: all
  become: true  # Or false, depending on the role's needs
  roles:
    - role: [Your Role Name]
      # Optional:  Set role variables here
      [Your Role Variable]: [Variable Value]