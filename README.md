# GitHub User Activity

This project is a console application that retrieves GitHub user activity using the GitHub API. It provides insights into the user's activity on GitHub, including recent commits, issues, and pull requests.

## Features

- Fetch recent GitHub user activity (commits, issues, pull requests)
- Simple console-based output
- Easily configurable for different GitHub usernames
- Supports authenticated requests with GitHub personal access token (optional)

## Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (version 8.0 or higher)
- A GitHub account
- [GitHub personal access token](https://docs.github.com/en/enterprise-server@3.0/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) (for authenticated requests to avoid rate limiting)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/MarvynHarryson/github-user-activity.git
   cd github-user-activity

2. Restore required packages:

    ```bash
    dotnet restore


## Usage

1. Build the project:

    ```bash
    dotnet build

2. Run the application with a GitHub username:

    ```bash
    dotnet run <your-github-username>
    ```

    Example:

    ```bash
    dotnet run john-doe

Then, rerun the application.


## Support My Work
If you enjoy my work or want to support what I do, feel free to [Buy Me a Coffee](https://buymeacoffee.com/marvynharry)!

## Contributing
Feel free to submit a pull request or report issues to help improve the project!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or support, please reach out via [GitHub Issues](https://github.com/MarvynHarry/github-user-activity/issues).