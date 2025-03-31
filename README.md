# 🎀 SuperAGI Private Key Disclosure 🎀
## Overview
A vulnerability was recently found in the SuperAGI web application, where sensitive API keys are inadvertently exposed. The DashboardService.js file interfaces with the backend to manage and retrieve data for the application's user dashboard. However, hardcoded API keys are transmitted in plain text through the file and are accessible through client-sided javascript, allowing unauthenticated users to view and extract these keys for their own use.
## Impact
This vulnerability allows unauthenticated users to view these keys through their browser's developer tools, enabling unauthorized access to backend services, potential data breaches, and misuse of the associated APIs. Not only does it compromise the integrity of the application's security architecture, but it also places sensitive user data at risk.
