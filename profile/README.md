## Genome Nexus 🧬
[Genome Nexus](https://genomenexus.org/) is a comprehensive resource integrating variant annotations from [more than a dozen sources relevant to cancer](https://docs.genomenexus.org/annotation-sources). The annotations can be accessed through a performant application programming interface and an intuitive user interface, supporting various use cases of variant interpretation. It is freely available under an open source license and can be installed in a private cloud or local environment and integrated with local institutional resources.

Genome Nexus is developed at Memorial Sloan Kettering Cancer Center (MSK) and has received several contributions from The Hyve. The Genome Nexus website is hosted by the Center for Molecular Oncology at MSK. The software is available under an open source license via GitHub.

## Documentation 📖
See [docs](https://docs.genomenexus.org)

## Repositories 📁
See [architecture section of the docs](https://docs.genomenexus.org/architecture) for more information about the Genome Nexus stack. These are the relevant repos:

- [genome-nexus](https://github.com/genome-nexus/genome-nexus): REST API in Java Spring Boot
- [genome-nexus-frontend](https://github.com/genome-nexus/genome-nexus-frontend): Frontend in TypeScript using React
- [genome-nexus-annotation-pipeline](https://github.com/genome-nexus/genome-nexus-annotation-pipeline): Command Line Client in Java for annotating MAF files
- [annotation-tools](https://github.com/genome-nexus/annotation-tools): Various tools that help with annotation including a Python based VCF2MAF converter

## Cite 📚
When using Genome Nexus, please cite [de Bruijn et al., JCO CCI 2022](https://ascopubs.org/doi/abs/10.1200/CCI.21.00144).

Genome Nexus aggregates variant annotation from various sources. See [this documentation](https://docs.genomenexus.org/annotation-sources) for all supported annotation sources. Remember to also cite the underlying annotation sources you are using.
