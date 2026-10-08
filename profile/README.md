# Macrostates

Macrostates gives your project written rules that coding agents can follow: how to organize code, manage development, test changes and keep documentation current.

Choose reusable specification packages for your technologies and combine them with your project’s own requirements. The specifications stay in your repository, where you can read, review and version them.

## How to use it

Point your coding agent to this page. For a new project, say:

> I want to start a new project using https://github.com/Macrostates.

For an existing project, say:

> I want my existing project to adopt https://github.com/Macrostates.

Add whatever you already know about the project: what it should do, your preferred technologies or any constraints. Your agent should follow the instructions below, discuss the appropriate packages with you and prepare the setup.

## Instructions for coding agents

If the user asks you to use Macrostates:

1. **Read the starting instructions.** Download or clone [macrostates-meta](https://github.com/Macrostates/macrostates-meta) into a temporary location. Read its `README.md`, follow its reading order and consult its project kickoff guidance. This inspection copy is separate from the released packages you install.

2. **Understand the project.** For a new project, establish its purpose, technologies and constraints. For an existing project, inspect its code, documentation and agent instructions first. Preserve existing work and identify conflicting conventions before proposing changes.

3. **Choose appropriate packages.** Use Meta and Process as the usual foundation, then select relevant repository and technology packages from Meta’s catalog. Explain the selection and verify release compatibility. Include only packages the project needs.

4. **Set up the specifications.** Follow the selected packages’ instructions. Keep the composition, verified release snapshots and project-specific requirements under `.macrostates/specs/`. Keep implementation documentation under `.macrostates/implementation/`. Application code stays in its normal locations.

5. **Verify and report.** Use the [Macrostates CLI](https://github.com/Macrostates/macrostates-cli), strongly recommended but optional, or equivalent manual checks. Summarize the setup, unresolved decisions and next steps. Proceed with application implementation according to the user’s request.

For existing projects, follow the selected Process package’s adoption rules rather than treating existing code as a new scaffold.

## AI assistance

This project was developed with AI assistance.
