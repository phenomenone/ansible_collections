# pichincha.sre

The collection title should indicate, at a high level, what the collection is for. 

## Description

Esta colleción se encarga de la automatización de tareas de monitoreo/readiness para plataformas y aplicaciones Windows, Unix, VMWare, F5, Kafka entre otras para el BP.


## Requirements

- Ansible: >= 2.4
- Python: >= 3.8

## Installation

Antes de utilizar esta collección, usted necesita instalar 'Ansible Galaxy command-line tool':

```
ansible-galaxy collection install NAMESPACE.COLLECTION_NAME
```
Tambien se puede incluir en un archivo requirements.yml y se intala con 'ansible-galaxy collection install -r requirements.yml' utilizando el siguiente formato de configuración:

```yaml
collections:
  - name: NAMESPACE.COLLECTION_NAME
```

Note that if you install any collections from Ansible Galaxy, they will not be upgraded automatically when you upgrade the Ansible package.
To upgrade the collection to the latest available version, run the following command:

```
ansible-galaxy collection install NAMESPACE.COLLECTION_NAME --upgrade
```

You can also install a specific version of the collection, for example, if you need to downgrade when something is broken in the latest version (please report an issue in this repository). Use the following syntax to install version 1.0.0:

```
ansible-galaxy collection install NAMESPACE.COLLECTION_NAME:==1.0.0
```

See [using Ansible collections](https://docs.ansible.com/ansible/devel/user_guide/collections_using.html) for more details.


In addition to the above boilerplate, this section should include any additional details specific to your collection, and what to expect at each step and after installation. Be sure to include any information that supports the installation process, such as information about authentication and credentialing. 

## Use Cases

This section should outline in detail 3-5 common use cases for the collection. These should be informative examples of how the collection has been used, or how you’d like to see it be used. 


## Testing

This section should include information on how the collection was tested and how it performed. Include information on what environments it’s been tested against, and any known exceptions or workarounds necessary for its use.



## Contributing (Optional)

This section is optional, and provides a section to describe how to contribute to the collection. You can include, or link to, contribution guidelines that describe the process for contribution and a code of conduct for contributing to the collection and interacting with other contributors. This section should also include contact information or links to community channels for discussion. All links must be full URLs, not GitHub relative links.


## Support

This section should include information about what is supported and how to get support for the collection. This can include supported versions of the collection, how to submit a support request, and any other information about how to get additional assistance.


## Release Notes and Roadmap

Most collections should link to their release notes/changelog. Collections that have a public roadmap available should also link to that. All links must be full URLs, not GitHub relative links.


## Related Information

Where available, link to general how to use collections or other related documentation applicable to the technology/product this collection works with. Useful materials such as demos, case studies, etc. may be linked here as well. All links must be full URLs, not GitHub relative links.


## License Information

Link to the license that the collection is published under. All links must be full URLs, not GitHub relative links.