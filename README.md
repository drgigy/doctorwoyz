# Doctor WOYZ - GitHub Pages Edition

This folder contains the static, browser-only version of Doctor WOYZ.

## Upload To GitHub

1. Create a new GitHub repository.
2. Upload `index.html` and `.nojekyll` to the repository root.
3. Open the repository's **Settings**.
4. Select **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)`.
7. Select **Save**.
8. Wait for GitHub to provide the website address.

## Using The Website

1. Open the deployed website.
2. Open **Settings** using the gear button.
3. Paste a Google AI Studio API key.
4. Choose the AI model.
5. Select **Save**.

The key is stored only in that browser's local storage. It is not included in
the HTML or GitHub repository.

Use **Remove Key** before handing the device to someone else or when the key is
no longer needed.

## Limitations

- Anyone with access to the same browser profile may be able to retrieve the
  locally saved key.
- A shared API key can be used outside Doctor WOYZ.
- Clearing browser data removes the saved key.
- This static version cannot securely enforce device approval.
- This version is intended for closed-group demonstrations, not production use
  with identifiable patient information.
