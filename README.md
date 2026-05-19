# Lifeful Dementia Day Care Website — Final Version

This is the finalised website package for Lifeful Dementia Day Care.

## Final updates included
- Latest newly generated images added across the website
- More diverse activity imagery throughout the homepage
- Premium professional layout retained
- Light transparent hero text panel preserved so the main image remains visible
- Address, pricing and contact details included
- Simple placeholder Privacy Policy and Cookie Policy pages included

## Main files
- `index.html`
- `styles.css`
- `privacy-policy.html`
- `cookie-policy.html`
- `assets/logo-lifeful.png`
- `assets/images/`

## Notes before launch
- Connect the enquiry form to your website host or email service
- Replace placeholder legal wording with your final approved legal text
- Confirm the email address `hello@lifefuldaycare.co.uk` if you plan to use it

- Updated to use the latest generated Lifeful logo in the website header and footer.

- Website updated to use the final Lifeful brand identity logo (`assets/logo-lifeful.png`).

- Hero section updated to a full-page 25% text / 75% image split layout.


## Final review fixes
- Rebuilt CSS to remove old conflicting hero styles.
- Improved desktop and mobile alignment, spacing, and symmetry.
- Optimised logo as transparent cropped web PNG.
- Improved text sizes and readability.
- Added form submission structure and thank-you page for static hosting.
- Improved card consistency, image heights, and responsive layout.

- Hero text top spacing removed; the text now starts at the top of the left panel.

- Hero image replaced in the latest split-hero version of the website.

- Hero image adjusted so the full image is visible without cropping people on the right, with a softer transparent presentation.

- Hero image updated to the corrected final version with both carers visible.

- Hero image updated to the latest version with two carers visible.


## Navigation link test
- Tested internal menu/action links against page section IDs.
- No missing internal section links found.
- Added scroll offset fixes so sticky header does not hide section headings.
- Improved mobile navigation scrolling.


## Contact form email setup
The contact form has been configured to send submissions to:
`ugangana@gmail.com`

It uses FormSubmit:
`https://formsubmit.co/ugangana@gmail.com`

Important:
- On the first form submission, FormSubmit usually sends a confirmation email to `ugangana@gmail.com`.
- You must open that confirmation email and activate the form.
- After activation, future submissions should arrive in the inbox.
- Check spam/junk if the activation email does not appear.


## Contact form fix — Netlify Forms version
The previous FormSubmit endpoint caused a Cloudflare 522 host error. This version removes FormSubmit and configures the contact form for Netlify Forms.

After uploading the site to Netlify:
1. Open the site in Netlify.
2. Go to Forms and confirm the `contact` form is detected.
3. Go to Site configuration / Forms / Form notifications.
4. Add an email notification to `ugangana@gmail.com`.
5. Submit a test enquiry.

If you host the website somewhere other than Netlify, this form will not email automatically. Use that host's form handling service, Formspree, or a small backend email script.

- Opening hours updated to 9:30 AM – 3:30 PM.
