# .github Repository

This repository is used to centrally manage GitHub configuration files for the organization/user **manojkumar-jmp**.

## Purpose

The `.github` repository allows you to define and share common GitHub settings and files across all repositories in your organization/user account. Placing files here enables consistent workflows, issue templates, and other community health files.

## Common Contents

- **Issue Templates:** Standardized templates for reporting bugs, feature requests, etc.
- **Pull Request Templates:** Guidelines for submitting pull requests.
- **GitHub Actions Workflows:** Reusable workflows to automate CI/CD and other tasks.
- **Funding Information:** Information about funding your projects.
- **CODEOWNERS:** Define code owners for repositories.

## How It Works

Files placed in this repository’s `.github/` directory may be automatically used by all other repositories under this organization/user—helping maintain consistency and save time.

## Structure Example

```
.github/
├── ISSUE_TEMPLATE/
│   ├── bug_report.md
│   └── feature_request.md
├── PULL_REQUEST_TEMPLATE.md
├── workflows/
│   └── ci.yml
├── FUNDING.yml
```

## References

- [GitHub Docs: Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)

---

Feel free to customize this README to better fit your specific needs!
