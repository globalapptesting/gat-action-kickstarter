### Kickstart your GAT actions integration!

This repository contains complete setup to launch your first tests using [GlobalAppTesting github action](https://github.com/GlobalAppTesting/gat-actions-request-test).

Test it yourself:
- Fork this repo
- Go to the "Actions" tab in your fork and click the green button
- Enable "Issues" in your repo settings
- Generate an API key by logging into [app.globalapptesting.com](https://app.globalapptesting.com) and going to Settings > API key > Generate new key.
- If you’re not yet a Global App Testing customer, get in touch with us [here](https://go.globalapptesting.com/early-access-exploratory-testing-test-execution) to sign up.
- Set your API key as a `GAT_API_KEY` secret in your repo.
- Generate new access token. See [official github guide](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token). "repo" permissions are enough.
- Set your access token as a `GAT_GH_ACCESS_TOKEN` secret in your repo.

You should also change the `application_url` in the workflow definition(`.github/workflows/main.yml`) to include your webpage URL and change the company description in the `description` field in `.gat.json`. Otherwise our testers will be checking [our webpage](https://www.globalapptesting.com).
