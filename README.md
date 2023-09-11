# awesome-sbom [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of SBOM (Software Bill Of Materials) related tools, frameworks, blogs, podcasts, and articles

# What is SBOM (Software Bill Of Materials) ? 
From [Wikipedia](https://en.wikipedia.org/wiki/Software_bill_of_materials):
> A software bill of materials (SBOM) is a list of components in a piece of software. Software vendors often create products by assembling open source and commercial software components. The SBOM describes the components in a product. It is analogous to a list of ingredients on food packaging: where you might consult a label to avoid foods that may cause an allergies, SBOMs can help companies avoid consumption of software that could harm their organization.
>
> The concept of a BOM is well-established in traditional manufacturing as part of supply chain management. A manufacturer uses a BOM to track the parts it uses to create a product. If defects are later found in a specific part, the BOM makes it easy to locate affected products.

## Contents

- 💼 [Official Projects](#official-projects)
    - 📂 [Repositories](#repositories)
    - 🗒️ [Docs](#docs)
    - 📰 [Blogs](#blogs-and-articles)
- 🐾 [Community Repositories](#community-repositories)
- 🗃️ [Blogs and Articles](#articles-and-blogs-1)
- 📹 [Videos](#videos)
- 📑 [Slides](#slides)
- 🎤 [Podcasts](#podcasts)
- :chart_with_upwards_trend: [Benchmarks](#benchmarks)

## Official projects

### Articles and Blogs

- [Wikipedia](https://en.wikipedia.org/wiki/Software_bill_of_materials) - Official Wikipedia Page
- [NTIA](https://www.ntia.gov/SBOM) - Official National Telecommunications and Information Administration Page
- [What is an SBOM?](https://www.linuxfoundation.org/blog/what-is-an-sbom/) - The Linux Foundation Article

### Tools (and [classification](https://ntia.gov/sites/default/files/publications/ntia_sbom_tooling_taxonomy-2021mar30_0.pdf))

|Tool|Build SBOM|Analyze SBOM|Edit SBOM|View SBOM|Diff SBOM|Import SBOM|Translate SBOM|Merge SBOM|Integrate with Other Tools|
|----|:--------:|:----------:|:-------:|:-------:|:-------:|:---------:|:------------:|:--------:|:------------------------:|
|AnthonyHarrison [SBOM4Python](https://pypi.org/project/sbom4python/)|CycloneDX,SPDX |
|AnthonyHarrison [SBOM4Rust](https://pypi.org/project/sbom4rust/)|CycloneDX,SPDX|
|AnthonyHarrison [SBOM4Files](https://pypi.org/project/sbom4files/)|CycloneDX,SPDX|
|AnthonyHarrison [Distro2SBOM](https://pypi.org/project/distro2sbom/)|CycloneDX,SPDX|
|AnthonyHarrison [SBOMDiff](https://pypi.org/project/sbomdiff/)| |CycloneDX,SPDX|CycloneDX,SPDX|
|AnthonyHarrison [SBOM2doc](https://pypi.org/project/sbom2doc/)| |CycloneDX,SPDX|CycloneDX,SPDX|
|AnthonyHarrison [SBOM2dot](https://pypi.org/project/sbom2dot/)| |CycloneDX,SPDX|CycloneDX,SPDX|
|AnthonyHarrison [SBOMAudit](https://pypi.org/project/sbomaudit/)| |CycloneDX,SPDX|CycloneDX,SPDX|
|AnthonyHarrison [SBOM-Manager](https://pypi.org/project/sbom-manager/)| |CycloneDX,SPDX|CycloneDX,SPDX|
|[bomber](https://github.com/devops-kung-fu/bomber)| |CycloneDX,SPDX| |CycloneDX,SPDX|
|[CycloneDX Maven Plugin](https://github.com/CycloneDX/cyclonedx-maven-plugin)|CycloneDX|
|[CycloneDX CLI tool](https://github.com/CycloneDX/cyclonedx-cli)| | |CycloneDX| |CycloneDX| |CycloneDX,SPDX|CycloneDX|
|CycloneDX [cdxgen](https://github.com/CycloneDX/cdxgen)|CycloneDX| | | | | | | |CycloneDX|
|Interlynk [SBOM Assembler](https://github.com/interlynk-io/sbomasm)|CycloneDX,SPDX| | | | | | |CycloneDX,SPDX|CycloneDX,SPDX|
|Interlynk [SBOM Quality Score](https://github.com/interlynk-io/sbomqs)| |CycloneDX,SPDX| |CycloneDX,SPDX| | | | |CycloneDX,SPDX|
|Interlynk [SBOM Grep](https://github.com/interlynk-io/sbomgr)| |CycloneDX,SPDX||CycloneDX,SPDX|||||CycloneDX,SPDX|
|Interlynk [SBOM Find & Pull](https://github.com/interlynk-io/sbomex)| || |CycloneDX,SPDX| | | | |CycloneDX,SPDX|
|[Kubernetes SBOM Tool](https://sigs.k8s.io/bom)|SPDX|
|Microsoft [SBOM tool](https://github.com/microsoft/sbom-tool)|SPDX|
|OSS Review Toolkit [ORT](https://github.com/oss-review-toolkit/ort)|CycloneDX,SPDX |
|[Syft](https://github.com/anchore/syft)|CycloneDX,SPDX|CycloneDX,SPDX| |CycloneDX,SPDX|
|Snyk SBOM [API](https://docs.snyk.io/snyk-api-info) & [CLI](https://docs.snyk.io/snyk-cli)|CycloneDX,SPDX|
|[Snyk SBOM Checker](https://snyk.io/code-checker/sbom-security/)| |CycloneDX,SPDX|
|[SPDX Maven Plugin](https://github.com/spdx/spdx-maven-plugin)|SPDX|
|[SPDX Gradle Plugin](https://github.com/spdx/spdx-gradle-plugin)|SPDX|
|[spdx-sbom-generator](https://github.com/spdx/spdx-sbom-generator)|SPDX|
|[SwiftBOM](https://github.com/CERTCC/SBOM/tree/master/SwiftBOM)|CycloneDX,SPDX,SWID|
|[Tern](https://github.com/tern-tools/tern)|CycloneDX,SPDX|
|[Trivy](https://github.com/aquasecurity/trivy)|CycloneDX,SPDX|CycloneDX,SPDX| |CycloneDX,SPDX|

### Repositories

- [CycloneDX Specification](https://github.com/CycloneDX/specification)
- [CycloneDX BOM Examples](https://github.com/CycloneDX/bom-examples)
- [CycloneDX/cyclonedx-maven-plugin](https://github.com/CycloneDX/cyclonedx-maven-plugin)
- [spdx-sbom-generator](https://github.com/spdx/spdx-sbom-generator)
- [tern-tools/tern](https://github.com/tern-tools/tern)
- [anchore/syft](https://github.com/anchore/syft)
- [dlorenc/sbom-oci](https://github.com/dlorenc/sbom-oci)
- [Cosign SBOM Spec](https://github.com/sigstore/cosign/blob/main/specs/SBOM_SPEC.md)
- [microsoft/sbom-tool](https://github.com/microsoft/sbom-tool)
- [SwiftBOM - generate SBOMs](https://github.com/CERTCC/SBOM/tree/master/SwiftBOM)
- [Kubernetes SBOM Tool](https://sigs.k8s.io/bom)
- [Aqua Trivy](https://github.com/aquasecurity/trivy)
- [bomber](https://github.com/devops-kung-fu/bomber)
  - [Snyk provider](https://github.com/devops-kung-fu/bomber/tree/main/providers/snyk)
- Snyk SBOM [API](https://docs.snyk.io/snyk-api-info) and [CLI](https://docs.snyk.io/snyk-cli)
- [Snyk SBOM Checker](https://snyk.io/code-checker/sbom-security/)
- [Interlynk SBOM Assembler](https://github.com/interlynk-io/sbomasm)
- [Interlynk SBOM Quality Score](https://github.com/interlynk-io/sbomqs)
- [Interlynk SBOM Grep](https://github.com/interlynk-io/sbomgr)
- [Interlynk SBOM Find and Pull](https://github.com/interlynk.io/sbomex)

## CycloneDX

- [CycloneDX Capabilities](https://cyclonedx.org/capabilities/)
- [CycloneDX Use Cases and Examples](https://cyclonedx.org/use-cases/)
- [CycloneDX Tool Center](https://cyclonedx.org/tool-center/)
- [Specification Overview](https://cyclonedx.org/specification/overview/)

## SPDX

- [The Software Package Data Exchange® (SPDX®)](https://spdx.dev/)
- [ISO/IEC 5962 - SPDX® Specification](https://www.iso.org/standard/81870.html)
- [ISO/IEC 5230:2020 - OpenChain Specification](https://www.iso.org/standard/81039.html)
- [SPDX Spec](https://spdx.github.io/spdx-spec/)
- [SPDX: It’s Already in Use for Global Software Bill of Materials (SBOM)](https://www.linuxfoundation.org/blog/spdx-its-already-in-use-for-global-software-bill-of-materials-sbom-and-supply-chain-security/)

## Community Repositories

- [SBOM-Operator for Kubernetes](https://github.com/ckotzbauer/sbom-operator)

### Security Tools

- [bomber](https://github.com/devops-kung-fu/bomber) - bomber is an application that scans SBoMs for security vulnerabilities.

## Articles and Blogs

- [Software Bill Of Materials: Formats, Use Cases, and Tools](https://fossa.com/blog/software-bill-of-materials-formats-use-cases-tools/)
- [Software Bill of Materials Required by 2021 Cyber Security Executive Order](https://fossa.com/blog/software-bill-of-materials-formats-use-cases-tools/)
- [The world needs a software bill of materials](https://news.ycombinator.com/item?id=26529619)
- [What is a software bill of materials?](https://www.synopsys.com/blogs/software-security/software-bill-of-materials-bom/)
- [Easily and Quickly Build an Accurate Open Source Inventory](https://www.revenera.com/software-composition-analysis/business-solutions/bill-of-materials.html)
- [Create a Cybersecurity Bill of Materials](https://www.promenadesoftware.com/blog/create-a-software-bill-of-materials)
- [What is an SBOM, and why should you Care??](https://boxboat.com/2021/05/12/what-is-sbom-and-why-should-you-care/)
- [Are you ready with your SBOM ? Think again !](https://nadgowdas.github.io/blog/2021/trust-sbom/)
- [Nisha Kumar and Allan Friedman - RSAC DevOps connect keynote](https://blogs.vmware.com/opensource/2021/06/15/software-bill-of-materials-and-modern-app-development-devops-connect-rsac-2021/)
- [Rose Judge on using Tern to generate a SBoM for containers](https://blogs.vmware.com/opensource/2020/08/29/rose-judge-on-tern-container-bill-of-materials/)
- [Creating a Software Supply Chain Landscape](https://zt.dev/posts/supply-chain-content-created/)
- [Analysis of a spdx-sbom-generator generated SBOM](https://zt.dev/posts/analysis-spdx-sbom-generator/)
- [Creating an SBOM for a golang app using spdx-sbom-generator](https://zt.dev/posts/creating-spdx-sbom/)
- [Analysis of a cyclonedx-gomod generated SBOM](https://zt.dev/posts/analysis-cyclonedx-gomod-sbom/)
- [Creating an SBOM for a golang app using cyclonedx-gomod](https://zt.dev/posts/creating-cyclonedx-gomod-sbom/)
- [What an SBOM Can Do for You](https://chainguard.dev/posts/2022-01-13-what-an-sbom-can-do-for-you)
- [BOM 101 – All the questions you were afraid to ask Software Bill of Materials](https://sysdig.com/blog/sbom-101-software-bill-of-materials/)
- [How to create SBOMs in Java with Maven and Gradle](https://snyk.io/blog/create-sboms-java-maven-gradle/) - Snyk blog
- [Comparing SBOM Standards: SPDX vs. CycloneDX](https://blog.sonatype.com/comparing-sbom-standards-spdx-vs.-cyclonedx-vs.-swid)
- [Top 10 Things You Should Know About Using SBOM to Secure Industrial IoT Devices - Red Alert Labs](https://www.redalertlabs.com/blog/top-10-things-you-should-know-about-using-sbom-to-secure-industrial-iot-devices)

## Videos

- [Mentorship Session: Generating Software Bill Of Materials](https://www.youtube.com/watch?v=EVnQ4Riecy8)
- [Software Bill of Materials: How to generate an SBOM from container images using Syft](https://www.youtube.com/watch?v=9oj3BC3vOtc)
- [SwiftBOM - generate SBOMs for PoC efforts and demos](https://youtube.com/playlist?list=PLKr8MJRsuoPHGqfcoj8auu7zax8oLRPsH)
- [Kubernetes Atlanta Meetup - Nov 2021 - SBOMs Container Signing and Verification, Intro to Gatekeeper](https://www.youtube.com/watch?v=PuTJ176djsc&t=22s)
- [FOSDEM 2023 - The 7 key ingredients of a great SBOM](https://fosdem.org/2023/schedule/event/sbom_key_ingredients/)

## Slides

- [Software Bill of Materials Presentation](https://csrc.nist.gov/CSRC/media/Projects/cyber-supply-chain-risk-management/documents/SSCA/Spring_2019/8MayAM2.3_Software_Bill_of_Materials_Robert_Martin_05_08_19_clean.pdf)

## Podcasts
- [DaBOM Podcast](https://dabom.show/)

## Benchmarks
- [SBOM Benchmark](https://sbombenchmark.dev) Quickly evaluate SBOM for quality, compliance and errors.



