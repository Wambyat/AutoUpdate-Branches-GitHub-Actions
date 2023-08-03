# GitHub Auto-Update
This is a way to make all your branches auto update to the latest push on the main branch. This uses GitHub actions. This will fail on private repositories.

### Steps to follow:
1. Copy the .github folder into your repository or make a repository using this one as a template.
1. In ./github/workflows/main.yml replace `<your email here>` with your GitHub email and `<your username here>` with your GitHub username.
After you create this GitHub will automatically create a GitHub Action and start it on every push to the main branch.
##### PS: The action will fail in this repository as I have not replaced `<your email here>` and `<your username here>`. To see the action actually working see [this repository.](https://github.com/Wambyat/IISC-Determining-anomalies-in-the-stock-market)
