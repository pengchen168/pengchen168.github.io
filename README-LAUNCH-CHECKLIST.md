# Polaris Website Update — Upload & Launch Checklist

## What's in this package
| File | Purpose |
|---|---|
| index.html | Bridge-first homepage with canonical tag, Open Graph tags, and Organization JSON-LD |
| services.html | Four bridge-led service groups |
| experience.html | Replaces Projects — "Polaris Assignments" separated from principal's prior experience |
| about.html | Firm overview, principal bio, credentials |
| teaming.html | Teaming & Qualifications page for prime consultants |
| contact.html | Real form endpoint (delivery-confirmed success), direct contact, privacy note |
| projects.html | Redirect stub so old /projects.html links land on experience.html |
| style.css | Shared stylesheet |
| sitemap.xml | All six pages |
| robots.txt | Allows crawling, references the sitemap |

Upload everything to the site root. Do NOT delete your existing polaris_logo.png
or Polaris_Capability_Statement.pdf — the pages reference both by those names.

Legal name is published as "Polaris Bridge Engineering LLC" (confirmed).
PE licensure is published as VA • MD • DC • NY • NJ (east-coast focus;
Washington State intentionally not shown).

## Form — already configured
contact.html contains your Web3Forms access key. Submissions are delivered to
the inbox linked in your Web3Forms dashboard (app.web3forms.com). After
uploading, submit a test inquiry from the live contact page and confirm it
arrives within a minute. The success message only appears after the server
confirms receipt; if sending fails, visitors see an error with your direct
email as fallback.

## Confirm before publishing
- [ ] Certification wording: pages say "Virginia DBE/MBE." If the certificate
      actually reads VDOT DBE/SWaM, adjust wording site-wide and on the PDF.
      Add cert number + expiration on teaming.html/about.html once verified.
- [ ] Exact FHWA/NBIS credential title — see the TODO comment in about.html.
- [ ] Tunnel inspection credential: add to about.html only if current, exact title.
- [ ] Software list on teaming.html: keep only tools with current access.
- [ ] Permissions confirmed for any client names, photos, drawings, or logos.
- [ ] Update Polaris_Capability_Statement.pdf to match: same legal name, same
      email (remove the old Outlook address), five-state PE list including DC,
      same revision date as the site.
- [ ] Add your LinkedIn company URL to the JSON-LD "sameAs" (TODO comment in
      index.html head).

## After publishing
- [ ] Test every nav link, tel/mailto link, PDF download, and the form on
      desktop and mobile.
- [ ] In Google Search Console: submit sitemap.xml, request reindexing, and
      later check that indexed snippets no longer show the old Outlook email.
