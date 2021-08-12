### Kickstart your GAT actions integration!

This repository contains complete setup to launch your first tests using [GlobalAppTesting github action](https://github.com/GlobalAppTesting/gat-actions-request-test).

Test it yourself:
- fork this repo
- go to the "Actions" tab in your fork and click the green button
- enable "Issues" in your repo settings
- sign up for your API KEY [here](https://go.globalapptesting.com/early-access-exploratory-testing-test-execution)
- set your API key as a `GAT_API_KEY` secret in your repo.
- generate new access token. See [official github guide](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token). "repo" permissions are enough.
- set your access token as a `GAT_GH_ACCESS_TOKEN` secret in your repo.

You should also change the `application_url` in the workflow definition(`.github/workflows/main.yml`) to include your webpage URL and change the company description in the `description` field in `.gat.json`. Otherwise our testers will be checking [our webpage](https://www.globalapptesting.com).
