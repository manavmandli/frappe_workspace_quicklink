# Frappe Workspace Quicklink

Turn any Frappe workspace into a direct sidebar shortcut. Instead of opening the workspace page, clicking the sidebar item navigates straight to a configured DocType, Report, Page, Dashboard, or URL.

## Screenshots

**Select the link type (DocType, Report, Page, Dashboard, URL):**

<img width="1297" height="794" alt="quick_link_type" src="https://github.com/user-attachments/assets/b5d0908f-a7cf-4773-9f80-f5a9063c19be" />

**Select the link to:**

<img width="1258" height="809" alt="quick_link_to" src="https://github.com/user-attachments/assets/e986551a-ab9e-400f-b79b-2b97e6e75573" />



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
