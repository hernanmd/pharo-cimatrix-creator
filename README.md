# Description

Create a GitHub Actiosn CI matrix file (.yml) for Pharo 7, 8 and 9 for your organization repositories.

# Installation

Just clone this repository into any empty directory:

```bash
git clone https://github.com/hernanmd/pharo-cimatrix-creator.git
```

# Usage

Uses a default template which you can easily customize editing the script.

Download your organization repositories:

```bash
./download_org_repos <your-github-organization-name>
```

Optionally filter out manually repositories which you do not want to add GitHub Actions.

Now run the script for the current directory:

```bash
./create_matrix .
```

To clean the generated .yml files and directories

```bash
./create_matrix . clean
```

