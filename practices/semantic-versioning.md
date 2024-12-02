# Semantic Versioning and Automated Git Tagging in the Release Pipeline

## What is Semantic Versioning?

Semantic Versioning (SemVer) is a versioning system designed to convey meaning about the underlying changes in a software release. It follows the format:

### Components of Semantic Versioning:
1. **MAJOR**: Increases when there are incompatible API changes.
2. **MINOR**: Increases when new features are added in a backward-compatible manner.
3. **PATCH**: Increases when backward-compatible bug fixes are made.

### Examples:
- `1.0.0`: Initial release.
- `1.1.0`: A new feature added (minor change).
- `1.1.1`: A bug fix (patch change).
- `2.0.0`: A breaking change (major update).

## Git Tags for Releases

Git tags are references that point to specific commits, often used to mark release versions. They help in:
- Identifying release versions.
- Facilitating rollbacks.
- Simplifying deployment processes.

### Types of Tags:
- **Annotated Tags**: Include metadata (e.g., author, date) and are stored as objects in Git.
- **Lightweight Tags**: Simpler and act as a pointer to a specific commit.

## Automating Git Tag Creation with a Release Pipeline

### Workflow Overview:
1. **Code reaches the `main` branch**:
   - Trigger the release pipeline.
2. **Determine the next version**:
   - Use a tool (e.g., `semantic-release`) or custom logic to determine whether a MAJOR, MINOR, or PATCH update is required based on commit messages or other indicators.
3. **Create a Git Tag**:
   - Automatically generate and push the tag to the repository.
