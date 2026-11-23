# IT Help Desk

An OutSystems Developer Cloud web app for submitting, tracking, assigning, and resolving IT support tickets.

## Live app

[Open IT Help Desk](https://personal-d4rugnq7-dev.outsystems.app/ITHelpDesk/)

The app runs in the OutSystems Personal Edition Development environment.

## Features

- Ticket queue with search and status filtering
- Ticket details with comments and assignment
- Ticket status updates, including resolution dates
- Submit-ticket form with required fields
- Ticket categories and statuses
- Sample tickets and comments
- Role-based access for employees, IT agents, and IT managers

## Access

Your ODC Portal membership does not automatically grant access to the application. Assign yourself an application end-user role for the Development stage:

1. Open ODC Portal.
2. Go to **Management > Govern > Users**.
3. Open your user.
4. Assign an IT Help Desk role for the **Development** stage.
5. Save, then open the [live app](https://personal-d4rugnq7-dev.outsystems.app/ITHelpDesk/).

## Roles

- **Employee** — submit and view support tickets
- **IT Agent** — track, assign, comment on, and resolve tickets
- **IT Manager** — manage tickets and oversee resolution

## Development setup

This workspace contains the OutSystems MCP agent instructions in [AGENTS.md](./AGENTS.md), the build tutorial in [build-first-app.md](./build-first-app.md), and the original build prompt in [it-help-desk-prompt.txt](./it-help-desk-prompt.txt).

The configured tenant is `personal-d4rugnq7.outsystems.dev`, and the MCP endpoint is:

```text
https://personal-d4rugnq7.outsystems.dev/mcp
```

## Useful prompts

```text
List my apps in OutSystems.
```

```text
Run the outsystems-app-architecture on the IT Help Desk app.
```

```text
Check the IT Help Desk logs in Development for errors from the last hour.
```

## References

- [OutSystems MCP setup guide](https://outsystems.com/mcp/outsystems-get-started.md)
- [AWS Coding Agent instructions](https://go.outsystems.com/aws-coding-agent)
- [User management](https://www.outsystems.com/tk/redirect?g=9e0fb9b7-d2b0-419f-a5d8-5b5ed730da5e)
- [Grant or revoke user roles](https://www.outsystems.com/tk/redirect?g=df369b59-5c40-4954-9622-722503ee54d1)
