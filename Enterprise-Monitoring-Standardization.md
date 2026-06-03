← Back to [Case Studies](Case-Studies.md) | Back to [Home](README.md)

## Modernizing Enterprise Monitoring Through Platform Standardization (Allstate)

### Situation
Critical monitoring systems relied on a collection of aging scripts, inconsistent interfaces, and duplicated code. Many monitoring functions had become non-operational following the transition from Python 2.

### Challenge
Restore monitoring capabilities while creating a maintainable foundation for future automation development across multiple enterprise storage platforms.

### Actions
- Designed and developed StorageTeamAPI as a common integration framework for enterprise storage and infrastructure platforms.
- Standardized access patterns for Hitachi, Pure Storage, IBM, Brocade, and ServiceNow systems.
- Established reusable components, version-controlled interfaces, and consistent logging standards.
- Built a comprehensive pytest regression suite validating supported integrations after every code change.
- Integrated automated testing into the development workflow to detect cross-platform regressions before deployment.
- Migrated 24+ monitoring scripts from Python 2 to Python 3.
- Added exception handling and reliability improvements across the monitoring ecosystem.

### Results
- Restored critical monitoring capabilities that had reportedly been unavailable for more than two years.
- Reduced script complexity and duplication through code reuse and standardization.
- Reduced script length by approximately 80% in many cases.
- Created a scalable foundation that accelerated future automation development.
- Improved maintainability, troubleshooting, and onboarding for future engineers.

### Technologies
Python, Pytest, REST APIs, Jenkins, GitHub, ServiceNow, Enterprise Storage Platforms

---

#### Contact
- GitHub: [Profile](https://github.com/jammane)
- LinkedIn: [Profile](https://www.linkedin.com/in/jeremiahmane)
- Email: [Email Me](mailto:jeremiahmane80@outlook.com)

← Back to [Case Studies](Case-Studies.md)
