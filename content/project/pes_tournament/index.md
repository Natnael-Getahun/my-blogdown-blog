---
author: Natnael Getahun
categories:
- Data Visualization
- Games
date: "2025-06-17"
draft: false
excerpt: Around March, 2025, my friends and I had the idea to start a gaming 
  tournament among ourselves. Our favorite game was a 2024-modded version of Pro 
  Evolution Soccer 2017 (PES 2017). Right away, I knew I wanted to build an 
  interactive dashboard to visualize our gaming statsn ending debates and trash talks 
  we had once and for all.
layout: single
links:
- icon: chart-bar
  icon_pack: fas
  name: Full Visualization
  url: https://lookerstudio.google.com/s/kkHakPXJ29U
- icon: database
  icon_pack: fas
  name: data
  url: https://docs.google.com/spreadsheets/d/1qk6I0gHj0qCiZAiNzXAJUAkHPJq1mW7C7qH513Wkig8/edit?usp=sharing
subtitle: Using Data Visualization to Settle Friendly Debates (and Trash Talk)
tags:
- Looker Studio
- Pes 2017
- Data Visualization
title: The Impostors League
---

![Formspree Logo](formspree-logo.png)

## [Formspree](https://formspree.io) makes it easy to receive submissions from HTML forms on your static website.

---

### Functional Form

This theme has a **form-to-email** feature built in, thanks to the simple Formspree integration. All you need to activate the form is a valid recipient email address saved in the front matter of the form
(`/content/forms/contact.md`). Of course, the example shown below (`your@email.here`) must not be used. Please use your actual email address.

```toml
# please replace with a valid Formspree form id or email address
formspree_form_id: your@email.here
```

Update that file and you're ready to begin receiving submissions. Just submit
the active form for the first time, and complete the email address verification
step with Formspree, and your contact form is live. The next time someone
fills it out, the submission will land in your inbox.

### Multiple Layouts

The files included with the theme have a contact page ready for copy/paste, or
you can type `hugo new forms/contact.md` and you're off to the races. There are two
layouts for `forms` – `split-right`, and `split-left` – you guessed it, one puts
the form on the right and the other on the left. You just fill out the front
matter, and the rest is automatic.

```toml
# layout options: split-right or split-left
layout: split-right
```

![Contact Form Split Right Layout Screenshot](built-in-contact-form-screenshot.png)

Both layouts display the page title and description opposite the form, and you
can also choose to show your social icon links if you have those configured in
the `config.toml` file.
