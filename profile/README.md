# RuleBeat

RuleBeat is an open-source, self-hosted Azure governance tool. It runs the
rules you create and customize on a schedule and tracks every finding until
it is fixed. Every check is a rule. Customize the built-in rules or create
your own for the checks you need, in a visual builder or as a raw query.
Built-in and custom rules run in the same scan, share the same suppressions
and history, and show up in the same dashboards and notifications.

RuleBeat only ever reads. It scans with a Reader credential you create, never
holds write access, and never blocks a deployment. It is open source and
free, and it runs entirely inside your own Azure subscription: one container,
no external database, no telemetry. Nothing about your tenant leaves your
deployment.

- **Product:** [rulebeat/rulebeat](https://github.com/rulebeat/rulebeat)
- **Website:** [rulebeat.com](https://rulebeat.com) · **Docs:** [docs.rulebeat.com](https://docs.rulebeat.com)
- **Bugs and feature requests:** [Issues](https://github.com/rulebeat/rulebeat/issues) · **Questions:** [Discussions](https://github.com/rulebeat/rulebeat/discussions)
- **Security:** see [SECURITY.md](https://github.com/rulebeat/.github/blob/main/SECURITY.md), report to security@rulebeat.com
