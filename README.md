# Ansible

## Prerequisites

- Python3
- sshpass（Managed Node にパスワード認証で ssh する場合）

## Getting started

ansible と ansible-galaxy の collection をインストールしてください。

```sh
python -m venv .env
source .env/bin/activate
pip install -r requirements.txt
ansible-galaxy install -r requirements.yml
```

playbook を実行してください。

```sh
ansible-playbook <playbook>
```

## Contributing

[CONTRIBUTING.md](./CONTRIBUTING.md)をご覧ください。
