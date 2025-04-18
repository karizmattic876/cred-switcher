# 🔐 cred-switcher

A simple CLI tool to quickly switch between different **Git identities** and **AWS credentials**.

Perfect for developers juggling multiple projects, clients, or AWS environments.

---

## 🚀 Features

- ✅ Switch global Git user name and email
- ✅ Update AWS credentials (`~/.aws/credentials` and `~/.aws/config`)
- ✅ Manage multiple profiles in one config
- ✅ Interactive prompts for adding profiles
- ✅ Secure input for AWS secrets (nothing printed to screen)

---

## 📦 Installation

### 🔁 Recommended: Use a Virtual Environment

```bash
git clone https://github.com/youruser/cred-switcher.git
cd cred-switcher

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install the CLI in editable mode
pip install --editable .

#Uninstall the CLI tool
deactivate
rm -rf venv/

pip uninstall cred-switcher

## Usage

cred-switcher set <profile>
cred-switcher add <profile>
cred-switcher list
cred-switcher show