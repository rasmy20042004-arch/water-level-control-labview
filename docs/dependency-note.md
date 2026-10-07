# Dependency Note

The uploaded LabVIEW project contained a machine-specific warning for a plant/PID example subVI. User-specific absolute paths were removed from the GitHub-ready copy.

If the project opens with a missing-subVI prompt:

1. Locate the equivalent PID / plant example VI in your local LabVIEW installation.
2. Relink the missing dependency from the project or block diagram.
3. Save the project using a project-relative path where possible.

This keeps the repository portable between computers.
