# Changelog

All notable changes to the `seoaudit.seowebchecker` Ansible Collection will be documented here.

## Release 1.0.0

### Major Changes
- Initial release of `seoaudit.seowebchecker` on [Ansible Galaxy](https://galaxy.ansible.com/).
- New action module `seoaudit.seowebchecker.seo_audit` for on-page SEO health scoring and checks.
- Deployment quality gate enforcement with `min_score` and `fail_on_alert`.
- Included role `seoaudit.seowebchecker.agent` for automated cron scheduling and report paths.
- Included role `seoaudit.seowebchecker.quality_gate` for deployment verification playbooks.
- Official platform integration with [https://seowebchecker.com/](https://seowebchecker.com/).
