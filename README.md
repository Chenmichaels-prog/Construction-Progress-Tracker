# Construction Progress Tracker

Free, open-source, client-side project progress tracking for construction teams, designers, and independent contractors.

## Features

- Create multiple projects and milestones with deadlines.
- Track 0–100% progress and milestone state (Not Started, Active, On Hold, Completed).
- Weighted completion = sum(milestone progress × weight) ÷ sum(weights).
- Show overdue unfinished milestones.
- Generate weekly status reports, including highlights, risks, and next actions.
- Print weekly reports to PDF using the browser or download TXT.
- Export/import a JSON backup of project data.
- No sign-in, backend, third-party libraries, or data sent to a server.

## Run and deploy

Open `index.html` in a modern browser or enable GitHub Pages on the repository: **Settings → Pages → Deploy from a branch → main → /(root)**. Proposed site URL: https://chenmichaels-prog.github.io/Construction-Progress-Tracker/ (works once Pages is activated).

## Data and privacy

Projects remain only in the current browser's `localStorage`. They are not synced across browsers, devices or users, and clearing browser storage removes them. **Export backup regularly.** Never publish actual confidential project or client information in public repository files. JSON backups may themselves contain sensitive information.

## Estimation caveats

Weights are user-defined and do not have to sum to 100. A milestone at 100% is marked Completed. On Hold milestones retain their weight in completion calculations. The overdue count compares incomplete milestone deadlines to the current date; it is not a forward-looking schedule forecast. This lightweight app does not implement authorization, collaborative editing, audit logs, earned-value analysis, or a formal document approval process.

## Sponsor

If you find this useful, [support ongoing open-source development on GitHub Sponsors](https://github.com/sponsors/Chenmichaels-prog) (when the sponsor profile is active).

## License

[MIT](LICENSE). Contributions and issues welcome.
