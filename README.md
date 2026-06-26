<p align="center">
  <img src="./DozerDB_logo.png" width="400" alt="DozerDB">
</p>

<p align="center">
  <em>Plugin build for DozerDB — combines core and browser into a single deployable artifact</em>
</p>

<p align="center">
  <a href="https://github.com/dozerdb/dozerdb-plugin/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-GPLv3-blue?style=for-the-badge" alt="License"></a>
  <a href="#-development"><img src="https://img.shields.io/badge/Java-17+-orange?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 17+"></a>
  <a href="https://neo4j.com"><img src="https://img.shields.io/badge/Neo4j-5.26.22-green?style=for-the-badge&logo=neo4j&logoColor=white" alt="Neo4j"></a>
</p>

<p align="center">
  <a href="https://dozerdb.org"><img src="https://img.shields.io/badge/Get_Started-FF6600?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Get Started"></a>
  <a href="mailto:info@greystonesgroup.com"><img src="https://img.shields.io/badge/Contact_Us-333333?style=for-the-badge&logo=gmail&logoColor=white" alt="Contact Us"></a>
</p>

---

## 📋 About

DozerDB enhances Neo4j Community Edition with enterprise features. This project builds the plugin — an uber JAR that combines [dozerdb-core](https://github.com/dozerdb/dozerdb-core) and [dozerdb-browser](https://github.com/dozerdb/dozerdb-browser) into a single artifact.

The plugin JAR is dropped into the Neo4j `lib` directory and takes control of the bootstrap process.

Visit **[dozerdb.org](https://dozerdb.org)** for installation instructions.

---

## 🔢 Versioning

The plugin version uses the current Neo4j full version number and appends a release number for DozerDB updates:

| Neo4j Version | DozerDB Release | Plugin Version |
|---------------|-----------------|----------------|
| 5.16.0        | First release   | `5.16.0.0`     |
| 5.16.0        | Browser update  | `5.16.0.1`     |
| 5.16.0        | Core fix        | `5.16.0.2`     |

The final number increments whenever `dozerdb-core` or `dozerdb-browser` has an update.

---

## 🛠️ Development

### Prerequisites

- **Java 17+** is required. You will get compile errors with older versions.
- We recommend [SDKMAN!](https://sdkman.io/) as an open source Java version manager.

### Building

```bash
./mvnw clean verify
```

---

## 📞 Support

<p>
  <a href="mailto:info@greystonesgroup.com"><img src="https://img.shields.io/badge/Email_Us-info@greystonesgroup.com-FF6600?style=flat-square&logo=gmail&logoColor=white" alt="Email Us"></a>
  <a href="https://github.com/dozerdb/dozerdb-core#-support"><img src="https://img.shields.io/badge/More_Info-dozerdb--core-333333?style=flat-square&logo=github&logoColor=white" alt="More Info"></a>
</p>

---

<p align="center">
  <sub>&copy; 2026 DozerDB Contributors</sub>
</p>
