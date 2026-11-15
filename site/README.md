# Oriental One Group website

Static website for orientalonegroup.co. Plain HTML and CSS, no build step needed.

## Pages

| File | Page |
|---|---|
| index.html | Home |
| about.html | About Us |
| hr-shared-services.html | Outsourced Remote HR Shared Services |
| payroll.html | Outsourced Payroll Services |
| recruitment.html | Recruitment Services |
| market-entry.html | Market Entry & Business Consulting |
| industries.html | Industries |
| insights.html | Insights |
| contact.html | Contact Us |

Images live in `assets/img`, the logos in `assets/brand`, and the favicons in the root folder.

## Publish with GitHub Pages

1. Create a new repository on GitHub and upload everything in this folder (keep the folder structure).
2. In the repository, go to Settings → Pages, choose "Deploy from a branch", select `main` and `/ (root)`, then save.
3. To use orientalonegroup.co, add the domain under Settings → Pages → Custom domain and point your DNS to GitHub Pages.

## Contact page: booking calendar

Visitors pick one of the next 10 weekdays and a time (9:30 am, 11:00 am, 2:00 pm or 3:30 pm Sydney time). The button opens an email to Support@orientalonegroup.co with the date and time already filled in. You reply to confirm. To change the times, edit the `TIMES` line near the bottom of `contact.html`.

## Contact page: enquiry form

Visitors fill in the form and press "Email Your Enquiry". Their own email app opens with a message to Support@orientalonegroup.co, with their details filled in, and they press send. No form service or server is needed.

## Still to do before launch

- **Legal pages:** Privacy Policy, Website Terms and Candidate Privacy Notice links in the footer need their pages.
- **Insights:** article links and filter buttons are placeholders until the articles are written.
- **Placeholders:** search the files for `[` to find details still to confirm (e.g. registered entity name, response times, payroll scope).
