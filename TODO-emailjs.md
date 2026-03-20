# EmailJS Integration Plan

**EmailJS credentials:**
- Email: dumbodetailing463@gmail.com
- Service ID: service_2zrafgp
- Template ID: template_wih2d4q
- Public Key: jcdVacE8mFepTtpN2

**Plan:**
1. Add EmailJS CDN script to index.html `<head>`
2. Update contact form:
   - Add `data-emailjs-service-id`, `data-emailjs-template-id`, `data-emailjs-user-id` attributes
   - Map form fields to template params
3. Add EmailJS init() with public key
4. Update form submit handler to use `emailjs.sendForm()`
5. Add success/error handling with user feedback
6. Test form submission

**Follow-up:** Confirm integration works by submitting test form.
