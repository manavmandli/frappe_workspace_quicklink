# Frappe Workspace Quicklink

Turn any Frappe workspace into a direct sidebar shortcut. Instead of opening the workspace page, clicking the sidebar item navigates straight to a configured DocType, Report, Page, Dashboard, or URL.

## Screenshots

**Configure quick link fields on an existing Workspace record:**

![Quick Link Configuration](screenshots/config_form.png)

**Select the link type (DocType, Report, Page, Dashboard, URL):**

![Quick Link Type Dropdown](screenshots/type_dropdown.png)

## How It Works

1. Go to **Settings → Workspace** and open an existing workspace record
2. Check **Is Quick Link**
3. Choose a **Quick Link Type** (DocType / Report / Page / Dashboard / URL)
4. Fill in **Link To** (or **URL** for external links)
5. Save — clicking that workspace in the sidebar now redirects directly to the configured destination

## Installation

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO
bench install-app frappe_workspace_quicklink
bench migrate
```

## License

MIT
