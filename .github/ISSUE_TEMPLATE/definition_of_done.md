---
name: Definition of done
about: '💫 Standard ticket when we finish up a project'
title: '💫 Definition of done'
labels: ''
assignees: 'levdbas'

---

### Tasks at start of project

- [ ] Do we have a hosting environment?
- [ ] Do we have a domain name?
- [ ] Will we do maintenance on the project?

### Tasks during project

- [ ] Bigger projects: do we have staging backups in place?

### Just before deployment

- [ ] Does the staging server has enough resources?
- [ ] ⚠️ BACKUP database ⚠️

### Tasks at end of project
- [ ] Did we set the correct manfinest information in child-setup.php
- [ ] Are licenses activated?
- [ ] Are forms working/do they send replies?
- [ ] Create [Recaptcha key](https://www.google.com/recaptcha/admin/create) and add it to forms plugin
- [ ] Is Mailgun set up?
- [ ] Check SMTP settings
- [ ] Add website to Google Analytics
- [ ] Configure tracking/analytics, is tagmanger container/analytics container loading and do we receive traffic?
- [ ] Add website to Google Search Console
- [ ] Did we enable caching? Did we set the caching to 10 hours max?
- [ ] Did we configured backups?
- [ ] Is the .env file set to production?
- [ ] Did we add the website to ManageWP?
- [ ] Add HTTP auth to staging environment or change username/password combination.
