# TiAmo Commission Payroll

A browser-based starter for preparing TiAmo Massage therapist commission statements.

## Included
- Therapist dropdown with add-therapist dialog
- Weekly pay-period dropdown (Thursday–Wednesday) and editable dates
- Automatic calculation in South African rand
- Payslip preview styled to resemble the supplied Canva commission statement
- Browser print / Save as PDF
- Local saved-statement history

## Calculation
**Total commission − levy − ads − advances + reimbursements = total commission payable**

## Run locally
Open `index.html` in a modern browser. Keep `index.html`, `style.css`, and `app.js` in the same folder.

## Deploy with GitHub Pages
In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then Save. GitHub will display the published URL after deployment.

## Important data/security note
This initial version stores therapist names and statements in the browser's local storage on that device only. It does not yet have Firebase cloud sync, user authentication, role permissions, audit logging, or ChiDesk integration. Do not treat local browser storage as a central payroll database or store sensitive payroll records on shared/public computers. The repository can be private; GitHub Pages publication is a separate setting and the deployed website itself may be publicly accessible depending on GitHub plan/settings. Confirm access requirements before enabling Pages for real payroll use.
